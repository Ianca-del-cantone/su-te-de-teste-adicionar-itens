# 🧾 Documentação de Qualidade: Suíte de Testes na Prática

Este repositório é parte do meu processo de aprendizado em QA.
Aqui documento, de forma prática e estratégica, a criação de uma suíte de testes baseada em critérios de aceite escritos em Gherkin. O foco é exercitar o olhar analítico sobre funcionalidades, organizar testes de forma clara e treinar o raciocínio necessário para garantir a qualidade de uma aplicação.

A ideia é treinar a clareza na escrita técnica, simular o dia a dia de um QA e reforçar a importância de uma suíte de testes bem estruturada como apoio à análise e automação.


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

---

## 🧪 O que é uma Suíte de Testes?
Uma suíte de testes é um conjunto organizado de casos de teste voltados a validar o comportamento de uma funcionalidade ou fluxo completo.
Ela serve para garantir que a aplicação esteja funcionando conforme o esperado, além de ajudar a identificar rapidamente erros e regressões.

- Ter uma suíte bem documentada é essencial para:
- Cobrir os principais cenários e variações
- Facilitar a execução manual e futura automação
- Ajudar na rastreabilidade dos testes
- Manter consistência na validação de funcionalidades
- Apoiar entregas com mais confiança

---

## ✍️ Linguagem Gherkin
A linguagem Gherkin é usada para escrever casos de teste de forma simples e legível, mesmo por pessoas não técnicas.
Ela segue o formato:

Cenário: Adicionar item na lista
Dado que estou na aplicação
Quando visualizo o campo de input
Então consigo digitar um texto
E o campo exibe o placeholder "O que preciso fazer?"

Esse formato facilita a comunicação entre desenvolvedores, QAs e stakeholders, pois descreve o comportamento do sistema pela ótica do usuário.

---

## 🧩 Funcionalidade
Adicionar item à lista de tarefas
Funcionalidade extraída do site TODO MVC, com foco em simular testes de uma lista interativa de tarefas.

---

## 📝 User Story
Eu, como usuária da aplicação
Gostaria de adicionar novos itens à minha lista de tarefas
Porque quero organizar e acompanhar o que preciso fazer no meu dia a dia

---

##📌 Regras de Negócio

-RN1: O campo de input deve conter o placeholder “O que preciso fazer?”
-RN2: O item só pode ser adicionado se o campo não estiver vazio
-RN3: Caracteres especiais devem ser aceitos no texto do item

---

## ✅ Critérios de Aceite (Gherkin)
Cenário: Adicionar item na lista
Dado que estou na aplicação
Quando digito "Estudar para prova" no campo de entrada e pressiono Enter
Então o item deve ser adicionado e exibido na lista de tarefas

---

## 🧠 Diferença entre Prioridade e Severidade

| Conceito       | O que significa                                                        | Quem define          |
| -------------- | ---------------------------------------------------------------------- | -------------------- |
| **Prioridade** | Define o quão rápido o teste deve ser executado ou o defeito resolvido | Time de produto / QA |
| **Severidade** | Mede o impacto técnico do problema no sistema                          | Time de QA           |

---

## 🧠 Sobre os Casos de Teste
Todos os testes foram escritos com foco em:

-Cobrir os principais comportamentos esperados
-Usar exemplos realistas (como "Estudar para prova", "Comprar ração")
-Trabalhar com critérios claros e mensuráveis
-Organizar os testes com colunas como Prioridade, Severidade, Status, etc.

---

## 🛠️ Objetivo do Projeto
Praticar documentação de testes com foco em clareza e estrutura

-Simular um fluxo real de validação funcional
-Reforçar o uso de Gherkin como ponte entre negócio e testes

---

## 📌 Observação
Este projeto não contém código-fonte, pois o foco está na documentação de testes e raciocínio analítico em QA.
É um exercício essencial para fortalecer a base teórica e desenvolver uma visão crítica sobre o que deve ser testado em uma aplicação.






















