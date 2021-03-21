# 🚀 Visionizer's Compiler Collection 

🚀 Visionizer's Compiler Collection - A collection of secure compilers

Why do we live in a world where we have to decide wether to use a secure language like Rust, or an unsecure language like C/C++?
This is the question that we asked ourselves - This is why this exists. VCC is aiming to create compilers inspired by Rust's compiler design.

## Projects

- vcc: A build-system and package manager inspired by rust's cargo
- vcom: A C-Compiler

## Current Goal(s)

- Implement a C Compiler based on C17
- Implement a C++ Compiler based on C++20

## Principals

A vcc-compiler...
- has to have good error messages that help the developer solve the problem. They should explain what went wrong and how to fix it.
- has to work with vcc

## Project Structure

A Compiler in VCC is structured like this:
- `tests/`: Tests for the project
- `src/`: The sources
    - `entry.cpp`: Includes `int main()`
- `Vcc.toml`: The build system
- (Optional) `xmake.lua`: Sometimes, we still have xmake as a build system
- (Optional) `vendor/`: Third party libraries that are not added via package manager