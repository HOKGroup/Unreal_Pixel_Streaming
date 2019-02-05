# Unreal Pixel Streaming

> ![Documentation from Epic Games](https://docs.unrealengine.com/en-us/Platforms/PixelStreaming/CustomPlayer) 

## You can specify the port you use for signalling server
Default port from Unreal is 80, you can update this by modifying `cirrus.js` file
Line 79 `var httpPort = 8080; `  
When the server has started and is ready to accept connections, you'll see the following lines in the console window:

| `Listening to proxy connections on: 8888 `|
|   `Http listening on *: 8080 `            |


