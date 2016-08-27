# Overview

[Patrick Walls](https://github.com/patrickwalls) convened and delivered the [UBC Scientific Software Seminar](https://github.com/patrickwalls/ubc-scientific-software-seminar) this summer [at UBC](http://www.math.ubc.ca/).

This is an example site built up from Patrick's content using [`minidocs`](https://github.com/freeman-lab/minidocs) leveraging [binder](http://mybinder.org/). 

All the notebooks: [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/patrickwalls/ubc-scientific-software-seminar)

### how minidocs works

I made a folder called `git-to-scikit` with a subfolder called `markdown` containing markdown files, and a `contents.json` file specifying some organizational structure. Then I ran this command in a terminal in the `git-to-scikit` folder:

```minidocs markdown/ -c contents.json -o site -l pims3.png```

![minidocs](https://wwejubwfy.s3.amazonaws.com/1._bash-2016-08-26-23-15-38.jpg) 

### how binder works

tbd...