#CAPTION#
getResultFile
-------------

Gets the result filename and buffer size of the given model cref.
#END#

#PYTHON#
.. code-block:: python

  filename, bufferSize, status = oms.getResultFile(cref)

#END#

#CAPI#
.. code-block:: c

  oms_status_enu_t oms_getResultFile(const char* cref, char** filename, int* bufferSize);

#END#

#DESCRIPTION#
#END#
