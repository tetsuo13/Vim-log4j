# log4php Syntax for Vim

Adds syntax highlighting for [log4j](http://logging.apache.org/log4j/) and
[log4php](http://logging.apache.org/log4php/) log files. Initially created to
solve log4php syntax highlighting.

## Installation

Copy `log4j.vim` into your `~/.vim/syntax` directory. Because there is no
reliable method of detecting log files generated from log4j/log4php, you can
output log files have a `.log` extension and add the following to your
`~/.vimrc` file to trigger the syntax highlighting:

    autocmd BufRead,BufNewFile *.log set syntax=log4j

If renaming log file extensions is not possible or desirable you can specify
the exact name or pattern for the log files:

    autocmd BufRead,BufNewFile program_log set syntax=log4j

## License

### This code is free to use under the terms of the MIT license.

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
