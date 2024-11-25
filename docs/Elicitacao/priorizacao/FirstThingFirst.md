# Introdução 

O método **First Things First** é uma abordagem de priorização amplamente utilizada para organizar tarefas e requisitos com base em sua urgência e importância. Popularizado por Stephen Covey em *Os 7 Hábitos das Pessoas Altamente Eficazes*, o método divide os itens em quatro categorias principais:

1. **Urgente e Importante**: Deve ser tratado imediatamente.
2. **Não urgente, mas importante**: Deve ser planejado para ações futuras.
3. **Urgente, mas não importante**: Pode ser delegado ou tratado paralelamente.
4. **Não urgente e não importante**: Pode ser adiado ou até descartado.

Na Engenharia de Requisitos, este método auxilia na priorização de funcionalidades e objetivos de projetos, garantindo que as ações mais relevantes sejam realizadas primeiro. Aqui, aplicaremos o método para priorizar os requisitos levantados em nosso projeto.

# Objetivo 

O objetivo da técnica First Thing First é garantir que os requisitos ou atividades mais importantes e de maior impacto sejam priorizados e realizados primeiro, promovendo um foco nos itens críticos para o sucesso do projeto, evitando desperdício de recursos, garantindo entregas relevantes e alinhadas com as expectativas dos stakeholders, além de facilitar o planejamento estratégico com foco em resultados que agreguem valor imediato.

# Metodologia 

Nesta seção, apresentamos os passos seguidos para aplicar o método **First Things First** na priorização de requisitos, utilizando informações coletadas por meio de diversas técnicas de elicitação.

# Gravação

<p >O vídeo pode ser visto direto no <a href="https://www.youtube.com/watch?v=AthY5wGXjwE">YouTube.</a></p>

<div style="text-align: center">
<p>Vídeo 1 - First Thing First</p>
</div>

<iframe width="560" height="315" src="https://www.youtube.com/embed/AthY5wGXjwE?si=XVTUNwi1OrDNXB5L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<p style="text-align: center; font-size: 14px;">
    Autor: <a href="https://github.com/GenilsonJrs" target="_blank">Genilson Silva</a>
</p>

## 1. Levantamento dos Requisitos 

Os requisitos foram identificados utilizando as seguintes técnicas de elicitação:

- **Entrevista**: Conversas estruturadas e semiestruturadas com stakeholders para compreender suas necessidades e expectativas.
- **Introspecção**: Reflexão dos analistas para identificar requisitos com base em experiências anteriores e conhecimento prévio.
- **Questionário**: Coleta de dados por meio de perguntas enviadas a um grupo de stakeholders.
- **Brainstorming**: Sessões colaborativas para reunir ideias e requisitos de forma criativa.

Os dados levantados foram organizados e consolidados em uma lista de requisitos.

## 2. Classificação de Urgência e Importância

Cada requisito foi avaliado segundo dois critérios:

- **Importância**: O impacto do requisito sobre o sucesso do projeto.
- **Urgência**: A necessidade de implementação no curto prazo.

Os valores foram atribuídos utilizando uma escala qualitativa:
- **Importância**: Alta, Média, Baixa.
- **Urgência**: Alta, Média, Baixa.

## 3. Priorização com a Matriz First Things First

Os requisitos foram organizados em uma matriz que define os seguintes quadrantes:
1. **Urgente e Importante**: Priorizados para implementação imediata.
2. **Não urgente, mas importante**: Planejados para desenvolvimento posterior.
3. **Urgente, mas não importante**: Delegados ou realizados em paralelo.
4. **Não urgente e não importante**: Adiados ou descartados.

## 4. Apresentação em Tabela

Os resultados foram organizados em uma tabela (Tabela 1) com as seguintes colunas:
- **Requisito**: Nome ou descrição do requisito.
- **Importância**: Classificação atribuída.
- **Urgência**: Classificação atribuída.
- **Decisão**: Ação sugerida com base na priorização.

# Tabela de Priorização de Requisitos

<div style="text-align: center">
<p>Tabela 1 - First Thing First</p>
</div>

