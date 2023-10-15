# 5manCustom

## Requirements: 

* Node (https://nodejs.org/en/download)
* NPM (curl -qL https://www.npmjs.com/install.sh | sh)

## 1. Running the app 100% locally without any server setup ##

You can run the application locally from your computer without setting up any
server-based resources. Saving and sharing wheels won't work,
but it may be enough if you want to run the application
without hosting it online. Here is how to do it:

1. Clone the repo

1. At the command prompt in the top-level directory, run
    ```
        npm install
    ```
1. At the command prompt in the *functions* directory, run
    ```
        npm install
    ```
1. Go back up to the top-level directory.

1. Run ```build_dev.sh``` [or do the Windows equivalent]
1. Run ```npx serve ./dist``` [or any static file server like http-server or
caddy]