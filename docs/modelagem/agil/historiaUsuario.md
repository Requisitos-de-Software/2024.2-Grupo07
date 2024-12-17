## Introdução

A técnica ágil, popularizada no desenvolvimento de software, foca na entrega contínua de valor e flexibilidade para responder rapidamente às mudanças e necessidades do cliente. Uma das metodologias ágeis mais utilizadas é o **desenvolvimento iterativo e incremental**, onde o trabalho é realizado em ciclos curtos chamados "sprints". Cada sprint termina em um conjunto de funcionalidades prontas, testadas e validadas. Dentro desse contexto, as **Histórias de Usuário** desempenham um papel crucial. Elas funcionam como uma ferramenta para comunicar os requisitos funcionais de maneira clara e acessível, orientando o desenvolvimento de funcionalidades de acordo com as necessidades dos usuários finais.

## Metodologia

As Histórias de Usuário são utilizadas para entender o que os usuários desejam de um sistema ou aplicação, descrevendo as funcionalidades desejadas a partir da perspectiva do usuário. Elas são organizadas em uma estrutura clara, que inclui critérios de aceitação e prioridade, permitindo que os desenvolvedores e stakeholders alinhem-se com os objetivos e expectativas do usuário.

Abaixo, a Tabela 1 apresenta o modelo utilizado para a criação das Histórias de Usuário. As Tabelas 2 a 42 detalham os requisitos funcionais do projeto, organizados no formato de Histórias de Usuário.

<font size="2"><p style="text-align: center">Tabela 1 - Modelo </p></font>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Título</th>
 <td>Criterio de Aceitação</td>
 <td>Prioridade</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>USX</td>
      <td>Eu, como xxx, posso xxx para xxx</td>
       <td> Lista com os critérios de aceitação <br>
       <b> Critério y - xxx </b> <br>
        <b>Dado</b> xxx <br>
         <b>Quando</b> xxx <br> 
         <b>E</b> xxx<br>
        <b> Então</b> xxx
      </td>
      <td>Alta, média ou baixa</td>
    </tr>
  </tbody>
</table>

<p style="text-align: center; font-size: 14px;">
    Autor: <a href="https://github.com/alanagabriele" target="_blank">Alana Gabriele</a>
  </p>

## Histórias de Usuário

