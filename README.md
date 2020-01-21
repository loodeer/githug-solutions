# githug 通关记录

[githug](https://github.com/Gazler/githug) 是 ruby 写的一个 `git` 游戏，window、mac、linux 系统下都可以玩。

它把平常可能遇到的一些场景都实例化，变成一个一个的关卡。

一共有 56 个关卡，本文档记录了我的通关记录。



更好的阅读体验请访问电子书：[githug 通关记录](https://loodeer.github.io/githug-solutions/)



下面是 githug 项目的官方使用说明。

 ### Prerequisites

  Githug requires Ruby 1.8.7 or higher.

  You can check which version of Ruby is installed with the following command:

  ```
  ruby --version
  ```

  If ruby is not installed, follow the installation instructions on [ruby-lang.org](https://www.ruby-lang.org/en/documentation/installation/).

  ### Installation

  To install Githug, run

  ```
  gem install githug
  ```

  If you get a complaint about permissions, you can rerun the command with `sudo`:

  ```
  sudo gem install githug
  ```

  ### Starting the Game

  After the gem is installed change directory to the location where you want the game-related assets to be stored. Then run `githug`:

  ```
  githug
  ```

  You will be prompted to create a directory.

  ```
  No githug directory found, do you wish to create one? [yn]
  ```

  Type `y` (yes) to continue, `n` (no) to cancel and quit Githug.

  ### Commands

  Githug has 4 game commands:

  - play - The default command, checks your solution for the current level
  - hint - Gives you a hint (if available) for the current level
  - reset - Reset the current level or reset the level to a given name or path
  - levels - List all the levels

更详细的说明请见 [githug 项目主页](https://github.com/Gazler/githug)。

