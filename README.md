sass
====

Use this image to watch a directory of SASS files and automatically compile on change.

Usage:

``` bash
$ docker run --rm -ti -v $PWD/sass:/src -v $PWD/css:/css anbraten/sass -rw -o /css /src
```

Where `$PWD/sass` is the directory containing your sass files and `$PWD/css` the directory compiled css files are placed in.

