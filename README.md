# Docker PowerShell

A Docker image that runs PowerShell. On Linux.

[![Docker Status](https://images.microbadger.com/badges/image/lambda3/powershell.svg)](https://hub.docker.com/r/lambda3/docker-powershell/)
[![License](https://img.shields.io/badge/licence-Apache%20License%202.0-blue.svg)](https://github.com/Lambda3/docker-powershell/blob/master/LICENSE.txt)
[![Issues open](https://img.shields.io/github/issues-raw/Lambda3/docker-powershel.svg)](https://huboard.com/Lambda3/docker-powershel)

## Running

To enter PowerShell interactivelly (the CLI):

````powershell
docker run -ti lambda3/powershell
````

You can also run it as an executable. This will list the files and exit:

````powershell
docker run -ti lambda3/powershell Get-ChildItem
````

## Maintainers/Core team

* [Giovanni Bassi](http://blog.lambda3.com.br/L3/giovannibassi/), aka Giggio, [Lambda3](http://www.lambda3.com.br), [@giovannibassi](https://twitter.com/giovannibassi)

Contributors can be found at the [contributors](https://github.com/Lambda3/docker-powershell/graphs/contributors) page on Github.

## Contact

Twitter is the best option.

## License

This software is open source, licensed under the Apache License, Version 2.0.
See [LICENSE.txt](https://github.com/Lambda3/docker-powershell/blob/master/LICENSE.txt) for details.
Check out the terms of the license before you contribute, fork, copy or do anything
with the code. If you decide to contribute you agree to grant copyright of all your contribution to this project, and agree to
mention clearly if do not agree to these terms. Your work will be licensed with the project at Apache V2, along the rest of the code.
