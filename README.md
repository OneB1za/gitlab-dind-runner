```
mv config.toml /etc/gitlab-runner/config.toml
```

```
docker-compose up -d
```
```
sudo docker exec -it gitlab-runner bash
```
```
gitlab-runner register
```
```
exit
```

```
sudo mkdir -p /srv/gitlab
```
```
sudo docker exec -it gitlab export GITLAB_HOME=/srv/gitlab
```
