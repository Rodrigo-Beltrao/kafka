# kafka
Criação, em notebook com python, de um sistema de mensageria com kafka. Foi criado um producer e um consumer para o sistema de mensageria e posteriormente foi realizado uma análise de dados a partir de um csv público do governo sobre os casos de covid. Ao final da análise, foi possível obter a relação de sobrevivendes de covid e comparar esses dados com o número de mortes e o número de casos confirmados por cada estado brasileiro no ano de 2022. 

O objetivo geral do código é implementar um exemplo básico de comunicação entre um produtor (producer) e um consumidor (consumer) utilizando uma fila (queue) do módulo queue da biblioteca padrão do Python.

O produtor tem como objetivo produzir uma mensagem (nesse caso, uma string) e adicioná-la na fila. Enquanto isso, o consumidor fica em um loop esperando por novas mensagens na fila. Quando uma mensagem é adicionada, o consumidor a retira da fila e faz alguma operação com ela (nesse caso, apenas imprime a mensagem na tela).

Esse é um exemplo simples, mas a ideia geral é que o produtor e o consumidor possam estar em processos ou threads diferentes, permitindo que a comunicação ocorra de forma assíncrona e eficiente entre diferentes partes de um sistema.
