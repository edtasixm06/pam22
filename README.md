# PAM 
## @edt ASIX M06-ASO Curs 2022-2023

Podeu trobar les imatges docker al Dockehub de [edtasixm06](https://hub.docker.com/u/edtasixm06/)

Podeu trobar la documentació del mòdul a [ASIX-M06](https://sites.google.com/site/asixm06edt/)

ASIX M06-ASO Escola del treball de barcelona


### PAM Containers:


Exemples d'imatges per practicar PAM individualment i per practicar autnticació PAM amb ldap.


 * **edtasixm06/pam22:base** Container PAM base per practicar regles PAM. Utilitza chfn per practicar els
   exmples del HowTo per aprendre el funcionament dels *type* (*auth*,*account*,*session* i*password*) i 
   dels *control* bàsics (*sufficient*, *required*,*requisite* i *optional*) i avançats (*die*, *ok*).
   També permet practicar *pam_mount.so* per muntar unitats de *tmpfs* o *NFS* als usuaris.

``` 
docker run --rm --name pam.edt.org -h pam.edt.prg --net 2hisx -it edtasixm06/pam22:base

```


