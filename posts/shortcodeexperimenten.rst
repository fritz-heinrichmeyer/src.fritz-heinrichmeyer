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

..


:sc:`{{% shortcodes %}}`

(Experimenten mit Makotemplates in Python und a shortcode und inline)
------------------------------------------------------------------------------------

`shortcodes (Source) </shortcodes/shortcodes.tmpl>`_





{{% template %}}
% for i in range(10): 
| body row ${i}
% endfor
% for i in range(10): 
+------------
% endfor
{{% /template %}}


(es klappt nicht!)
