###############
# Description #
###############

Currently numbers for six card brands can be generated in four different output formats. 
Use proper command line arguments for desired branded cards. 
Cards are generated in a text file in the same direcotry where the EXE file is stored. 




#########
# Usage #
#########

Supported card brands and arguments are given below:

+-----------------------------------------------+
| Arguments |             Brand                 |
+-----------------------------------------------+
|   vis     |  Generates Visa cards             |
+-----------------------------------------------+
|   mas     |  Generates Mastercard cards       | 
+-----------------------------------------------+
|   amx     |  Generates American Express cards | 
+-----------------------------------------------+
|   dis     |  Generates Discover cards         | 
+-----------------------------------------------+
|   jcb     |  Generates JCB cards              | 
+-----------------------------------------------+
|   cup     |  Generates China Union Pay cards  | 
+-----------------------------------------------+


Supported output formats:
+-----------------------------------------------+
| Arguments |             Brand                 |
+-----------------------------------------------+
|   json    |  Generates cards in JSON format   |
+-----------------------------------------------+
|   xml     |  Generates cards in XML format    | 
+-----------------------------------------------+
|   csv     |  Generates cards in CSV format    | 
+-----------------------------------------------+



############
# Examples #
############

c:\> dummy_PAN_generator.exe 10 vis json


generates 10 Visa cards in JSON format.



c:\> dummy_PAN_generator.exe 50 cup xml


generates 50 China Union Pay cards in XML format



c:\> dummy_PAN_generator.exe 25 amx csv


generates 25 American Express cards in CSV format



c:\> dummy_PAN_generator.exe 100 dis


generates 100 Discover cards in default format.



-- EOF --