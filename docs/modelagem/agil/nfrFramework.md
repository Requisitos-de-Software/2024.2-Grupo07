# NFR Framework

## Introdução

O Framework de Requisitos Não Funcionais (NFR) é um método estruturado para lidar com requisitos não funcionais no desenvolvimento de software. Foi criado com o objetivo de auxiliar engenheiros e analistas de sistemas na identificação, representação, análise e monitoramento da satisfação de requisitos não funcionais (como desempenho, segurança, confiabilidade, manutenibilidade, entre outros) ao longo da vida útil do software.

Neste documento, o **Threads**, um aplicativo selecionado para estudo, será utilizado como base para análise e aplicação do framework.

---

## Metodologia

Para que este documento pudesse ser produzido, foram utilizados os requisitos não funcionais presentes no projeto e elicitados no artefato de requisitos, que trata dos requisitos identificados em relação ao aplicativo **Threads**.

O framework leva em consideração o conceito de _softgoal_, que se refere a um objeto desprovido de definição clara e critérios de satisfação sólidos. Esses _softgoals_ são utilizados para representar requisitos não funcionais e podem estar conectados entre si, refletindo as influências que exercem no sistema.

---

### Tipos de Softgoals

Os softgoals desempenham um papel essencial na modelagem e no atendimento dos requisitos não funcionais (NFR). Eles são classificados em diferentes tipos conforme apresentado na **Tabela 1**, que detalha suas características e finalidades. A **Figura 1** ilustra visualmente esses tipos, permitindo uma melhor compreensão de suas representações e relações no contexto do desenvolvimento do sistema.

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Tipos de Softgoals</p></font>

| Tipo de Softgoal                   | Descrição                                                                                                                                                                                                                                                                                                          |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Softgoals NFR**                  | Representam os requisitos não funcionais e podem ser organizados hierarquicamente no desenvolvimento do projeto.                                                                                                                                                                                                   |
| **Softgoals de Operacionalização** | Representam as soluções de implementação para atender aos _softgoals_ NFR ou outros _softgoals_ de operacionalização. Incluem operações, processos, estruturas de dados e restrições no sistema para cumprir as necessidades indicadas.                                                                            |
| **Softgoals de Afirmação (CLAIM)** | Consideram as características do domínio, como prioridades e carga de trabalho, no processo de tomada de decisão. Servem como justificativa para apoiar ou negar a priorização e seleção de componentes, facilitando a revisão, justificativa, melhoria do sistema e rastreamento das decisões de desenvolvimento. |

<font size=""><p style="text-align: center"> **Figura 1:** Tipos de Softgoals

</p></font>

<center>
![Softgoals](../imagens/softgoals.png)
</center>

<font size="3"><p style="text-align: center"> Autor: Silva, Reinaldo Antônio.

</p></font>

---

### Avaliação de Softgoals

A avaliação de _softgoals_ envolve a análise do nível de satisfação dos requisitos não funcionais, considerando um conjunto de decisões baseadas nas interações entre os requisitos e suas implicações. Esse processo permite identificar como os _softgoals_ contribuem para a realização dos objetivos do sistema, bem como compreender possíveis conflitos e incertezas.

A seguir, são apresentados os tipos de avaliação dos _softgoals_ e suas respectivas categorizações:

- **✓ Satisfeito**: Indica que o requisito não funcional foi plenamente atendido.
- **𝒲+ Parcialmente satisfeito**: Representa uma satisfação parcial, onde o requisito foi atendido, mas com algumas limitações.
- **X Não atendido**: Indica que o requisito não funcional não foi realizado.
- **𝒲- Parcialmente não atendido**: Refere-se a uma realização negativa parcial, onde o requisito apresenta falhas, mas não completamente.
- **C Conflitante**: Aponta para uma relação de conflito entre os requisitos, onde existem elementos positivos e negativos simultaneamente.
- **u Indeterminado**: Representa um estado desconhecido ou incerto, onde não há informações suficientes para determinar o nível de atendimento do requisito.

Para uma visualização prática dos símbolos e suas categorizações, consulte a **Figura 2**.

<font size="2"><p style="text-align: center"> **Figura 2:** Rótulos de propagação de impacto

</p></font>

![Rotulos](../imagens/rotulos.png)

<p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro</a></p>

### Tipos de Contribuições e Decomposições

A análise de contribuições e decomposições desempenha um papel crucial na compreensão do impacto dos elementos sobre os softgoals. A **Tabela 2** apresenta os diferentes tipos de contribuições (positivas e negativas) e suas intensidades, além de destacar os mecanismos de decomposição AND e OR, que indicam as condições necessárias para a satisfação de um softgoal.

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Tipos de Contribuições e Decomposições</p></font>

