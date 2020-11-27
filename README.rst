========
py-br-boleto
========

.. _py-br-boleto-synopsis:

O projeto original pode ser encontrado aqui: https://github.com/eduardocereto/pyboleto

py-br-boleto provides a python class to generate "boletos de cobranca" as these
are the Brazilian equivalent for invoices.

It's easy to implement classes for new banks.

This class is still in development and currently has no documented API.

.. _py-br-boleto-implemented-bank:

Implemented Banks
=================

You can help writing code for more banks or printing and testing current
implementations.

For now here's where we are.

 +----------------------+----------------+-----------------+------------+
 | **Bank**             | **Carteira /** | **Implemented** | **Tested** |
 |                      | **Convenio**   |                 |            |
 +======================+================+=================+============+
 | **Banco do Brasil**  | 18             | Yes             | Yes        |
 +----------------------+----------------+-----------------+------------+
 | **Banrisul**         | x              | Yes             | Yes        |
 +----------------------+----------------+-----------------+------------+
 | **Bradesco**         | 06, 03         | Yes             | Yes        |
 +----------------------+----------------+-----------------+------------+
 | **Caixa Economica**  | SR             | Yes             | No         |
 +----------------------+----------------+-----------------+------------+
 | **HSBC**             | CNR, CSB       | Yes             | No         |
 +----------------------+----------------+-----------------+------------+
 | **Itau**             | 157            | Yes             | Yes        |
 +----------------------+----------------+-----------------+------------+
 | **Itau**             | 175, 174, 178, | Yes             | No         |
 |                      | 104, 109       |                 |            |
 +----------------------+----------------+-----------------+------------+
 | **Real**             | 57             | Yes             | No         |
 +----------------------+----------------+-----------------+------------+
 | **Santander**        | 102            | Yes             | Yes        |
 +----------------------+----------------+-----------------+------------+
 | **Santander**        | 101, 201       | Yes             | No         |
 +----------------------+----------------+-----------------+------------+

.. _py-br-boleto-docs:

Documentation
=============

http://packages.python.org/py-br-boleto/

The best way to learn how to create Boletos using py-br-boleto is to look at the
examples at `pdf_py-br-boleto_sample.py`_ or `html_py-br-boleto_sample.py`_


.. _pdf_py-br-boleto_sample.py: https://github.com/eduardocereto/py-br-boleto/blob/master/bin/pdf_py-br-boleto_sample.py

.. _html_py-br-boleto_sample.py: https://github.com/eduardocereto/py-br-boleto/blob/master/bin/html_py-br-boleto_sample.py

.. _py-br-boleto-installation:

Installation
============

You can install py-br-boleto either via the Python Package Index (PyPI)
or from source.

To install using pip,::

    $ pip install py-br-boleto

To install using easy_install,::

    $ easy_install py-br-boleto


.. _py-br-boleto-installing-from-source:

Downloading and installing from source
--------------------------------------

Download the latest version of py-br-boleto from
http://pypi.python.org/pypi/py-br-boleto/

You can install it by doing the following,::

    $ tar xvfz py-br-boleto-0.0.0.tar.gz
    $ cd py-br-boleto-0.0.0
    $ python setup.py build
    # python setup.py install # as root

.. _py-br-boleto-installing-from-hg:

Using the development version
-----------------------------

You can clone the repository by doing the following::

    $ git clone https://github.com/eduardocereto/py-br-boleto.git

.. _py-br-boleto-unittests:

Executing unittests
===================

You need either setuptools or distribute in order to execute the tests. Chances are you already have one or another. You also need `pdftohtml`_.::

    $ cd py-br-boleto
    $ python setup.py test


.. _pdftohtml: http://poppler.freedesktop.org/

.. _py-br-boleto-license:

License
=======

This software is licensed under the `New BSD License`. See the ``LICENSE``
file in the top distribution directory for the full license text.

.. vim:tw=0:sw=4:et
