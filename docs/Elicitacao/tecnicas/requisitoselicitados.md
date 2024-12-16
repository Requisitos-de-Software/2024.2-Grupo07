## Introdução

Este documento apresenta os requisitos levantados para o projeto, identificados utilizando uma combinação de técnicas de elicitação: questionário, entrevista, brainstorming e introspecção. Essas abordagens foram selecionadas para proporcionar uma compreensão abrangente das necessidades e expectativas do sistema, capturando requisitos funcionais e não funcionais de forma consolidada na Tabela 1 abaixo.

### Requisitos Funcionais e Não Funcionais (RF e RNF)

<font size="2"><p style="text-align: center">Tabela 1 - Requisitos elicitados </p></font>

| **Identificador** | **Requisito**                                                                                                                                           | **Origem**    | **Tipo** |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | -------- |
| **01**            | O usuário deve poder curtir publicações.                                                                                                                | Introspecção  | RF       |
| **02**            | O usuário deve poder comentar publicações.                                                                                                              | Introspecção  | RF       |
| **03**            | O usuário deve poder repostar publicações.                                                                                                              | Introspecção  | RF       |
| **04**            | O usuário deve poder personalizar o visual do aplicativo.                                                                                               | Brainstorming | RF       |
| **05**            | O usuário deve receber notificações baseadas no uso do aplicativo.                                                                                      | Brainstorming | RF       |
| **06**            | O usuário deve poder personalizar o feed.                                                                                                               | Brainstorming | RF       |
| **07**            | O usuário deve poder integrar ou desconectar a conta do Instagram.                                                                                      | Brainstorming | RF       |
| **08**            | O usuário deve controlar quem pode visualizar suas postagens.                                                                                           | Entrevista    | RF       |
| **09**            | O sistema deve sugerir conteúdos relevantes ao usuário com base em seus interesses.                                                                     | Introspecção  | RF       |
| **10**            | O sistema deve permitir a criação de publicações com texto, imagens e links.                                                                            | Introspecção  | RF       |
| **11**            | O usuário deve configurar a visibilidade da conta como pública ou privada.                                                                              | Entrevista    | RF       |
| **12**            | O sistema deve criar "Trend Topics" para destacar os assuntos mais discutidos.                                                                          | Entrevista    | RF       |
| **13**            | O sistema deve reduzir anúncios intrusivos e ajustar algoritmos para maior transparência.                                                               | Questionário  | RNF      |
| **14**            | O sistema deve verificar contas com número de telefone e email cadastrados.                                                                             | Brainstorming | RF       |
| **15**            | O sistema deve melhorar o algoritmo para priorizar conteúdos relevantes ao usuário.                                                                     | Entrevista    | RNF      |
| **16**            | O sistema deve evitar a sobrecarga de notificações irrelevantes.                                                                                        | Brainstorming | RNF      |
| **17**            | O sistema deve garantir uma interface simples e intuitiva para novos usuários.                                                                          | Introspecção  | RNF      |
| **18**            | O sistema deve implementar moderação para reduzir bots e publicações irrelevantes.                                                                      | Entrevista    | RNF      |
| **19**            | O sistema deve oferecer autenticação avançada para segurança do usuário.                                                                                | Entrevista    | RNF      |
| **20**            | O sistema deve garantir tempos de resposta inferiores a 1 segundo para interações usuais.                                                               | Introspecção  | RNF      |
| **21**            | O sistema deve oferecer controle de privacidade.                                                                                                        | Entrevista    | RF       |
| **22**            | O sistema deve sugerir post gerados por Inteligência Artificial de acordo com as preferências e interesses do usuário.                                  | Brainstorming | RF       |
| **23**            | O sistema deve permitir que os usuários criem e salvem rascunhos de postagens mesmo sem conexão com a internet.                                         | Brainstorming | RF       |
| **24**            | O sistema deve permitir que os usuários agendem postagens para serem publicadas em horários específicos.                                                | Brainstorming | RF       |
| **25**            | O sistema deve sugerir novos usuários para seguir, com base nos interesses e nas interações do usuário.                                                 | Brainstorming | RF       |
| **26**            | O sistema deve permitir que os usuários façam backup e restaurem seus dados, como postagens e configurações.                                            | Brainstorming | RF       |
| **27**            | O sistema deve fornecer um histórico de interações do usuário, incluindo curtidas, comentários e compartilhamentos.                                     | Brainstorming | RF       |
| **28**            | O aplicativo deve minimizar o consumo de bateria em dispositivos móveis, garantindo uma taxa de consumo inferior a 5%.                                  | Brainstorming | RNF      |
| **29**            | O sistema deve permitir salvar postagens para leitura posterior em uma seção específica do perfil.                                                      | Brainstorming | RF       |
| **30**            | O sistema deve permitir gravar e enviar mensagens de voz diretamente em uma thread ou como resposta a um comentário.                                    | Brainstorming | RF       |
| **31**            | O sistema deve permitir aos usuários criar comunidades ou grupos temáticos dentro da plataforma.                                                        | Brainstorming | RF       |
| **32**            | O sistema deve adicionar uma funcionalidade para traduzir automaticamente threads escritas em outros idiomas.                                           | Brainstorming | RF       |
| **33**            | O sistema deve permitir respostas anônimas em discussões públicas moderadas.                                                                            | Brainstorming | RF       |
| **34**            | O sistema deve ser compatível com dispositivos móveis de versões Android 8.0 e iOS 12 ou superiores.                                                    | Questionário  | RNF      |
| **35**            | O sistema deve permitir agendamento de publicações para horários futuros.                                                                               | Introspecção  | RF       |
| **36**            | O sistema deve oferecer reações variadas (além de "curtir") para publicações.                                                                           | Introspecção  | RF       |
| **37**            | O sistema deve permitir a tradução automática de publicações para o idioma preferido do usuário.                                                        | Introspecção  | RF       |
| **38**            | O usuário deve poder denunciar contas ou postagens por violação de regras.                                                                              | Entrevista    | RF       |
| **39**            | O usuário deve poder ocultar publicações antigas de seu perfil sem excluí-las.                                                                          | Entrevista    | RF       |
| **40**            | O sistema deve permitir que o usuário faça login com autenticação biométrica.                                                                           | Brainstorming | RF       |
| **41**            | O sistema deve permitir que o usuário compartilhe postagens diretamente em plataformas externas.                                                        | Brainstorming | RF       |
| **42**            | O sistema deve ser compatível com versões de navegador mais antigas, garantindo funcionalidade em Chrome 70+ e Firefox 70+.                             | Introspecção  | RNF      |
| **43**            | O sistema deve garantir alta disponibilidade, com menos de 1% de tempo de inatividade mensal.                                                           | Brainstorming | RNF      |
| **44**            | O sistema deve criptografar todos os dados de login e autenticação para garantir a segurança das informações.                                           | Entrevista    | RNF      |
| **45**            | O sistema deve permitir que o usuário altere suas preferências de notificações para personalizar a experiência.                                         | Brainstorming | RF       |
| **46**            | O sistema deve permitir que o usuário defina um tema escuro ou claro no aplicativo.                                                                     | Brainstorming | RF       |
| **47**            | O sistema deve ser otimizado para uso em dispositivos com pouca memória RAM.                                                                            | Brainstorming | RNF      |
| **48**            | O sistema deve ser compatível com os navegadores mais recentes, como Google Chrome, Safari e Edge.                                                      | Brainstorming | RNF      |
| **49**            | O sistema deve permitir ao usuário gerenciar múltiplas contas no mesmo aplicativo.                                                                      | Brainstorming | RF       |
| **50**            | O sistema deve garantir que o feed de publicações seja carregado rapidamente, mesmo com grande volume de conteúdo.                                      | Brainstorming | RNF      |
| **51**            | O sistema deve permitir que o usuário tenha uma área de mensagens privadas para interações pessoais.                                                    | Brainstorming | RF       |
| **52**            | O sistema deve permitir que o usuário personalize a exibição de postagens no feed (por exemplo, mostrando mais fotos).                                  | Brainstorming | RF       |
| **53**            | O sistema deve permitir ao usuário fazer upload de vídeos em alta definição.                                                                            | Brainstorming | RF       |
| **54**            | O sistema deve garantir que os dados do usuário sejam armazenados de forma segura, com backup regular.                                                  | Brainstorming | RNF      |
| **55**            | O sistema deve permitir que o usuário defina preferências de anúncios, como limitar tipos de anúncios exibidos.                                         | Brainstorming | RF       |
| **56**            | O sistema deve garantir que o conteúdo do usuário seja sempre acessível, com um tempo de recuperação abaixo de 10 segundos.                             | Brainstorming | RNF      |
| **57**            | O sistema deve exibir uma confirmação visual (ex.: animação ou alerta) assim que o usuário realizar ações como curtir, salvar ou compartilhar conteúdo. | Brainstorming | RF       |
| **58**            | O sistema deve possibilitar o usuário a filtrar conteúdos no feed com base em categorias específicas.                             | Brainstorming | RF      |
| **59**            | O sistema deve possibilitar ao usuário adicionar legendas automáticas aos vídeos que envia, com suporte para múltiplos idiomas. | Brainstorming | RF       |

