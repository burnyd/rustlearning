### Create the directories
mkdir $PWD/rustprojects
cd $PWD/rustprojects
mkdir hello_world
cd hello_world

### Create a main.rs file
touch main.rs

## Compile it
rustc main.rs

## Run it
➜  hello_world rustc main.rs
➜  hello_world ./main
Hello, world!

    println!("Hello, world!");
! == means a marco is being called.