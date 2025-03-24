# Make sure to build your project
``` bash
cd McpClient 
npm run build

cd ../McpServer
npm run build
```

# To Run
``` bash
cd McpClient
node dist/index.js ../McpServer/dist/index.js
```