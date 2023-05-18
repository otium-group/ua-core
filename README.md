uap-core
========

This repository contains the core of [BrowserScope][2]'s original [user agent string parser][3]: data collected over the years by [Steve Souders][4] and numerous other contributors, extracted into a separate [YAML file][5] so as to be reusable _as is_ by implementations in any programming language.

This repo itself does _not_ contain a parser: only the necessary data to build one. There exists a ref implementation, along with multiple, production-ready implementations in various programming languages.

License
-------

The data contained in `regexes.yaml` is Copyright 2009 Google Inc. and available under the [Apache License, Version 2.0][6].

[2]: http://www.browserscope.org
[3]: http://code.google.com/p/ua-parser/
[4]: http://stevesouders.com/
[5]: https://raw.github.com/ua-parser/uap-core/master/regexes.yaml
[6]: http://www.apache.org/licenses/LICENSE-2.0
