[log-obsidian-github-vault-app Github repo](https://github.com/otmjka/log-obsidian-github-vault-app)

TODO:
try https://remarkjs.github.io/react-markdown/
image support
code snippets
embed video

idea go to github
human-readability name entry point
that guide to other parts of logs

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

crete file

`.github/workflows/deploy.yaml`

create repository

ECR_REPOSITORY: akjmto/log-blog

ECS_SERVICE: auth-back-service

need to understand vpc
https://redrobot.dev/learn/articles/aws-vpc
https://medium.com/@redrobotdev/next-js-deployment-using-ecs-with-fargate-1a730a8d0cb1

https://github.com/vercel/next.js/blob/canary/examples/with-docker/Dockerfile
