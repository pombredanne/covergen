# Covergen ![Coverage](http://img.shields.io/badge/coverage-100.0%25-brightgreen.svg)


Autoupdate a coverage badge in your README.md with this one dumb trick!

To try it out:

```shell
go get github.com/natefinch/covergen
```

Then run go test:

```shell
go test
```

Now check out the README.md ... it is updated automagically!  No other commands need be run.

Check out covergen_test.go for how it works.

The only drawback is that you more than double the time it takes to run your tests...
