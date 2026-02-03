# Atividade Kotlin 💻
Exercícios sobre Kotlin 

## Exercício 1 - Conversor de Temperatura ☀️ Celsius
```
fun main(){
	var celsius = 29.0
    var temp= celsius * 9/5 + 32 
    print(temp)
}
```

## Exercício 2 - Conversor de Temperatura 🌥️ Fahrenheit
```
fun main(){
	var fahrenheit = 212
    var celsius = (fahrenheit - 32) * 5/9 
    print(celsius)
}
```

## Exercício 3 - Volume 🛢️
```
fun main(){
	var raio = 5.0
    var altura = 10.0
   	val volume = 3.14 * (Math.pow(raio,2.0) * altura) //pow = elevado
    
    print(volume)
}
```

## Exercício 4 - Combustível ⛽
```
fun main(){
	var distancia = 10.0
    var consumo = 2.0
    
    var litrosGastos = distancia/consumo
    print(litrosGastos)
}
```

## Exercício 5 - Prestação em Atraso 💵
```
fun main(){
	val valor_Original = 500.0
    val meses_atraso = 2.0
    val taxa_juros = 2.0
    
    val valor = (valor_Original * (1.0 + (taxa_juros/100.0) * meses_atraso))
    print(valor)
}
```

## Exercício 6 - Troca de Valores 🔃
```
fun main(){
	var A = 5
    var B = 10
    
    val troca = A
    A = B
    B = troca
    print("A: $A, B: $B")
}
```

## Exercício 7 - Adição e Multiplicação ➕✖️
```
fun main(){
	val N1 = 1
    val N2 = 2
    val N3 = 3
    val N4 = 4
    
    //Adição
    val R12 = N1 + N2
    val R13 = N1 + N3
    val R14 = N1 + N4
    val R23 = N2 + N3
    val R24 = N2 + N4
    val R34 = N3 + N4
    
    //Multiplicação
    val R21 = N1 * N2
   	val R31 = N1 * N3
    val R41 = N1 * N4
    val R32 = N2 * N3
    val R42 = N2 * N4
    val R43 = N3 * N4
    
    println("Adições: $N1 + $N2 = $R12, $N1 + $N3 = $R13, $N1 + $N4 = $R14, $N2 + $N3 = $R23, $N2 + $N4 = $R24, $N3 + $N4 = $R34")
    print("Multiplicações: $N1 * $N2 = $R21, $N1 * $N3 = $R31, $N1 * $N4 = $R41, $N2 * $N3 = $R32, $N2 * $N4 = $R42, $N3 * $N4 = $R43")
}
```

## Exercício 8 - Volume da Caixa Retangular 📦
```
fun main(){
	val comprimento = 4
    val largura = 6
    val altura = 2
    
    val volume = comprimento * largura * altura
    print(volume)
}
```

## Exercício 9 - Quadrado de um Número Inteiro ✴️
```
fun main(){
	val n1 = -3
    
    val quadrado = n1 * n1
    print(quadrado)
}
```

## Exercício 10 - Diferença de Números Inteiros ➖
```
fun main(){
	val n1 = -3
    val n2 = 8
    
    val diferenca = n1 - n2
    print("$diferenca ($n1 - $n2)")
}
```

## Exercício 11 - Dólar para Real 💸
```
fun main(){
	val dolar = 50.0
    
    val real = dolar * 5.24 //cotação dólar atualmente
    print(real)
}
```

## Exercício 12 - Real para Dólar 💲
```
fun main(){
	val real = 100.0
    
    val dolar = real/5.24
    print(dolar)
}
```

## Exercício 13 - Soma dos Quadrados de 3 Números ➕
```
fun main(){
	val n1 = 2
    val n2 = 3
    val n3 = 4
    
    val quad1 = n1 * n1
    val quad2 = n2 * n2
    val quad3 = n3 * n3
    
    val soma = quad1 + quad2 + quad3
   	print("$soma ($n1² + $n2² + $n3² = $quad1 + $quad2 + $quad3 = $soma)")
}
```

## Exercício 14 - Quadrado da Soma de 3 Números ✳️
```
fun main(){
	val n1 = 2
    val n2 = 3
    val n3 = 4
    
    val soma = n1 + n2 + n3
    val quadrado = soma * soma
   	print("$quadrado (($n1 + $n2 + $n3)² = $soma² = $quadrado)")
}
```

## Exercício 15 - Produto e Soma de 4 Números ✖️➕
```
fun main(){
	val n1 = -1
    val n2 = 8
    val n3 = 0
    val n4 = 2
    
    val produto = n1 * n3
    val soma = n2 + n4
    
    print("Produto: $produto($n1 * $n3), Soma: $soma($n2 + $n4)")
}
```
