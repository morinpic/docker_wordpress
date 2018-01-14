# docker_wordpress
WordPressのTheme開発用環境

## Usage
1. Edit the `.env`, `Movefile`.
2. Copy `target_theme` to themes's folder.
3. `docker-compose up -d`

### pull
```
docker-compose exec wordpress wordmove pull -e production -upd
```

### push
```
docker-compose exec wordpress wordmove push -e production -t
```
