# nodeJS fundamentales


## What is nodejs ? 

Node.js is an open-source server side runtime environment built on Chrome's V8 JavaScript engine. It provides an event driven, non-blocking (asynchronous) I/O and cross-platform runtime environment for building highly scalable server-side applications using JavaScript.

## NodeJS key features:

### Asynchronous and Event driven
All APIs of Node.js are asynchronous. This feature means that if a Node receives a request for some Input/Output operation, it will execute that operation in the background and continue with the processing of other requests. Thus it will not wait for the response from the previous requests

### Fast in Code execution
Node.js uses the V8 JavaScript Runtime engine, the one which is used by Google Chrome. Node has a wrapper over the JavaScript engine which makes the runtime engine much faster and hence processing of requests within Node.js also become faster.

### Single Threaded but Highly Scalable
Node.js uses a single thread model for event looping. The response from these events may or may not reach the server immediately. However, this does not block other operations. Thus making Node.js highly scalable. Traditional servers create limited threads to handle requests while Node.js creates a single thread that provides service to much larger numbers of such requests.


### No Buffering
Node. Js applications never buffer data, which dramatically reduces the processing time of uploading files, such as videos or audios. In other words, it **simply outputs data in chunks**, meaning that, for example, a user can watch videos without any interruption.Node.js applications never buffer any data. They simply output the data in chunks

## Why use Node. Js

**Node. Js is an extremely powerful server-side platform to develop modern, reliable and scalable web applications, trusted by global companies such as Netflix, Uber, LinkedIn and PayPal**

Due to its single thread characteristics combined with a multi thread platform that runs in background, it’s EVENT DRIVEN ARCHITICTURE is perfect for building fast and scalable data-intensive apps, data streaming (think YouTube), a real-time chat application, or a server-side web app,However, it is not suitable for anything that requires heavy server-side processing (e.g. video conversion).








