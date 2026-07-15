# shiori.codes

The standalone public website for [ShioriCode](https://shiori.codes), built with Astro and deployed on Vercel.

## Development

```sh
bun install
bun run dev
```

Before publishing:

```sh
bun run typecheck
bun run build
```

Release downloads are resolved client-side from the public
[`shiorihq/ShioriCode`](https://github.com/shiorihq/ShioriCode) GitHub releases API.

