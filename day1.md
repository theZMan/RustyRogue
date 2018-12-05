Day 1

Install Rust 1.30.1 from here https://www.rust-lang.org/en-US/install.html or if you already have it run `rustup upgrade`

Check versions with `cargo --version`, `rustc --version` and `rustdoc --version`

Make a new project `cargo new --bin rustyrogue`

Run it `cargo run`

Using Visual Studio Code with Rust? Is it more viable than last time? RLS extension appears to have been updated https://marketplace.visualstudio.com/items?itemName=rust-lang.rust
Install Code Runner and you can press the run buttons https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner
Still no F5 debugging but it will do for now.

Investigate a rust library to do the terminal output PanVurses seems to be sufficient https://github.com/ihalila/pancurses
`cargo install pancurses`

Useful information on roguelikes http://www.gamasutra.com/blogs/JoshGe/20181029/329512/How_to_Make_a_Roguelike.php and http://roguebasin.roguelikedevelopment.org/index.php?title=Main_Page and http://rogueliketutorials.com/libtcod/1


Notes:
Github markup reference here https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf

IDEAS: [LIBTCOD](https://bitbucket.org/libtcod/libtcod/) - might be a fun one to make a rust wrapper for

Things I had forgotten about git because I dont use it every day!
git config --global user.email zman@thezbuffer.com
git config --global user.name "Andy Dunn"
git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"

