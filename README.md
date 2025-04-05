# testing GH actions

* 1
* 2
* 3
* 4
* 5

1. foo
1. bar
1. baz
1. qux
1. quux

## hyperlink checking

Some actions only support HTML which isn't conducive for checking Markdown hyperlinks!

I'm more so after validating external hyperlinks as opposed to relative links.

* [link-check-action](https://github.com/marketplace/actions/link-check-action)
   * requires statically defining file name
* [markdown-link-check](https://github.com/marketplace/actions/markdown-link-check)
   * deprecated? Readme refers to linkspector below
* [action-linkspector](https://github.com/UmbrellaDocs/action-linkspector)
* [lychee-action](https://github.com/lycheeverse/lychee-action)
   * written in Rust

Time for a broken/invalid ~bare link~ ([no bare links says the MDLinter](https://github.com/clearly/broken))
and an [invalid Markdown link](https://github.com/yeah/this/is/broken).
How about an [invalid website](https://gggithuuub.com) too?