<details>
  <summary>US01 - Configurar a visibilidade da conta como pública ou privada</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 2 - Configurar visibilidade</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US01</td>
        <td>Eu, como usuário, posso configurar a visibilidade da minha conta como pública ou privada para controlar quem pode ver minhas publicações.</td>
        <td>
          <b>Critério 1 - Configuração de Visibilidade</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu acessar as configurações da conta, <br>
          <b>E</b> selecionar a opção de visibilidade, <br>
          <b>Então</b> minha conta deve ser marcada como pública ou privada com base na minha escolha. <br><br>
          <b>Critério 2 - Indicação Visual</b> <br>
          <b>Dado</b> que a visibilidade da minha conta está configurada como privada, <br>
          <b>Quando</b> outro usuário tentar acessar meu perfil, <br>
          <b>Então</b> ele deve visualizar uma mensagem indicando que o perfil é privado.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US02 - Gravar e enviar mensagens de voz diretamente em uma thread</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 3 - Mensagens de voz</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US02</td>
        <td>Eu, como usuário, posso gravar e enviar mensagens de voz diretamente em uma postagem ou como resposta a um comentário para compartilhar ideias rapidamente.</td>
        <td>
          <b>Critério 1 - Gravação de Voz</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu acessar uma thread ou comentário, <br>
          <b>E</b> clicar no botão de gravação, <br>
          <b>Então</b> o sistema deve iniciar a gravação de uma mensagem de voz. <br><br>
          <b>Critério 2 - Envio de Voz</b> <br>
          <b>Dado</b> que gravei uma mensagem de voz, <br>
          <b>Quando</b> eu clicar no botão de envio, <br>
          <b>Então</b> a mensagem de voz deve ser anexada à postagem ou ao comentário correspondente.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US03 - Visualizar Trend Topics</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 4 - Trend Topics</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US03</td>
        <td>Eu, como usuário, posso visualizar os assuntos mais discutidos em uma lista de Trend Topics para identificar rapidamente tópicos populares.</td>
        <td>
          <b>Critério 1 - Exibição de Tendências</b> <br>
          <b>Dado</b> que existem tópicos populares no sistema, <br>
          <b>Quando</b> eu acessar a página inicial, <br>
          <b>Então</b> devo visualizar uma lista com os Trend Topics atualizados. <br><br>
          <b>Critério 2 - Atualização em Tempo Real</b> <br>
          <b>Dado</b> que um novo tópico se torna popular, <br>
          <b>Quando</b> ele atingir o volume necessário, <br>
          <b>Então</b> ele deve ser incluído automaticamente na lista de tendências.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US04 - Verificar contas com número de telefone e email cadastrados</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 5 - Verificação de contas</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US04</td>
        <td>Eu, como usuário, posso verificar minha conta com número de telefone e email cadastrados para aumentar a segurança do meu perfil.</td>
        <td>
          <b>Critério 1 - Verificação de Telefone</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu informar meu número de telefone, <br>
          <b>E</b> receber um código de verificação, <br>
          <b>Então</b> devo conseguir validar minha conta inserindo o código corretamente. <br><br>
          <b>Critério 2 - Verificação de Email</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu informar meu email, <br>
          <b>E</b> receber um código de verificação, <br>
          <b>Então</b> devo conseguir validar minha conta inserindo o código corretamente.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US05 - Responder anonimamente em discussões públicas moderadas</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 6 - Respostas Anônimas</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US05</td>
        <td>Eu, como usuário, posso responder anonimamente em discussões públicas moderadas para compartilhar opiniões sem revelar minha identidade.</td>
        <td>
          <b>Critério 1 - Resposta Anônima</b> <br>
          <b>Dado</b> que estou participando de uma discussão pública moderada, <br>
          <b>Quando</b> eu optar por responder anonimamente, <br>
          <b>Então</b> minha resposta deve ser exibida sem associar meu perfil ao conteúdo publicado. <br><br>
          <b>Critério 2 - Moderação de Respostas</b> <br>
          <b>Dado</b> que respondi anonimamente, <br>
          <b>Quando</b> minha resposta for publicada, <br>
          <b>Então</b> ela deve passar por moderação antes de ser exibida publicamente.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US06 - Tradução automática de publicações</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 7 - Tradução Automática</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US06</td>
        <td>Eu, como usuário, posso traduzir automaticamente publicações para meu idioma preferido para entender conteúdos em outros idiomas.</td>
        <td>
          <b>Critério 1 - Tradução Automática</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu acessar uma publicação em outro idioma, <br>
          <b>E</b> clicar no botão de traduzir, <br>
          <b>Então</b> o sistema deve exibir a publicação traduzida no idioma configurado.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US07 - Reduzir anúncios intrusivos e ajustar algoritmos para maior transparência</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 8 - Anúncios e Algoritmos</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US07</td>
        <td>Eu, como usuário, desejo que os anúncios sejam menos intrusivos e os algoritmos mais transparentes para melhorar minha experiência.</td>
        <td>
          <b>Critério 1 - Redução de Anúncios</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu navegar pelo feed, <br>
          <b>Então</b> devo visualizar anúncios em menor frequência e com menor impacto visual. <br><br>
          <b>Critério 2 - Algoritmos Transparentes</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu interagir com publicações, <br>
          <b>Então</b> devo ser informado de como minha interação influencia as recomendações futuras.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US08 - Implementar moderação para reduzir bots e publicações irrelevantes</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 9 - Moderação de Bots e Conteúdo</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US08</td>
        <td>Eu, como administrador, posso moderar publicações para reduzir bots e publicações irrelevantes.</td>
        <td>
          <b>Critério 1 - Detecção de Bots</b> <br>
          <b>Dado</b> que sou administrador, <br>
          <b>Quando</b> eu identificar contas com comportamento suspeito, <br>
          <b>Então</b> devo ter ferramentas para revisar e excluir essas contas. <br><br>
          <b>Critério 2 - Moderação de Conteúdo</b> <br>
          <b>Dado</b> que sou administrador, <br>
          <b>Quando</b> eu revisar publicações, <br>
          <b>Então</b> devo poder marcar conteúdos irrelevantes para remoção ou revisão.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US09 - Upload de vídeos em alta definição</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 10 - Upload de Vídeos</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US09</td>
        <td>Eu, como usuário, posso fazer upload de vídeos em alta definição para compartilhar conteúdos de qualidade.</td>
        <td>
          <b>Critério 1 - Upload de Vídeos</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu clicar no botão de upload de vídeo, <br>
          <b>Então</b> devo conseguir selecionar e enviar vídeos em alta definição para o sistema. <br><br>
          <b>Critério 2 - Qualidade do Vídeo</b> <br>
          <b>Dado</b> que enviei um vídeo, <br>
          <b>Quando</b> ele for reproduzido no sistema, <br>
          <b>Então</b> a qualidade original do vídeo deve ser mantida.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US10 - Exibir confirmação visual para ações do usuário</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 11 - Confirmação Visual</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US11</td>
        <td>Eu, como usuário, quero visualizar uma confirmação visual ao interagir com uma postagem para ter certeza de que minha ação foi concluída.</td>
        <td>
          <b>Critério 1 - Confirmação de Curtir</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu clicar no botão de curtir em uma publicação, <br>
          <b>Então</b> o sistema deve exibir uma animação de preenchimento do ícone de curtida. <br><br>
          <b>Critério 2 - Confirmação de Salvar</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu clicar no botão de salvar uma publicação, <br>
          <b>Então</b> o sistema deve exibir um alerta de sucesso informando que o conteúdo foi salvo. <br><br>
          <b>Critério 3 - Confirmação de Compartilhar</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu clicar no botão de compartilhar uma publicação, <br>
          <b>Então</b> o sistema deve exibir uma mensagem indicando que o link ou conteúdo foi copiado ou enviado.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/alanagabriele">Alana Gabriele</a></p>

