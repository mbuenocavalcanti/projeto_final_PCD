# Projeto_final_PCD

## Simulação do crescimento de microorganismos em um Quimiostato
Aluna: Mariana Bueno Cavalcanti

Profs. Responsáveis: Dr. Daniel R. Cassar, Dr. James M. Almeida e Dr. Leandro Lemos.

Trabalho final de Práticas em Ciências de Dados da Ilum Escola de Ciência

### Introdução
Os quimiostatos são sistemas amplamente utilizados em processos biotecnológicos para o cultivo contínuo de microrganismos sob condições controladas. Nesse tipo de reator, nutrientes são continuamente adicionados ao sistema enquanto uma quantidade de biomassa é removida, mantendo o volume constante. Essa operação permite estudar o crescimento microbiano, o consumo de substratos e a influência de diferentes parâmetros operacionais sobre a dinâmica da cultura.

O modelo matemático de um quimiostato é uma ferramenta importante para compreender e prever o comportamento desses sistemas. Entre os modelos mais utilizados destaca-se a cinética de Monod, que descreve a relação entre a taxa específica de crescimento dos microrganismos e a concentração do substrato disponível. Por meio dessa abordagem, foi possível analisar como fatores como taxa máxima de crescimento, constante de saturação, taxa de diluição e rendimento(biomassa/substrato) afetam o número desses microorganismos e a concentração de nutrientes ao longo do tempo.

Neste trabalho foi desenvolvido um simulador computacional simples utilizando a linguagem Python, com as bibliotecas Tkinter e Matplotlib, para representar o funcionamento de um quimiostato. A interface gráfica permite ao usuário modificar os parâmetros do modelo e acompanhar a evolução do crescimento microbiano e da concentração de substrato por meio de um gráfico dinâmico. Dessa forma, o simulador é uma ferramenta didática para o estudo da linguagem Python e como as suas aplicações englobam outras áreas da ciência.

### Objetivo
Desenvolver uma simulação simplificada de um quimiostato utilizando a linguagem Python, baseado na cinética de crescimento microbiano de Monod, para analisar a dinâmica da biomassa e do substrato em um cultivo contínuo.


### Como funciona
Ao executar o programa em um ambiente compatível com Python, uma interface gráfica é aberta contendo os parâmetros do modelo de quimiostato com valores iniciais pré-definidos. O usuário pode alterar esses parâmetros, como taxa máxima de crescimento (μmax), constante de saturação (Ks), taxa de diluição (D), concentração de substrato de entrada (Sin) e rendimento celular (Y).

Após configurar os valores desejados e clicar no botão "Iniciar", a simulação é executada. O gráfico de Concentração (g/L) versus Tempo (h) é atualizado continuamente, exibindo a evolução da biomassa (X) e do substrato (S) ao longo do processo. O usuário pode interromper a simulação a qualquer momento utilizando o botão "Parar" ou retornar o sistema às condições iniciais por meio do botão "Resetar".

### Conclusão
Os resultados obtidos confirmam o comportamento esperado para um cultivo contínuo, evidenciando a capacidade do modelo computacional em representar em pequena escala a interação entre crescimento microbiano e consumo de substrato. Além disso, a interface gráfica desenvolvida permitiu a visualização em tempo real das variáveis do sistema, tornando a ferramenta útil para fins didáticos e para uma melhor compreensão dos conceitos relacionados à linguagem Python.

### Referências
[CARDOSO, Rodolfo Andrade. Crescimento bacteriano no quimiostato: uma aplicação da teoria de equações diferenciais ordinárias. 2018. 99 f. Monografia (Bacharelado em Matemática) – Universidade Federal de Ouro Preto, Instituto de Ciências Exatas e Biológicas, Departamento de Matemática, Ouro Preto, 2018. Acesso em: 17 jun. 2026.](https://www.monografias.ufop.br/bitstream/35400000/1588/1/MONOGRAFIA_CrescimentoBacterianoQuimiostato.pdf)

[OPENAI. Conversa no ChatGPT. Acesso em: 18 jun. 2026](https://chatgpt.com/share/6a342511-9b6c-83e9-8a8e-9f811f10635c)

[PYTHON SOFTWARE FOUNDATION. tkinter — Python interface to Tcl/Tk. Acesso em: 8 jun. 2026](https://docs.python.org/3/library/tkinter.html)
