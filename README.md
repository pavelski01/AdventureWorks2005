# AdventureWorks2005

CREATE DATABASE AdventureWorks2005  
ON  
(   
&nbsp;&nbsp;&nbsp;FILENAME = 'path\to\mdf\file'  
)  
LOG ON  
(  
&nbsp;&nbsp;&nbsp;FILENAME = 'path\to\ldf\file'  
)  
FOR ATTACH;  
