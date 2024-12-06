# Especificação Suplementar

## Introdução

A Especificação Suplementar é um documento que detalha os requisitos não contemplados diretamente nos casos de uso. Este documento complementa a descrição funcional do sistema, abrangendo aspectos como desempenho, usabilidade, confiabilidade, suporte e outros, garantindo a qualidade e a satisfação dos usuários. Ele também captura requisitos como normas legais, atributos de qualidade, desempenho e compatibilidade.

A rede social Threads foi escolhida como objeto de estudo para explorar esses aspectos. Para organizar e documentar os requisitos suplementares, utilizamos a metodologia **FURPS+**, adaptada às especificidades do sistema.

---

## Metodologia

A metodologia utilizada para a elaboração deste documento é baseada no modelo **FURPS+**, amplamente reconhecido como uma técnica eficaz para a identificação e organização de requisitos não funcionais. O acrônimo FURPS+ representa as categorias:

- **F:** Funcionalidade
- **U:** Usabilidade
- **R:** Confiabilidade
- **P:** Desempenho
- **S:** Suporte

Além disso, inclui requisitos adicionais como restrições de design e documentação. Este documento foi estruturado com base nessas categorias para detalhar os requisitos não funcionais relacionados ao aplicativo Threads.

---

# FURPS+

## F: Funcionalidade (Functionality)

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Funcionalidade </p></font>

| **ID**  | **Descrição**                                                                                                    |
|---------|------------------------------------------------------------------------------------------------------------------|
| FUN01   | O sistema deve incluir funcionalidades de busca por hashtags e conteúdos relevantes.                             |
| FUN02   | O sistema deve permitir a criação e personalização de perfis de usuário, incluindo foto, biografia e configurações de privacidade. |
| FUN03   | O sistema deve permitir bloqueio e denúncia de perfis ou conteúdos impróprios, com moderação automatizada e manual. |
| FUN04   | O sistema deve permitir a configuração de filtros personalizados para conteúdos indesejados no feed do usuário.   |
| FUN05   | O sistema deve incluir uma funcionalidade de mensagens diretas (DMs) para comunicação privada entre usuários.     |
| FUN06   | O sistema deve disponibilizar relatórios de desempenho de postagens para contas profissionais, incluindo métricas de alcance e engajamento. |
| FUN07   | O sistema deve permitir a exclusão ou edição de postagens e comentários feitos pelo usuário.                     |

