# Instructions to reproduce

```
npx gatsby-cli new my-example-with-gatsby-and-docz
cd my-example-with-gatsby-and-docz
yarn add docz docz-theme-default --dev
```

Modify `package.json` to add the following script:
```
...
  "docz:dev": "docz dev"
...
```

and then run:
- `yarn develop` to see your Gatsby site at http://localhost:8000,
- `yarn docz:dev` to see your Docz site at http://localhost:3000.