# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

## Tasks

### Setup Node Environment

Node server has been set up using:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`

### Create a new endpoint in the server.ts file

Endpoint in `./src/server.ts` uses query parameter to download an image from a public URL, filter the image, and return the result.

```typescript
import { filterImageFromURL, deleteLocalFiles } from "./util/util";
```

### Deploying the system

Deploing involved - `eb init` a new application and `eb create` a new environment to deploy the image-filter service! Also, `eb deploy` to push changes.

### Custom Domain Name

### Elastic Beanstalk Endpoint

http://udagram-dev.us-east-2.elasticbeanstalk.com/filteredimage?image_url=https://images.unsplash.com/photo-1534361960057-19889db9621e?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80

### Github url

https://github.com/hannahochim/udacity-udagram
