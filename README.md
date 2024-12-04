# ControleDeFluxo-Desafio-Java-DIO

**Objetivo:**

O projeto "ControleDeFluxo-Desafio-Java-DIO" tem como principal objetivo implementar um algoritmo que, a partir de dois números inteiros fornecidos pelo usuário, calcula a diferença entre eles e, em seguida, imprime uma sequência numérica até o valor dessa diferença. Além disso, o sistema incorpora um mecanismo de tratamento de exceções para garantir que o primeiro número seja sempre maior que o segundo, evitando resultados inesperados.

**Desafios e Soluções:**

* **Tratamento de Exceções:**
    * **Identificação da Condição:** O maior desafio consistiu em identificar a condição que poderia gerar um erro: quando o segundo número é maior que o primeiro.
    * **Lançamento da Exceção:** Ao detectar essa condição, o sistema lança uma exceção personalizada (ou uma exceção padrão do Java) para sinalizar o erro e interromper a execução normal do programa.
    * **Captura e Tratamento:** A exceção lançada é capturada por um bloco `try-catch`, permitindo que o programa continue a execução mesmo em caso de erro, exibindo uma mensagem informativa ao usuário sobre a causa do problema.

**Tecnologias Utilizadas:**

* **Java:** A linguagem Java foi utilizada para a implementação do projeto, devido à sua ampla utilização e robustez no desenvolvimento de aplicações.

**Resultado Alcançado:**

* **Aprendizado sobre Tratamento de Exceções:**
    * **Conceitos Fundamentais:** O desenvolvimento do projeto permitiu consolidar o entendimento sobre os mecanismos de tratamento de exceções em Java, como:
        * **Blocos `try-catch`:** Utilizados para capturar e tratar exceções, evitando que o programa encerre abruptamente.
        * **Hierarquia de Exceções:** Compreensão da relação entre diferentes tipos de exceções e a importância de escolher a exceção adequada para cada situação.
        * **Exceções Personalizadas:** Criação de exceções personalizadas para representar erros específicos do domínio do problema.
    * **Aplicabilidade:** Foi possível observar como o tratamento de exceções torna um programa mais robusto e resiliente, permitindo que ele continue funcionando mesmo em situações inesperadas.

**Em resumo:**

O projeto "ControleDeFluxo-Desafio-Java-DIO" proporcionou uma experiência prática de aplicação dos conceitos de tratamento de exceções em Java, permitindo ao desenvolvedor construir um algoritmo que lida de forma elegante com situações de erro. A capacidade de identificar, lançar e capturar exceções é fundamental para garantir a qualidade e a confiabilidade de qualquer aplicação.

