# dokku-wkhtmltopdf 2023

 is an awesome plugin for [dokku][dokku] that properly installs the wkhtmltopdf into the docker instance.

This is a fork from [dokku-wkhtmltopdf][https://github.com/mbriskar/dokku-wkhtmltopdf] with updated libraries for 2023

## Installation

On your dokku server:
```sh
dokku plugin:install https://github.com/mbriskar/dokku-wkhtmltopdf.git wkhtmltopdf
```

All future deployments will have dokku-wkhtmltopdf installed.

## License

The MIT License (MIT)

Copyright (c) 2015 Matej Briškár && 2023 Pedro Schlickmann Mendes

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
