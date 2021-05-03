## Especificação do Projeto

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação dos usuários em um trabalho de imersão feita pelos membros da equipe a partir da observação dos usuários em seu local natural e por meio de entrevistas. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas nas Figuras que se seguem.

|  **Tales Tavares**  ||
| --- | --- |
| **Dados** | **Motivações** |
| **Idade:** 55 anos | Manter a empresa atualizada |
| **Ocupação:** Proprietário de uma construtora | Abrir representações em outras cidades |
| **Aplicativos que mais usa** | **Frustração** |
| E-mail <br/> Facebook | Falta de informações sobre certificação |

| **Marcio Marques**  ||
| --- | --- |
| **Dados** | **Motivação** |
| **Idade:** 37 anos | Abrir uma construtora e incorporadora |
| **Ocupação:** Engenheiro Civil |
| **Aplicativos que mais usa** | **Frustração** |
| Instagram <br/> Facebook <br/> LinkedIn| As empresas que prestam serviço na área de certificação são desatualizadas em termos de tecnologia |

## Histórias de Usuários

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários.

| **Eu como … [PERSONA]** | … **quero/desejo …[O QUE]** | … **para .... [POR QUE]** |
| --- | --- | --- |
| Tales Tavares | encontrar uma empresa que tenha informações confiáveis sobre certificação de materiais | receber creditação de qualidade para minha construtora. |
| Tales Tavares | ter a certeza de que estou recebendo informações confiáveis | evitar retrabalho e frustrações. |
| Marcio Marques | ter convicção que as informações apresentadas são as mais atuais | que a minha (futura) construtora seja reconhecida como inovadora. |
| Marcio Marques | firmar parceria com uma empresa inovadora | facilitar o processo de comunicação e troca de informações. |

## Requisitos do Projeto

Após identificar todas as necessidades e demandas propostas pelas personas do projeto foi possível determinar as funcionalidades que o sistema deve apresentar para atender tais solicitações.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.

| **ID** | **Descrição** | **Prioridade** |
| --- | --- | --- |
| RF-01 | O site deve descrever os objetivos e funcionalidades desenvolvidos no projeto | Alta |
| RF-02 | O site deve fornecer informações referente as normas e certificações que devem ser cumpridas/obtidas pelas construtoras em cada etapa de uma obra | Alta |
| RF-03 | O site deve permitir o cadastro do perfil laboratórios (fornecedor) de ensaios com as informações: nome da empresa, contato, setor, localização, tipos de ensaios realizados, certificações, principais clientes, prazo mínimo de entrega de cada tipo de serviço. | Alta |
| RF-04 | O site deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário: localizar possíveis laboratórios que possam executar os ensaios, localizar laboratórios próximos, localizar laboratórios com melhor classificação, localizar laboratórios que tenham uma determinada certificação. | Alta |
| RF-05 | O site deve permitir visualizar as informações de contatos do mantenedor do site | Média |
| RF-06 | Permitir a classificação dos laboratórios de ensaios pelas empresas de Construção Civil | Média |
| RF-07 | O site deve disponibilizar informações sobre notícias, eventos e treinamentos relevantes para o setor | Baixa |
| RF-08 | O site dever gerar um selo de confiabilidade para cada laboratório que atingir a meta de nota de classificação. | Alta |
| RF-09 | O site deve permitir o cadastro das construtoras (cliente) com as informações: nome da empresa, responsável pelo projeto, localização, setor. | Média |
| RF-10 | O site deve conter uma página com mapa apontando a localização dos laboratórios. | Baixa |
| RF-11 | O layout da interface do site deverá destacar sua principal funcionalidade que é a busca por laboratórios.| Média |

### Requisitos Não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

| **ID** | **Descrição** | **Prioridade** |
| --- | --- | --- |
| RNF-01 | Deverá ser providenciado o ambiente de hospedagem do site, no qual permitirá sua publicação na internet e a manutenção do mesmo durante seu ciclo de vida. (Provedor de nuvem, Github Pages, etc.) | Alta |
| RNF-02 | O Site deve possuir um banco de dados (Mysql, Mariadb ou Postgres), com os dados dos fornecedores e clientes. | Alta |
| RNF-03 | A interface deverá utilizar linguagens front-end padrões (HMTM, CSS, JavaScript). | Alta |
| RNF-04 | O site deverá ser integrado aos mecanismos de pesquisa na internet (Google, Bing, Yahoo Search). | Média |
| RNF-05 | O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge). | Média |
| RNF-06 | O funcionamento interno do site deverá ser desenvolvido utilizando algoritmos otimizados para a filtragem das opções solicitadas. | Baixa |

### Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

| **ID** | **Descrição** |
| --- | --- |
| RE-01 | O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 07/07/2021. |
| RE-02 | O aplicativo deve se restringir às tecnologias básicas da Web no Front-end |
| RE-03 | A equipe não pode subcontratar o desenvolvimento do trabalho. |
