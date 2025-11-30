# Projeto CPU MIGS (8-bits)

## Resumo do Projeto
O projeto *MIGS* consiste no desenvolvimento e simulação de um processador de *8 bits* com arquitetura customizada baseada em princípios RISC. Implementado no ambiente *Logisim, o sistema adota a **Arquitetura Harvard*, separando fisicamente a memória de instruções (ROM de 12 bits) da memória de dados (RAM de 8 bits).

A CPU é composta por uma Unidade de Controle dedicada para decodificação de instruções, um Banco de Registradores com leitura dupla para operações aritméticas eficientes e uma ULA (Unidade Lógica e Aritmética) modular capaz de executar operações de soma, subtração, multiplicação, divisão e lógica booleana. O projeto visa demonstrar o fluxo de dados (datapath) e sinais de controle em um ambiente de organização de computadores.

---

## Integrantes do Grupo

| Nome Completo | R.A. |
| :--- | :--- |
| *Alex Saifi de Souza* | 081230025 |
| *Felipe de Carvalho* | 081230026 |
| *Júlio César Caberlino Ferro* | 081230003 |
| *Matheus Mitsuo Sato Silva* | 081230046 |
| *Nicolas Gomes Lima* | 081230048 |

---
## Instruções para execução do circuito
1. Abra o arquivo "CPU_MIGS.circ" no software Logsim Evolution
2. Verifique se todos os subcircuitos (Banco de Registradores, ULA, Unidade de Controle e Registrador) estão carregados corretamente.
3. Execute o circuito principal ("main") e pressione o botão de clock para iniciar a simulação
4. Observe o fluxo de dados entre os módulos e a execução das instruções armazenadas na memória
5. É possível alterar o conteúdo da memória ram com o nome de IR (Registro de instruções) para testar diferente instruções no MIGS (as intruções devem estar em hexadecimal, e devem respeitar as conexões realizadas entre a unidade de controle e os demais componentes).
---

## Link para o vídeo explicativo

https://youtu.be/Bs8rr8cL2Bg

---

### Estrutura dos Arquivos
* CPU_MIGS.circ: Arquivo fonte do circuito no Logisim.
* Documentacao_Tecnica.pdf: Detalhamento da arquitetura, diagrama de blocos e decisões de projeto.
