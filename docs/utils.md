```bash
git remote add gitlab git@gitlab.com:nemanjam/tailwindcss-hello-world.git && \
git remote add all git@github.com:nemanjam/tailwindcss-hello-world.git && \
git remote set-url --add --push all git@github.com:nemanjam/tailwindcss-hello-world.git && \
git remote set-url --add --push all git@gitlab.com:nemanjam/tailwindcss-hello-world.git && \
git remote -v
```

```bash
scp -r ./dist/* ubuntu@arm1:~/traefik-proxy/apps/nginx-with-volume/website/
```
