### v1.1.3

- project-away, project-rename
- skipvalidation
- conversions (toint, tohex, ...)
- deprecated todynamic (in favor of parse_json)
- strcat_array. deprecated array_strcat
- deprecated makelist, makeset, make_dictionary

### v1.1.2

- Add `true`, `false` as constants. These were accidentally removed when forking.

### v1.1.1

- Allow whitespace between function name and opening paren, e.g. `materialize (` is now supported. Before, it had to be `materialize(`.
- All functions are scoped as `support.function` now, instead of some being `keyword.function.kusto`, which, for many themes, shares a color with `keyword.operator.kusto` which does not parse well for humans.

### v1.1.0

> First version forked off https://github.com/josin/kusto-syntax-highlighting

Comprehensive scope inclusion for (almost) all builtins listed in the [Kusto docs](https://aka.ms/kdocs):
 - data types
 - query statement keywords
 - tabular operators
 - `evaluate` plugins
 - join kinds
 - join strategies
 - series analysis functions
 - parse kinds
 - render kinds
 - scalar operators
 - scalar functions

Also specific inclusion of the `.create-or-alter` control command.

## 1.0.1

- Adding logo for the extension

## 1.0.0

- Initial release
