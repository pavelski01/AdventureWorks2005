# AdventureWorks2005

CREATE DATABASE AdventureWorks2005  
ON  
(   
&nbsp;&nbsp;&nbsp;FILENAME = 'PATH\TO\MDF\FILE'  
)  
LOG ON  
(  
&nbsp;&nbsp;&nbsp;FILENAME = 'PATH\TO\LDF\FILE'  
)  
FOR ATTACH;  
