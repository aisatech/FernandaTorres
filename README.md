# [fernanda.rest](https://fernanda.rest)

A free REST API for random Fernanda Torres quotes (fernanda as a Service).

Built with [Cloudflare Workers](https://workers.cloudflare.com/).

## Usage

### `GET` [https://api.fernanda.rest](https://api.fernanda.rest)

```json
{
  "quote": "I feel like I'm too busy writing history to read it."
}
```

### `GET` [https://api.fernanda.rest/text](https://api.fernanda.rest/text)

```text
The world is our office
```

### `GET` [https://api.fernanda.rest/quotes](https://api.fernanda.rest/quotes)

> [!WARNING]  
> This response format may change.

```ts
[
    ...,
    "I leave my emojis bart Simpson color",
    "I love sleep; it's my favorite.",
    ...,
]
```

## Development

```shell
pnpm dev
```

## License

MIT
