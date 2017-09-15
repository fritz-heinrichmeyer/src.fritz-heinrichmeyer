<!-- 
.. title: Doktorarbeit
.. slug: Doktorarbeit
.. date: 2016-12-13 13:47:58 UTC+01:00
.. tags: 
.. category:  
.. link: 
.. description: Doktorarbeit von Fritz Heinrichmeyer
.. type: text
-->





Dissertation
============


`script.pdf <script.pdf>`_


Dissertation, Universität Erlangen-Nürnberg 1989


Beiträge zur Lösung des Approximationsproblems im Tschebyscheff'schen Sinne beim Systementwurf
----------------------------------------------------------------------------------------------

Das Programm TOPT wurde in *C* geschrieben

C++ virtuelle Klassen und virtuelle Methoden wurden durch C Zeiger simuliert.

Beipiel:

.. code-block:: C 


 typedef struct {
  int art;
   void (*fu[3])(void);
  } PARA_FU;
  typedef double (* STABFUNP)(int , int , int , OPT_LINE *); 
   typedef struct {
	int art;
	void (* fr)(COMPLEX *, double);
	STABFUNP stabtest; 
	PARA_FU *para;
	double LogFak;
	double DmL;
  } EBENEN_PAR;








Beispiele
---------
Diskretes Psophometerfilter:




.. image:: psophometer.gif
   :alt: psophometer





Gleichzeitige Approximation von Dämpfung und Gruppenlaufzeit:


.. image:: luminanz.gif
   :alt:  luminanz 


