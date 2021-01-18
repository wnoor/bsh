# bsh-ldapsearch
Simple Bean shell code to connect and search through ldap

Beanshell interpreter is required to execute the code. Script can also be executed using Groovy.

#Example search
Search where sn starts with D, limit result to 2 before search update connection paramters according to your environment

```shell
NamingEnumeration result = searchByFilter("sn=D*", 2);
```
