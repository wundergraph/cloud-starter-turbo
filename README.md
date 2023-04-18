# WunderGraph Cloud Starter + Turborepo

[![CI](https://github.com/wundergraph/cloud-starter-turbo/actions/workflows/ci.yaml/badge.svg)](https://github.com/wundergraph/cloud-starter-turbo/actions/workflows/ci.yaml)

This starter combines [WunderGraph](https://wundergraph.com/) Cloud with [Turborepo](https://github.com/vercel/turbo) to create an optimized monorepo experience for your WunderGraph application.

### Getting started locally

```shell
npm install
npm run build
npm run dev
```

Fetch `Germany (DE)` from your WunderGraph.

```shell
curl -X GET http://localhost:3000/operations/Countries?code=DE
```

### Deploy to WunderGraph Cloud

1. Fork this repo
2. Sign in to [WunderGraph Cloud](https://cloud.wundergraph.com)
3. Create a new project
4. Import the forked repo
5. Deploy the project

Try it out (replace `YOUR_PROJECT_NAME` with your project name):

```shell
curl -X GET https://{YOUR_PROJECT_NAME}.wundergraph.dev/operations/Countries?code=DE
```

### Make changes

1. Make changes to the `main` branch, e.g. change the query in `apps/api/operations/Countries.graphql`
2. Commit and push the changes

See your changes live in less than a minute. If you don't make changes that will affect the WunderGraph build, the build will be fetched from the cache. 

### Learn More

Read the [Docs](https://wundergraph.com/docs).