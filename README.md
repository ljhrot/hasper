# Hasper

This is a port of Ghost's default theme [Casper](https://github.com/tryghost/casper) for Jekyll inspired by [Jasper](https://github.com/jekyller/jasper).

## Live demo

[Hasper Live Demo](https://ljhrot.github.io/hasper)

[Casper's Original Here](https://demo.ghost.io)

## How to use it

**Requirement:** [Hugo](https://github.com/gohugoio/hugo)

### 1. Create a New Site 

``` bash
$ hugo new site quickstart
```

### 2. Add the `hasper` Theme

``` bash
$ cd quickstart
$ git init
$ git submodule add https://github.com/ljhrot/hasper.git themes/hasper
$ echo 'theme = "hasper"' >> config.toml
```

### 3. Add Some Content

``` bash
$ cp themes/hasper/archetypes/default.md archetypes/default.md
$ hugo new posts/my-first-post.md
```

Edit the newly created content file if you want, it will start with something like this:

```
---
layout: post
cover: 
navigation: true
title: "My First Post"
date: 2020-08-21T23:36:45+08:00
draft: true
tags: 
logo: 
author: 
comment: false
---
```

### 4. Start the Hugo server
Now, start the Hugo server with drafts enabled:

```bash
$ hugo server -D
```

**Navigate to your new site at http://localhost:1313/.**

### 5. Next

**Important:** You will find a demo in [exampleSite](https://github.com/ljhrot/hasper/tree/master/exampleSite). Take a look at the files in this folder, 
especially config.toml and data folder.

## Thanks

- [Jasper](https://github.com/jekyller/jasper)

## Copyright & License

Same licence as the one provided by Ghost's team. See Casper's theme [license](GHOST.txt).

Copyright (C) 2015-2017 - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
