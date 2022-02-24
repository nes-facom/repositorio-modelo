# <p align="center"> Práticas em Desenvolvimento de Software <br/> (Repositório Modelo) </p>

<p align="center">
  <img src="Logo1-NES_branco.png" height="175px" />
  <br/>
  <small>Logo ou screenshot da aplicação</small>
</p>

Este repositório é um modelo de como os alunos das disciplinas de Prática em Desenvolvimento de Software I e II podem organizar seus respectivos projetos e artefatos gerados. Portanto, a partir deste ponto, será proposta uma estrutura básica contendo uma descrição simplificada de cada seção. Recomendações e instruções mais detalhadas podem ser encontradas no arquivo [INSTRUCOES.md](INSTRUCOES.md).

Use desta seção para apresentar seu produto de forma simples e sussinta, assim como na frase acima.

## Estrutura do documento

- [Descrição do projeto](#descri%C3%A7%C3%A3o-do-projeto)
- [Funcionalidades](#funcionalidades)
- [Requisitos](#requisitos)
- [Instalação](#instala%C3%A7%C3%A3o--implanta%C3%A7%C3%A3o)
- [Primeiros passos](#primeiros-passos)
- [Autores e histórico](#autores-e-hist%C3%B3rico)
- [Licença](#licen%C3%A7a)

## Descrição do projeto

Nesta seção você deve apresentar, de forma mais detalhada, um pouco mais do projeto que foi desenvolvido, para isso apresente: o contexto, o problema e a solução proposta.

Busque ser objetivo e apresentar cada um dos pontos em um parágrafo dedicado.

## Funcionalidades

Liste as principais funcionalidades do sistema implementado. Você pode usar de checkbox para indicar aquelas que foram, ou não, implementadas na versão atual. Por exemplo:

- [x] Funcionalidade 1
- [ ] Funcionalidade 2
- [ ] ...

## Requisitos

Aqui você deve apresentar todos os requisitos para que sua aplicação funcione corretamente. Você também pode listar dependências opcionais, se houver.

Começe indicando qual, ou quais, sistemas operacionais são suportados. Por exemplo: `Este sistema foi desenvolvido e amplamente testado em ambientes Unix ...`

Para cada uma das dependências do sistema é importatne listar também a versão mínima necessária. Por exemplo:

- [Docker](https://www.docker.com/) (versão 20 ou superior)
  - Se necessário, você pode deixar alguma observação ou instrução necessária.
- [Python](https://www.python.org/) (versão 3.10 ou superior)
- [Node.js](https://nodejs.org/) (versão 16)
- ...

## Instalação / Implantação

Nesta seção você deverá trazer um passo a passo do que é necessário para a implantação do sistema desenvolvido.

Preferencialmente, use de ferramentas que automatizem a instalação/implantação do sistema, ou partes dele. Por exemplo, se você precisa compilar os arquivos do sistema para utilizá-lo, uma ótima opção é o [Make](https://www.gnu.org/software/make/). Com ele é possível automatizar todo processo de preparação e compilaçãocom um simples comando no terminal:

```sh
make
```

Outras ferramentas podem, inclusive, automatizar o processo de inicialização dos serviços da ferramenta, como o [Docker Compose](https://docs.docker.com/compose/):

```sh
docker-compose up -d
```

Se o sistema precisa ser implantado manualmente, descreva detalhadamente os passos necessários para a correta instalação. Neste caso, u

1. Abra um terminal no diretório do projeto ....
2. Instale as dependências usando o comando xxxx ...
3. Compile o código fonte com o comando yyyy ...
4. ....

Por fim, lembre-se de destacar quando necessário quais variáveis de ambientes (do inglês _environment variables_) são utilizadas ou necessárias para o processo. Muitas vezes a falta destas variáveis pode causar erros e impedir a correta implantação do sistema.

## Primeiros passos

Use esta seção para mostrar os primeiros passos para usar a aplicação. Lembre-se que esta parte deve ser focada no uso pelos clientes finais da aplicação, portanto, seja objetivo e use _screenshots_ quando necessário.

## Autores e histórico

Este sistema foi desenvolvido pela seguinte equipe:

- [Fulano](https://github.com/fulano) (fulano@email.com)
- [Sicrano](https://github.com/sicrano) (sicrano@email.com)
- ....

Orientado pelo professor [Beltrano Silva](https://github.com/beltrano-silva) e proposto por XXXX YYYY.

> :warning: Se o projeto for de continuidade, vocẽ deverá mencionar qual e criar um link para o projeto original.

## Licença

Este sistema está disponível sob a licença [XXXX](https://opensource.org/licenses/).

> :warning: Você deve discutir a licença com seu professor orientador!

> :warning: Lembre-se também de criar, ou alterar, o arquivo LICENSE deste repositório para refletir adequadamente a licença atual.
