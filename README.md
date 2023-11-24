# SuperHeroes

Este é um projeto para cadastro de super-heróis e seus superpoderes.

## Tecnologias utilizadas

### Front-end
- Angular
- Material
- Tailwind CSS
- SCSS
- TypeScript
- HTML

### Back-end
- ASP.NET Core 7
- Entity Framework Core
- SQLite

## Instalação

Para clonar o repositório:

```
git clone --recursive https://github.com/Brennon-Oliveira/SuperHeroes.git
```

Isso criará duas pastas, `SuperHeroesApi` e `SuperHeroesFront`.

### Front-end

Entre na pasta `SuperHeroesFront` e instale as dependências:

```
npm install --force
```

Inicie o servidor de desenvolvimento:

```
npm run start
```

ou

```
ng serve
```

Acesse http://localhost:4200 no navegador.

### Back-end

#### Recomendado
Abra a solução `SuperHeroesApi` no Visual Studio:
___
#### ou
Execute no terminal
```
dotnet build
```

Para zerar o banco de dados, exclua os arquivos `app.db` e rode:

```
dotnet ef database update --project .\SuperHeroes.Api\ 
```

Inicie o servidor:

```
dotnet run --project .\SuperHeroes.Api\
```

Acesse a documentação Swagger em http://localhost:7043/swagger/index.html.

## Funcionalidades

O sistema permite:

- Listar super-heróis
- Cadastrar novos super-heróis
- Editar super-heróis
- Excluir super-heróis
- Listar superpoderes
- Cadastrar novos superpoderes
- Editar superpoderes
- Excluir superpoderes
