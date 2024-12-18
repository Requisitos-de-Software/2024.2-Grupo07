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

Os softgoals desempenham um papel essencial na modelagem e no atendimento dos requisitos não funcionais (NFR). Eles são classificados em diferentes tipos conforme apresentado na **Tabela 1**, que detalha suas características e finalidades. A **Figura 1** ilustra visualmente esses tipos, permitindo uma melhor compreensão de suas representações e relações no contexto do desenvolvimento do sistema.

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Tipos de Softgoals</p></font>

| Tipo de Softgoal               | Descrição                                                                                                                                          |
|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Softgoals NFR**              | Representam os requisitos não funcionais e podem ser organizados hierarquicamente no desenvolvimento do projeto.                                   |
| **Softgoals de Operacionalização** | Representam as soluções de implementação para atender aos *softgoals* NFR ou outros *softgoals* de operacionalização. Incluem operações, processos, estruturas de dados e restrições no sistema para cumprir as necessidades indicadas. |
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

A avaliação de *softgoals* envolve a análise do nível de satisfação dos requisitos não funcionais, considerando um conjunto de decisões baseadas nas interações entre os requisitos e suas implicações. Esse processo permite identificar como os *softgoals* contribuem para a realização dos objetivos do sistema, bem como compreender possíveis conflitos e incertezas.  

A seguir, são apresentados os tipos de avaliação dos *softgoals* e suas respectivas categorizações:  

- **✓ Satisfeito**: Indica que o requisito não funcional foi plenamente atendido.  
- **𝒲+ Parcialmente satisfeito**: Representa uma satisfação parcial, onde o requisito foi atendido, mas com algumas limitações.  
- **X Não atendido**: Indica que o requisito não funcional não foi realizado.  
- **𝒲- Parcialmente não atendido**: Refere-se a uma realização negativa parcial, onde o requisito apresenta falhas, mas não completamente.  
- **C Conflitante**: Aponta para uma relação de conflito entre os requisitos, onde existem elementos positivos e negativos simultaneamente.  
- **u Indeterminado**: Representa um estado desconhecido ou incerto, onde não há informações suficientes para determinar o nível de atendimento do requisito.  

Para uma visualização prática dos símbolos e suas categorizações, consulte a **Figura 2**. 

<font size=""><p style="text-align: center"> **Figura 2:** Rótulos de propagação de impacto
</p></font>

![Rotulos](../imagens/rotulos.png)

<p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro</a></p>
---

### Tipos de Contribuições e Decomposições

A análise de contribuições e decomposições desempenha um papel crucial na compreensão do impacto dos elementos sobre os softgoals. A **Tabela 2** apresenta os diferentes tipos de contribuições (positivas e negativas) e suas intensidades, além de destacar os mecanismos de decomposição AND e OR, que indicam as condições necessárias para a satisfação de um softgoal.

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

A Tabela 3 a seguir lista os Requisitos Não-Funcionais utilizados para a criação do NFR Framework.

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Requisitos Não Funcionais</p></font>

| **ID**   | **Descrição**                                                                                   | **Rastreabilidade**                |
|----------|-------------------------------------------------------------------------------------------------|-----------------------------------|
| RNF01    | O sistema deve ser compatível com dispositivos móveis de versões Android 8.0 e iOS 12 ou superiores. |                                   |
| RNF02    | O sistema deve garantir que os dados do usuário sejam armazenados de forma segura, com backup regular. |                                 |
| RNF03    | O sistema deve permitir que o usuário altere suas preferências de notificações para personalizar a experiência. |                                  |
| RNF04    | O sistema deve garantir que o feed de publicações seja carregado rapidamente, mesmo com grande volume de conteúdo. |                             |
| RNF05    | O sistema deve ser otimizado para uso em dispositivos com pouca memória RAM.                      |                                   |
| RNF06    | O sistema deve garantir alta disponibilidade, com menos de 1% de tempo de inatividade mensal.       |                                   |
| RNF07    | O sistema deve permitir que o usuário defina um tema escuro ou claro no aplicativo.                |                                   |
| RNF08    | O sistema deve garantir que o conteúdo do usuário seja sempre acessível, com um tempo de recuperação abaixo de 10 segundos. |                                  |
| RNF09    | O sistema deve ser compatível com versões de navegador mais antigas, garantindo funcionalidade em Chrome 70+ e Firefox 70+. |                                   |
| RNF10    | O sistema deve garantir que os dados do usuário sejam armazenados de forma segura, com backup regular. | |
| RNF11    | O sistema deve permitir que o usuário defina preferências de anúncios, como limitar tipos de anúncios exibidos. | |
| RNF12    | O sistema deve permitir que o usuário personalize a exibição de postagens no feed (por exemplo, mostrando mais fotos). | |
| RNF13    | O sistema deve ser compatível com os navegadores mais recentes, como Google Chrome, Safari e Edge. | |



