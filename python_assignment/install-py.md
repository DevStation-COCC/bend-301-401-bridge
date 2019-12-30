# Python 3 Installation Instructions

[Back to README.md](README.md)

## Mac
You can use Homebrew to search for everything you can install with the brew search command, but to provide us with a shorter list, let’s instead search for just the available Python-related packages or modules:

```
$ brew search python
```

The Terminal will output a list of what you can install, like this:

```
app-engine-python          micropython                python3                 
boost-python               python                     wxpython                 
gst-python                 python-markdown            zpython                  
homebrew/apache/mod_python               homebrew/versions/gst-python010        
homebrew/python/python-dbus              Caskroom/cask/kk7ds-python-runtime     
homebrew/python/vpython                  Caskroom/cask/mysql-connector-python   

```

Python 3 will be among the items on the list. Let’s go ahead and install it:

```
$ brew install python3
```

The Terminal window will give you feedback regarding the installation process of Python 3, it may take a few minutes before installation is complete.

Along with python 3, homebrew will install pip.

you can use pip to install and manage programming packages you may want to use in our projects. You can install Python packages by typing:

```
$ pip3 install package_name
```
Here, `package_name` can refer to any Python package or library.

To update your version of Python 3, you can first update Homebrew and then update Python:

```
$ brew update
$ brew upgrade python3
```

## WSL/Linux
Update repositories:
```
$ sudo apt-get update
```

Install Python 3
```
$ sudo apt install python3.6
```

Along with python 3, apt will install pip.

you can use pip to install and manage programming packages you may want to use in our projects. You can install Python packages by typing:

```
$ pip3 install package_name
```
Here, `package_name` can refer to any Python package or library.

[Back to README.md](README.md)