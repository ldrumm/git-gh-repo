# git-gh-repo

Simple bash script for creating github repos from the shell


## Usage

make sure `git-gh-repo` is on your `$PATH`, then simply execute one of the following:
    `git gh-repo add $reponame`
    `git gh-repo rm $reponame`

A new repository will be created for your account.


## prerequisites
 - A modern `bash`
 - A modern `curl`
 - A GitHub [oauth token](https://github.com/settings/tokens/) with repo
   read/write scopes and your GH username in `git.config <hub.oauthtoken>
   and <hub.user> respectively:

    ```ini
    [hub]
        user = ...
        oauthtoken = ...
    ```

## Licence
 Public Domain
