[![Build Status](https://travis-ci.org/slightlynybbled/tk_tools.svg?branch=master)](https://travis-ci.org/slightlynybbled/tk_tools)

[![Documentation Status](https://readthedocs.org/projects/tk-tools/badge/?version=latest)](http://tk-tools.readthedocs.io/en/latest/?badge=latest)

# Purpose

This repository holds useful high-level widgets written in pure python.  
This library used type hints and requires Python 3.5+; it could, however, be back-ported to earlier Python versions without difficulty.

Here are some examples screenshots of the widgets you can create:

#### Button-Grid:  
![Button-Grid](https://raw.githubusercontent.com/slightlynybbled/tk_tools/master/docs/img/button-grid.png)
#### Byte-Label:  
![Byte-Label](https://raw.githubusercontent.com/slightlynybbled/tk_tools/master/docs/img/byte-label.png)
#### Calendar:  
![Calendar](https://raw.githubusercontent.com/slightlynybbled/tk_tools/master/docs/img/calendar.png)
#### Dropdown:  
![Dropdown](https://raw.githubusercontent.com/slightlynybbled/tk_tools/master/docs/img/dropdown.png)
#### Entry-Grid:  
![Entry-Grid](https://raw.githubusercontent.com/slightlynybbled/tk_tools/master/docs/img/entry-grid.png)
#### Graph:  
![Graph](https://raw.githubusercontent.com/slightlynybbled/tk_tools/master/docs/img/graph.png)
#### Key-Value:  
![Key-Value](https://raw.githubusercontent.com/slightlynybbled/tk_tools/master/docs/img/key-value.png)
#### Label-Grid:  
![Label-Grid](https://raw.githubusercontent.com/slightlynybbled/tk_tools/master/docs/img/label-grid.png)
#### LED: (size can be scaled)  
![LED](https://raw.githubusercontent.com/slightlynybbled/tk_tools/master/docs/img/led.gif)
#### Rotary-Scale: (Tachymeter)    
![Rotary-Scale](https://raw.githubusercontent.com/slightlynybbled/tk_tools/master/docs/img/rotary-scale.png)

For more details, check out the [documentation](https://tk-tools.readthedocs.io).

# Testing

Currently, only style-level tests are implemented.  To execute:

    flake8 tk_tools

# Contributions

Contributions for new widgets, documentation, tests, and resolving issues are welcome.

Contribution guidelines:

1. Fork the repository to your account.
2. Clone your account repository to your local development environment.
3. Create/checkout a new branch appropriately named by feature, bug, issue number, whatever.
4. Make your changes on your branch. The ideal changes would:

 - have working examples in the examples directory
 - have documentation in the docs directory

5. Push your changes to your github account.
6. Create a pull request from within github.

All code is to be passing `flake8` before it is merged into master!
