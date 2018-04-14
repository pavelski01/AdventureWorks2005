# AdventureWorks2005

CREATE DATABASE AdventureWorks2005  
ON  
(   
   FILENAME = 'PATH\TO\MDF\FILE'  
)  
LOG ON  
(  
   FILENAME = 'PATH\TO\LDF\FILE'  
)  
FOR ATTACH;  
