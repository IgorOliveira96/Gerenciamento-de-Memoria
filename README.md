# Gerenciamento-de-Memoria


Nome: Igor de Oliveira Silva
Matrícula: 3672

Exemplos de como executar:
	$ gcc -Wall vmm.c -o vmm  (Compila o gerenciador de memória)

	$ ./vmm random 10 < anomaly.dat  (Executa o Random passando como parâmetro o arquivo dos acessos)

	$ ./vmm fifo 10 < anomaly.dat  (Executa o Fifo passando como parâmetro o arquivo dos acessos)

	$ ./vmm second_chance 10 < anomaly.dat  (Executa o Segunda Chance passando como parâmetro o arquivo dos acessos)

	$ ./vmm nru 10 < anomaly.dat  (Executa o NRU passando como parâmetro o arquivo dos acessos)

	$ ./vmm aging 10 < anomaly.dat  (Executa o Aging passando como parâmetro o arquivo dos acessos)

	$ ./vmm mfu 10 < anomaly.dat  (Executa o MFU passando como parâmetro o arquivo dos acessos)
