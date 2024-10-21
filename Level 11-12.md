# Level 11 -> 12

Objective: The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions.

1. using cat data.txt gives "Gur cnffjbeq vf 7k16JArUVv5LxVuJfsSVdbbtaHGlw9D4"

2. rotation cipher needs to be performed on this.
this cna be done by using dcode website or alternatively by using the built in funciton "tr"

Command used: **_tr 'A-Za-z' 'N-ZA-Mn-za-m' < data.txt_**

_**tr**_: used for translating or substituting characters.

_**'A-Za-z'**_:specifies uppercase and lowercase input chars.

_**'N-ZA-Mn-za-m'**_: specifies the ROT13 mapping, rotating the letters by 13 positions.

3. The response given is "The password is 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4"

**Password:** 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4 