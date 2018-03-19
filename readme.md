# Hey there! You found my portfolio!
Thanks for checking it out. Here's how you can download and build it:

`$ git clone https://github.com/fanny-jiang/portfolio.git`

## Install and Run Hugo
1. Install Hugo
  ```
  $ brew install hugo
  $ hugo version    # to verify your new install
  ```
2. Run server
  ```
  $ hugo server    # auto-compiles as you work
  ```

## Edit Project
  * Template lives in `/layouts/index.html`
  * Config vars and content go in `/config.toml`
  * Static files go in `/static`
  * Themes live in `/themes   # duh`
  * Meta info stuff go in `/content`
  * Compiled project ends up in `/public`

## Deployment
1. Install Firebase
  ```
  $ npm install -g firebase-tools
  ```
2. Login to Firebase Google Account
  ```
  $ firebase login
  ```
3. Deploy to Firebase
  ```
  $ hugo && firebase deploy   # yay
  ```
