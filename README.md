# nome_do_projeto

descricao_do_projeto

Esse projeto foi criado por <NOME_DO_TIME ou NOME_DAS_PESSOAS>

# Contexto
> **Note**
> Uma descrição do serviço, por exemplo: "project_name é um serviço de..."

# Que problema(s) tenta resolver?
> **Note**
> Descrever com detalhes o que este serviço está tentando resolver

# Principais funcionalidades
> **Note**
> Descrever quais as principais funcionalidades do serviço

# Arquitetura
> **Note**
> Existem processos, serviços ou componentes envolvidos? Como eles se encaixam?
> Existem requisitos ambientais (AWS) ou de apoio (Kafka, Zookeeper)?
>
> Diagramas são bem-vindos aqui. Busque usar a [integração entre Github e Mermaid](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/)

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

# Escopo do serviço

## Este serviço é indicado para:
> **Note**
> Em que circunstâncias este serviço é adequado? Por que?

## Este serviço NÃO é indicado para:
> **Note**
> Em que circunstâncias este serviço não é adequado? Por que?

# Alternativas
> **Note**
> Existem serviços alternativos no mesmo espaço?
> O que os difere?

# Outras características relevantes
> **Note**
> Liste aspectos operacionais (latência, escalabilidade, segurança) que devem ser destacados

# Recursos
> **Note**
> Links externos, documentações, referências etc

# Execução do projeto e configuração de ambiente

## Requisitos
- `Fastify ^4.3.0`
- `Node.js 16 LTS or later`

## Code Style

* Check [TypeScript Code Style Best Practices Recommendations](https://google.github.io/styleguide/tsguide.html)

## Linting

### List issues

```bash
$ yarn lint
```

### Fix issues

```bash
$ yarn lint:fix
```

## Testing

### Run all tests:

```bash
$ yarn test
```
### Run autotest

```bash
$ yarn test:watch
```

### Unit tests

```bash
$ yarn unit
```

### Integration tests

```bash
$ yarn integration
```

## Running

```bash
$ git clone git@github.com:flash-tecnologia/project_name.git
$ cd project_name
$ yarn
$ yarn dev
```

If everything went well you can play here -> http://localhost:3000/docs
