# cpp_project_template

This repository contains 'The template for cpp projects', including a basic example of writing a C++ library named 'utils' for message printing. <br/>
Additionally,'PRINTING_HELLO_WORLD' application utilizes the library to print "Hello World!" on the terminal, without directly using 'iostream'. <br/>

## Compile

You can use the following commands to download and compile the package.

```
git clone https://github.com/iminolee/cpp_project_template.git
cd ~/cpp_project_template/
cmake -S . -B build
cmake --build build
cd build/application/
./printing_hello_world
```
