# Start Nginx

```
start nginx
```

# Stop Nginx

```
nginx -s
```

# Reload

```
nginx -s reload
```

# Test

```
curl -I -X OPTIONS -H "Origin: http://example.cn" http://localhost:8000
curl -I -X OPTIONS -H "Origin: https://example.com" http://localhost:8000
curl -I -X OPTIONS -H "Origin: http://app1.example.cn" http://localhost:8000
curl -I -X OPTIONS -H "Origin: https://app2.example.com:8080" http://localhost:8000
curl -I -X OPTIONS -H "Origin: http://example2.cn" http://localhost:8000
curl -I -X OPTIONS -H "Origin: https://example.us" http://localhost:8000
curl -I -X OPTIONS -H "Origin: https://example.cn:abc" http://localhost:8000
```
