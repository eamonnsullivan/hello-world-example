# hello-world-example

FIXME: my new application.

## Installation

Download from https://github.com/eamonnsullivan/hello-world-example

## Usage

FIXME: explanation

Run the project directly, via `:exec-fn`:

    $ clojure -X:run-x
    Hello, Clojure!

Run the project, overriding the name to be greeted:

    $ clojure -X:run-x :name '"Someone"'
    Hello, Someone!

Run the project directly, via `:main-opts` (`-m eamonnsullivan.hello-world-example`):

    $ clojure -M:run-m
    Hello, World!

Run the project, overriding the name to be greeted:

    $ clojure -M:run-m Via-Main
    Hello, Via-Main!

Run the project's tests (they'll fail until you edit them):

    $ clojure -M:test:runner

Build an uberjar:

    $ clojure -X:uberjar

Run that uberjar:

    $ java -jar hello-world-example.jar

## Options

FIXME: listing of options this app accepts.

## Examples

...

### Bugs

...

### Any Other Sections
### That You Think
### Might be Useful

## License

Copyright © 2021 Eamonn

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
