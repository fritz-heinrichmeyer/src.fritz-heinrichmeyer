.. title: RSTtablesExperimente
.. slug: rsttablesexperimente
.. date: 2017-01-21 10:01:54 UTC+01:00
.. tags: Java, RST
.. category: 
.. link: 
.. description: RST Tables Experimente
.. type: text

- `(Quellen RST Für Fortgeschrittene ) <http://docutils.sourceforge.net/docs/ref/rst/directives.html#class>`_ 
- `A reStructuredText Primer <https://getnikola.com/quickstart.html>`_

.. raw:: html

  <link href="all-nocdn.css" rel="stylesheet" type="text/css">
  <div class="row">
  <div class="col-md-6">

Tables Experimente, Grid system und Bilder




.. class:: table-striped

+------------+------------+-----------+ 
| Header 1   | Header 2   | Header 3  | 
+============+============+===========+ 
| body row 1 | column 2   | column 3  | 
+------------+------------+-----------+ 
| body row 2 | Cells may span columns.| 
+------------+------------+-----------+ 
| body row 3 | Cells may  | - Cells   | 
+------------+ span rows. | - contain | 
| body row 4 |            | - blocks. | 
+------------+------------+-----------+
| body row 1 | column 2   | column 3  | 
+------------+------------+-----------+ 
| body row 2 | Cells may span columns.| 
+------------+------------+-----------+ 
| body row 3 | Cells may  | - Cells   | 
+------------+ span rows. | - contain | 
| body row 4 |            | - blocks. | 
+------------+------------+-----------+

.. raw:: html

 </div><div class="col-md-6">


- Cells 
- contain
- blocks



.. raw:: html

 </div>
  </div>
  <br />

..

   Ende div class=row 
   Ende div class=row
   
     Ende div class=row



text und Bilder

Für die Ende der  rst- „raw“ Umgebung ist er rst-„..“-Ansatz (Zeile 63 in rsttablesexperimente.rst) notwendig.

Grid System  und rst- „raw“ Umgebung mit „Bootstrap“.CSS- stylesheets  in RST zu arbeiten  ist möglich, aber nicht sehr komfortabel.


- Cells 
- contain
- blocks



**Ein schönes Bild:**

.. class:: "img-circle"

.. image:: /luise.jpg
   :alt: ein schönes Bild
   :align: center






