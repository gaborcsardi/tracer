


# tracer

> Slick Call Stacks

[![Project Status: WIP - Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip)
[![Linux Build Status](https://travis-ci.org/mangothecat/tracer.svg?branch=master)](https://travis-ci.org/mangothecat/tracer)
[![Windows Build status](https://ci.appveyor.com/api/projects/status/github/mangothecat/tracer?svg=true)](https://ci.appveyor.com/project/gaborcsardi/tracer)
[![](http://www.r-pkg.org/badges/version/tracer)](http://www.r-pkg.org/pkg/tracer)
[![CRAN RStudio mirror downloads](http://cranlogs.r-pkg.org/badges/tracer)](http://www.r-pkg.org/pkg/tracer)

Better looking call stacks after an error.

## Installation


```r
source("https://install-github.me/mangothecat/tracer")
```

## Usage


```r
library(tracer)
```

After an error, call `tb()` instead of `traceback()`, to get a nice
error stack:

![](/inst/screenshot1.png)

To browse the code of the locations on the calls, supply the number of
the call to `tb()`:

![](/inst/screenshot2.png)

Note the `tracer` can often show you the (deparsed) source code with the
call location, even if the original R source code is no more available,
like in the case of installed packages.

## License

MIT © Mango Solutions