</details>

<details>
  <summary>US11 - Agendamento de Publicações</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 12 - Agendamento de Publicações</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>RF01</td>
        <td>Eu, como usuário, posso agendar publicações para horários futuros.</td>
        <td>
          <b>Critério 1 - Agendamento de Publicações</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu criar uma postagem e escolher uma data e horário futuros, <br>
          <b>Então</b> o sistema deve agendar a publicação.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro </a></p>

</details>

<details>
  <summary>US12 - Reações Variadas</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 13 - Reações Variadas</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>RF02</td>
        <td>Eu, como usuário, posso reagir às publicações com opções variadas além de "curtir".</td>
        <td>
          <b>Critério 1 - Reações Variadas</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu visualizar uma publicação, <br>
          <b>Então</b> devo poder escolher entre várias opções de reação (ex.: "adorar", "haha").
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro </a></p>

</details>

<details>
  <summary>US13 - Tradução Automática</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 14 - Tradução Automática</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US13</td>
        <td>Eu, como usuário, posso traduzir automaticamente publicações para meu idioma preferido.</td>
        <td>
          <b>Critério 1 - Tradução Automática</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu visualizar uma publicação em outro idioma, <br>
          <b>Então</b> devo poder traduzir para meu idioma preferido.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro </a></p>

</details>

<details>
  <summary>US14 - Denúncia de Contas ou Postagens</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 15 - Denúncia de Contas ou Postagens</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US14</td>
        <td>Eu, como usuário, posso denunciar contas ou postagens que violem as regras da plataforma.</td>
        <td>
          <b>Critério 1 - Denúncia de Postagens</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu visualizar uma publicação inadequada, <br>
          <b>Então</b> devo poder denunciá-la.
        </td>
        <td>Alta</td>
      </tr>
      <tr>
        <td></td>
        <td>Critério 2 - Denúncia de Contas</td>
        <td>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> acessar um perfil inadequado, <br>
          <b>Então</b> devo poder denunciá-lo.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro </a></p>

</details>

<details>
  <summary>US15 - Compartilhamento Externo</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 16 - Compartilhamento Externo</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US15</td>
        <td>Eu, como usuário, posso compartilhar postagens diretamente em plataformas externas.</td>
        <td>
          <b>Critério 1 - Compartilhamento Externo</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu clicar para compartilhar uma postagem, <br>
          <b>Então</b> devo ver opções de plataformas externas.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro </a></p>

</details>

<details>
  <summary>US16 - Backup e Restauração de Dados</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 17 - Backup e Restauração de Dados</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US16</td>
        <td>Eu, como usuário, posso fazer backup e restaurar meus dados (postagens e configurações).</td>
        <td>
          <b>Critério 1 - Backup de Dados</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu acessar as configurações, <br>
          <b>Então</b> devo poder criar um backup.
        </td>
        <td></td>
      </tr>
      <tr>
        <td></td>
        <td>Critério 2 - Restauração de Dados</td>
        <td>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> acessar as configurações, <br>
          <b>Então</b> devo restaurar o backup.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro </a></p>

