*This project has been created as part of the 42 curriculum by vlourenc.*

# Get Next Line

## Description
O projeto **get_next_line** tem como objetivo a implementação de uma função em C que, quando chamada dentro de um loop, permite ler um ficheiro linha a linha até ao seu fim. Este projeto introduz o conceito fundamental de **variáveis estáticas** e gestão de buffers, sendo um desafio de manipulação de memória e ponteiros. O maior desafio reside em lidar com o facto de que o tamanho de uma linha é desconhecido até que o caractere de quebra-de-linha (`\n`) seja encontrado.

## Instructions

### Compilação
O código deve ser compilado com as flags `-Wall -Wextra -Werror`. É necessário definir o tamanho do buffer na compilação usando a flag `-D BUFFER_SIZE=n`.

Exemplo:
cc -Wall -Wextra -Werror -D BUFFER_SIZE=42 get_next_line.c get_next_line_utils.c main.c -o gnl .

# 📚 Resources

## Referências Clássicas

    Unix System Calls - read(): Documentação oficial sobre a leitura de file descriptors.
	Static Variables in C: Guia sobre o tempo de vida e escopo de variáveis estáticas.
	42 Docs - Get Next Line: Explicação técnica sobre gestão de buffers.

# Uso de IA

Neste projeto, a Inteligência Artificial foi utilizada como um "Peer Mentor" nas seguintes tarefas:

	Simulação de Defesa: Preparação para a avaliação através de perguntas teóricas sobre casos limite (ficheiros vazios, BUFFER_SIZE=1, etc.).

    Documentação: Auxílio na estruturação deste ficheiro README conforme os requisitos do subject.