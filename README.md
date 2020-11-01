# Coffee identifier using Fast.ai and Render.com

You can test your changes locally by installing Docker and using the following command:

```
docker build -t coffee .

docker run --rm -it -p 5000:5000 coffee
```

# Deploy on render
```
1. Sign up for render
2. Choose service, and then +new > web service
3. Put your repository, and change the environtment to docker
4. It is enough to use the cheapest plan, $7 for a month. You could suspend it to prevent unnecessary costs. 
5. Deploy it from github using manual deploy first, then you could update the latest commit automatically. Use the official reference from fast.ai below for more explanation on deployment process. 
```

# Reference

This is a modified fast.ai deployment on render, https://github.com/render-examples/fastai-v3
