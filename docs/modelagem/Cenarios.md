# Cenários

## Introdução

Os cenários são descrições detalhadas, geralmente em linguagem natural, que representam situações ou eventos específicos relacionados ao uso de um sistema ou aplicação. Eles têm como objetivo descrever o contexto, os atores, os recursos necessários e o fluxo de interação entre os elementos envolvidos, permitindo um entendimento mais profundo de como o sistema deve funcionar em diferentes condições.



---
## Cenário 1
<center>

**Tabela 1: Exibir e gerenciar Trend Topics.**

| **Cenário 1** |
|---------------|
| **Título**    |
| _Exibir e gerenciar Trend Topics._ |
| **Objetivo**  |
| _Permitir que o usuário visualize e interaja com os principais tópicos em alta na plataforma._ |
| **Contexto**  |
| <p>Local: _Tela inicial do aplicativo Threads._</p> <p>Tempo: _Aproximadamente 1 minuto._</p> <p>Pré-condição: _Existirem tópicos em alta registrados e atualizados no sistema._</p> |
| **Atores**    |
| _Usuário do aplicativo Threads._ |
| **Recursos**  |
| <p>_Conexão com a internet._</p> <p>_Dispositivo móvel com o aplicativo Threads instalado._</p> |
| **Episódios** |
| <p>_O usuário acessa a tela inicial do aplicativo._</p> <p>_O sistema exibe uma lista dos tópicos em alta baseados na região, idioma ou preferências do usuário._</p> <p>_O usuário seleciona um tópico em alta._</p> <p>_O sistema redireciona para uma página com postagens relacionadas ao tópico escolhido._</p> <p>_O usuário pode interagir com as postagens (curtir, comentar, compartilhar)._</p> |
| **Restrição** |
| <p>_Apenas tópicos com volume de interações significativas serão exibidos._</p> <p>_O usuário deve estar conectado à internet para acessar os Trend Topics._</p> |
| **Exceção**   |
| <p>_Erro de conexão: Caso haja falha na conexão com a internet, o aplicativo exibirá uma mensagem informando que os Trend Topics não podem ser carregados._</p> <p>_Sem dados disponíveis: Caso não existam tópicos em alta, o aplicativo exibirá uma mensagem informando que ainda não há tendências disponíveis._</p> |

**Fonte:**  [Samuel Ribeiro](https://github.com/SamuelRicosta).

</center>

---
## Cenário 2
<center>

**Tabela 2: Personalização do Perfil.**

| **Cenário 2** |
|---------------|
| **Título**    |
| _Customizar o perfil do usuário._ |
| **Objetivo**  |
| _Permitir que o usuário personalize visualmente seu perfil, incluindo imagem de fundo, bordas e outros elementos._ |
| **Contexto**  |
| <p>Local: _Tela de edição do perfil no aplicativo Threads._</p> <p>Tempo: _Aproximadamente 5 minutos._</p> <p>Pré-condição: _O usuário deve estar logado no aplicativo._</p> |
| **Atores**    |
| _Usuário do aplicativo Threads._ |
| **Recursos**  |
| <p>_Conexão com a internet._</p> <p>_Dispositivo móvel com o aplicativo Threads instalado._</p> <p>_Imagens ou recursos externos para upload (opcional)._</p> |
| **Episódios** |
| <p>_O usuário acessa a seção de edição de perfil._</p> <p>_O sistema exibe as opções de personalização disponíveis (imagem de fundo, bordas, cores, fontes, etc.)._</p> <p>_O usuário seleciona um item para personalizar, como a imagem de fundo._</p> <p>_O sistema permite que o usuário escolha entre opções fornecidas ou faça upload de uma imagem própria._</p> <p>_O usuário ajusta os elementos visuais de acordo com suas preferências._</p> <p>_O sistema exibe uma pré-visualização do perfil personalizado._</p> <p>_O usuário salva as alterações realizadas._</p> |
| **Restrição** |
| <p>_O upload de imagens deve obedecer aos limites de tamanho e formato especificados pelo aplicativo._</p> <p>_Certas opções avançadas de personalização podem estar disponíveis apenas para usuários premium._</p> |
| **Exceção**   |
| <p>_Erro de conexão: Se a internet estiver indisponível, o sistema não permitirá o upload de imagens ou a visualização de opções externas._</p> <p>_Imagem inválida: Caso o arquivo carregado não esteja no formato correto, o aplicativo exibirá uma mensagem de erro._</p> |

**Fonte:** [Samuel Ribeiro](https://github.com/SamuelRicosta).

</center>
---

## Referências

- ASSOCIAÇÃO Brasileira de Normas Técnicas. **NBR 6023: Informação e documentação - Referências - Elaboração**. Rio de Janeiro, 2018.  
- BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. **Interação humano-computador**. Elsevier, 2010.  
- GABRIEL Campello; DOUGLAS Alves. **Análise de requisitos de software da aplicação Duolingo**. Disponível em: [https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/). Acesso em: 24 nov. 2023.  
- SERRANO, Milene. **Requisitos – Aula 10**. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Acesso em: 24 nov. 2023.  

| Versão | Data       | Descrição            | Autor                                        | Revisor                                            |
| :----: | ---------- | -------------------- | -------------------------------------------- | -------------------------------------------------- |
|  1.0   | 06/12/2024 | Criação do documento e cenarios 1 e 2  | [Samuel Ribeiro](https://github.com/SamuelRicosta)  | [Carlos Eduardo](https://github.com/dudupaz) |
