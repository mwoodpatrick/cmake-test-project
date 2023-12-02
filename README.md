# cmake-test-project
Simple cmake example

A simple cmake example based on [How to Install CMake on Debian 12, 11 or 10](https://www.linuxcapable.com/how-to-install-cmake-on-debian-linux/#Section-3-Test-CMake-Installation-with-a-Sample-Program-on-Debian-12-11-or-10)
```
sudo apt update
sudo apt upgrade
sudo apt install cmake
cmake --version
mkdir cmake-test-project
 cd cmake-test-project
nvim main.cpp
 nvim CMakeLists.txt
mkdir build && cd build
 cmake ..
make
 ./cmake_test_project
	Hello, CMake!
gh repo create
	? What would you like to do? Push an existing local repository to GitHub
	? Path to local repository .
	? Repository name cmake-test-project
	? Repository owner mwoodpatrick
	? Description Simple cmake example
	? Visibility Public
	✓ Created repository mwoodpatrick/cmake-test-project on GitHub
	X Sorry, your reply was invalid: "t" is not a valid answer, please try again.
	? Add a remote? Yes
	? What should the new remote be called? origin
	✓ Added remote git@github.com:mwoodpatrick/cmake-test-project.git
```

Also see:

* [Markdown Guide](https://www.markdownguide.org)
* [Codespaces](https://github.com/codespaces)
