# Service Bot contrib

## Setup instructions

### Step 1: Docksal environment setup

**This is a one time setup - skip this if you already have a working Docksal environment.**  

Follow [Docksal environment setup instructions](http://docksal.readthedocs.io/en/master/getting-started/env-setup)
   
### Step 2: Project setup

1. Clone this repo into your Projects directory

    ```
    git clone <repo_url> servicebot
    cd servicebot
    ```

2. Initialize the site

    This will initialize local settings and install the site via drush

    ```
    fin init
    ```

3. **On Windows** add `192.168.64.100  drupal7.docksal` to your hosts file

4. Point your browser to

    ```
    http://servicebot-d7.docksal
    ```


## Working with servicebot module.

Download the module with git enabled.

    ```
    fin drush dl servicebot --package-handler=git_drupalorg
    ```

