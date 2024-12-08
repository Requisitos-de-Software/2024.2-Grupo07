## Introdução

Léxico, no que tange a área de requisitos de software, refere-se ao reconhecimento do conjunto de termos, palavras ou frases que são relevantes e específicos para o sistema ou aplicativo em desenvolvimento.

## Metodologia

Os léxicos do Threads foram identificados a partir da utilização do aplicativo e dos requisitos elicitados na etapa de [Elicitação de requisitos](../../Elicitacao/tecnicas/requisitoselicitados). Na tabela 1, temos um exemplo de como os léxicos serão apresentados e descritos:

<font size="2"><p style="text-align: center">Tabela 1 - Exemplo das tabelas de Léxicos. </p></font>

| **Léxico**       | **Noção**                          | **Impacto**                                   | **Sinônimo(s)**    | **Classificação** | **Requisitos Relacionados**                                                                                  |
|------------------|------------------------------------|-----------------------------------------------|--------------------|--------------------|-------------------------------------------------------------------------------------------------------------|
| Nome do Léxico 1          | Símbolos               | Descrição do efeito              | Sinônimo(s)          | Verbo/Objeto/Estado             | Códigos dos Requisitos                                             |
| Nome do Léxico 2          | Símbolos               | Descrição do efeito              | Sinônimo(s)          | Verbo/Objeto/Estado             | Códigos dos Requisitos                                             |
| Nome do Léxico 3          | Símbolos               | Descrição do efeito              | Sinônimo(s)          | Verbo/Objeto/Estado             | Códigos dos Requisitos                                             |

