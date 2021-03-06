========
subcell'
========


--------
Overview
--------
This library provides functions for accessing 16-bit and 8-bit subsets of cells.


---------
Functions
---------
+-----------------+-------------------------------+
| Function        | Stack                         |
+=================+===============================+
| highWord        | cellAddr -- highwordAddr      |
+-----------------+-------------------------------+
| lowWord         | cellAddr -- lowwordAddr       |
+-----------------+-------------------------------+
| w@              | wordAddr -- val               |
+-----------------+-------------------------------+
| w@+             | wordAddr -- wordAddr val      |
+-----------------+-------------------------------+
| w!              | val wordAddr --               |
+-----------------+-------------------------------+
| w!+             | val wordAddr -- wordAddr+1    |
+-----------------+-------------------------------+
| highByte        | wordAddr -- highbyteAddr      |
+-----------------+-------------------------------+
| lowByte         | wordAddr -- lowbyteAddr       |
+-----------------+-------------------------------+
| c@              | byteAddr -- val               |
+-----------------+-------------------------------+
| c@+             | byteAddr -- byteAddr val      |
+-----------------+-------------------------------+
| c!              | val byteaddr --               |
+-----------------+-------------------------------+
| c!+             | val byteAddr -- byteAddr+1    |
+-----------------+-------------------------------+
| highNibble      | byteAddr -- highnibbleAddr    |
+-----------------+-------------------------------+
| lowNibble       | byteAddr -- lownibbleAddr     |
+-----------------+-------------------------------+
| nibble@         | nibbleAddr -- val             |
+-----------------+-------------------------------+
| nibble@+        | nibbleAddr -- nibbleAddr val  |
+-----------------+-------------------------------+
| nibble!         | val nibbleAddr --             |
+-----------------+-------------------------------+
| nibble!+        | val nibbleAddr -- nibbleAddr+1|
+-----------------+-------------------------------+
| packString      | strAddr --                    |
+-----------------+-------------------------------+
| printPack       | strAddr --                    |
+-----------------+-------------------------------+
| getPackedLength | strAddr -- strLen             |
+-----------------+-------------------------------+


