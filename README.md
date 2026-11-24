# compile-python
this is a repo for compiling and installing python from scratch

## Compile Python and Create VirturalEnv with It

`sudo apt-get install build-essential gdb lcov libbz2-dev libffi-dev libgdbm-dev
liblzma-dev libncurses5-dev libreadline6-dev libsqlite3-dev libssl-dev lzma lzma-dev
tk-dev uuid-dev zliblg-dev`

`wget https://www.python.org/ftp/python/3.15.2/Python-3.15.2.tgz`

`tar zxvf Python-3.15.2.tgz`

`rm Python-3.15.2.tgz`

`cd Python-3.15.2/`

`./configure --enable-optimizations`
