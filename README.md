# interleave-pdf

A simple Python program for interleaving pdf documents (inserting blank pages inbetween the regular printed leaves).

It was motivated by the desire to print lecture notes on a landscape a4 page with the pdf content on one side and blank space to take notes during lectures on the other. This is something not usually achievable using normal printer drivers. Once the document is interleaved all that is required is selecting landscape orientation and choosing two (or four) pages per sheet.

# Quickstart

1. [Download latest release] and unzip it.

    Or, clone this repository and checkout latest release
```bash
$ git clone git@github.com:nyxgear/interleave-pdf.git

$ cd interleave-pdf

# checkout the latest version
$ git checkout v0.1.0
```

2. (Optional) Create and activate a virtual environment

```bash
# being inside the project directory

# install python virtualenv
$ sudo apt-get install python3-venv

# create the virtual env
$ python3 -m venv venv

# activate it
$ source venv/bin/activate
```

3. Install dependencies

    Interleave-pdf requires PyPDF2 for the pdf operations and tkinter for the GUI.

    Install them with

```bash
(venv) $ sudo apt-get install python3-tk

(venv) $ pip3 install -r requirements.txt
```


4. Run and use interleave-pdf

```bash
# only if you created a virtual env and/or the virtualenv is not yet active
$ source venv/bin/activate

(venv) $ python3 interleave-pdf.py
```

 [Download latest release]: https://github.com/sproberts92/interleave-pdf/releases
 