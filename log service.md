
[log-obsidian-github-vault-app Github repo](https://github.com/otmjka/log-obsidian-github-vault-app)

```

[+] check how obsidian save files

	used vault folder
	files saves as `.md`
	there are some obsidian iternal files

[+] used image files (not supported) ![[Pasted image 20241030085040.png]]

[+] push to repository

	https://github.com/otmjka/log-content
	
[+] create next.js app
[+] fetch repository
[+] get list articles
[+] get content of articles


```

[+] next make a repository as docker container 

[Nextjs docker doc ](https://nextjs.org/docs/app/building-your-application/deploying#docker-image)

```bash
docker compose -f docker/development/compose.yaml up
docker compose -f docker/production/compose.yaml up
```

===

now need create `production` branch, with CI/CD
build image
deploy to aws