</details>

<details>
  <summary>US17 - Histórico de Interações</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 18 - Histórico de Interações</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US17</td>
        <td>Eu, como usuário, posso visualizar o histórico de interações com outros usuários.</td>
        <td>
          <b>Critério 1 - Histórico de Interações</b> <br>
          <b>Dado</b> que sou um usuário, <br>
          <b>Quando</b> eu acessar meu perfil, <br>
          <b>Então</b> devo poder ver o histórico de interações (mensagens, comentários, likes).
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro </a></p>

</details>

<details>
  <summary>US18 - Rascunhos Offline</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 19 - Rascunhos Offline</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US18</td>
        <td>Eu, como usuário, posso criar e salvar rascunhos de postagens offline.</td>
        <td>
          <b>Critério 1 - Rascunhos Offline</b> <br>
          <b>Dado</b> que sou um usuário,<br> 
          <b>Quando</b> estiver offline, <br>
          <b>Então</b> devo criar e salvar rascunhos que poderão ser publicados quando online.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro </a></p>

</details>

<details>
  <summary>US19 - Respostas Anônimas</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 20 - Respostas Anônimas</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US19</td>
        <td>Eu, como usuário, posso responder anonimamente em discussões públicas moderadas.</td>
        <td>
          <b>Critério 1 - Respostas Anônimas</b> <br>
          <b>Dado</b> que sou um usuário,<br> 
          <b>Quando</b> estiver em uma discussão pública,<br> 
          <b>Então</b> devo responder anonimamente, visível apenas para moderadores.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro </a></p>

</details>

<details>
  <summary>US20 - Criação de Comunidades</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 21 - Criação de Comunidades</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US20</td>
        <td>Eu, como usuário, posso criar comunidades ou grupos temáticos dentro da plataforma.</td>
        <td>
          <b>Critério 1 - Criação de Comunidades</b> <br>
          <b>Dado</b> que sou um usuário,<br> 
          <b>Quando</b> desejar criar um grupo,<br> 
          <b>Então</b> devo configurar nome, descrição e regras da comunidade.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/SamuelRicosta" target="_blank">Samuel Ribeiro </a></p>

</details>

<details>
  <summary>US21 - Salvar postagens para leitura posterior</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 22 - Salvar postagens</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US21</td>
        <td>Eu, como usuário, posso salvar postagens para leitura posterior em uma seção específica do meu perfil, para facilitar o acesso a conteúdos importantes.</td>
        <td>
          <b>Critério 1 - Botão de Salvar</b> <br>
          <b>Dado</b> que sou um usuário visualizando uma postagem, <br>
          <b>Quando</b> eu clicar no botão "Salvar", <br>
          <b>Então</b> a postagem deve ser adicionada à seção de "Salvos" no meu perfil. <br><br>
          <b>Critério 2 - Listagem no Perfil</b> <br>
          <b>Dado</b> que sou um usuário acessando a seção "Salvos", <br>
          <b>Quando</b> eu visualizar a lista, <br>
          <b>Então</b> todas as postagens salvas devem ser exibidas em ordem cronológica.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/dudupaz">Carlos Eduardo</a></p>

</details>

<details>
  <summary>US22 - Sugerir novos usuários para seguir</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 23 - Sugerir novos usuários</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US22</td>
        <td>Eu, como usuário, desejo receber sugestões de novos usuários para seguir, baseadas nos meus interesses e interações, para expandir minha rede.</td>
        <td>
          <b>Critério 1 - Sugestões Personalizadas</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> acessar a aba de sugestões, <br>
          <b>Então</b> devo ver uma lista de usuários recomendados baseada nos meus interesses. <br><br>
          <b>Critério 2 - Interação com Sugestões</b> <br>
          <b>Dado</b> que estou visualizando as sugestões, <br>
          <b>Quando</b> clicar em "Seguir", <br>
          <b>Então</b> o usuário selecionado deve ser adicionado à minha lista de seguidos.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/dudupaz">Carlos Eduardo</a></p>

</details>

