# Introspecção

## Introdução

A técnica de introspecção é um método de elicitação de requisitos que se baseia na análise subjetiva do engenheiro de requisitos ou de um membro da equipe. Esse método permite explorar as percepções e experiências individuais para identificar funcionalidades essenciais e possíveis melhorias no sistema. De acordo com o dicionário Michaelis (2024), a introspecção consiste em:

1. Observação e descrição por determinada pessoa de suas experiências e seus padrões de comportamento.
2. Psicologia: Método de observação e descrição objetiva dos fatos psíquicos e do conteúdo da consciência do próprio observador.

Aplicar a introspecção em engenharia de requisitos é útil em projetos onde o conhecimento inicial do sistema é limitado, permitindo ao analista projetar cenários e identificar características essenciais a partir de sua própria perspectiva de uso.

## Objetivo

O objetivo deste documento é registrar os requisitos do aplicativo **Threads** elicitados por meio da introspecção. A partir da análise do aplicativo, buscamos:

- Identificar funcionalidades essenciais para garantir a melhor experiência do usuário;
- Propor melhorias baseadas em padrões observados em aplicativos similares;
- Considerar cenários de uso cotidianos e identificar requisitos funcionais e não funcionais do sistema.

## Metodologia

A introspecção foi aplicada seguindo os seguintes passos:

1. **Exploração inicial**: Foram levantadas informações gerais sobre o **Threads**, como sua proposta, principais funcionalidades e objetivos.
2. **Criação de cenários**: Simularam-se interações típicas de usuários no sistema, como criação de posts, consumo de conteúdo e interações sociais.
3. **Análise introspectiva**: Baseando-se em experiências pessoais e em padrões observados em aplicativos semelhantes, foram elencadas funcionalidades desejadas e características esperadas para cada cenário.
4. **Documentação dos requisitos**: As observações foram organizadas em requisitos funcionais (RF) e não funcionais (RNF), cada um identificado com base em sua prioridade e impacto no sistema.

Os cenários simulados e as observações obtidas estão descritos na **Tabela 1**, enquanto os requisitos elicitados com base nessa análise estão detalhados na **Tabela 2**.

---

## Cenários e Observações

A **Tabela 1** apresenta os cenários de uso do aplicativo Threads e as observações feitas com base na análise introspectiva:

<font size="2"><p style="text-align: center">**Tabela 1** - Cenários e observações obtidas por introspecção. </p></font>

| **Cenário de uso**           | **Observações**                                                                              |
| ---------------------------- | -------------------------------------------------------------------------------------------- |
| Abertura do aplicativo       | A tela inicial deve apresentar os conteúdos mais recentes das contas seguidas pelo usuário.  |
| Publicação de posts          | Deve ser possível criar um post com texto, imagens e links de maneira simples e intuitiva.   |
| Interação com posts          | O usuário deve conseguir curtir, comentar, repostar e salvar posts sem atrasos perceptíveis. |
| Exploração de conteúdo       | O sistema deve sugerir conteúdos relevantes com base em interesses do usuário.               |
| Configurações de privacidade | Deve ser possível alternar entre contas públicas e privadas rapidamente.                     |

## <font size="2"><p style="text-align: center"> Autor: [Samuel Ribeiro](https://github.com/SamuelRicosta) </p></font>

## Requisitos elicitados

Com base nos cenários descritos na **Tabela 1**, foram elicitados os seguintes requisitos funcionais (RF) e não funcionais (RNF), conforme apresentados na **Tabela 2**:

<font size="2"><p style="text-align: center">**Tabela 2** - Requisitos elicitados com base na técnica de introspecção. </p></font>

<table border="1"> <tr> <th><strong>Identificador</strong></th> <th><strong>Requisito</strong></th> <th><strong>Tipo</strong></th> </tr> <tr> <td><strong>01</strong></td> <td>O sistema deve reduzir anúncios intrusivos e ajustar algoritmos para maior transparência.</td> <td>RNF</td> </tr> <tr> <td><strong>02</strong></td> <td>O sistema deve melhorar o algoritmo para priorizar conteúdos relevantes ao usuário.</td> <td>RNF</td> </tr> <tr> <td><strong>03</strong></td> <td>O sistema deve evitar a sobrecarga de notificações irrelevantes.</td> <td>RNF</td> </tr> <tr> <td><strong>04</strong></td> <td>O sistema deve implementar moderação para reduzir bots e publicações irrelevantes.</td> <td>RNF</td> </tr> <tr> <td><strong>05</strong></td> <td>O sistema deve oferecer autenticação avançada para segurança do usuário.</td> <td>RNF</td> </tr> <tr> <td><strong>06</strong></td> <td>O sistema deve garantir tempos de resposta inferiores a 1 segundo para interações usuais.</td> <td>RNF</td> </tr> <tr> <td><strong>07</strong></td> <td>O aplicativo deve minimizar o consumo de bateria em dispositivos móveis, garantindo uma taxa de consumo inferior a 5%.</td> <td>RNF</td> </tr> <tr> <td><strong>08</strong></td> <td>O sistema deve ser compatível com dispositivos móveis de versões Android 8.0 e iOS 12 ou superiores.</td> <td>RNF</td> </tr> </table>

## <font size="2"><p style="text-align: center"> Autor: [Samuel Ribeiro](https://github.com/SamuelRicosta) </p></font>

## Referências

- MICHAELIS. Dicionário Michaelis de Língua Portuguesa. Disponível em: [https://michaelis.uol.com.br](https://michaelis.uol.com.br). Acesso em: 21 nov. 2024.
- BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da. _Interação Humano-Computador_. Elsevier, 2010.
- SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 2022. Material apresentado para a disciplina de Engenharia de Requisitos no curso de Engenharia de Software.

---

## Histórico de Versões

| **Versão** | **Data**   | **Descrição**        | **Autor(es)**                                      | **Revisor(es)**                                    |
| ---------- | ---------- | -------------------- | -------------------------------------------------- | -------------------------------------------------- |
| 1.0        | 21/11/2024 | Criação do documento | [Samuel Ribeiro](https://github.com/SamuelRicosta) | [Genilson Silva](https://github.com/GenilsonJrs)   |
| 1.1        | 23/11/2024 | Arrumado legenda     | [Samuel Ribeiro](https://github.com/SamuelRicosta) | [Alana Gabriele](https://github.com/alanagabriele) |
| 1.2        | 17/12/2024 | Ajustes no documento     | [Genilson Silva](https://github.com/GenilsonJrs) | [Alana Gabriele](https://github.com/alanagabriele) |