<font size="2"><p style="text-align: center"> Autores: [Genilson Junior](https://github.com/GenilsonJrs) e [Carlos Eduardo](https://github.com/dudupaz) </p></font>


## Léxicos

Logo abaixo estão os Léxicos de Verbo, Objeto e Estado respectivamente, presentes nas tabelas 2, 3 e 4.

### Tabela de Léxicos de Verbo

<font size="2"><p style="text-align: center">Tabela 2 - Léxicos de Verbo. </p></font>

| **Léxico**       | **Noção**                          | **Impacto**                                   | **Sinônimo(s)**    | **Classificação** | **Requisitos Relacionados**                                                                                  |
|------------------|------------------------------------|-----------------------------------------------|--------------------|--------------------|-------------------------------------------------------------------------------------------------------------|
| Curtir           | Expressar interesse em conteúdo.  | Melhora engajamento e interação do usuário.  | "Like"            | Verbo              | <a href="../../Elicitacao/tecnicas/requisitoselicitados">01</a>                                             |
| Comentar         | Adicionar opinião ou resposta.    | Aumenta a interação e discussões no sistema. | "Responder"       | Verbo              | <a href="../../Elicitacao/tecnicas/requisitoselicitados">02</a>                                             |
| Repostar         | Compartilhar publicações.         | Amplia o alcance de conteúdos no sistema.    | "Compartilhar"    | Verbo              | <a href="../../Elicitacao/tecnicas/requisitoselicitados">03</a>                                             |
| Personalizar     | Alterar configurações visuais.    | Gera uma experiência mais agradável.         | "Configurar"      | Verbo              | <a href="../../Elicitacao/tecnicas/requisitoselicitados">04</a>                                             |
| Configurar       | Ajustar parâmetros do sistema.    | Facilita o controle de funcionalidades.      | "Ajustar"         | Verbo              | <a href="../../Elicitacao/tecnicas/requisitoselicitados">11</a>                                             |

<font size="2"><p style="text-align: center">Autores: [Carlos Eduardo](https://github.com/dudupaz) e [Genilson Junior](https://github.com/GenilsonJrs).</a></font>

### Tabela de Léxicos de Objeto

<font size="2"><p style="text-align: center">Tabela 3 - Léxicos de Objeto. </p></font>

| **Léxico**       | **Noção**                          | **Impacto**                                   | **Sinônimo(s)**    | **Classificação** | **Requisitos Relacionados**                                                                                  |
|------------------|------------------------------------|-----------------------------------------------|--------------------|--------------------|-------------------------------------------------------------------------------------------------------------|
| Publicação       | Conteúdo compartilhado.           | Centraliza interações e informações.         | "Postagem"        | Objeto             | <a href="../../Elicitacao/tecnicas/requisitoselicitados">01</a>, <a href="../../Elicitacao/tecnicas/requisitoselicitados">02</a>, <a href="../../Elicitacao/tecnicas/requisitoselicitados">03</a>, <a href="../../Elicitacao/tecnicas/requisitoselicitados">10</a> |
| Notificação      | Alerta de eventos no sistema.     | Mantém o usuário informado e engajado.       | "Alerta"          | Objeto             | <a href="../../Elicitacao/tecnicas/requisitoselicitados">05</a>, <a href="../../Elicitacao/tecnicas/requisitoselicitados">16</a> |
| Feed             | Fluxo de publicações personalizável.| Centraliza o acesso ao conteúdo relevante.  | "Timeline"        | Objeto             | <a href="../../Elicitacao/tecnicas/requisitoselicitados">06</a>, <a href="../../Elicitacao/tecnicas/requisitoselicitados">09</a> |
| Conta            | Perfil único de um usuário.       | Identifica e autentica o usuário.            | "Perfil"          | Objeto             | <a href="../../Elicitacao/tecnicas/requisitoselicitados">07</a>, <a href="../../Elicitacao/tecnicas/requisitoselicitados">11</a>, <a href="../../Elicitacao/tecnicas/requisitoselicitados">14</a> |
| Algoritmo        | Sistema de processamento lógico.  | Prioriza conteúdos e experiências do usuário.| "Mecanismo"       | Objeto             | <a href="../../Elicitacao/tecnicas/requisitoselicitados">09</a>, <a href="../../Elicitacao/tecnicas/requisitoselicitados">15</a> |

<font size="2"><p style="text-align: center">Autores: [Genilson Junior](https://github.com/GenilsonJrs) e [Carlos Eduardo](https://github.com/dudupaz).</a></font>

### Tabela de Léxicos de Estado

<font size="2"><p style="text-align: center">Tabela 4 - Léxicos de Estado. </p></font>

| **Léxico**       | **Noção**                          | **Impacto**                                   | **Sinônimo(s)**    | **Classificação** | **Requisitos Relacionados**                                                                                  |
|------------------|------------------------------------|-----------------------------------------------|--------------------|--------------------|-------------------------------------------------------------------------------------------------------------|
| Público          | Visível para todos.               | Aumenta o alcance de conteúdos.              | "Aberto"          | Estado             | <a href="../../Elicitacao/tecnicas/requisitoselicitados">11</a>                                             |
| Privado          | Restrito a pessoas autorizadas.   | Melhora o controle de privacidade.           | "Fechado"         | Estado             | <a href="../../Elicitacao/tecnicas/requisitoselicitados">11</a>                                             |
| Engajado         | Ativo no sistema.                 | Melhora a retenção de usuários.              | "Interativo"      | Estado             | <a href="../../Elicitacao/tecnicas/requisitoselicitados">01</a>, <a href="../../Elicitacao/tecnicas/requisitoselicitados">02</a>, <a href="../../Elicitacao/tecnicas/requisitoselicitados">05</a> |
| Relevante        | Alinhado aos interesses.          | Facilita a experiência personalizada.        | "Significativo"   | Estado             | <a href="../../Elicitacao/tecnicas/requisitoselicitados">09</a>, <a href="../../Elicitacao/tecnicas/requisitoselicitados">15</a> |
| Moderado         | Filtrado e organizado.            | Evita spam e conteúdos indesejados.          | "Controlado"      | Estado             | <a href="../../Elicitacao/tecnicas/requisitoselicitados">18</a>                                             |

<font size="2"><p style="text-align: center">Autores: [Genilson Junior](https://github.com/GenilsonJrs) e [Carlos Eduardo](https://github.com/dudupaz).</a></font>

## Bibliografia

> SERRANO, Milene e Maurício. Requisitos - Aula 10. UnB-FGA, Gama, DF. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf).

## Histórico de Versões

| Versão | Data       | Descrição            | Autor                                        | Revisor                                            |
| :----: | ---------- | -------------------- | ------------------------------------------ | --------------------------------------------------- |
|  1.0   | 03/12/2024 | Criação do documento e inserção de léxicos | [Carlos Eduardo](https://github.com/dudupaz) | [Samuel Ribeiro](https://github.com/SamuelRicosta)  |
|  2.0   | 08/12/2024 | Alterações, Formatação e Adição de léxicos | [Genilson Silva](https://github.com/GenilsonJrs) | [Samuel Ribeiro](https://github.com/SamuelRicosta)  |