<font size="3"><p style="text-align: center">Fonte: [Carlos Eduardo](https://github.com/dudupaz) e [Samuel Ribeiro](https://github.com/SamuelRicosta). </p></font>
---

## U: Usabilidade (Usability)

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Usabilidade </p></font>

| **ID**  | **Descrição**                                                                                                   |
|---------|---------------------------------------------------------------------------------------------------------------|
| RU01    | O aplicativo deve possuir uma interface intuitiva que permita o aprendizado do uso em até 5 minutos para novos usuários. |
| RU02    | O sistema deve garantir que tarefas complexas possam ser realizadas com no máximo 5 interações.               |
| RU03    | O design da interface deve ser consistente em cores, tipografia e ícones, refletindo a identidade visual da Meta. |
| RU04    | O aplicativo deve suportar modos claro e escuro, permitindo ao usuário alternar entre eles conforme preferência. |

<font size="3"><p style="text-align: center">Fonte: [Carlos Eduardo](https://github.com/dudupaz) e [Samuel Ribeiro](https://github.com/SamuelRicosta). </p></font>
---

## R: Confiabilidade (Reliability)

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Confiabilidade </p></font>

| **ID**  | **Descrição**                                                                                                   |
|---------|---------------------------------------------------------------------------------------------------------------|
| RE01    | O aplicativo deve estar disponível 99,9% do tempo, com interrupções programadas limitadas a horários de menor uso. |
| RE02    | Deve ser possível recuperar dados críticos do usuário, como publicações e mensagens, em até 4 horas após uma falha no sistema. |
| RE03    | O sistema deve implementar backups regulares para garantir a recuperação de dados em caso de falhas.           |
| RE04    | Qualquer falha crítica deve ser detectada e comunicada à equipe de suporte em tempo real, com soluções implementadas em até 6 horas. |
| RE05    | O sistema deve fornecer opções claras para recuperação de conta, como redefinição de senha.                     |

<font size="3"><p style="text-align: center">Fonte: [Carlos Eduardo](https://github.com/dudupaz) e [Samuel Ribeiro](https://github.com/SamuelRicosta). </p></font>
---

## P: Desempenho (Performance)

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Desempenho </p></font>

| **ID**  | **Descrição**                                                                                                   |
|---------|---------------------------------------------------------------------------------------------------------------|
| PE01    | O tempo de carregamento do feed principal deve ser inferior a 2 segundos em redes 4G ou superiores.            |
| PE02    | O sistema deve realizar atualizações no feed sem exigir recarga manual da página.                              |
| PE03    | A publicação de textos ou imagens deve ser concluída em até 1 segundo após a ação do usuário.                  |
| PE04    | A abertura do perfil de um usuário deve ocorrer em menos de 500 ms após o clique.                              |
| PE05    | O envio de mensagens deve ter tempo de entrega inferior a 1 segundo em condições normais de rede.              |

<font size="3"><p style="text-align: center">Fonte: [Carlos Eduardo](https://github.com/dudupaz) e [Samuel Ribeiro](https://github.com/SamuelRicosta). </p></font>
---

## S: Suporte (Supportability)

<font size="3"><p style="text-align: center"><b>Tabela 5</b> - Suporte </p></font>

| **ID**  | **Descrição**                                                                                                   |
|---------|---------------------------------------------------------------------------------------------------------------|
| SU01    | O aplicativo deve ser compatível com dispositivos móveis rodando as versões mais recentes e as duas versões anteriores de iOS e Android. |
| SU02    | A interface deve ser responsiva e adaptável a diferentes tamanhos de tela, incluindo smartphones e tablets.    |
| SU03    | As atualizações devem ser lançadas regularmente para corrigir bugs, garantir compatibilidade e introduzir melhorias. |
| SU04    | Deve haver suporte multilíngue, incluindo inglês, espanhol e português, com a possibilidade de expansão para outros idiomas no futuro. |
| SU05    | O sistema deve ter uma documentação acessível e detalhada para usuários e desenvolvedores.                     |
| SU06    | A equipe de suporte deve estar disponível 24/7 para responder a questões críticas e garantir a solução de problemas em até 8 horas. |

<font size="3"><p style="text-align: center">Fonte: [Carlos Eduardo](https://github.com/dudupaz) e [Samuel Ribeiro](https://github.com/SamuelRicosta). </p></font>
---

## Conclusão

A Especificação Suplementar para o Threads reflete a importância dos requisitos não funcionais no desenvolvimento de um aplicativo confiável e eficiente. A abordagem sistemática com o modelo FURPS+ assegura que aspectos essenciais, como usabilidade, confiabilidade, desempenho e suporte, sejam considerados e implementados para atender às expectativas dos usuários.

---

## Referências

- ASSOCIAÇÃO Brasileira de Normas Técnicas. **NBR 6023: Informação e documentação - Referências - Elaboração.** Rio de Janeiro, 2018.
- BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. **Interação humano-computador.** Elsevier, 2010.
- SERRANO, Milene. **Requisitos – Aula 10.** Disponível em: [https://aprender3.unb.br](https://aprender3.unb.br). Acesso em: 24 nov. 2023.

---

## Histórico de Versões

| Versão | Data       | Descrição            | Autor                                        | Revisor                                            |
| :----: | ---------- | -------------------- | -------------------------------------------- | -------------------------------------------------- |
|  1.0   | 05/12/2024 | Criação do documento e inserção de parte da Especificação Suplementar | [Carlos Eduardo](https://github.com/dudupaz) | [Genilson Silva](https://github.com/GenilsonJrs) |
|  1.1   | 06/12/2024 | Arrumando estrutura do documento | [Samuel Ribeiro](https://github.com/SamuelRicosta)  | [Alana Gabriele](https://github.com/alanagabriele) |

