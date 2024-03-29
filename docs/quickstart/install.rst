.. highlight:: sh

Installation
============

.. important:: The `ligo.skymap` package requires `Python`_ 3.6 or later.

On Linux or macOS x86_64 systems, we recommend installing `ligo.skymap` using
`pip`_ or `conda`_, either of which will automatically install all of the
additional :ref:`Python dependencies <python-dependencies>`.

(On other operating systems and architectures, you can :doc:`install from
source <../develop>`.)

Option 1: pip
-------------

To install `ligo.skymap` using `pip`_, you will need pip 19.0 or later. You can
update pip to the most recent version by running this command::

    $ pip install --upgrade pip

Then, just run this command::

    $ pip install ligo.skymap

You are now ready to get started using `ligo.skymap`.

Option 2: conda
---------------

If you are using the Anaconda Python distribution or the lightweight Miniconda version, you can install `ligo.skyamp` using `conda`_. First, enable the `conda-forge`_ repository by running these commands::

    $ conda config --add channels conda-forge
    $ conda config --set channel_priority strict

Then, run this command::

    $ conda install ligo.skymap

You are now ready to get started using `ligo.skymap`.

.. _Python: https://www.python.org
.. _`pip`: https://pip.pypa.io
.. _`Python package index`: https://pypi.org/project/ligo.skymap/
.. _`conda`: https://conda.io
.. _`conda-forge`: https://conda-forge.org

.. _python-dependencies:
.. note:: When you use pip to install `ligo.skymap` with pip or conda, it will
          automatically install the following required Python packages:

          *  `Astroplan <http://astroplan.readthedocs.io>`_ ≥ 0.5
          *  Astropy_ ≥ 3.1
          *  `astropy-healpix <https://astropy-healpix.readthedocs.io>`_ ≥ 0.3
          *  `Astroquery <https://astroquery.readthedocs.io>`_
          *  `Healpy <http://healpy.readthedocs.io>`_
          *  `h5py <https://www.h5py.org>`_
          *  `LALSuite <https://pypi.python.org/pypi/lalsuite>`_ ≥ 6.53
          *  `lscsoft-glue <https://pypi.org/project/lscsoft-glue/>`_ ≥ 2.0.0
          *  `ligo-gracedb <https://pypi.org/project/ligo-gracedb/>`_ ≥ 2.0.1
          *  `ligo-segments <https://pypi.org/project/ligo-segments/>`_ ≥ 1.2.0
          *  `Matplotlib <https://matplotlib.org>`_ ≥ 3.0.2
          *  `NetworkX <https://networkx.github.io>`_
          *  `Numpy <http://www.numpy.org>`_ ≥ 1.14
          *  `Pillow <http://pillow.readthedocs.io>`_ ≥ 2.5.0
          *  `ptemcee <https://github.com/willvousden/ptemcee>`_
          *  `python-ligo-lw <https://pypi.org/project/python-ligo-lw/>`_
          *  `Reproject <https://reproject.readthedocs.io>`_ ≥ 0.3.2
          *  `Scipy <https://www.scipy.org>`_ ≥ 0.14
          *  `Seaborn <https://seaborn.pydata.org>`_ ≥ 0.8.0
          *  `tqdm <https://tqdm.github.io>`_
          *  `pytz <http://pytz.sourceforge.net>`_

          The following packages are optional for specific features:

          *  `pytest <https://docs.pytest.org>`_ for running the test suite
