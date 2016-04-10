# 32c3_flash
Docker container for 32c3_flash CTF

# To Install

```
docker build -t ryarnyah/32c3_flash .
docker run -d -p 8001:8001 --read-only ryarnyah/32c3_flash
```

# Usage
```
# Firmware image
http://X.X.X.X:8001/flash.tgz
# CTF Page
http://X.X.X.X:8001/upload.py
```