| Tipo de Contribuição            | Descrição                                                                                           |
| ------------------------------- | --------------------------------------------------------------------------------------------------- |
| **Contribuições Positivas (+)** | Indicadores de que uma decisão ou elemento contribui para a satisfação de um _softgoal_.            |
| **++ (Forte Positiva)**         | Uma contribuição muito significativa e positiva.                                                    |
| **+ (Fraca Positiva)**          | Uma contribuição positiva moderada.                                                                 |
| **Contribuições Negativas (-)** | Indicadores de que uma decisão ou elemento dificulta a satisfação de um _softgoal_.                 |
| **-- (Forte Negativa)**         | Um impacto muito significativo e prejudicial.                                                       |
| **- (Fraca Negativa)**          | Um impacto negativo moderado.                                                                       |
| **Decomposição AND**            | Todos os sub-_softgoals_ precisam ser atendidos para que o _softgoal_ pai seja satisfeito.          |
| **Decomposição OR**             | Apenas um ou mais sub-_softgoals_ precisam ser atendidos para que o _softgoal_ pai seja satisfeito. |

<p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro</a></p>

### Tabela de Requisitos Não Funcionais

A Tabela 3 a seguir lista os Requisitos Não-Funcionais utilizados para a criação do NFR Framework.

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Requisitos Não Funcionais</p></font>

| **ID** | **Descrição**                                                                                                               | **Rastreabilidade**                                                                                                   |
| ------ | --------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| RNF01  | O sistema deve reduzir anúncios intrusivos e ajustar algoritmos para maior transparência.                                   | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF41</a> |
| RNF02  | O sistema deve melhorar o algoritmo para priorizar conteúdos relevantes ao usuário.                                         | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF42</a> |
| RNF03  | O sistema deve evitar a sobrecarga de notificações irrelevantes.                                                            | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF43</a> |
| RNF04  | O sistema deve implementar moderação para reduzir bots e publicações irrelevantes.                                          | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF44</a> |
| RNF05  | O sistema deve oferecer autenticação avançada para segurança do usuário.                                                    | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF45</a> |
| RNF06  | O sistema deve garantir tempos de resposta inferiores a 1 segundo para interações usuais.                                   | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF46</a> |
| RNF07  | O aplicativo deve minimizar o consumo de bateria em dispositivos móveis, garantindo uma taxa de consumo inferior a 5%.      | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF47</a> |
| RNF08  | O sistema deve ser compatível com dispositivos móveis de versões Android 8.0 e iOS 12 ou superiores.                        | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF48</a> |
| RNF09  | O sistema deve ser compatível com versões de navegador mais antigas, garantindo funcionalidade em Chrome 70+ e Firefox 70+. | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF49</a> |
| RNF10  | O sistema deve garantir alta disponibilidade, com menos de 1% de tempo de inatividade mensal.                               | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF50</a> |
| RNF11  | O sistema deve criptografar todos os dados de login e autenticação para garantir a segurança das informações.               | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF51</a> |
| RNF12  | O sistema deve ser otimizado para uso em dispositivos com pouca memória RAM.                                                | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF52</a> |
| RNF13  | O sistema deve ser compatível com os navegadores mais recentes, como Google Chrome, Safari e Edge.                          | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF53</a> |
| RNF14  | O sistema deve garantir que o feed de publicações seja carregado rapidamente, mesmo com grande volume de conteúdo.          | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF54</a> |
| RNF15  | O sistema deve garantir que os dados do usuário sejam armazenados de forma segura, com backup regular.                      | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF55</a> |
| RNF16  | O sistema deve garantir que o conteúdo do usuário seja sempre acessível, com um tempo de recuperação abaixo de 10 segundos. | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF56</a> |
| RNF17  | O sistema deve permitir que o usuário configure o status online ou offline.                                                 | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF57</a> |
| RNF18  | O sistema deve permitir a criação de listas de amigos próximos.                                                             | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF58</a> |
| RNF19  | O sistema deve permitir respostas anônimas em discussões públicas moderadas.                                                | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF59</a> |
| RNF20  | O sistema deve permitir salvar rascunhos de postagens mesmo sem conexão.                                                    | <a href="https://requisitos-de-software.github.io/2024.2-Threads/Elicitacao/tecnicas/requisitoselicitados/">RNF60</a> |

<p style="text-align: center; font-size: 14px;">
    Autores: <a href="https://github.com/GenilsonJrs" target="_blank">Genilson Silva</a> e <a href="https://github.com/SamuelRicosta" target="_blank"> Samuel Ribeiro. </a>
</p>

## NFR Framework - NFR01: Compatibilidade e Performance

### Descrição

