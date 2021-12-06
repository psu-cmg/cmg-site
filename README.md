[cmg.psu.edu](http://cmg.psu.edu) ![Build and Deploy](https://github.com/psu-cmg/cmg-site/actions/workflows/build-and-deploy.yml/badge.svg?branch=master)
===

### Hugo

We use [Hugo](https://gohugo.io/) to build our site.  Installation instructions can be found [here](https://gohugo.io/getting-started/installing/).

## Usage

You can clone the repo using:

```
$ git clone --recursive https://github.com/psu-cmg/cmg-site.git
```

or

```
$ git clone https://github.com/psu-cmg/cmg-site.git
$ cd cmg-site
$ git submodule update --init --recursive
```

You can build the site using:

```
$ cd cmg-site
$ hugo
```

You can test out the site using:

```
$ hugo server
```

