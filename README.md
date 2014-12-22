dockerfile-imapsync
===================

Dockerfile for imapsync

Based on:
* Repository [skempken/dockerfile-imapsync](https://github.com/skempken/dockerfile-imapsync)
* Build instructions for imapsync here:
  * http://teamflawless.org/2012/installing-and-using-imapsync-on-ubuntu/


Usage
-----

```bash
$ docker run gissehel/imapsync <usual imapsync arguments>
```

or 

```bash
$ alias imapsync='sudo docker run -i gissehel/imapsync'
```

and then

```bash
$ imapsync <usual imapsync arguments>
```
