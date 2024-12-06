# Especificação Suplementar

## Introdução

A Especificação Suplementar é um documento que detalha os requisitos não contemplados diretamente nos casos de uso. Este documento complementa a descrição funcional do sistema, esses requisitos, embora não estejam diretamente relacionados à funcionalidade específica do software, abrangem aspectos como desempenho, usabilidade, confiabilidade, suporte e outros, garantindo a qualidade e a satisfação dos usuários. capturando requisitos como normas legais, atributos de qualidade, desempenho, compatibilidade, entre outros. 

A rede social Threads, foi escolhida como objeto de estudo para explorar esses aspectos. Para organizar e documentar os requisitos suplementares, utilizaremos a metodologia FURPS+, adaptada às especificidades do sistema.

## Metodologia

A metodologia utilizada para a elaboração deste documento é baseada no modelo FURPS+, que é amplamente reconhecido como uma técnica eficaz para a identificação e organização de requisitos não funcionais. O acrônimo FURPS+ representa as categorias **Funcionalidade**, **Usabilidade**, **Confiabilidade**, **Desempenho** e **Suporte**, além de requisitos adicionais como restrições de design e documentação.

Este documento foi estruturado com base nas categorias do modelo FURPS+. Cada seção detalha os requisitos não funcionais relacionados à respectiva categoria, tendo como base os requisitos elicitados previamente para o aplicativo Threads.

---

# FURPS+

## F: Funcionalidade (Functionality)

| ID    | Descrição                                                                                                           |
|-------|-------------------------------------------------------------------------------------------------------------------|
| FUN01 | O sistema deve incluir funcionalidades de busca por hashtags e conteúdos relevantes.                    |
| FUN02 | O sistema deve permitir a criação e personalização de perfis de usuário, incluindo foto, biografia e configurações de privacidade. |
| FUN03 | O sistema deve permitir bloqueio e denúncia de perfis ou conteúdos impróprios, com moderação automatizada e manual. |
| FUN04 | O sistema deve permitir a configuração de filtros personalizados para conteúdos indesejados no feed do usuário.    |
| FUN05 | O sistema deve incluir uma funcionalidade de mensagens diretas (DMs) para comunicação privada entre usuários.      |
| FUN06 | O sistema deve disponibilizar relatórios de desempenho de postagens para contas profissionais, incluindo métricas de alcance e engajamento. |
| FUN07 | O sistema deve permitir a exclusão ou edição de postagens e comentários feitos pelo usuário.                      |


---

## U: Usabilidade (Usability)
A usabilidade de um sistema, segundo Nielsen, é a capacidade de permitir que os usuários realizem suas tarefas de forma eficiente, eficaz e satisfatória. Para o Threads, os seguintes requisitos não funcionais de usabilidade foram identificados:

| ID   | Descrição                                                                                  |
|------|--------------------------------------------------------------------------------------------|
| RU01 | O aplicativo deve possuir uma interface intuitiva que permita o aprendizado do uso em até 5 minutos para novos usuários. |
| RU02 | O sistema deve garantir que tarefas complexas possam ser realizadas com no máximo 5 interações. |
| RU03 | O design da interface deve ser consistente em cores, tipografia e ícones, refletindo a identidade visual da Meta. |
| RU04 | O aplicativo deve suportar modos claro e escuro, permitindo ao usuário alternar entre eles conforme preferência. |


---

## R: Confiabilidade (Reliability)
A confiabilidade do Threads assegura uma experiência estável e consistente para seus usuários. Os seguintes requisitos foram identificados:

| ID   | Descrição                                                                                  |
|------|--------------------------------------------------------------------------------------------|
| RE01 | O aplicativo deve estar disponível 99,9% do tempo, com interrupções programadas limitadas a horários de menor uso. |
| RE02 | Deve ser possível recuperar dados críticos do usuário, como publicações e mensagens, em até 4 horas após uma falha no sistema. |
| RE03 | O sistema deve implementar backups regulares para garantir a recuperação de dados em caso de falhas. |
| RE04 | Qualquer falha crítica deve ser detectada e comunicada à equipe de suporte em tempo real, com soluções implementadas em até 6 horas. |
| RE05 | O sistema deve fornecer opções claras para recuperação de conta, como redefinição de senha. |

---

## P: Desempenho (Performance)
O desempenho do Threads deve garantir rapidez e eficiência nas interações, como segue:

| ID   | Descrição                                                                                  |
|------|--------------------------------------------------------------------------------------------|
| PE01 | O tempo de carregamento do feed principal deve ser inferior a 2 segundos em redes 4G ou superiores. |
| PE02 | O sistema deve realizar atualizações no feed sem exigir recarga manual da página. |
| PE03 | A publicação de textos ou imagens deve ser concluída em até 1 segundo após a ação do usuário. |
| PE04 | A abertura do perfil de um usuário deve ocorrer em menos de 500 ms após o clique. |
| PE05 | O envio de mensagens deve ter tempo de entrega inferior a 1 segundo em condições normais de rede. |

---

## S: Suporte (Supportability)
O suporte ao Threads abrange aspectos de manutenção, adaptabilidade e portabilidade, como descrito abaixo:

| ID   | Descrição                                                                                  |
|------|--------------------------------------------------------------------------------------------|
| SU01 | O aplicativo deve ser compatível com dispositivos móveis rodando as versões mais recentes e as duas versões anteriores de iOS e Android. |
| SU02 | A interface deve ser responsiva e adaptável a diferentes tamanhos de tela, incluindo smartphones e tablets. |
| SU03 | As atualizações devem ser lançadas regularmente para corrigir bugs, garantir compatibilidade e introduzir melhorias. |
| SU04 | Deve haver suporte multilíngue, incluindo inglês, espanhol e português, com a possibilidade de expansão para outros idiomas no futuro. |
| SU05 | O sistema deve ter uma documentação acessível e detalhada para usuários e desenvolvedores. |
| SU06 | A equipe de suporte deve estar disponível 24/7 para responder a questões críticas e garantir a solução de problemas em até 8 horas. |

---

A Especificação Suplementar para o Threads reflete a importância dos requisitos não funcionais no desenvolvimento de um aplicativo confiável e eficiente. A abordagem sistemática com o modelo FURPS+ assegura que aspectos essenciais, como usabilidade, confiabilidade, desempenho e suporte, sejam considerados e implementados para atender às expectativas dos usuários.

---

## Histórico de Versões

| Versão | Data       | Descrição            | Autor                                        | Revisor                                            |
| :----: | ---------- | -------------------- | -------------------------------------------- | -------------------------------------------------- |
|  1.0   | 05/12/2024 | Criação do documento e inserção de parte da Especificação Suplementar | [Carlos Eduardo](https://github.com/dudupaz) | [Genilson Silva](https://github.com/GenilsonJrs) |

