.. image:: http://applejack.science.ru.nl/lamabadge.php/python-ucto
   :target: http://applejack.science.ru.nl/languagemachines/

Ucto for Python
=================

This is a Python binding to the tokenizer Ucto. Tokenisation is one of the first step in almost any Natural Language Processing task, yet it is not always as trivial a task as it appears to be. This binding makes the power of the ucto tokeniser available to Python. Ucto itself is a regular-expression based, extensible, and advanced tokeniser written in C++ (https://languagemachines.github.io/ucto).

Installation
----------------

Easy
~~~~~~~~~~

For easy installation, please use our LaMachine distribution (https://proycon.github.io/LaMachine).

Manual
~~~~~~~~~~~~

 * Make sure to first install ucto itself (https://languagemachines.github.io/ucto) and all its dependencies
 * Install Cython if not yet available on your system: ``$ sudo apt-get cython cython3`` (Debian/Ubuntu, may differ for others)
 * Run:  ``$ sudo python setup.py install``   (Make sure to use the desired version of python)


Test and Example
----------------------

Run and inspect ``example.py`` (Python 3) or ``example2.py`` (Python 2) for testing and documentation.