Este SIG (Sistemas de Informação Gráfica) agrupa requisitos não funcionais relacionados à compatibilidade e performance do sistema Threads. Esses requisitos são cruciais para garantir que o sistema seja acessível e eficiente em diferentes ambientes de uso, desde dispositivos móveis até navegadores web antigos e modernos.

### Requisitos

Os Requisitos utilizados para a confecção da Figura 3 estão presentes na Tabela 3:

- **RQ08**: O sistema deve ser compatível com dispositivos móveis de versões Android 8.0 e iOS 12 ou superiores

- **RQ12**: O sistema deve ser otimizado para uso em dispositivos com pouca memória RAM.

- **RQ09**: O sistema deve ser compatível com versões de navegador mais antigas, garantindo funcionalidade em Chrome 70+ e Firefox 70+.

- **RQ13**: O sistema deve ser compatível com os navegadores mais recentes, como Google Chrome, Safari e Edge.

Com isso, segue a Figura 3 com o NFR relativo a Compatibilidade e Performance:

<font size=""><p style="text-align: center"> **Figura 3:** SIG Compatibilidade e Performance

</p></font>

<center>
<div style="width: 640px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/b9bec417-0b78-4b69-87f3-f4908a34d43b" id="XLfBowYI2Faa"></iframe></div>
</center>

<p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro</a></p>

### Propagacao dos Impactos

A seguir, na Tabela 4, temos a avaliação da propagação dos impactos relativa à Figura 3.

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - tabela de Impactos </p></font>

| **NFR**                       | **Impacto** | **Avaliador**                                      |
| ----------------------------- | ----------- | -------------------------------------------------- |
| Compatibilidade e Performance | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Compatibilidade               | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Dispositivos Moveis           | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Android 8.0+                  | **𝒲+**      | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| iOS 12+                       | **𝒲+**      | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Navegadores Antigos           | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Chrome 70+                    | **𝒲+**      | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Firefox 70+                   | **𝒲+**      | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Navegadores Modernos          | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Chrome                        | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Safari                        | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Edge                          | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Performance                   | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Otimizacao                    | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
| Pouca Memoria RAM             | **X**       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |

<p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro</a></p>

## NFR Framework - NFR02: Desempenho

Este SIG (Sistemas de Informação Gráfica) agrupa requisitos não funcionais relacionados ao desempenho do sistema Threads. Esses requisitos são essenciais para assegurar que o sistema ofereça uma performance consistente, com tempos de resposta rápidos e utilização eficiente dos recursos, independentemente do volume de dados ou da carga de usuários simultâneos. A prioridade é garantir uma experiência fluida e ágil, desde a interação com o feed de postagens até o carregamento de páginas e o processamento de dados em dispositivos diversos.

## Requisitos

Os Requisitos utilizados para a confecção da Figura 3 estão presentes na Tabela 3:

- **RQ06**: O sistema deve garantir tempos de resposta inferiores a 1 segundo para interações usuais.

- **RQ07**: O aplicativo deve minimizar o consumo de bateria em dispositivos móveis, garantindo uma taxa de consumo inferior a 5%.

- **RQ12**: O sistema deve ser otimizado para uso em dispositivos com pouca memória RAM.

- **RQ16**: O sistema deve garantir que o conteúdo do usuário seja sempre acessível, com um tempo de recuperação abaixo de 10 segundos.

Com isso, segue a Figura 3 com o NFR relativo a Compatibilidade e Performance:

<font size="3"><p style="text-align: center"><b>Figura 4 </b> - SIG Desempenho</p></font>

<center>
<div style="width: 640px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/bfed40cc-9870-4549-a871-54e519cdcec8" id="4RfB5gTnTy_A"></iframe></div>
</center>

