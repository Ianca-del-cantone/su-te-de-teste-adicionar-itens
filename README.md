<div style="overflow-x:auto;">

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Cenário</th>
      <th>Caso de Teste (Gherkin)</th>
      <th>Prioridade</th>
      <th>Severidade</th>
      <th>Resultado Esperado</th>
      <th>Resultado Obtido</th>
      <th>Defeitos</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>CT01</td>
      <td>Adicionar um novo item à lista de tarefas</td>
      <td>Dado que o usuário digita "Estudar para prova" no campo de entrada<br>Quando pressiona a tecla Enter<br>Então o item deve ser adicionado e exibido na lista de tarefas</td>
      <td>Alta</td>
      <td>Crítica</td>
      <td>Então o item deve ser adicionado e exibido na lista de tarefas</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT02</td>
      <td>Exibir ícone de seleção para marcar conclusão do item</td>
      <td>Dado que possuo ao menos um item "Comprar ração" na lista<br>Quando passo o mouse sobre o item<br>Então um ícone de seleção (checkbox) deve ser exibido à esquerda do item</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Então um ícone de seleção (checkbox) deve ser exibido à esquerda do item "Comprar ração"</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT03</td>
      <td>Exibir botão de exclusão ao passar o mouse sobre o item</td>
      <td>Dado que exista ao menos um item "Estudar para prova" na lista de tarefas<br>Quando o usuário posiciona o mouse sobre o item<br>Então deve ser exibido um botão de exclusão (ícone "X" vermelho)</td>
      <td>Média</td>
      <td>Média</td>
      <td>Então deve ser exibido um botão de exclusão (ícone "X" vermelho) à direita do item "Estudar para prova"</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT04</td>
      <td>Exibição do rodapé após criação da lista</td>
      <td>Dado que a lista de itens foi criada<br>Então um rodapé deve ser exibido ao final dessa lista</td>
      <td>Média</td>
      <td>Baixa</td>
      <td>Então um rodapé deve ser exibido ao final da lista</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT05</td>
      <td>Exibição do contador e dos filtros no rodapé</td>
      <td>Dado que o rodapé esteja visível<br>Então deve ser exibido:<br>- Um contador com a quantidade de itens restantes<br>- As opções de filtro: "All", "Active" e "Completed"</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Então deve ser exibido:<br>- Um contador com a quantidade de itens restantes<br>- As opções de filtro: "All", "Active" e "Completed"</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT06</td>
      <td>Adicionar item com caracteres especiais</td>
      <td>Dado que o usuário digita um item com caracteres especiais (ex: "Comprar ração @ petshop #1")<br>Quando pressiona a tecla Enter<br>Então o item deve ser exibido exatamente como digitado</td>
      <td>Baixa</td>
      <td>Baixa</td>
      <td>Então o item deve ser adicionado e exibido na lista com todos os caracteres preservados</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Aberto</td>
    </tr>
    <tr>
      <td>CT07</td>
      <td>Remover item da lista usando o botão de exclusão</td>
      <td>Dado que exista um item "Estudar para prova" na lista<br>Quando o usuário clica no botão de exclusão (ícone "X" vermelho)<br>Então o item deve ser removido da lista</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Então o item deve ser removido da lista e não aparece mais</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Aberto</td>
    </tr>
  </tbody>
</table>

</div>






























