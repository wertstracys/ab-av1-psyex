### Dockerfile
---
```
FROM encodev/svtav1enc:latest
WORKDIR /bot
COPY .env .
CMD ["bash", "run.sh"]
```
