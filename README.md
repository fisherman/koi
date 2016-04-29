[travis-link]: https://travis-ci.org/fisherman/fisherman
[travis-badge]: https://img.shields.io/travis/fisherman/fisherman.svg

# Koi

Project scaffolder.

## Install

With [fisherman]

```
fisher koi
```

## Usage

```
koi your/repo folder
```

## Templates
### .intro

At times you want to present or explain some info to the template user. This can be done by writing text in `.intro`. Only the first 10 lines will be printed during the scaffolding process, to encourage conciseness.

### .vars
Your template folder should have a `.vars` file in the root directory. Write each variable name in a separate line as follows:

```
foo
bar
baz
```

`koi` will substitute all appearances of `{{{variable-name}}}` in files with user-input during the scaffolding process. For example of a template, look at [koi-template].

## Credit

Much of the code was based off [fisherman/new], written by @bucaran.

[slack-link]: https://fisherman-wharf.herokuapp.com
[slack-badge]: https://fisherman-wharf.herokuapp.com/badge.svg
[fisherman]: https://github.com/fisherman/fisherman

[fisherman/new]:https://github.com/fisherman/new
[koi-template]: https://github.com/jethrokuan/koi-template
