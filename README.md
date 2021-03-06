[![Build Status](https://travis-ci.org/hexlet-codebattle/battle_asserts.svg?branch=master)](https://travis-ci.org/hexlet-codebattle/battle_asserts)
[![Hexlet chat](http://slack-ru.hexlet.io/badge.svg)](http://slack-ru.hexlet.io)

## Setup for development

* Install [leiningen](http://leiningen.org)

## Contributing

1. Fork it
2. Clone repo (`https://github.com/{your-nickname}/battle_asserts.git`)
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Make changes
5. Run tests (`make test`).
6. Commit your changes (`git commit -am 'Added some feature'`)
7. Push to the branch (`git push origin my-new-feature`)
8. Create new Pull Request
9. Check if Request passed Travis-Ci

## How to add a new problem

You have to write the description of the problem and the correct implementation. See examples in `src/battle_asserts/issues`. Corresponding tests are in `test/battle_asserts/issues`.

A problem file includes:

* `level` — difficulty of the problem; possible values are `elementary`, `easy`, `medium`, `hard`.
* `description` — detailed description of the problem.
* `test-data` — data in a specified format which will be used to test solutions. The first element in this list will be displayed as an example to players, so it should clarify and illustrate the problem as much as possible. Do not choose a trivial case for this example.
* `arguments-generator` — arguments generator for the `solution` function;
    generated arguments will be used to test players' solutions.
* `solution` — implemented correct solution.

Test file includes a call to a test generator (the same for all tests).

## Related links

### Leiningen

* http://leiningen.org/#install
* https://github.com/technomancy/leiningen/blob/stable/doc/TUTORIAL.md
