# <p align="center"> Práticas em Desenvolvimento de Software <br/> (Instruções de Uso) </p>

> :warning: Este repositório é somente um modelo e, portanto, pode ser adaptado no que for necessário.

## Começando com o modelo

A seguir são apresentadas algumas instruções de como você pode fazer o melhor uso deste modelo.

1. Faça um _fork_ deste projeto usando sua conta pessoa. Ao clicar no botão `Fork` (acima) o GitHub irá criar uma cópia deste projeto e associar à sua conta.

   > Se desejar, você também pode simplesmente clonar o projeto, ou fazer download dos arquivos fonte, e então enviar a um novo repositório criado manualmente.

2. Adicione os membros da sua equipe como colaboradores no projeto que foi copiado. Acesse em `Settings > Colaborators > Add people`. Depois de adicioná-los, os mesmos terão de aceitar o convite para ter permissão para acessar o repositório.

3. Renomei o repositório para um nome mais adequado e elaborado junto à equipe (`Settings > General > Repository name`).

4. Modifique o arquivo [README.md](README.md) e adicione ou altere as informações no mesmo quando já disponíveis. Algumas seções serão necessárias serem modificadas somente pŕoximo à entrega do projeto, contudo, diversas outras podem ser atualizadas como forma de refletir o atual estado do andamento do projeto.

## Sobre a estrutura de diretórios

A estrutura de diretórios deste repositório é baseada em um modelo comum a diversos projetos. Mas a mesma poderá ser modificada de acordo com a necessidade ou desejo.

A atual estrutura sugere:

- **/dist**: Diretorio onde arquivos gerados durante o processo de compitação são armazenados. Em geral, sua exclusão não implica em perdas ao projeto já que podem ser re-compilados a qualquer momento.

- **/docs**: Diretorio destinado ao armazenamento de documentos produzidos durante o desenvolvimento. <ins>Atenção</ins>: evite armazenar links para documentos externos pois os mesmos podem serem quebrados futuramente!

- **/src**: Diretorio destinado ao armazenamento dos arquivos fonte do projeto.

- **/tests**: Diretorio destinado ao armazenamento de arquivos de teste (_e.g._, unitários ou de integração).

- **/utils**: Diretorio destinado ao armazenamento de ferramentas e utilitários que podem ser utilizados no contexto do sistema.

- No diretório raiz podem ser armazenados arquivos de configuração ou quaisquer outros documentos genéricos, desde que estes não dificultem o entendimento do mesmo.

## Sobre os arquivos _.keep_

Em alguns diretórios, foram colocados arquivos com nome `.keep`. Tais arquivos não tem valor e podem ser deletados a qualquer momento. O propósito destes é manter a existência das pastas desde que o sistema de controle git não envia diretórios arquivos para o repositório.