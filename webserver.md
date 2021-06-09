1.- À quelle famille de logiciels appartiennement Nginx, Apache, lighttpd ou encore IIS ? 

2.- Comment peut-on faire en sorte qu'Nginx écoute sur un port différent du port 80 ?

3.- À quoi sert le protocol TLS ?

4.- Quelle directive Nginx permet d'appliquer un comportement en fonction de l'URI (Uniform Resource Identifier) reçu par le serveur ?

- `path_directive`
- `location`
- `map`

5.- Quel protocol utilise un serveur web pour transmettre les données à un client ?

- http
- ftp
- www
- ssh

6.- Quel protocol est utilisé pour interfacer un serveur web avec le gestionnaire de processus de PHP (chargé de renvoyer le résultat de l'interprétation du code) ?

- CGI
- FastCGI
- SCGI 

7.- Que permet de faire l'extrait suivant ?

```
if ($request_method !~ ^(GET|POST|HEAD)$) {
    return '405';
}
```

8.- Quel module permet à Nginx et/ou Apache de compresser le contenu renvoyé au client ? 

9.- Quelle directive permet d'indiquer à un hôte Nginx quel domaine est concerné par la configuration du bloc `server` ?

- `server_name`
- `host_name`
- `domain_name`
- `ServerName`

10.- Quel symbole permet d'indiquer dans une directive `location` que l'on souhaite utiliser une expression régulière pour comparer le chemin (URI) de la requête à celui exprimé dans cette même location ?

11.- Quel effet aura le bloc location suivant ?

```
location ~* \.(png|gif|ico|cur|heic|webp)$ {
    expires    7d;
    access_log off;
}
```

12.- À quoi sert le header `Strict-Transport-Security` ?

13.- Quel avantage principal offre HTTP/2 ?

14.- Citer quelques avantages d'avoir un répartiteur de charge (loadbalancer) devant les backends web.

15.- Expliquer à quoi sert l'instruction suivante

```
location ~* ^/(?:wp-content|wp-includes)/.*\.php$ {
    deny all;
}
```

16.- Que fournit le projet letsencrypt ? 

17.- À quoi sert un serveur de noms de domaine ? (DNS)

