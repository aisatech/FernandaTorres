# [fernanda.rest](https://fernanda.rest)

A diva está servindo mesmo! :sparkles: :microphone: :boom: 

REST API gratuita para servir frases da Fernanda Torres para sua aplicação ou apenas para sua diversão.
As frases foram retiradas de seus personagens, livros, entrevistas e discursos. 

[!ATENÇÃO:] Aqui é o Brasil! O Readme é em português e a API também. 

A API é disponibilizada para o mundo com o serviço supimpa do [Cloudflare Workers](https://workers.cloudflare.com/).

## Usabilidade

### `GET` [https://api.fernanda.rest](https://api.fernanda.rest)

```json
{
  "quote": "Amiga, se a gente não se ajudar, quem vai? - Fátima (Fernanda Torres) - Tapas e Beijos"
}
```

### `GET` [https://api.fernanda.rest/text](https://api.fernanda.rest/text)

```text
⁠A vida presta, e muito!
```

### `GET` [https://api.fernanda.rest/quotes](https://api.fernanda.rest/quotes)

> [!ATENÇÃO]  
> Os dados podem vir em outros formatos.

```ts
[
    ...,
    "⁠A vida presta, e muito!",
    "O amor nada tem de etéreo, é carne, é físico, e brutal.",
    ...,
]
```

## Development

```shell
pnpm dev 
```
ou 

```node
npm run dev 
```

## License

MIT 
Use tudo, só não pode tentar ganhar dinheiro com meu Saas ein? 


