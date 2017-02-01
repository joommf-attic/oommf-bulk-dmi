Bulk Dzyaloshinkii-Moriya energy extension for OOMMF [1].

.. math::
   w_\text{dmi} = D \mathbf{m} \cdot (\nabla \times \mathbf{m})

Marijan Beg, Ryan A. Pepper, and Hans Fangohr (University of
Southampton), January 2017

Modification of OOMMF extension Oxs_DMexchange6ngbr.h [2].

How to install:
---------------

1. Copy `BulkDMI.h` and `BulkDMI.cc` to `oommf/app/oxs/local/` directory.

2. Run `pimake`.

3. Use Oxs_BulkDMI in MIF scripts.

Acknowledgements:
-----------------

Developed as a part of OpenDreamKit Horizon 2020 European Research
Infrastructure project (676541), and the EPSRC Programme grant on
Skyrmionics (EP/N032128/1).

References:
-----------

[1] M.J. Donahue and D.G. Porter. OOMMF User's Guide, Version
1.0. National Institute of Standards and Technology, Gaithersburg, MD
(Sept 1999)

[2] Rohart, S., & Thiaville, A. Physical Review B, 88, 184422 (2013).
