# NFR Framework

## Introdução
O Framework de Requisitos Não Funcionais (NFR) é um método estruturado para lidar com requisitos não funcionais no desenvolvimento de software. Foi criado com o objetivo de auxiliar engenheiros e analistas de sistemas na identificação, representação, análise e monitoramento da satisfação de requisitos não funcionais (como desempenho, segurança, confiabilidade, manutenibilidade, entre outros) ao longo da vida útil do software.

Neste documento, o **Threads**, um aplicativo selecionado para estudo, será utilizado como base para análise e aplicação do framework.

---

## Metodologia

Para que este documento pudesse ser produzido, foram utilizados os requisitos não funcionais presentes no projeto e elicitados no artefato de requisitos, que trata dos requisitos identificados em relação ao aplicativo **Threads**.

O framework leva em consideração o conceito de *softgoal*, que se refere a um objeto desprovido de definição clara e critérios de satisfação sólidos. Esses *softgoals* são utilizados para representar requisitos não funcionais e podem estar conectados entre si, refletindo as influências que exercem no sistema.

---

### Tipos de Softgoals

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Tipos de Softgoals</p></font>

| Tipo de Softgoal               | Descrição                                                                                                                                          |
|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Softgoals NFR**              | Representam os requisitos não funcionais e podem ser organizados hierarquicamente no desenvolvimento do projeto.                                   |
| **Softgoals de Operacionalização** | Representam as soluções de implementação para atender aos *softgoals* NFR ou outros *softgoals* de operacionalização. Incluem operações, processos, estruturas de dados e restrições no sistema para cumprir as necessidades indicadas. |
| **Softgoals de Afirmação (CLAIM)** | Consideram as características do domínio, como prioridades e carga de trabalho, no processo de tomada de decisão. Servem como justificativa para apoiar ou negar a priorização e seleção de componentes, facilitando a revisão, justificativa, melhoria do sistema e rastreamento das decisões de desenvolvimento. |

<p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro</a></p>

**Figura 1:** Tipos de Softgoals  

![](imagens/softgoals.png)

Autor: Silva, Reinaldo Antônio.

---

Após determinar o tipo de *softgoal*, deve-se realizar uma avaliação. Esse processo determina o quanto os requisitos não funcionais são satisfatórios por meio de um conjunto de decisões. Para tal, atribuímos os rótulos de:  
- "Satisfeito",  
- "Parcialmente satisfeito",  
- "Não atendido",  
- "Parcialmente não atendido",  
- "Conflitante",  
- "Indeterminado".

**Figura 2:** Rótulos de propagação de impacto  

![](imagens/rotulos.png)


Autor: Silva, Reinaldo Antônio.

---

### Tipos de Contribuições e Decomposições

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Tipos de Contribuições e Decomposições</p></font>

| Tipo de Contribuição    | Descrição                                                                                  |
|-------------------------|------------------------------------------------------------------------------------------|
| **Contribuições Positivas (+)** | Indicadores de que uma decisão ou elemento contribui para a satisfação de um *softgoal*.                        |
| **++ (Forte Positiva)** | Uma contribuição muito significativa e positiva.                                        |
| **+ (Fraca Positiva)**  | Uma contribuição positiva moderada.                                                     |
| **Contribuições Negativas (-)** | Indicadores de que uma decisão ou elemento dificulta a satisfação de um *softgoal*.                            |
| **-- (Forte Negativa)** | Um impacto muito significativo e prejudicial.                                           |
| **- (Fraca Negativa)**  | Um impacto negativo moderado.                                                           |
| **Decomposição AND**    | Todos os sub-*softgoals* precisam ser atendidos para que o *softgoal* pai seja satisfeito. |
| **Decomposição OR**     | Apenas um ou mais sub-*softgoals* precisam ser atendidos para que o *softgoal* pai seja satisfeito. |

<p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro</a></p>

---
### Tabela de Requisitos Não Funcionais

| **ID**   | **Descrição**                                                                                   | **Rastreabilidade**                |
|----------|-------------------------------------------------------------------------------------------------|----------------------------------- |
| RNF01    | O sistema deve ser compatível com dispositivos móveis de versões Android 8.0 e iOS 12 ou superiores. |                               |
| RNF02    | O sistema deve garantir que os dados do usuário sejam armazenados de forma segura, com backup regular. |                             |
| RNF03    | O sistema deve permitir que o usuário altere suas preferências de notificações para personalizar a experiência. |                    |
| RNF04    | O sistema deve garantir que o feed de publicações seja carregado rapidamente, mesmo com grande volume de conteúdo. |                 |


<p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro</a></p>

---



---

## Referências
**CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J.** Non-Functional Requirements in Software Engineering. Springer Science & Business Media, 2000.

**SILVA, Reinaldo Antônio da**. UFPE Repositório. Disponível em: [https://repositorio.ufpe.br/handle/123456789/34150](https://repositorio.ufpe.br/handle/123456789/34150). Acesso em: 22 jun. 2024.


## Histórico de Versões

| Versão | Data       | Descrição           | Autor                                              | Revisor                                      |
| :----: | ---------- | ------------------- | -------------------------------------------------- | -------------------------------------------- |
|  1.0   | 16/12/2024 | Criação do documento | [Samuel Ribeiro](https://github.com/SamuelRicosta) | [Alana Gabriele](https://github.com/alanagabriele) |
