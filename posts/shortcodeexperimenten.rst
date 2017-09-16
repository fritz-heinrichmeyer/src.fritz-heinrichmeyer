.. title: shortcode Experimente
.. slug: shortcodeexperimenten
.. date: 2017-04-04 10:15:47 UTC+02:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

Experimenten mit Makotemplates in Python und a shortcode
--------------------------------------------------------

..


:sc:`{{% shortcodes %}}`

(Experimenten mit Makotemplates in Python und a shortcode und inline)
------------------------------------------------------------------------------------

`shortcodes (Source) </shortcodes/shortcodes.tmpl>`_




:sc:`{{% template %}}
% for i in range(10): 
| body row ${i}
% endfor
${chr(13)+chr(10)}${1+1}
% for i in range(10): 
+------------
% endfor
{{% /template %}}`


Shortcodes inline and reStructuredText and Mako simultaneously fail!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

(bzw. es klappt nicht!)
