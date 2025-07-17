# Screen Match - Projeto Java (Alura)

Este projeto foi desenvolvido como parte do curso de Java da Alura, com o objetivo de introduzir conceitos fundamentais da linguagem, como variáveis, estruturas condicionais, loops, entrada de dados e manipulação de tipos. O projeto simula um sistema simples de avaliação de filmes, permitindo ao usuário interagir via terminal.

## Estrutura do Projeto

O projeto está organizado em arquivos Java, cada um abordando um conceito ou funcionalidade específica:

- **Main.java**: Introdução ao projeto, exibe informações básicas sobre um filme, como nome, ano de lançamento, média de avaliações e classificação. Demonstra o uso de variáveis, operações matemáticas e impressão formatada.

- **Condicional.java**: Apresenta o uso de estruturas condicionais (`if`, `else`, operadores lógicos) para liberar ou não o acesso a um filme, dependendo do plano do usuário e do ano de lançamento.

- **Leitura.java**: Demonstra como capturar dados do usuário utilizando a classe `Scanner`, solicitando o nome do filme, ano de lançamento e avaliação.

- **Loop.java**: Utiliza um laço `for` para coletar múltiplas avaliações do usuário e calcular a média das notas.

- **OutroLoop.java**: Mostra o uso de um laço `while` para permitir avaliações indefinidas até que o usuário decida encerrar (digitando -1), calculando a média das avaliações recebidas.

- **Contador.java**: Exemplo simples de laço `while` para contar de 1 a 10, reforçando o conceito de repetição.

## Como Executar

1. Certifique-se de ter o Java instalado (JDK 17 ou superior recomendado).
2. Compile os arquivos Java na pasta `src`:
   ```bash
   javac src/*.java
   ```
3. Execute o arquivo desejado, por exemplo:
   ```bash
   java -cp src Main
   ```

## Possíveis Melhorias Futuras

- **Persistência de Dados**: Salvar avaliações e filmes em arquivos ou banco de dados para manter o histórico entre execuções.
- **Interface Gráfica**: Evoluir de um sistema de terminal para uma interface gráfica (Swing, JavaFX ou web).
- **Cadastro de Usuários**: Permitir múltiplos usuários, cada um com seu próprio perfil e avaliações.
- **Catálogo de Filmes**: Gerenciar uma lista de filmes, permitindo adicionar, remover e buscar filmes.
- **Validação de Dados**: Melhorar a robustez do sistema, validando entradas do usuário para evitar erros.
- **Testes Automatizados**: Adicionar testes unitários para garantir a qualidade e funcionamento do código.
- **Internacionalização**: Suporte a múltiplos idiomas além do português.

## Sobre o Curso

Este projeto faz parte do curso de Java da Alura, que visa ensinar os fundamentos da linguagem de forma prática e progressiva, preparando o aluno para desafios maiores no desenvolvimento de aplicações Java.

---

Desenvolvido por Eduardo durante o curso da Alura. 