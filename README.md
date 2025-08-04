## 🧾 Documentação de Qualidade: Suíte de Testes na Prática





<details>
  <summary><strong>📋 Clique aqui para ver a suíte de testes</strong></summary>

<br>

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
      <td>Adicionar item à lista</td>
      <td>Dado que o usuário digita "Estudar para prova"<br>Quando pressiona Enter<br>Então o item deve ser exibido na lista</td>
      <td>Alta</td>
      <td>Crítica</td>
      <td>Então o item deve ser exibido na lista</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT02</td>
      <td>Ícone de seleção</td>
      <td>Dado que haja o item "Comprar ração"<br>Quando passo o mouse<br>Então um checkbox deve ser exibido à esquerda</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Então um checkbox deve ser exibido à esquerda</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT03</td>
      <td>Botão de exclusão</td>
      <td>Dado que haja o item "Estudar para prova"<br>Quando passo o mouse<br>Então um "X" vermelho deve ser exibido à direita</td>
      <td>Média</td>
      <td>Média</td>
      <td>Então um "X" vermelho deve ser exibido à direita</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT04</td>
      <td>Rodapé visível</td>
      <td>Dado que haja itens<br>Então um rodapé deve ser exibido</td>
      <td>Média</td>
      <td>Baixa</td>
      <td>Então um rodapé deve ser exibido</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT05</td>
      <td>Contador e filtros</td>
      <td>Dado que o rodapé esteja visível<br>Então deve exibir:<br>- Contador<br>- Filtros "All", "Active", "Completed"</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Então deve exibir o contador e os filtros</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT06</td>
      <td>Caracteres especiais</td>
      <td>Dado que digite "Comprar ração @ loja #1"<br>Quando pressionar Enter<br>Então o item deve ser exibido com os caracteres</td>
      <td>Baixa</td>
      <td>Baixa</td>
      <td>Então o item deve ser exibido com os caracteres</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Aberto</td>
    </tr>
    <tr>
      <td>CT07</td>
      <td>Remover item</td>
      <td>Dado que haja o item "Estudar para prova"<br>Quando clicar no "X" vermelho<br>Então o item deve ser removido da lista</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Então o item deve ser removido da lista</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Aberto</td>
    </tr>
  </tbody>
</table>

</details>