<details>
  <summary>US23 - Compartilhar postagens em plataformas externas</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 24 - Compartilhar postagens</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US23</td>
        <td>Eu, como usuário, posso compartilhar postagens diretamente em plataformas externas, para aumentar o alcance do conteúdo.</td>
        <td>
          <b>Critério 1 - Opção de Compartilhar</b> <br>
          <b>Dado</b> que sou um usuário visualizando uma postagem, <br>
          <b>Quando</b> clicar no botão "Compartilhar", <br>
          <b>Então</b> deve abrir uma lista de plataformas externas disponíveis. <br><br>
          <b>Critério 2 - Confirmação de Compartilhamento</b> <br>
          <b>Dado</b> que selecionei uma plataforma externa, <br>
          <b>Quando</b> confirmar o compartilhamento, <br>
          <b>Então</b> o conteúdo deve ser publicado na plataforma selecionada.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/dudupaz">Carlos Eduardo</a></p>

</details>

<details>
  <summary>US24 - Criar enquetes interativas</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 25 - Criar enquetes</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US24</td>
        <td>Eu, como usuário, posso criar enquetes interativas em minhas postagens, para engajar minha audiência.</td>
        <td>
          <b>Critério 1 - Formulário de Enquete</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> criar uma nova postagem, <br>
          <b>Então</b> devo ter a opção de adicionar uma enquete com no máximo 4 opções de resposta. <br><br>
          <b>Critério 2 - Resultados em Tempo Real</b> <br>
          <b>Dado</b> que uma enquete foi publicada, <br>
          <b>Quando</b> outros usuários votarem, <br>
          <b>Então</b> os resultados devem ser atualizados em tempo real.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/dudupaz">Carlos Eduardo</a></p>

</details>

<details>
  <summary>US25 - Agendar postagens</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 26 - Agendar postagens</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US25</td>
        <td>Eu, como usuário, posso agendar postagens para horários específicos, para otimizar a visibilidade do conteúdo.</td>
        <td>
          <b>Critério 1 - Escolha de Data e Hora</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> criar uma postagem, <br>
          <b>Então</b> devo ter a opção de selecionar a data e hora para publicação. <br><br>
          <b>Critério 2 - Publicação Automática</b> <br>
          <b>Dado</b> que uma postagem foi agendada, <br>
          <b>Quando</b> o horário agendado chegar, <br>
          <b>Então</b> a postagem deve ser publicada automaticamente.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/dudupaz">Carlos Eduardo</a></p>

</details>

<details>
  <summary>US26 - Denunciar contas ou postagens</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 27 - Denunciar contas ou postagens</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US26</td>
        <td>Eu, como usuário, posso denunciar contas ou postagens que violem as regras da comunidade, para melhorar a segurança da plataforma.</td>
        <td>
          <b>Critério 1 - Opção de Denúncia</b> <br>
          <b>Dado</b> que estou visualizando uma postagem ou perfil, <br>
          <b>Quando</b> clicar no botão "Denunciar", <br>
          <b>Então</b> devo ver uma lista de motivos predefinidos para a denúncia. <br><br>
          <b>Critério 2 - Confirmação de Denúncia</b> <br>
          <b>Dado</b> que selecionei um motivo, <br>
          <b>Quando</b> confirmar a denúncia, <br>
          <b>Então</b> o sistema deve registrar a denúncia e exibir uma mensagem de confirmação.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/dudupaz">Carlos Eduardo</a></p>

</details>

<details>
  <summary>US27 - Ocultar publicações antigas</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 28 - Ocultar publicações antigas</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US27</td>
        <td>Eu, como usuário, posso ocultar publicações antigas do meu perfil sem precisar excluí-las, para manter a privacidade.</td>
        <td>
          <b>Critério 1 - Opção de Ocultar</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> acessar minhas publicações antigas, <br>
          <b>Então</b> devo ter a opção de ocultar uma publicação. <br><br>
          <b>Critério 2 - Visualização Privada</b> <br>
          <b>Dado</b> que uma publicação está oculta, <br>
          <b>Quando</b> acessar meu perfil, <br>
          <b>Então</b> somente eu devo conseguir visualizar essa publicação.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/dudupaz">Carlos Eduardo</a></p>

</details>

