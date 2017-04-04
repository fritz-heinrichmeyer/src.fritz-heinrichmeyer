.. title: shortcodeExperimenten
.. slug: shortcodeexperimenten
.. date: 2017-04-04 10:15:47 UTC+02:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

Experimenten mit Makotemplates in Python und a shortcode
--------------------------------------------------------


:sc:`{{% shortcodes %}}`

Experimenten mit Makotemplates in Python und a shortcode
--------------------------------------------------------
`shortcodes (Source) </shortcodes/shortcodes.tmpl>`_


.. raw:: html


  {{% template %}}
  <ul>
  % for i in range(10): 
  <li>${i}</li>
  % endfor
  </ul>
  {{% /template %}}


..