<font size="2"><p style="text-align: center; font-size: 14px;">
Autor: <a href="https://github.com/GenilsonJrs" target="_blank">Genilson Silva </a>

## Histórico de Versões

| **Versão** | **Data**   | **Descrição**           | **Autor(es)**                                      | **Revisor(es)**                                    |
| ---------- | ---------- | ----------------------- | -------------------------------------------------- | -------------------------------------------------- |
| 1.0        | 24/11/2024 | Criação do documento    | [Alana Gabriele](https://github.com/alanagabriele) | [Genilson Silva](https://github.com/GenilsonJrs)   |
| 2.0        | 24/11/2024 | Ajustes dos requisitos  | [Alana Gabriele](https://github.com/alanagabriele) | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| 2.1        | 08/12/2024 | Alterações e formatação | [Genilson Silva](https://github.com/GenilsonJrs)   | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| 2.2        | 13/12/2024 | Adição de requisitos    | [Genilson Silva](https://github.com/GenilsonJrs)   | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| 2.3        | 16/12/2024 | Adição de requisitos    | [Alana Gabriele](https://github.com/alanagabriele) | [Carlos Eduardo](https://github.com/dudupaz)       |
| 2.4        | 16/12/2024 | Adição de requisitos    | [Carlos Eduardo](https://github.com/dudupaz) | [Alana Gabriele](https://github.com/alanagabriele)       |
