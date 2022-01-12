# Loan Qualifier App
An application for filtering a csv list of loans and creating a list of just the ones you qualify for.

---

## Technologies
This project uses Python 3 in addition to the following libraries and add ons:

* [csv](https://docs.python.org/3/library/csv.html) for reading from and writing to csv files.

* [sys](https://google.github.io/python-fire/guide/) for the exit function.

* [fire](https://docs.python.org/3/library/csv.html) for creating the CLI.

* [questionary](https://github.com/tmbo/questionary) for asking questions through the CLI.

* [pathlib](https://docs.python.org/3/library/pathlib.html) for the path functions to locate the csv files.



## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install fire
pip install questionary
```

---

## Usage

After running the app through a terminal such as Gitbash, you will go through the following steps:
* You will be asked to provide the directory for a rate sheet csv.
* You will be asked to provide your credit score.
* You will be asked to provide your monthly debt.
* You will be asked to provide your monthly income.
* You will be asked to provide the loan amount you are looking for.
* You will be asked to provide your current home value.

After this you will be told the number of loans you qualify for and be asked if you would like to save the filtered list as a csv file.
* If you choose "No", the app terminates.
* If you choose "Yes", you will be asked to provide a directory for the location you want the list saved.

![Image of app running in terminal](https://user-images.githubusercontent.com/96391748/149060732-03ceb66c-4174-4ee9-9d6a-c74cc444a6b1.png)


---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE