# dotfiles-ansible

## MacOS

1. Install Homebrew
    
    ```shell
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

2. Install basic deps

    ```shell
    brew install openssl readline sqlite3 xz zlib
    ```

3. Install Pyenv

    ```shell
    brew install pyenv

    pyenv install 3.11.8
    pyenv global 3.11.8
    ```

4. Install Ansible

    ```shell
    pip install ansible
    ```

5. Run MacOS playbook

    ```shell
    ansible-playbook -i inventory/dev_macos playbook.yml
    ```