| Ítem | Requisito                                                                 | Tipo          | Importância | Urgência | Decisão                                    |
|------|---------------------------------------------------------------------------|---------------|-------------|----------|--------------------------------------------|
| 01   | O usuário deve ser capaz de curtir publicações.                           | Funcional     | Alta        | Alta     | Urgente e Importante: Deve ser tratado imediatamente. |
| 02   | O usuário deve ser capaz de comentar publicações.                         | Funcional     | Alta        | Alta     | Urgente e Importante: Deve ser tratado imediatamente. |
| 03   | O usuário deve ser capaz de repostar publicações.                         | Funcional     | Alta        | Alta     | Urgente e Importante: Deve ser tratado imediatamente. |
| 04   | O usuário deve ser capaz de personalizar o visual do aplicativo.          | Funcional     | Alta        | Baixa    | Não urgente, mas importante: Deve ser planejado para ações futuras. |
| 05   | O usuário deve ser capaz de receber notificações baseadas no uso do app.  | Funcional     | Alta        | Baixa    | Não urgente, mas importante: Deve ser planejado para ações futuras. |
| 06   | O usuário deve ser capaz de personalizar o feed.                          | Funcional     | Alta        | Alta     | Urgente e Importante: Deve ser tratado imediatamente. |
| 07   | O usuário deve ser capaz de integrar ou desconectar a conta do Instagram. | Funcional     | Alta        | Baixa    | Não urgente, mas importante: Deve ser planejado para ações futuras. |
| 08   | O usuário deve ser capaz de controlar quem pode visualizar suas postagens.| Funcional     | Alta        | Baixa    | Não urgente, mas importante: Deve ser planejado para ações futuras. |
| 09   | O sistema deve sugerir conteúdos relevantes ao usuário com base em seus interesses. | Funcional  | Alta        | Alta     | Urgente e Importante: Deve ser tratado imediatamente. |
| 10   | O sistema deve permitir a criação de publicações com texto, imagens e links. | Funcional  | Alta        | Alta     | Urgente e Importante: Deve ser tratado imediatamente. |
| 11   | O usuário deve ser capaz de configurar a visibilidade de sua conta como pública ou privada. | Funcional | Alta        | Baixa    | Não urgente, mas importante: Deve ser planejado para ações futuras. |
| 12   | O sistema deve criar "Trend Topics" para destacar os assuntos mais discutidos. | Funcional | Alta        | Alta     | Urgente e Importante: Deve ser tratado imediatamente. |
| 13   | O sistema deve reduzir anúncios intrusivos e ajustar algoritmos para maior transparência. | Funcional | Alta        | Alta     | Urgente e Importante: Deve ser tratado imediatamente. |
| 14   | O sistema deve verificar contas com base em número de telefone e email cadastrado. | Funcional | Alta        | Baixa    | Não urgente, mas importante: Deve ser planejado para ações futuras. |
| 15   | O sistema deve melhorar o algoritmo para priorizar conteúdos mais relevantes ao usuário. | Funcional | Alta        | Baixa    | Não urgente, mas importante: Deve ser planejado para ações futuras. |
| 16   | O sistema deve implementar mecanismos de moderação para redução de bots e publicações irrelevantes. | Funcional | Alta        | Alta     | Urgente e Importante: Deve ser tratado imediatamente. |
| 17   | O sistema deve evitar a sobrecarga de notificações irrelevantes.          | Não Funcional | Alta        | Médio    | Urgente, mas não importante: Pode ser delegado ou tratado paralelamente. |
| 18   | O sistema deve garantir uma interface simples e intuitiva para novos usuários. | Não Funcional | Alta        | Baixa    | Não urgente, mas importante: Deve ser planejado para ações futuras. |
| 19   | O sistema deve oferecer autenticação avançada para segurança do usuário.  | Não Funcional | Alta        | Baixa    | Não urgente, mas importante: Deve ser planejado para ações futuras. |
| 20   | O sistema deve garantir tempos de resposta inferiores a 1 segundo para interações usuais. | Não Funcional | Alta        | Baixa    | Não urgente, mas importante: Deve ser planejado para ações futuras. |
| 21   | O sistema deve oferecer o controle de privacidade.                        | Não Funcional | Alta        | Alta     | Urgente e Importante: Deve ser tratado imediatamente. |

<p style="text-align: center; font-size: 14px;">
    Autor: <a href="https://github.com/GenilsonJrs" target="_blank">Genilson Silva</a>
</p>

# Conclusão

A aplicação da técnica First Thing First no processo de priorização de requisitos para o aplicativo Threads demonstrou ser uma abordagem estratégica e eficiente. Essa técnica possibilitou identificar com clareza os requisitos mais importantes e urgentes, garantindo que os esforços da equipe fossem direcionados para funcionalidades críticas ao sucesso do projeto. O processo destacou a relevância de atender primeiro às necessidades que impactam diretamente a experiência do usuário, enquanto permitiu planejar ações futuras para requisitos menos urgentes. Com isso, a priorização não apenas otimizou o uso dos recursos, mas também assegurou um desenvolvimento alinhado às expectativas e demandas dos usuários, promovendo um avanço estruturado no aprimoramento do Threads.

## Referências

- Covey, S. R. (1989). *Os 7 Hábitos das Pessoas Altamente Eficazes*. FranklinCovey Co.
- Sommerville, I. (2011). *Engenharia de Software* (9ª ed.). Pearson.



| **Versão** | **Data**       | **Descrição**               | **Autor(es)** | **Revisor(es)** |  
|------------|----------------|-----------------------------|---------------|-----------------|  
| 1.0        | 24/11/2024     | Criação do documento       | [Samuel Ribeiro](https://github.com/SamuelRicosta)   | [Genilson Silva](https://github.com/GenilsonJrs)    |  
| 1.1        | 24/11/2024     | Adição do vídeo e conteúdo       | [Genilson Silva](https://github.com/GenilsonJrs)   | [Samuel Ribeiro](https://github.com/SamuelRicosta)    |  