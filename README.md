# Bitcoin_Arbitrage

This project uses Jupyter lab and pandas to analyze historical Bitcoin price data and look for arbitrage opportunities.

---

## Technologies

This code was written on Windows 11 running python 3.7.13. It also uses Pandas (Version 1.3.5) and Jupyterlab (Version 3.3.2)

---

## Installation Guide

Both Pandas and Jupyterlab can be installed using the pip install function.

---

## Usage

This was a project to investigate historical Bitcoin arbitrage opportunites from Bitstamp and Coinbase. While it is possible to replace the csv files with your own to investigate other exchanges, adding a third would require adding additional functionality. If you want to edit the dates that are being used in the notebook, simply change these date locations

```.loc['2018-01-15']```

To a month or day included in the dataset that you would like to see.
Here is an example plot from the notebook. Note the .loc date selection.

![Screenshot of the app.](Challenges/bitcoin_arbitrage/Resources/bitcoin_plot_screenshot.png)

---

## Contributors

Garrett Hernandez -gtkhhz@gmail.com

---

## License

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

For more information, please refer to <https://unlicense.org>
