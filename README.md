# testing GH actions

* 1
* 2
* 3
* 4
* 5

1. foo
1. bar

## hyperlink checking

Some actions only support HTML which isn't conducive for checking Markdown hyperlinks!

I'm more so after validating external hyperlinks as opposed to relative links.

* https://github.com/marketplace/actions/link-check-action
  * requires statically defining file name
* https://github.com/marketplace/actions/markdown-link-check
  * deprecated? Readme refers to linkspector below
* https://github.com/UmbrellaDocs/action-linkspector
* https://github.com/lycheeverse/lychee-action
  * written in Rust

Time for a broken/invalid bare link (https://github.com/clearly/broken) and an [invalid Markdown link](https://github.com/yeah/this/is/broken). How about an [invalid website](https://gggithuuub.com) too?
