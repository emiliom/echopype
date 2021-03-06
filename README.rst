.. image:: https://travis-ci.org/OSOceanAcoustics/echopype.svg?branch=master
    :target: https://travis-ci.org/OSOceanAcoustics/echopype
.. image:: https://readthedocs.org/projects/echopype/badge/?version=latest
    :target: https://echopype.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status
.. image:: https://mybinder.org/badge_logo.svg
    :target: https://mybinder.org/v2/gh/OSOceanAcoustics/echopype/master

Echopype
========

Echopype is a package built for enhancing the interoperability and scalability
in ocean sonar data processing.
These data are widely used for obtaining information about the distribution and
abundance of marine animals, such as fish and krill.
Our ability to collect large volumes of sonar data from a variety of
ocean platforms has grown significantly in the last decade.
However, most of the new data remain under-utilized.
echopype aims to address the root cause of this problem - the lack of
interoperable data format and scalable analysis workflows that adapt well
with increasing data volume - by providing open-source tools as entry points for
scientists to make discovery using these new data.


Installaion and Usage
---------------------

Echopype currently supports file conversion and computation of data produced by:

- Simrad EK60 echosounder (``.raw`` files)
- ASL Environmental Sciences AZFP echosounders (``.01A`` files)

The file conversion functionality converts data stored in manufacturer-specific
binary formats into a standardized netCDF files, based on which all subsequent
computations are performed.
The data processing routines include calibration (instrument-specific), noise
removal, and mean volume backscattering strength (MVBS) calculation.

Check out the `echopype documentation`_ for details on installation and usage!

.. _echopype documentation: https://echopype.readthedocs.io



License
-------

Echopype is licensed under the open source Apache 2.0 license.

`Wu-Jung Lee <http://leewujung.github.io>`_ (@leewujung)
and `Kavin Nguyen <https://github.com/ngkavin>`_ (@ngkavin)
are the primary developers of this project.

Other contributors include:
`Valentina Staneva <https://escience.washington.edu/people/valentina-staneva/>`_ (@valentina-s),
`Frederic Cyr <https://github.com/cyfr0006>`_ (@cyfr0006),
`Sven Gastauer <https://www.researchgate.net/profile/Sven_Gastauer>`_ (@SvenGastauer),
`Marian Peña <https://www.researchgate.net/profile/Marian_Pena2>`_ (@marianpena),
`Mark Langhirt <https://www.linkedin.com/in/mark-langhirt-7b33ba80>`_ (@bnwkeys),
`Erin LaBrecque <https://www.linkedin.com/in/erin-labrecque/>`_ (@erinann),
`Emma Ozanich <https://www.linkedin.com/in/emma-reeves-ozanich-b8671938/>`_ (@emma-ozanich),
`Aaron Marburg <http://apl.uw.edu/people/profile.php?last_name=Marburg&first_name=Aaron>`_ (@amarburg)

---------------

Copyright (c) 2018--, echopype Developers.
