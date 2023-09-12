Este código de Python busca e imprime todos los números primos en el rango del 0 al 9999 y mide el tiempo que lleva hacerlo.
import time
inicio = time.time()

for i in range(0,10000):
    conta = 0
    for n in range(1, i+1):
        residue = i%n
        if residue == 0:
            conta = conta + 1
              
    if conta == 2:
        print(f'{i} es un primo')
        
        
fin = time.time()
print("t = ", (fin - inicio)*1000)
