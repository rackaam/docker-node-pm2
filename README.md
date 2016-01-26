```
docker run -e "APP=server.js" -p 3000:80 -p 5858:5858 -v **/path/to/app/folder/**:/app -ti rakam/node-pm2 /bin/bash /launch
```
