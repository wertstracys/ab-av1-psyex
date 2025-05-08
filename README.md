### Dockerfile
---
```
FROM encodev/svtav1enc:2025-05-08
WORKDIR /bot
COPY .env .
CMD ["bash", "run.sh"]
```