<font size="3"><p style="text-align: center"> Autor: [Carlos Eduardo](https://github.com/dudupaz)</p></font>

### Propagacao dos Impactos

A seguir, na Tabela 5, temos a avaliação da propagação dos impactos relativa à Figura 4.

<center>

<b>Tabela 5</b> - Impactos Desempenho

| NFR                                         | Impacto | Avaliador                                    |
| ------------------------------------------- | ------- | -------------------------------------------- |
| Desempenho                                  | 𝒲+      | [Carlos Eduardo](https://github.com/dudupaz) |
| Tempo de resposta                           | 𝒲+      | [Carlos Eduardo](https://github.com/dudupaz) |
| Utilização de recursos                      | 𝒲-      | [Carlos Eduardo](https://github.com/dudupaz) |
| Pouca utilização de recursos                | ✓       | [Carlos Eduardo](https://github.com/dudupaz) |
| Feed                                        | 𝒲+      | [Carlos Eduardo](https://github.com/dudupaz) |
| Login                                       | 𝒲+      | [Carlos Eduardo](https://github.com/dudupaz) |
| Carregamento de postagens inferior a 500ms  | ✓       | [Carlos Eduardo](https://github.com/dudupaz) |
| Tempo inferior a 500ms em interações usuais | 𝒲+      | [Carlos Eduardo](https://github.com/dudupaz) |
| Realizar login em menos de 2 segundos       | 𝒲+      | [Carlos Eduardo](https://github.com/dudupaz) |
| Usar pouco a CPU                            | 𝒲-      | [Carlos Eduardo](https://github.com/dudupaz) |
| Minimizar o consumo da bateria              | 𝒲+      | [Carlos Eduardo](https://github.com/dudupaz) |

Autor: [Carlos Eduardo](https://github.com/dudupaz)

</center>

## NFR Framework - NFR03: Personalização e Usabilidade

### Descrição

Este SIG (Sistemas de Informação Gráfica) agrupa requisitos não funcionais relacionados à personalização e usabilidade do sistema Threads. Esses requisitos são fundamentais para garantir que o sistema seja flexível, permitindo ao usuário adaptar a plataforma conforme suas preferências, além de melhorar a experiência do usuário, tornando-a mais prática e intuitiva.

### Requisitos

- **RQ17**: O sistema deve permitir que o usuário configure o status online ou offline. (Personalização)
- **RQ18**: O sistema deve permitir a criação de listas de amigos próximos. (Personalização)
- **RQ19**: O sistema deve permitir respostas anônimas em discussões públicas moderadas. (Usabilidade)
- **RQ20**: O sistema deve permitir salvar rascunhos de postagens mesmo sem conexão. (Usabilidade)

Com isso, segue a Figura 5 com o NFR relativo a Personalização e Usabilidade:

<font size=""><p style="text-align: center"> **Figura 5:** Rótulos de propagação de impacto

</p></font>

<center>
<div style="width: 640px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/a118647a-b113-492b-abe2-521b36aeb931" id="rUfB_U8JtMFv"></iframe></div></center>

<p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs" target="_blank">Genilson Silva</a></p>

### Propagacao dos Impactos

A seguir, na Tabela 4, temos a avaliação da propagação dos impactos relativa à Figura 3.

<font size="3"><p style="text-align: center"><b>Tabela 6</b> - Tabela de Impactos </p></font>

| **NFR**                      | **Impacto** | **Avaliador**                                    |
| ---------------------------- | ----------- | ------------------------------------------------ |
| **Usabilidade**              | **✓**       | [Genilson Silva](https://github.com/GenilsonJrs) |
| **Personalização**           | **✓**       | [Genilson Silva](https://github.com/GenilsonJrs) |
| **Respostas Anônimas**       | **𝒲+**      | [Genilson Silva](https://github.com/GenilsonJrs) |
| **Salvar Rascunhos**         | **✓**       | [Genilson Silva](https://github.com/GenilsonJrs) |
| **Configurar Status Online** | **✓**       | [Genilson Silva](https://github.com/GenilsonJrs) |
| **Criar Lista de Amigos**    | **𝒲+**      | [Genilson Silva](https://github.com/GenilsonJrs) |

<p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs" target="_blank">Genilson Silva</a></p>

## Referências

> **CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J.** Non-Functional Requirements in Software Engineering. Springer Science & Business Media, 2000.

> **SILVA, Reinaldo Antônio da**. UFPE Repositório. Disponível em: [https://repositorio.ufpe.br/handle/123456789/34150](https://repositorio.ufpe.br/handle/123456789/34150). Acesso em: 22 jun. 2024.

## Histórico de Versões

| Versão | Data       | Descrição                                             | Autor                                              | Revisor                                            |
| :----: | ---------- | ----------------------------------------------------- | -------------------------------------------------- | -------------------------------------------------- |
|  1.0   | 16/12/2024 | Criação do documento                                  | [Samuel Ribeiro](https://github.com/SamuelRicosta) | [Alana Gabriele](https://github.com/alanagabriele) |
|  1.1   | 17/12/2024 | implementação do NFR01                                | [Samuel Ribeiro](https://github.com/SamuelRicosta) | [Alana Gabriele](https://github.com/alanagabriele) |
|  1.2   | 17/12/2024 | implementação do NFR02 - Desempenho                   | [Carlos Eduardo](https://github.com/dudupaz)       | [Alana Gabriele](https://github.com/alanagabriele) |
|  1.3   | 17/12/2024 | implementação do NFR03 - Usabilidade e Personalização | [Genilson Silva](https://github.com/GenilsonJrs)   | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
|  1.4   | 17/12/2024 | Incorporando o lucidchart                             | [Alana Gabriele](https://github.com/alanagabriele) | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
