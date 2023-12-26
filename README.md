# Sample Next.js transpilePackages

## How to start.

In dev, I was worried that the transpilePackage would not work, so I started it after building it.

```shell
pnpm i
pnpm build
pnpm start
```

## Browserslist example

```typescript
["defaults", "Chrome >= 60", "Android >= 6", "iOS >= 14", "Safari >= 14"];
```

## tanstack-query, devTools

```json
{
  "dependencies": {
    "@tanstack/react-query": "^5.15.0",
    "@tanstack/react-query-devtools": "^5.15.0"
  }
}
```

[reference](https://tanstack.com/query/latest/docs/react/installation#requirements)

```
Chrome >= 91
Firefox >= 90
Edge >= 91
Safari >= 15
iOS >= 15
Opera >= 77
```

## Next.js browser support

[reference](https://nextjs.org/docs/architecture/supported-browsers)

```json
{
  "browserslist": [
    "chrome 64",
    "edge 79",
    "firefox 67",
    "opera 51",
    "safari 12"
  ]
}
```
