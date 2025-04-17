<div align="center">
   <picture>
      <source alt="Manga app logo" media="(prefers-color-scheme: dark)" srcset="./docs/assets/logo-dark.png" width="100">
      <source alt="Manga app logo" media="(prefers-color-scheme: light)" srcset="./docs/assets/logo-light.png" width="100">
      <img alt="Manga app logo" src="./docs/assets/logo-dark.png" width="100">
    </picture>
  <h1>Manga create APIs docs</h1>
</div>

<p>Bem vindo a documentação de criação de APIs para o Manga! Você pode consultar o documentação <a href="https://aiko-dev.github.io/manga-create-api-docs/">aqui</a>.</p>

> [!WARNING]
> Essa documentação ainda está em desenvolvimento. Algumas partes podem estar incompletas ou desatualizadas.

<h2 align="center">Desenvolvendo a documentação</h2>

<p>O projeto utiliza <a href="https://www.python.org">Python</a>, com o gerenciador de pacotes <a href="https://python-poetry.org">Poetry</a>. Certifique-se de instala-los antes de iniciar o desenvolvimento.</p>

<p>Ative o ambiente virtual:</p>

```bash
poetry shell
```

<p>Instale as dependências do projeto:</p>

```bash
poetry install
```

<p>Para iniciar o servidor de desenvolvimento, execute:</p>

```bash
mkdocs serve
```

<p>Para construir a documentação, execute:</p>

```bash
mkdocs build
```

> Isso criará uma pasta chamada `dist` na raíz do projeto. Para visualizar a documentação, abra o `index.html` no navegador.

<h2 align="center">Contribuindo</h2>

Você pode contribuir para este projeto criando um fork deste repositório, implementando suas alterações em uma nova branch e enviando um pull request descrevendo as alterações feitas.

<h2 align="center">Licença</h2>

Este projeto utiliza a liscensa MIT, leia [LICENSE](./LICENSE) para mais detalhes.