<details>
  <summary>US28 - Fazer backup e restaurar dados</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 29 - Fazer backup e restaurar dados</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US28</td>
        <td>Eu, como usuário, posso fazer backup e restaurar meus dados, como postagens e configurações, para evitar perda de informações importantes.</td>
        <td>
          <b>Critério 1 - Backup Manual</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> acessar as configurações, <br>
          <b>Então</b> devo ter a opção de gerar um backup dos meus dados. <br><br>
          <b>Critério 2 - Restauração de Dados</b> <br>
          <b>Dado</b> que tenho um arquivo de backup, <br>
          <b>Quando</b> acessar a opção de restaurar dados, <br>
          <b>Então</b> o sistema deve restaurar minhas postagens e configurações com sucesso.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/dudupaz">Carlos Eduardo</a></p>

</details>

<details>
  <summary>US29 - Filtrar conteúdos no feed</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 30 - Filtrar conteúdos</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US29</td>
        <td>Eu, como usuário, posso filtrar conteúdos no feed com base em categorias específicas, para visualizar apenas o que for relevante para mim.</td>
        <td>
          <b>Critério 1 - Opção de Filtro</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> acessar meu feed, <br>
          <b>Então</b> devo ter a opção de selecionar categorias específicas para filtrar os conteúdos exibidos. <br><br>
          <b>Critério 2 - Atualização em Tempo Real</b> <br>
          <b>Dado</b> que um filtro foi aplicado, <br>
          <b>Quando</b> novos conteúdos forem carregados, <br>
          <b>Então</b> apenas os conteúdos que atendem ao filtro devem ser exibidos.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/dudupaz">Carlos Eduardo</a></p>

</details>

<details>
  <summary>US30 - Adicionar legendas automáticas aos vídeos</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 31 - Adicionar legendas automáticas</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US30</td>
        <td>Eu, como usuário, posso adicionar legendas automáticas aos vídeos que envio, com suporte para múltiplos idiomas, para torná-los acessíveis.</td>
        <td>
          <b>Critério 1 - Geração Automática</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> enviar um vídeo, <br>
          <b>Então</b> devo ter a opção de gerar legendas automáticas com suporte a múltiplos idiomas. <br><br>
          <b>Critério 2 - Editar Legendas</b> <br>
          <b>Dado</b> que as legendas foram geradas, <br>
          <b>Quando</b> acessar a opção de edição, <br>
          <b>Então</b> devo poder corrigir ou ajustar o texto gerado automaticamente.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/dudupaz">Carlos Eduardo</a></p>

</details>

<details>
  <summary>US31 - Sugerir textos de postagens com IA</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 31 - Sugerir textos de postagens com IA</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US31</td>
        <td>Eu, como usuário, posso receber sugestões automáticas de textos ao criar postagens, com base em palavras-chave fornecidas, para facilitar a criação.</td>
        <td>
          <b>Critério 1 - Sugestão Automática</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> começar a criar uma postagem e fornecer palavras-chave, <br>
          <b>Então</b> o sistema deve sugerir textos relevantes gerados por IA. <br><br>
          <b>Critério 2 - Ajuste Manual</b> <br>
          <b>Dado</b> que o texto foi sugerido, <br>
          <b>Quando</b> desejar ajustar o conteúdo, <br>
          <b>Então</b> devo ser capaz de editar ou complementar o texto.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs">Genilson Silva</a></p>
</details>

<details>
  <summary>US32 - Oferecer reações variadas para publicações</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 32 - Reações variadas para publicações</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US32</td>
        <td>Eu, como usuário, posso usar reações variadas (além de curtir) para expressar minhas emoções em publicações.</td>
        <td>
          <b>Critério 1 - Tipos de Reação</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> visualizar uma postagem, <br>
          <b>Então</b> devo ter opções como "curtir", "adorar", "surpreso" e outras reações. <br><br>
          <b>Critério 2 - Alterar Reação</b> <br>
          <b>Dado</b> que já reagi a uma publicação, <br>
          <b>Quando</b> quiser modificar minha reação, <br>
          <b>Então</b> devo conseguir substituir a reação anterior.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs">Genilson Silva</a></p>
</details>

