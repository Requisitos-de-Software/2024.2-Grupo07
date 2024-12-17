## Introdução

Este documento apresenta os requisitos levantados para o projeto, identificados utilizando uma combinação de técnicas de elicitação: questionário, entrevista, brainstorming e introspecção. Essas abordagens foram selecionadas para proporcionar uma compreensão abrangente das necessidades e expectativas do sistema, capturando requisitos funcionais e não funcionais de forma consolidada na Tabela 1 abaixo.

### Requisitos Funcionais e Não Funcionais (RF e RNF)

<font size="2"><p style="text-align: center">Tabela 1 - Requisitos elicitados </p></font>

| **Identificador** | **Requisito**                                                                 | **Origem** | **Tipo** |
| ----------------- | --------------------------------------------------------------------------- | ---------- | -------- |
| **01**            | O usuário deve poder configurar a visibilidade da conta.                    | Entrevista           | RF       |
| **02**            | O usuário deve poder gravar e enviar mensagens de voz.                      |Entrevista            | RF       |
| **03**            | O sistema deve exibir Trend Topics para visualização dos tópicos populares. |Entrevista            | RF       |
| **04**            | O usuário deve poder definir o tema escuro ou claro no aplicativo.          | Entrevista           | RF       |
| **05**            | O sistema deve oferecer uma área de mensagens privadas para interações.    |Entrevista            | RF       |
| **06**            | O sistema deve verificar contas com número de telefone e email cadastrados. | Entrevista           | RF       |
| **07**            | O sistema deve permitir a tradução automática de publicações.              |Entrevista            | RF       |
| **08**            | O sistema deve reduzir a exibição de anúncios intrusivos.                   |  Entrevista          | RF       |
| **09**            | O sistema deve implementar moderação para reduzir bots e publicações irrelevantes. | Entrevista           | RF       |
| **10**            | O sistema deve permitir o upload de vídeos em alta definição.              | Entrevista           | RF       |
| **11**            | O sistema deve exibir uma confirmação visual ao realizar ações.           | Entrevista           | RF       |
| **12**            | O sistema deve oferecer um histórico de interações do usuário.             |Entrevista            | RF       |
| **13**            | O sistema deve permitir respostas anônimas em discussões públicas moderadas. |Entrevista            | RF       |
| **14**            | O sistema deve permitir que o usuário salve postagens para leitura posterior. |Entrevista            | RF       |
| **15**            | O sistema deve sugerir usuários para seguir, com base nas interações do usuário. |Entrevista            | RF       |
| **16**            | O sistema deve permitir a criação de enquetes interativas.                 | Entrevista           | RF       |
| **17**            | O sistema deve permitir ao usuário denunciar contas ou postagens.          |Entrevista            | RF       |
| **18**            | O usuário deve poder ocultar publicações antigas de seu perfil sem excluí-las. | Entrevista           | RF       |
| **19**            | O sistema deve permitir backup e restauração de dados, como postagens e configurações. |Entrevista            | RF       |
| **20**            | O sistema deve permitir filtrar conteúdos no feed com base em categorias específicas. |Entrevista            | RF       |
| **21**            | O sistema deve permitir que o usuário adicione legendas automáticas aos vídeos enviados. | Entrevista           | RF       |
| **22**            | O sistema deve sugerir textos gerados por Inteligência Artificial para publicações. |Entrevista            | RF       |
| **23**            | O sistema deve oferecer reações variadas para publicações.                 |Entrevista            | RF       |
| **24**            | O sistema deve permitir salvar rascunhos de postagens mesmo sem conexão.   | Entrevista           | RF       |
| **25**            | O sistema deve permitir agendar postagens para horários futuros.           | Entrevista           | RF       |
| **26**            | O sistema deve permitir o compartilhamento de postagens externas.          |Entrevista            | RF       |
| **27**            | O sistema deve permitir criar comunidades ou grupos dentro da plataforma.  |Entrevista            | RF       |
| **28**            | O sistema deve permitir que o usuário gerencie múltiplas contas no mesmo aplicativo. |Entrevista            | RF       |
| **29**            | O sistema deve oferecer autenticação avançada para segurança do usuário.   |Entrevista            | RF       |
| **30**            | O sistema deve permitir fixar postagens no perfil do usuário.              |Entrevista            | RF       |
| **31**            | O sistema deve permitir editar publicações após a postagem.                |Questionário            | RF       |
| **32**            | O sistema deve permitir marcar outros usuários em postagens.               |Questionário            | RF       |
| **33**            | O sistema deve permitir ver estatísticas detalhadas sobre as postagens.   |Questionário            | RF       |
| **34**            | O sistema deve permitir que o usuário receba alertas de menções.           |Questionário            | RF       |
| **35**            | O sistema deve permitir reações a comentários em postagens.                |Questionário            | RF       |
| **36**            | O sistema deve permitir criar listas de amigos próximos.                   |Brainstorming            | RF       |
| **37**            | O sistema deve permitir realizar pesquisas de conteúdo.                    |Brainstorming            | RF       |
| **38**            | O sistema deve permitir denunciar comentários ofensivos.                  |Brainstorming            | RF       |
| **39**            | O sistema deve sugerir postagens personalizadas de acordo com as preferências do usuário. |Brainstorming            | RF       |
| **40**            | O sistema deve permitir configurar o status online ou offline do usuário. |Brainstorming            | RF       |
| **41**            | O sistema deve reduzir anúncios intrusivos e ajustar algoritmos para maior transparência. |Introspecção            | RNF      |
| **42**            | O sistema deve melhorar o algoritmo para priorizar conteúdos relevantes ao usuário. | Introspecção           | RNF      |
| **43**            | O sistema deve evitar a sobrecarga de notificações irrelevantes.            |Introspecção            | RNF      |
| **44**            | O sistema deve implementar moderação para reduzir bots e publicações irrelevantes. |Introspecção            | RNF      |
| **45**            | O sistema deve oferecer autenticação avançada para segurança do usuário.    |Introspecção            | RNF      |
| **46**            | O sistema deve garantir tempos de resposta inferiores a 1 segundo para interações usuais. |Introspecção            | RNF      |
| **47**            | O aplicativo deve minimizar o consumo de bateria em dispositivos móveis, garantindo uma taxa de consumo inferior a 5%. |Introspecção            | RNF      |
| **48**            | O sistema deve ser compatível com dispositivos móveis de versões Android 8.0 e iOS 12 ou superiores. |Introspecção            | RNF      |
| **49**            | O sistema deve ser compatível com versões de navegador mais antigas, garantindo funcionalidade em Chrome 70+ e Firefox 70+. | Brainstorming           | RNF      |
| **50**            | O sistema deve garantir alta disponibilidade, com menos de 1% de tempo de inatividade mensal. |Brainstorming            | RNF      |
| **51**            | O sistema deve criptografar todos os dados de login e autenticação para garantir a segurança das informações. |Brainstorming            | RNF      |
| **52**            | O sistema deve ser otimizado para uso em dispositivos com pouca memória RAM. | Brainstorming           | RNF      |
| **53**            | O sistema deve ser compatível com os navegadores mais recentes, como Google Chrome, Safari e Edge. |Brainstorming            | RNF      |
| **54**            | O sistema deve garantir que o feed de publicações seja carregado rapidamente, mesmo com grande volume de conteúdo. |Brainstorming            | RNF      |
| **55**            | O sistema deve garantir que os dados do usuário sejam armazenados de forma segura, com backup regular. |Brainstorming            | RNF      |
| **56**            | O sistema deve garantir que o conteúdo do usuário seja sempre acessível, com um tempo de recuperação abaixo de 10 segundos. |Brainstorming            | RNF      |

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
| 2.5        | 17/12/2024 | Ajustes no documento    | [Genilson Silva](https://github.com/GenilsonJrs) | [Alana Gabriele](https://github.com/alanagabriele)       |
