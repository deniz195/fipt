
===================================
``FIPT``: Fast impedance tortuosity
===================================

.. image:: https://readthedocs.org/projects/fipt/badge/?version=latest
:target: https://fipt.readthedocs.io/en/latest/?badge=latest
:alt: Documentation Status

A fast way to get ionic resistance
==================================

.. intro-begin
FIPT is a measurement technique that allows a fast determination of the ionic resistance for battery electrodes. The technique is based on the work by J. Landesfeind (`DOI: 10.1149/issn.1945-7111 <https://dx.doi.org/10.1149/2.1141607jes>`_) and then optimized for execution speed and reliability at `Battrion <https://battrion.com>`_.

This repository contains the information to build an FIPT setup, prepare the electrolyte and the standard operating procedure (SOP) to successfully execute a measurement.
.. intro-end

Why?
===============
The ionic resistance (or the MacMullin number) is a key performance metric for any battery electrode. It describes how easily ions can move through the electrode during fast charging or heavy use of the battery. It is therefore important for all manufacturers to optimize the ionic resistance of their electrodes.

Battrions Aligned Graphite Technology is a powerful way to reduce the ionic resistance by up to 50% through aligning graphite particles in an electrode.

What do I need?
===============

These are the things that you need to build your setup

- A 3D printer
- Couple of screws
- Kapton tape and 3mm foam.

Use the files in the `cad` folder and follow the assembly instructions.

Once you have the setup assembled, prepare the electrolyte. This needs:

- A salt (e.g. NaClO4)
- A solvent (e.g. EC:DMC)

The recipe for a useful electrolyte mixture is given in the `electrolyte` folder.

Finally, get your electrode, print out the SOP from the `sop` folder and get your first measurement. For this you need:

- An impendance analyzer
- Separator material
- A 200ul or 1ml pipette

In about 2-10min your measurement should be done.


I got the data. What now?
=========================

Data analysis code is available at `fipt-analysis <https://github.com/deniz195/fipt-analysis>`_

Contributing
============

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

For questions please feel free to reach out to Deniz Bozyigit (`dbozyigit@battrion.com <mailto:dbozyigit@battrion.com>`_)

License
=======
`GPL v3.0 <https://choosealicense.com/licenses/gpl-3.0/>`_




