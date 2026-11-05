# Lista de Convidados

Aplicação web para organizar convidados e padrinhos de um casamento, acompanhar confirmações e visualizar estatísticas da lista.

> Projeto pessoal/acadêmico desenvolvido com HTML, CSS e JavaScript, com persistência e sincronização de dados usando Firebase Firestore.

## Funcionalidades

- Cadastro e remoção de convidados.
- Organização por lado do casal (noivo, noiva ou ambos).
- Cadastro de grupo/família e quantidade de acompanhantes.
- Controle de status: pendente, confirmado ou recusado.
- Pesquisa por nome e filtros por status.
- Painel com totais e progresso das confirmações.
- Área separada para padrinhos, madrinhas, pajens e damas.
- Sincronização dos dados entre dispositivos conectados ao mesmo banco.

## Tecnologias

- **HTML5** — estrutura da aplicação.
- **CSS3** — layout responsivo e identidade visual.
- **JavaScript** — interações, filtros, formulários e atualização da interface.
- **Firebase Firestore** — armazenamento e sincronização dos dados.

## Como executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em um navegador moderno.
3. Na primeira utilização, conecte a aplicação a um projeto Firebase/Firestore usando a configuração solicitada pela própria interface.
4. Configure as regras do Firestore antes de utilizar dados reais.

Como a aplicação é uma página estática, também pode ser publicada em um serviço de hospedagem estática. A configuração de hospedagem não está incluída neste repositório.

## Segurança e privacidade

- Não coloque senhas, tokens privados ou credenciais de serviço no código do navegador.
- A configuração web do Firebase não substitui regras de segurança.
- Configure regras do Firestore para permitir somente as operações necessárias e evitar acesso indevido aos dados.
- Utilize dados fictícios em demonstrações públicas; não publique nomes ou informações pessoais de convidados.

## Estrutura atual

O projeto está concentrado no arquivo `index.html`, que contém a estrutura, os estilos e a lógica JavaScript da aplicação.

## Próximas melhorias

- Separar HTML, CSS e JavaScript em arquivos próprios.
- Adicionar validação e mensagens de erro mais claras nos formulários.
- Documentar o modelo de dados do Firestore.
- Adicionar capturas de tela e uma demonstração online.
- Revisar e documentar as regras de segurança do banco.

---

Desenvolvido por [Luis Felipe](https://github.com/Luis9999999).
