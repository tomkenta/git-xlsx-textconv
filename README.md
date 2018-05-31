# git-xlsx-textconv - git text converter for xlsx file

git diff wrapper for xlsx file.

<img src="http://t.co/5Epi6NXHZ5">

# install

    $ go get github.com/tomkenta/git-xlsx-textconv
    
# .gitconfig

    [diff "xlsx"]
        binary = true
        textconv = $GOPATH/bin/git-xlsx-textconv

# .gitattributes in your project repository

    *.xlsx diff=xlsx

# LICENSE

Golang port is:

    The MIT License (MIT)
    Copyright © 2014 Tokuhiro Matsuno, http://64p.org/ <tokuhirom@gmail.com>

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the “Software”), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.

Original Perl version is:

    Copyright (C) Kazuhiro Osawa 2014-

    This library is free software; you can redistribute it and/or modify
    it under the same terms as Perl itself.

# SEE ALSO

This command is ported from Perl version.

Ref. https://github.com/yappo/p5-git-xlsx-textconv.pl

There is python port:

https://gist.github.com/nmz787/c43bc109db915064f188
