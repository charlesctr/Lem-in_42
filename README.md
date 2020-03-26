<h1 align="center">Welcome to Lem-in_42 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
  </a>
</p>

<h1>What is Lem-in ?</h1> 

<p>

* The lem-in project at 42 consists in writing a program that takes an undirected graph (an anthill composed of connected rooms) and computes the most efficient way to move N ants from source node to sink node.

* It serves as an introduction to graph theory and maximum flow problems. </p>


## Install

```sh
Usage:

	make <command> :

- lemin:	Compilation and creation of lem-in binary
- lib:		Compilation of libft library
- norm		Check
- clean:	Delete only object files from library and lem-in
- fclean:	Delete all object files and binay from lem-in and libft
- re:		Recompile lem-in project
- help:		Display this usage section

Makefile compatible with multithreading :

make lemin -j8
```

## Usage

```sh
./lem-in [-l] < path/to/map

Exemple :

./lem-in < ./maps/map2ch
3
##start
A 0 0
B 1 1
C 2 2
D 3 3
E 4 4
F 5 5
G 6 6
##end
H 7 7
A-B
A-C
B-E
C-D
C-F
E-F
D-G
F-H
G-H

L1-B L2-C
L1-E L2-D L3-B
L1-F L2-G L3-E
L1-H L2-H L3-F
L3-H
```

## Run tests

![alt text](https://github.com/charlesctr/Lem-in_42/blob/master/menu_lem-in.png)

![alt text](https://github.com/charlesctr/Lem-in_42/blob/master/check_lem-in.png)



```sh
./lemincheck.sh
```

## Authors

👤 **Charles**

* GitHub: [@charlesctr](https://github.com/charlesctr)

👤 **Florian**

* GitHub: [@therrythecreator](https://github.com/therrythecreator)

## 📝 License

Copyright © 2020 [Charles Ctr] (https://github.com/charlesctr).<br />
***
