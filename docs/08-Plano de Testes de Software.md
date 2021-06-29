#
# 8. Plano de Testes de Software

Os requisitos para realização dos testes de software são:

- Site publicado na Internet
- Navegador da Internet - Chrome, Firefox ou Edge
- Conectividade de Internet para acesso às plataformas (APIs)

Os testes funcionais a serem realizados no site são descritos a seguir.

| **Caso de Teste** | **CT-01 – Realizar login no sistema** |
| --- | --- |
| **Requisitos Associados** | RNF-01: Permitir a manutenção do site durante seu ciclo de vida. |
| **Objetivo do Teste** | Verificar se a rotina de login está funcionando corretamente |
| **Passos** | 1) Acessar o Navegador e informar o endereço do Site2) Visualizar a página principal e selecionar a opção &quot;Login&quot;3) Digitar e-mail e senha de acesso previamente cadastrados4) Clicar em Login |
| **Critérios de Êxito** | Os mantedores do site devem conseguir ter acesso ao mesmo – login realizado corretamente. |

| **Caso de Teste** | **CT-02 – Realizar cadastro de Laboratórios e Construtoras** |
| --- | --- |
| **Requisitos Associados** | RF- 03: O site deve permitir o cadastro de laboratórios de ensaios.RF-09: O site deve permitir o cadastro das construtoras (cliente) com as informações: nome da empresa, responsável pelo projeto localização. |
| **Objetivo do Teste** | Verificar se os dados estão sendo armazenados corretamente através do Java Script |
| **Passos** | 1) Acessar o Navegador e informar o endereço do Site2) Visualizar a página principal e selecionar a opção &quot;Cadastros&quot;3) Selecionar o tipo e preencher os campos solicitados4) Verificar se os dados foram armazenados em Local Storage |
| **Critérios de Êxito** | Dados submetidos devem ser salvos em um array gerado por código Java Script em Local Storage e apresentados na página Serviços como tabela |

| **Caso de Teste** | **CT-03 - Visualizar notícias principais** |
| --- | --- |
| **Requisitos Associados** | RF-03 e RF-06 - O site deve apresentar na página principal notícias dinâmicas obtidas por meio de canais de notícias da Internet (API) |
| **Objetivo do Teste** | Verificar se a carga de notícias está acontecendo corretamente |
| **Passos** | 1) Acessar o Navegador2) Informar o endereço do Site3) Visualizar a página principal |
| **Critérios de Êxito** |
- Deve haver uma requisição AJAX no painel NETWORK das ferramentas do Desenvolvedor (recurso do Navegador).
- As notícias devem ser exibidas corretamente no site, sendo necessárias pelo menos 3 notícias sendo apresentadas
- As notícias devem trazer imagens visíveis associadas ao assunto da notícia
 |

| **Caso de Teste** | **CT-04 - Visualizar detalhes da notícia** |
| --- | --- |
| **Requisitos Associados** | RF-03 e RF-06 - O site deve permitir ao usuário visualizar o texto completo da notícia com todos os detalhes da publicação |
| **Objetivo do Teste** | Verificar se as notícias estão sendo apresentadas completamente na página de leitura da notícia |
| **Passos** | 1) Acessar o Navegador2) Informar o endereço do Site3) Visualizar a página principal4) Clicar em uma notícia |
| **Critérios de Êxito** | A página deve apresentar o título da notícia, imagem de destaque da notícia, data da notícia, autor da notícia e o texto completo da notícia |
