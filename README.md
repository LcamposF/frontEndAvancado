# Exercicíos

Este repositório contém os exercícios da Aula1 - React

📚 Questão A) Crie 4 componentes no seu projeto: Adicao, Subtracao, Multiplicacao e Divisao. Esses componentes devem renderizar a seguinte frase dentro de uma tag 'h1': “O resultado de num1 + num2 é igual a resultado”. Use: (-) para subtração (*) para multiplicação (/) para divisão As variáveis 'num1' e 'num2' são atributos do seu componente. Importe esses componentes criados para o App.js e passe os valores de num1 e num2 como propriedade com o objetivo de exibir a frase inteira na tela.

 <h1>Solução: </h1> 
 
Nesta atividade, foram desenvolvidos quatro componentes independentes em React: Adicao, Subtracao, Multiplicacao e Divisao. Cada componente é responsável por executar uma operação aritmética entre dois valores numéricos (num1 e num2), recebidos via propriedades (props).

Cada componente retorna um elemento 'h1'com a seguinte estrutura:

![image](https://github.com/user-attachments/assets/3614092d-ee4b-48e3-9a0c-010e9a6f1cee)

Após a criação dos componentes, fiz a importação de todos dentro do 'App.jsx', e atribuí os valores das variáveis 'num1' e 'num2':

![image](https://github.com/user-attachments/assets/9b6e6193-3c63-4e0d-9d0e-7bd21ba419f4)

💻 Resultado no navegador: 

![image](https://github.com/user-attachments/assets/92fdcce0-62d5-4d54-8ed0-6e354862962b)

📚 Questão B) Crie um componente chamado “PrecisoEstudar.jsx”. Esse componente deve renderizar a seguinte frase dentro de uma tag 'h1': “Preciso estudar NOME-DE-ALGUMA-TECNOLOGIA”. O componente deve ter uma propriedade chamada “nomeDaTecnologia” que irá exibir o nome da tecnologia na frase. Importe esse componente criado para o App.jsx e passe o nome da tecnologia como propriedade com o objetivo de exibir a frase inteira na tela.

 <h1>Solução: </h1>

Além dos componentes matemáticos, foi criado o componente PrecisoEstudar, que exibe uma mensagem motivacional indicando uma tecnologia que estou estudando. O nome da tecnologia é passado como props (nomeDaTecnologia) e incluído na frase exibida dentro de um 'h1':

![image](https://github.com/user-attachments/assets/9aa71f1e-4fd0-4306-b39a-c384d3e56232)

Após a criação do componente, fiz a importação dentro do 'App.jsx':

![image](https://github.com/user-attachments/assets/6455a0b5-9acc-4876-88ce-1e934c835812)

💻 Resultado no navegador:

![image](https://github.com/user-attachments/assets/4f7e1119-7b03-40ce-bbc7-a03c6ccd5827)