<details>
  <summary>US33 - Criar e salvar rascunhos offline</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 33 - Criar e salvar rascunhos offline</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US33</td>
        <td>Eu, como usuário, posso criar e salvar rascunhos de postagens mesmo sem conexão com a internet.</td>
        <td>
          <b>Critério 1 - Salvar Offline</b> <br>
          <b>Dado</b> que estou sem conexão, <br>
          <b>Quando</b> criar um rascunho, <br>
          <b>Então</b> o sistema deve salvar o conteúdo localmente. <br><br>
          <b>Critério 2 - Publicar ao Reconectar</b> <br>
          <b>Dado</b> que um rascunho foi salvo offline, <br>
          <b>Quando</b> houver conexão, <br>
          <b>Então</b> devo poder publicá-lo diretamente.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs">Genilson Silva</a></p>
</details>

<details>
  <summary>US34 - Agendar postagens</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 34 - Agendar postagens</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US34</td>
        <td>Eu, como usuário, posso agendar postagens para horários específicos no futuro.</td>
        <td>
          <b>Critério 1 - Definir Horário</b> <br>
          <b>Dado</b> que estou criando uma postagem, <br>
          <b>Quando</b> acessar a opção de agendamento, <br>
          <b>Então</b> devo poder escolher uma data e horário específicos para a publicação. <br><br>
          <b>Critério 2 - Gerenciar Agendamentos</b> <br>
          <b>Dado</b> que agendei uma postagem, <br>
          <b>Quando</b> acessar a lista de agendamentos, <br>
          <b>Então</b> devo poder editar ou cancelar o agendamento.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs">Genilson Silva</a></p>
</details>

<details>
  <summary>US35 - Compartilhar postagens em plataformas externas</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 35 - Compartilhar postagens externamente</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US35</td>
        <td>Eu, como usuário, posso compartilhar postagens diretamente em plataformas externas para ampliar seu alcance.</td>
        <td>
          <b>Critério 1 - Compartilhamento</b> <br>
          <b>Dado</b> que estou visualizando uma postagem, <br>
          <b>Quando</b> selecionar a opção de compartilhamento, <br>
          <b>Então</b> devo poder enviá-la para redes externas como Instagram, Facebook ou WhatsApp. <br><br>
          <b>Critério 2 - Personalizar Compartilhamento</b> <br>
          <b>Dado</b> que escolhi uma plataforma, <br>
          <b>Quando</b> quiser adicionar um comentário antes de compartilhar, <br>
          <b>Então</b> devo poder incluir texto adicional.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs">Genilson Silva</a></p>
</details>

<details>
  <summary>US36 - Criar comunidades ou grupos temáticos</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 36 - Criar comunidades ou grupos temáticos</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US36</td>
        <td>Eu, como usuário, posso criar comunidades ou grupos temáticos dentro da plataforma para compartilhar conteúdos específicos.</td>
        <td>
          <b>Critério 1 - Criação de Comunidades</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> acessar a opção de criar comunidades, <br>
          <b>Então</b> devo poder definir um nome, descrição e regras do grupo. <br><br>
          <b>Critério 2 - Gerenciamento de Membros</b> <br>
          <b>Dado</b> que criei uma comunidade, <br>
          <b>Quando</b> gerenciar membros, <br>
          <b>Então</b> devo poder aceitar, remover ou banir usuários.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs">Genilson Silva</a></p>
</details>

<details>
  <summary>US37 - Carregar o feed rapidamente</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 37 - Carregar o feed rapidamente</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US37</td>
        <td>Eu, como usuário, posso visualizar o feed carregando rapidamente, mesmo com um grande volume de conteúdo.</td>
        <td>
          <b>Critério 1 - Carregamento Eficiente</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> acessar o feed, <br>
          <b>Então</b> o sistema deve carregar as postagens em menos de 2 segundos. <br><br>
          <b>Critério 2 - Paginação ou Scroll Progressivo</b> <br>
          <b>Dado</b> que estou navegando pelo feed, <br>
          <b>Quando</b> rolar a página, <br>
          <b>Então</b> novos conteúdos devem ser carregados progressivamente.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs">Genilson Silva</a></p>
</details>

<details>
  <summary>US38 - Gerenciar múltiplas contas</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 38 - Gerenciar múltiplas contas</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US38</td>
        <td>Eu, como usuário, posso gerenciar múltiplas contas no mesmo aplicativo para alternar entre perfis facilmente.</td>
        <td>
          <b>Critério 1 - Adicionar Contas</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> acessar a seção de contas, <br>
          <b>Então</b> devo poder adicionar várias contas com login individual. <br><br>
          <b>Critério 2 - Alternar Contas</b> <br>
          <b>Dado</b> que adicionei múltiplas contas, <br>
          <b>Quando</b> quiser alternar, <br>
          <b>Então</b> devo poder mudar de conta com um único clique.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs">Genilson Silva</a></p>
