# Rotas

Sua API precisará de rotas específicas para lidar com as requisições feitas pelo cliente. Estas rotas estãos especificadas abaixo.

> [!WARNING]
> Durante o desenvolvimento, tenha em mente que apenas o domínio de sua API será configurado no aplicativo. Todas as rotas posteriores já são definidas internamente no cliente.
>
> Considere o seguinte exemplo para melhor entendimento:
>
> | Configurado no cliente           | Internamente no cliente | Descrição                                                                                                             |
> | -------------------------------- | ----------------------- | --------------------------------------------------------------------------------------------------------------------- |
> | `https://minha-api-legal.com`    | `/recents`              | `https://minha-api-legal.com` + `/recents`. Caso endpoint `/recents` exista no domínio, ele será utilizado.           |
> | `https://minha-api-legal.com/v3` | `/recents`              | `https://minha-api-legal.com/v3` + `/recents`. Caso endpoint `/recents` exista no endpoint `/v3`, ele será utilizado. |

## Tabela de rotas

Abaixo estão listadas todas as rotas básicas necessárias na sua API. Abordaremos cada uma delas adiante.

| Rotas              | Descrição             | Método |
| ------------------ | --------------------- | ------ |
| `/`                | Rota inicial          | GET    |
| `/recents`         | Recentes              | GET    |
| `/popular`         | Populares             | GET    |
| `/search`          | Busca                 | GET    |
| `/item`            | Detalhes do item      | GET    |
| `/category`        | Categorias            | GET    |
| `/chapters`        | Capitulos             | GET    |
| `/chapters-images` | Imagens dos capitulos | GET    |
