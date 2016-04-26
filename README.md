# become BIRB
this is a game about a human that is also a birb.

## setup
- use Node >4. If you don't have this, [install nvm](https://github.com/creationix/nvm#install-script) as to not loose control of your Node development environments in the future, and then install and use Node 4:

  ```sh
  nvm install 4
  nvm use 4
  ```
- clone this directory into whatever folder you want to be working from:

  ```sh
  git clone https://github.com/sunmoyed/become-birb.git
  cd become-birb
  ```
- install project and dev dependencies:

  ```sh
  npm install
  ```
- wait for one million years; take a burrito or boba break for maximal efficiency.
- yay you're ready to go!

## running locally
- make sure you're using Node 4 in your current terminal:

  ```sh
  nvm use 4
  ```
- run development:

  ```sh
  npm start
  ```

## working with tile maps

This project uses [Tiled](http://www.mapeditor.org/) to create and manage tile maps. Download it from the project page and open `.tmx` files with the GUI.

## thx
[Daniel Belohlavek](https://github.com/belohlavek) made a great [phaser+es6 boilerplate](https://github.com/belohlavek/phaser-es6-boilerplate), thanks!

[Blarget](http://blarget.org/) gave this world an excellent [spritesheet](http://opengameart.org/content/minimalist-pixel-tileset).
