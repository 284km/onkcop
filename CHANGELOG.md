# onkcop

## v0.47.1.2 (2017-03-01)

[full changelog](https://github.com/onk/onkcop/compare/v0.47.1.1...v0.47.1.2)

* Change `Style/StringLiteralsInInterpolation` to `double_quotes` style.


## v0.47.1.1 (2017-03-01)

[full changelog](https://github.com/onk/onkcop/compare/v0.47.1.0...v0.47.1.1)

* Update `rubocop-rspec` v1.12.0.
* Enable `Style/StringMethods` cop.
* Enable `Style/StringLiteralsInInterpolation` cop.
* Change `RSpec/DescribedClass` to `explicit` style.
* Exclude `*.gemspec` from `Metrics/BlockLength` cop.
* Disable `Lint/EmptyWhen` cop.


## v0.47.1.0 (2017-01-20)

[full changelog](https://github.com/onk/onkcop/compare/v0.46.0.1...v0.47.1.0)

* Update to `rubocop` v0.47.1 and `rubocop-rspec` v1.10.0.
* Remove `Style/SingleLineBlockParams` cop config because disabled by default.
* Disable new `Security/YAMLLoad` cop.


## v0.46.0.1 (2017-01-07)

[full changelog](https://github.com/onk/onkcop/compare/v0.46.0.0...v0.46.0.1)

* Update to `rubocop-rspec` v1.9.1.
* Disable `RSpec/MessageExpectation` cop that is replaced with a new cop: `RSpec/MessageSpies`.
* Add CLI for setup `.rubocop.yml`.


## v0.46.0.0 (2016-11-30)

[full changelog](https://github.com/onk/onkcop/compare/v0.45.0.0...v0.46.0.0)

* Update to `rubocop` v0.46.0.
* Use new `Style/EmptyMethod` cop with `expanded` style.
* Use `Style/TernaryParentheses` cop `require_parentheses_when_complex` style.


## v0.45.0.0 (2016-11-02)
[full changelog](https://github.com/onk/onkcop/compare/v0.44.1.1...v0.45.0.0)

* Update to `rubocop` v0.45.0 and `rubocop-rspec` v1.8.0.
* Disable new `RSpec/ImplicitExpect` cop.
* Explicitly enable `Rspec/MessageExpectation` cop that is now disabled by default.
* Exclude Gemfile, Guardfile on `Metrics/BlockLength`.
* Disable `Style/TernaryParentheses` cop.
* Enable `Rails/HttpPositionalArguments` cop that fixes bug.
