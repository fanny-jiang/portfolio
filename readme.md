# Hey there! You found my portfolio
Thanks for checking it out. Here's how you can download and build it:

`$ git clone https://github.com/fanny-jiang/portfolio.git`

## Install and Run Hugo
1. Install Hugo
  ```
  $ brew install hugo
  $ hugo version    # to verify your new install
  ```
2. Run server
  ```$ hugo server    # auto-compiles as you work
  ```

## Edit Project
1. Template lives in `/layouts/index.html`
2. Config vars and content go in `/config.toml`
3. Static files go in `/static`
4. Themes live in `/themes   # duh`
5. Meta info stuff go in `/content`
6. Compiled project ends up in `/public`

## Deployment
1. Install Firebase
  ```$ npm install -g firebase-tools
  ```
2. Login to Firebase Google Account
  ```$ firebase login
  ```
3. Deploy to Firebase
  ```$ hugo && firebase deploy   # yay
  ```
