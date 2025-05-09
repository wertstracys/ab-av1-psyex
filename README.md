### Dockerfile
---
```
FROM encodev/svtav1enc:2025-05-09
WORKDIR /bot
COPY .env .
CMD ["bash", "run.sh"]
```
