# Cloudflare setup

## Tunnel

### Create .env file

```shell
TOKEN=your_cloudflare_tunnel_token
```

### Connect to Tunnel

```shell
docker compose -p your_project_name -f tunnel.yaml up -d
```

### Shut down Tunnel

```shell
docker compose -p your_project_name -f tunnel.yaml down
```
