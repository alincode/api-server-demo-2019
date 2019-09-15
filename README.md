# API Server example

```
docker build -t api-server:0.0.1-dev .
docker run -d -p 3000:3000 --name api-container api-server:0.0.1-dev
```

open <http://0.0.0.0:3000/>