</details>

<details>
  <summary>US39 - Oferecer autenticação avançada</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 39 - Oferecer autenticação avançada</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US39</td>
        <td>Eu, como usuário, posso acessar o sistema com autenticação avançada para aumentar a segurança da conta.</td>
        <td>
          <b>Critério 1 - Autenticação em Duas Etapas</b> <br>
          <b>Dado</b> que sou um usuário registrado, <br>
          <b>Quando</b> fizer login, <br>
          <b>Então</b> devo ter a opção de ativar autenticação em duas etapas (código SMS ou aplicativo autenticador). <br><br>
          <b>Critério 2 - Recuperação Segura</b> <br>
          <b>Dado</b> que esqueci minha senha, <br>
          <b>Quando</b> iniciar a recuperação, <br>
          <b>Então</b> o sistema deve validar minha identidade por email ou telefone.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs">Genilson Silva</a></p>
</details>

<details>
  <summary>US40 - Backup e restauração de dados</summary>

  <div style="text-align: center;">
    <p><strong>Tabela 40 - Backup e restauração de dados</strong></p>
  </div>

  <table>
    <thead>
      <tr>
        <th>ID</th>
        <th>Título</th>
        <th>Critérios de Aceitação</th>
        <th>Prioridade</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US40</td>
        <td>Eu, como usuário, posso fazer backup e restaurar meus dados, incluindo postagens e configurações, para evitar perdas.</td>
        <td>
          <b>Critério 1 - Realizar Backup</b> <br>
          <b>Dado</b> que sou um usuário autenticado, <br>
          <b>Quando</b> acessar a opção de backup, <br>
          <b>Então</b> devo poder salvar meus dados em um arquivo seguro. <br><br>
          <b>Critério 2 - Restaurar Dados</b> <br>
          <b>Dado</b> que possuo um arquivo de backup, <br>
          <b>Quando</b> acessar a opção de restauração, <br>
          <b>Então</b> o sistema deve recuperar minhas postagens e configurações anteriores.
        </td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p style="text-align: center;">Autor - <a href="https://github.com/GenilsonJrs">Genilson Silva</a></p>
</details>

<font size="3"><p style="text-align: center">Autores: [Alana Gabriele](https://github.com/alanagabriele), [Samuel Ribeiro](https://github.com/SamuelRicosta) e [Carlos Eduardo](https://github.com/dudupaz). </p></font>

## Referências

> SERRANO, Milene e Maurício. Requisitos - Aula 15. Disponível em: [https://aprender3.unb.br/pluginfile.php/2972504/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf](https://aprender3.unb.br/pluginfile.php/2972504/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf).

> Ministério da agricultura, Pecuária e Abastecimento. Template Estoria de Usuário. Disponível em: [https://www.gov.br/agricultura/pt-br/acesso-a-informacao/licitacoes-e-contratos/edital/2019/pregao-eletronico-no-05-2018/templates-artefatos/estoria-de-usuario.doc/view](https://www.gov.br/agricultura/pt-br/acesso-a-informacao/licitacoes-e-contratos/edital/2019/pregao-eletronico-no-05-2018/templates-artefatos/estoria-de-usuario.doc/view)

## Histórico de Versões

| Versão | Data       | Descrição                      | Autor                                              | Revisor                                            |
| :----: | ---------- | ------------------------------ | -------------------------------------------------- | -------------------------------------------------- |
|  1.0   | 16/12/2024 | História do usuário            | [Alana Gabriele](https://github.com/alanagabriele) | [Carlos Eduardo](https://github.com/dudupaz)       |
|  1.1   | 16/12/2024 | Acionando histórias de usuário | [Samuel Ribeiro](https://github.com/SamuelRicosta) | [Alana Gabriele](https://github.com/alanagabriele) |
|  1.2   | 16/12/2024 | Acionando histórias de usuário | [Carlos Eduardo](https://github.com/dudupaz)       | [Samuel Ribeiro](https://github.com/SamuelRicosta) |
|  1.3   | 17/12/2024 | Acionando histórias de usuário | [Genilson Silva](https://github.com/GenilsonJrs)   | [Alana Gabriele](https://github.com/alanagabriele) |
