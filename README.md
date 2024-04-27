Acesse a pasta `nestjs`:

```bash
cd nestjs
```

Rode os containers com o comando:

```bash
docker compose up
```

Entre no container do `nest`:

```bash
docker compose exec app bash
```

Instale as dependências:

```bash
npm install
```

Rode o comando para o `prisma` criar realizar a `migrate`:

```bash
npx prisma migrate dev
```

Para rodar a aplicação rode o comando:

```bash
npm run start:dev
```

Existe um arquivo na raiz do projeto Nest.js, o `api.http` que você pode usar para testar a aplicação com o plugin do VSCode [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client).