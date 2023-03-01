<h1 align = "center"> Implementação do algoritmo de coversão de um Automato Finito Não-Deterministico sem transição vazia para Autômato Finito Determinístico </h1>

Aluno: Marco Aurelio Balduino de Souza

Mátricula: 202011957

Disciplina: Linguagens formais e automatos

<h2>Sobre o Trabalho</h2>
<p>O programa feito, é uma implementação de um algoritmo de conversão do Automato Finito Não-Deterministico sem transição vazia para Autômato Finito Determinístico.</p>

<h2>Requisitos</h2>
<p>O programa foi desenvolvido no Windows 11 64 bits versão 22H2, utilizando Python na versão 3.10.10</p>

<h2>Execução</h2>
<p>
  Para a execução desse programa o simulador deve simular qualquer versão solicitada.Para a realização do simulador, seguimos esses passos:
  <br>
  1. Crie um novo AFD com o mesmo alfabeto do AFN. <br>
  2. Crie um novo estado inicial para o AFD que corresponderá ao conjunto de estados iniciais do AFN.<br>
  3. Para cada conjunto de estados do AFN que ainda não foi adicionado ao AFD, faça o seguinte:<br>
      a. Crie um novo estado no AFD.<br>
      b. Para cada símbolo do alfabeto, encontre o conjunto de estados que podem ser alcançados a partir do conjunto atual através do símbolo.<br>
      c. Adicione uma transição do novo estado do AFD para o conjunto encontrado no passo anterior.<br>
  4. Repita o passo 3 até que não haja mais conjuntos de estados a serem adicionados ao AFD.
</p>

<!--
**MarcoABsouza/MarcoABsouza** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
