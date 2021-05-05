Code Block <BR>
In order to write a code block:<BR>
header<BR>
========== <BR>
Print in python ::<Br>
print('hello')<Br>
>>hello<BR>

Linking rst files to main file
Guide<br>
^^^^^^^^<br>
.. toctree::<br>
   :maxdepth: 2<br><br>
   contact<br>
   :caption: Contents:<br>

   Here contact.rst is a file.<Br>
   Note: file name must be below the colons of maxdepth. 
<br><br>

### Linking any rst file to any rst page<br>
- :doc:`custum name <userManual>`<br>
(here userManual is a rst page in the same folder)

### Linking in the same page
(the section to link)<br>
.. _My target:

Explicit targets
~~~~~~~~~~~~~~~~
<br>
:ref:` custom name <My target>`


