# [fernanda.rest](https://fernanda-torres.isabelleoliveiradesign.workers.dev/)

A diva está servindo mesmo! :sparkles: :microphone: :boom: 

REST API gratuita para servir frases da Fernanda Torres para sua aplicação ou apenas para sua diversão.
As frases foram retiradas de seus personagens, livros, entrevistas e discursos. 

[!ATENÇÃO:] Aqui é o Brasil! O Readme é em português e a API também. 

A API é disponibilizada para o mundo com o serviço supimpa do [Cloudflare Workers](https://workers.cloudflare.com/).

## Usabilidade

### `GET` [https://api.fernanda.rest](https://fernanda-torres.isabelleoliveiradesign.workers.dev/)

```json
{
  "quote": "Amiga, se a gente não se ajudar, quem vai? - Fátima (Fernanda Torres) - Tapas e Beijos"
}
```

### `GET` [https://api.fernanda.rest/text](https://fernanda-torres.isabelleoliveiradesign.workers.dev/text)

```text
⁠A vida presta, e muito!
```

### `GET` [https://api.fernanda.rest/quotes](https://fernanda-torres.isabelleoliveiradesign.workers.dev/quotes)

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

## Desenvolvimento

Aqui eu adicionei um molhinho no terminal. 
Recomendo fortemente clonar e rodar no seu localhost.

```shell
pnpm dev 
```
ou 

```node
npm run dev 
```

## License

MIT 
Use tudo na paz, dando os créditos para o divo de quem fiz o fork. 
Se for usar algo exclusivo desse repositório, é tudo nosso. ☭



