
===================================
FIPT: Fast impedance tortuosity
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

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube.com/embed/r1cBf72wSwA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Why?
====

.. why-begin

The ionic resistance (or the MacMullin number) is a key performance metric for any battery electrode. It describes how easily ions can move through the electrode during fast charging or heavy use of the battery. It is therefore important for all manufacturers to optimize the ionic resistance of their electrodes.

Battrions Aligned Graphite Technology is a powerful way to reduce the ionic resistance by up to 50% through aligning graphite particles in an electrode.

.. why-end


I'm sold. What do I need?
=========================

Here are the three main steps:

-	`Build your FIPT cell <https://fipt.readthedocs.io/en/latest/assembly.html>`_
-	`Get the materials <https://fipt.readthedocs.io/en/latest/materials.html>`_
-	`Measure ionic resistance (aka SOP) <https://fipt.readthedocs.io/en/latest/sop.html>`_

You find more details in the `full documentation <https://fipt.readthedocs.io/>`_


I got the data. What now?
=========================

Data analysis code is available at `fipt-analysis <https://github.com/deniz195/fipt-analysis>`_


Contribute
==========

.. contrib-begin
You can find all source files here: `<https://github.com/deniz195/fipt>`_

Pull requests are welcome. 

.. For major changes, please open an issue first to discuss what you would like to change.
.. Please make sure to update tests as appropriate.

For questions please feel free to reach out to Deniz Bozyigit (`dbozyigit@battrion.com <mailto:dbozyigit@battrion.com>`_)
.. contrib-end

License
=======
`GPL v3.0 <https://choosealicense.com/licenses/gpl-3.0/>`_