<p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro</a></p>

---
## NFR Framework - NFR01: Compatibilidade e Performance

### Descrição

Este SIG (Sistemas de Informação Gráfica) agrupa requisitos não funcionais relacionados à compatibilidade e performance do sistema Threads. Esses requisitos são cruciais para garantir que o sistema seja acessível e eficiente em diferentes ambientes de uso, desde dispositivos móveis até navegadores web antigos e modernos.



### Requisitos

Os Requisitos utilizados para a confecção da Figura 3 estão presentes na Tabela 3:

- **RQ01**: O sistema deve ser compatível com dispositivos móveis de versões Android 8.0 e iOS 12 ou superiores

- **RQ05**: O sistema deve ser otimizado para uso em dispositivos com pouca memória RAM.

- **RQ09**: O sistema deve ser compatível com versões de navegador mais antigas, garantindo funcionalidade em Chrome 70+ e Firefox 70+.

- **RQ13**: O sistema deve ser compatível com os navegadores mais recentes, como Google Chrome, Safari e Edge.

Com isso, segue a Figura 3 com o NFR relativo a Compatibilidade e Performance:

<font size=""><p style="text-align: center"> **Figura 3:** SIG Compatibilidade e Performance
</p></font>

![Sig](../imagens/SIG.png)

### Propagacao dos Impactos

A seguir, na Tabela 4, temos a avaliação da propagação dos impactos relativa à Figura 3.

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - tabela de Impactos </p></font>

| **NFR**                       | **Impacto** | **Avaliador**       |
|-------------------------------|-------------|--------------------|
| Compatibilidade e Performance | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Compatibilidade               | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Dispositivos Moveis           | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Android 8.0+                  | **𝒲+**      | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| iOS 12+                       | **𝒲+**      | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Navegadores Antigos           | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Chrome 70+                    | **𝒲+**      | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Firefox 70+                   | **𝒲+**      | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Navegadores Modernos          | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Chrome                        | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Safari                        | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Edge                          | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Performance                   | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Otimizacao                    | **✓**       | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |
| Pouca Memoria RAM             | **X**       | [Samuel Ribeiro](https://github.com/SamuelRicosta)           |


<p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro</a></p>


---

## Referências
**CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J.** Non-Functional Requirements in Software Engineering. Springer Science & Business Media, 2000.

**SILVA, Reinaldo Antônio da**. UFPE Repositório. Disponível em: [https://repositorio.ufpe.br/handle/123456789/34150](https://repositorio.ufpe.br/handle/123456789/34150). Acesso em: 22 jun. 2024.


## Histórico de Versões

| Versão | Data       | Descrição           | Autor                                              | Revisor                                      |
| :----: | ---------- | ------------------- | -------------------------------------------------- | -------------------------------------------- |
|  1.0   | 16/12/2024 | Criação do documento | [Samuel Ribeiro](https://github.com/SamuelRicosta) | [Alana Gabriele](https://github.com/alanagabriele) |
|  1.1   | 17/12/2024 | implementação do NFR01   | [Samuel Ribeiro](https://github.com/SamuelRicosta) | [Alana Gabriele](https://github.com/alanagabriele) |
