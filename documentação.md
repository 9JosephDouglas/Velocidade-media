# Cálculo da Velocidade Média

Este programa em Python tem como objetivo calcular a **velocidade média** com base na variação de espaço e tempo fornecida pelo usuário.

---

## Funcionamento do Programa

O programa realiza os seguintes passos:
1. Solicita ao usuário a variação de espaço (`s`) em metros.
2. Solicita ao usuário a variação de tempo (`t`) em segundos.
3. Calcula a velocidade média utilizando a fórmula:

   

\[
   V_m = \frac{s}{t}
   \]



4. Exibe o resultado da velocidade média em:
   - Metros por segundo (m/s).
   - Quilômetros por hora (km/h).

---

## Código Completo

```python
s = float(input("Digite o valor da variação de espaço:")) 
t= float(input("Digite o valor de variação de tempo:")) 
Vm = s/t

print(f"A velocidade media é:{Vm}m/s")  
print(f"A velocidade media é:{Vm * 3.6}km/h")
