.. title: tkVersionPrint


Imprime la version de TK que se esta usando actualmente.

.. code-block:: python

   from Tkinter import *
   root = Tk()
   #
   tkversion = root.tk.eval('info patchlevel')
   print 'TK Version = '+tkversion
   #
   root.mainloop()

Ejemplo:

.. code-block:: python

   juan@maverick:~$ /usr/bin/env python test.py
   TK Version = 8.5.8

