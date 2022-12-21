# Simple starter for WunderGraph Cloud

A simple starter that consumes the [Countries API](https://countries.trevorblades.com/).

### Getting started locally

```shell
npm install
npm run generate 
npm run build
npm run dev
```

Get Countries

```shell
curl -X GET http://localhost:3000/
```

---

### Deploy to WunderGraph Cloud

1. Fork this repo
2. Sign in to [WunderGraph Cloud](https://cloud.wundergraph.com)
3. Create a new project
4. Import the forked repo
5. Deploy the project

Try it out (replace `YOUR_PROJECT_ID` with your project id):

```shell
curl -X GET https://{YOUR_PROJECT_NAME}.wundergraph.dev/operations/Countries
```

### Make changes

1. Make changes to the `main` branch, e.g. change the query in `apps/api/operations/Countries.graphql`
2. Commit and push the changes

See your changes live in less than 50 seconds.

```shell
curl -X GET https://{YOUR_PROJECT_NAME}.wundergraph.dev/operations/Countries
```

---

### Learn More

Read the [Docs](https://wundergraph.com/docs).