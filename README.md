# Atividade 02 - Iniciativa Android

## Atividade 1: **Verificador de idade**

- **Objetivo**: Criar um app que permita ao usuário inserir sua idade e exiba uma mensagem indicando se ele é menor de idade, maior de idade ou está na "meia idade" (entre 18 e 60 anos).

**Passos:**

1. `EditText`: para o usuário inserir a idade.
2. `Button`: para verificar a idade.
3. `TextView`: para exibir a mensagem com base na idade.
4. **Lógica**:
    - Se a idade for menor que 18: "Você é menor de idade."
    - Se a idade for entre 18 e 60: "Você está na meia idade."
    - Se a idade for maior que 60: "Você é idoso."

## Atividade 2: **Calculadora Simples**

- **Objetivo**: Criar uma calculadora simples que realize a soma ou subtração de dois números inseridos pelo usuário.

**Passos:**

1. Dois `EditText`: para o usuário inserir dois números.
2. Dois `Button`: um para somar e outro para subtrair os números.
3. `TextView`: para exibir o resultado.
4. **Lógica**:
    - Use `if` para verificar se os inputs não estão vazios.
    - Realize a operação matemática correspondente (soma ou subtração) e exiba o resultado no `TextView`.

## Atividade 3: **Verificador de Senha**

- **Objetivo**: Criar um app que solicite uma senha do usuário e verifique se a senha inserida é a correta, exibindo uma mensagem de sucesso ou erro.

**Passos:**

1. `EditText`: para o usuário inserir a senha.
2. `Button`: para verificar a senha.
3. `TextView`: para exibir "Senha correta" ou "Senha incorreta".
4. **Lógica**:
    - Defina uma senha fixa (ex.: "1234").
    - Use um `if` para comparar a senha inserida com a senha fixa e exiba a mensagem correta.

## Atividade 4: **Conversor de Temperatura (Desafio Extra)**

- **Objetivo**: Criar um app que converta a temperatura de Celsius para Fahrenheit ou vice-versa, com base na escolha do usuário.

**Passos:**

1. `EditText`: para o usuário inserir a temperatura.
2. Dois `RadioButton`: um para selecionar a conversão de Celsius para Fahrenheit e outro para Fahrenheit para Celsius.
3. `Button`: para realizar a conversão.
4. `TextView`: para exibir o resultado da conversão.
5. **Lógica**:
    - Use `if` ou `when` para verificar qual conversão foi escolhida pelo usuário.
    - Fórmulas:
        - De Celsius para Fahrenheit: `(Celsius * 9/5) + 32`
        - De Fahrenheit para Celsius: `(Fahrenheit - 32) * 5/9`
    - Exiba o resultado no `TextView`.

Essa atividade reforça o uso de inputs, controle condicional e lógica de conversão, além de apresentar um cenário prático e útil.
