# Blue/Green Nginx Deployment (Ports 8081/8082)

This setup deploys two environments (Blue & Green) using the same Docker image:
**yimikaade/wonderful:devops-stage-two**

### Ports
| Service | Internal | External |
|----------|-----------|-----------|
| Nginx (Proxy) | 80 | 8080 |
| Blue | 8081 | 8081 |
| Green | 8082 | 8082 |

### Run
```bash
docker-compose up -d