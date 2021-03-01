gtab for GVim 
==

- open files as tabs in a gvim instance  
- list existing instances  
- create new instances  
- manually specify an instance  

How it works
==

- it create a gvim servername id with the hostname,the basedir of current directory and the parent shell id
- when trying to open a file, it checks for instances and add them to current instance if needed or start a new instance


Examples
==

```
gtab
gtab myfile
gtab -l
gtab -s customid
gtab -s customid file
```
