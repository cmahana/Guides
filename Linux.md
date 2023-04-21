
**Sorts list by size in human readable form**

> ls -Sahl
---

**Bash History** This one points to the home but sudo it and point it where you will
> cat ~/.bash_history 
---

**Find by size** example here is 800M but this is adjustable.
> sudo find <folder to look in> -type f -size +800M | grep <grepFilter>

  
 **Salt commands** 
  *a simple Salt command example.* 
  the servername can be modified to hit multiple places. For instance server01 and server02 will both be touched if you enter 'server0*'
  >  sudo salt '<servername>' cmd.run 'ls -Sahl /opt/program/shared/log/'

