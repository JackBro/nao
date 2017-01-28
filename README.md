# nao
```nao(no-meaning assembly omiter)``` is dead code eliminator plugin for IDA pro.

before:

![before](./before.png)

after:

![after](./after.png)


## Requirement
- IDAPython
- [Unicorn](http://www.unicorn-engine.org/) and Python binding

### How to Install Unicorn
Please follow the link.

[Download – Unicorn – The ultimate CPU emulator](http://www.unicorn-engine.org/download/)

## Installation
Please run ```nao.py``` as the IDAPython script.
After you run nao.py, you'll see ```eliminate dead code``` button on edit menu.

![edit_menu](./edit_menu.png)

## Usage
```Shift-D``` display eliminated disassemble code from current function.

## Licence
[GPL v3 license](LICENCE)
