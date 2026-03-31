# nomes-invertidos📌 Projeto: Inverter Nome em C#
🧠 Descrição

Este programa em C# tem como objetivo ler quatro nomes digitados pelo usuário e exibi-los na ordem inversa.

Ele utiliza variáveis auxiliares para realizar a troca de posições dos nomes, funcionando como um pequeno “espelho lógico” 🪞 que inverte a sequência informada.

⚙️ Funcionamento
O programa solicita ao usuário a digitação de 4 nomes.
Os nomes são armazenados em variáveis (nome1, nome2, nome3, nome4).
Um mecanismo de troca (usando a variável auxiliar) inverte a ordem:
nome1 troca com nome4
nome2 troca com nome3
Os nomes são exibidos já invertidos no console.
🧩 Estrutura do Código
Console.Write() → Exibe mensagens para o usuário
Console.ReadLine() → Captura os nomes digitados
Variável auxiliar → Usada para fazer a troca dos valores
Console.WriteLine() → Mostra o resultado final
Console.ReadKey() → Mantém o console aberto até o usuário pressionar uma tecla
🔄 Exemplo de Execução
Entrada:
Digite o nome#1: João
Digite o nome#2: Maria
Digite o nome#3: Pedro
Digite o nome#4: Ana
Saída:
Nomes inseridos na sequência Invertida:
Ana
Pedro
Maria
João
💡 Lógica Utilizada

A inversão é feita manualmente com trocas:

nome1 ↔ nome4
nome2 ↔ nome3

Como se os nomes estivessem em fila e alguém virasse a fila de ponta-cabeça 🔄
