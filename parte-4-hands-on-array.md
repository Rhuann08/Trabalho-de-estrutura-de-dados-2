# Parte 4 — Hands On 1: Investigação do Array

*Responsável: Rhuann Pabllo Ferreira Magalhães - RGM: 45157782<img width="1042" height="504" alt="teste 3" src="https://github.com/user-attachments/assets/49f6b34e-20e7-4c31-a3eb-90864dbf6507" />
<img width="1025" height="459" alt="array teste 2" src="https://github.com/user-attachments/assets/dbc333e0-34f4-4211-bffa-f128bec6078b" />
<img width="821" height="499" alt="array tste 1" src="https://github.com/user-attachments/assets/98a89329-330b-4031-92e6-57b8b54be1ed" />
*

**Quantidade de operações de percurso do array:**
O vetor de 10 posições foi percorrido em 4 blocos separados, para ficar mais fácil de codar: um `for` para preencher (10 leituras), outro para mostrar na tela (10 impressões), mais um para somar e achar o maior e o menor (mais 10 acessos) e o último para ver quem estava acima da média (outros 10). No fim das contas, deu um total de umas 40 operações de percurso.

**Complexidade do algoritmo desenvolvido:**
O(n), linear pura. Mesmo com vários `for` no código, eles ficam soltos, um depois do outro, sem loop dentro de loop. Então o tempo de execução sobe de forma direta conforme o tamanho do vetor cresce.

---

## 💬 Comentários

Nesse trecho eu entendi que mesmo tendo vários for no programa, eles não deixam o algoritmo muito mais pesado porque são executados um depois do outro. Como cada um percorre o vetor uma vez, a quantidade de operações aumenta de acordo com o tamanho do vetor. Por isso a complexidade continua sendo O(n), ou seja, linear.
