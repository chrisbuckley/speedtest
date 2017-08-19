speedtest
=========

Simple bandwidth test in browser javascript.


Example
-------

https://frankl.in/speedtest/

You can change the number precision up to 3 decimals using the arrow
keys on your keyboard.


Installation
------------

Just clone the repo or download the `speedtest.htm` file.

To keep the repository small I have not included the test binaries.
You can download them from my server, **please don't hotlink them!!**

* [1mb.bin](https://frankl.in/speedtest/1mb.bin)
* [5mb.bin](https://frankl.in/speedtest/5mb.bin)
* [10mb.bin](https://frankl.in/speedtest/10mb.bin)
* [100mb.bin](https://frankl.in/speedtest/100mb.bin)

Or generate them yourself:

The `of=` specifies the output filename and `bs=` the filesize in bytes
where the M suffix is megabytes and G is gigabytes.

```sh
# 100mb.bin
$ dd if=/dev/zero of=100mb.bin bs=100M count=1
```


Unlicense
---------

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>


Author
------

[Franklin van de Meent](https://frankl.in)

Do you like this project?
Please consider to [buy me a coffee](https://ko-fi.com/franklin).
