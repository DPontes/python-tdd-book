# "Test Driven Development With Python" [Book](https://www.obeythetestinggoat.com/pages/book.html#toc)

This repository will include all the code present in the above mentioned book, at the pace that I will have the execises completed.

It will hopefully have more in-depth comments than the ones present in the original repo, as suited to me for my current and future understanding.

## Tips

While following the book, make sure you have the Python Virtual Environment activated (see [prerequisites](https://www.obeythetestinggoat.com/book/pre-requisite-installations.html) for instructions).
The activation command is (for Mac/Linux):
```bash
python3.6 -m venv virtualenv
source virtualenv/bin/activate
```

To get the server up and running:
```bash
python manage.py runserver
```

To run the functional tests
```bash
python manage.py test functional_tests
```

To run the unit tests
```bash
python manage.py test lists
```
