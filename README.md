# cute

A little project to play with Qt in Rust, also see https://rust-qt.github.io

This was quickly abandoned as it seems most of the code has to be `unsafe`. See https://rust-qt.github.io/qt/unsafety/ .


## Installation

- On Ubuntu, you need to install at least these packages: `sudo apt install cmake qttools5-dev qtbase5-dev`.
- This list might be incomplete because I also installed `qtcreator` which pulled in a lot of packages.

## Run

- cargo run