# TIC-REST
API REST JAVA

Développement d'une API pour un projet d'école.   
L'API doit répondre à une requête et renvoyer un fichier json.   
L'API exploite une base de données sql fournie.   
   
Requête : http://<ip>:<port>/api/domains.json   
Retours attendus :   
  Bonne requête :   
   
>    {   
>  	"code": 200,   
>  	"message": "success",   
>  	"datas": [   
>  		{   
>  			"id": 1,   
>  			"slug": "mailer",   
>  			"name": "mailer",   
>  			"description": "Liste des mails automatisé"   
>  		},   
>  		{   
>  			"id": 2,   
>  			"slug": "documents",   
>  			"name": "documents",   
>  			"description": "un petit teste de documents a traduire."   
>  		}   
>  	]   
>  }   
  
