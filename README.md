# Project 
    - cpp
    - poco
    - mongo

# Dependencias
    - c++
    - poco
    - vcpkg

# Install poco - vcpkg
    Step 1: Clone the vcpkg repo

        git clone https://github.com/Microsoft/vcpkg.git

        Make sure you are in the directory you want the tool installed to before doing this.

    Step 2: Run the bootstrap script to build vcpkg

        .\vcpkg\bootstrap-vcpkg.bat

# Install libraries for your project
    - vcpkg install [packages to install]