Adaption of the of [repository](https://github.com/username/repository) theme.

## Installation

To install Contrast as your default theme, first install this repository in the `themes/` directory:

    $ cd themes/
    $ git clone https://github.com/username/repository.git

Second, specify `repository` as your default theme in the `config.toml` file. Just add the line

    theme = "repository"

at the top of the file.

### Example config

```
title = "Blog"
author = "username"
theme = "repository"

[params]
  minimal = false
  excerpts = false
  description = "my blog"

[menu]
  [[menu.main]]
    identifier = "about"
    name = "About"
    url = "/about/"
    weight = 10
```
