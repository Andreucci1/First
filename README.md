1-programa em Python
      def pertence_fibonacci(numero):
        fibonacci = [0, 1]
        while fibonacci[-1] < numero:
        fibonacci.append(fibonacci[-1] + fibonacci[-2])
        if numero in fibonacci:
        return f"O número {numero} pertence à sequência de Fibonacci."
        else:
        return f"O número {numero} NÃO pertence à sequência de Fibonacci."
2-programa em Python
       def verificar_letra_a(texto):
           texto_lower = texto.lower()
           ocorrencias = texto_lower.count('a')
           if ocorrencias > 0:
           return f"A letra 'a' ocorre {ocorrencias} vez(es) no texto."
           else:
           return "A letra 'a' não foi encontrada no texto."
 3- Nao consegui resolver
 
 4- Descubra a lógica e complete o próximo elemento:
a) 1, 3, 5, 7, ___
Diferença entre os números é sempre 2.
Resposta: 9

b) 2, 4, 8, 16, 32, 64, ____
Cada número é o dobro do anterior
Resposta: 128

c) 0, 1, 4, 9, 16, 25, 36, ____
Essa sequência representa os quadrados de números inteiros: 
Resposta: 49

d) 4, 16, 36, 64, ____
 quadrados dos números pares consecutivos
 Resposta: 100

e) 1, 1, 2, 3, 5, 8, ____
Essa é a famosa sequência de Fibonacci, onde cada número é a soma dos dois anteriores
Resposta: 13

f) 2,10, 12, 16, 17, 18, 19, ____
Nao entendi

5-Liga o primeiro e o segundo interruptor por 5 minutos.
Desligue o segundo interruptor e deixe o primeiro ligado.
Vá até a sala das lâmpadas:
A lâmpada acesa - primeiro interruptor.
A lâmpada apagada, mas quente - segundo interruptor.
A lâmpada apagada e fria - terceiro interruptor.

