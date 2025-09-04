# trabalho_quebra_de_senhas
Repositório para a implementação, realização e resultados, do trabalho proposto para a matéria de Programação Paralela. A ideia central é desenvolver um algoritmo de quebra de senhas, utilizando a linguagem C (ou GO) por meio de um ataque de força bruta e monitorar o tempo de execução com determinados números de threads.

Explicação:

A proposta desse projeto é desenvolver um algoritmo que execute em paralelo utilizando pthreads, OpenMp ou GO, para quebrar uma senha de 8 digitos (apenas números em um primeiro momento) que execute com N threads (número definido pelo aluno).

A realizar:

- Desenvolvimento e entrega de um código resolvendo de maneira sequencial (sem o uso de threads ou com uma thread apenas).
- Desenvolvimento e entrega de um código resolvendo de maneira paralela (com o uso de threads sem um número definido de threads).
- Entrega de uma tabela (pode ser no excel mesmo), contendo os tempos de execução de cada código (códigos devem ser executados 20 vezes).
- Entrega de um arquivo Makefile para compilação dos códigos.

Orientações Gerais:

Fechar outros programas quando for rodar os códigos, para que não haja interferência nos tempos de execução.  
Se estiver utilizando um notebook ao executar, certificar-se de que não entre em modo de economia de energia (executar com o carregador conectado).  
Realização individual.

Introdução:

Utilizaremos a WSL (Windows Subsystem for Linux) vinculada ao VSCode para a execução dos códigos.  
Primeiro precisamos garantir que a WSL estava instalada adequadamente. Pode-se utilizar tanto o Powershell quando o Prompt de Comando (cmd), no projeto utilizei o Prompt por questão de comodidade mesmo.  
Execute o comando 'wsl --install' (sem aspas simples), a WSL possui várias distribuições (para ver as outras distribuições disponíveis execute o comando 'wsl --list --online' e caso queira instalar outra distribuição execute o comando 'wsl --install -d <NomeDaDistribuição>'), porém utilizaremos a padrão do Ubuntu. 
