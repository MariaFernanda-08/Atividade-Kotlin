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

## Exercício 16 - Novo Salário com Aumento 💹
```
fun main(){
	val salario = 1000.0
    val porcentagem = 10.0
    
    val aumento = salario * (porcentagem/100.0)
    val novo = salario + aumento
    
    print("Novo salário: $novo, Aumento: $aumento")
}
```

## Exercício 17 - Área de uma Circunferência ⭕
```
fun main(){
	val raio = 5.00
    
    val area = 3.14 * raio * raio
    print(area)
}
```

## Exercício 19 - Cálculo das 4 Operações Básicas
```
fun main(){
	val n1 = -15
    val n2 = 3
    
    val soma = n1 + n2
    val subtracao = n1 - n2
    val multiplicacao = n1 * n2
    val divisao = n1/n2
    
    println("Adição: $n1 + $n2 = $soma")
    println("Subtração: $n1 - $n2 = $subtracao")
    println("Multiplicação: $n1 * $n2 = $multiplicacao")
    print("Divisão: $n1/$n2 = $divisao")
}
```

## Exercício 20 - Velocidade de um Projétil 🚀
```
fun main(){
	val distancia = 200.0
    val tempo = 4.0
    
    val km = distancia/tempo
    val velocidade = km/3.6
    print("Velocidade: $velocidade m/s")
}
```

## Exercício 21 - Potência ⬆️
```
fun main(){
	val base = -3.0
    val expoente = 4.0
    
    val resultado = Math.pow(base,expoente)
    print(resultado)
}
```

## Exercício 22 - Volume de uma Esfera 🌎
```
fun main(){
	val raio = 5.00
    
    val volume = (4.0/3.0) * 3.14 * Math.pow(raio,3.0)
    print(volume)
}
```

## Exercício 23 - Pés para Metros 👣
```
fun main(){
	val pes = 10.0
    
    val metros = pes * 0.3048
    print(metros)
}
```

## Exercício 24 - Cálculo de Raiz ✅
```
fun main(){
	val base = 16.0
    val indice = 2.0
    
    val raiz = Math.pow(base,1.0/indice)
    print(raiz)
}
```

## Exercício 25 - Sucessor e Antecessor ➡️⬅️
```
fun main(){
	val numero = -3
   	
    val sucessor = numero + 1
    val antecessor = numero - 1
    
    print("Sucessor: $sucessor, Antecessor: $antecessor")
}
```

## Exercício 26 - Quadrado da Divisão ➗
```
fun main(){
	val n1 = 10.0
    val n2 = 2.0
    
    val resultado_divisao = n1/n2
    val resultadoQuadrado = resultado_divisao * resultado_divisao
    print(resultadoQuadrado)
}
```

## Exercício 27 - Diferença ➖
```
fun main(){
	val n1 = 10.0
    val n2 = 5.0
    val diferenca:Double
    
    if (n1 > n2){
		diferenca = n1 - n2
    } else{
		diferenca = n2 - n1
    }
    
    print(diferenca)
}
```

## Exercício 28 - Positivo, Negativo ou Neutro 🔢
```
fun main(){
	val numero = 0
   	
    if (numero > 0) {
		print("Positivo")
    } else if (numero < 0){
		print("Negativo")
   	} else{
		print("Neutro")
    }
}
```

## Exercício 29 - Média das Notas 🧾
```
fun main(){
	val nota1 = 8.0
    val nota2 = 7.0
    val nota3 = 6.0
    val nota4 = 8.0
    
    val media = (nota1 + nota2 + nota3 + nota4)/4
    if (media >= 5){
		print("Média: $media, Aprovado!")
    } else{
		print("Média: $media, Reprovado")
    }
}
```

## Exercício 30 - Média das Notas com Verificação 📝
```
fun main(){
	val nota1 = 3.0
    val nota2 = 4.0
    val nota3 = 5.0
    val nota4 = 6.0
    
    val media = (nota1 + nota2 + nota3 + nota4)/4
    if (media > 7){
		print("Média: $media, Aprovado!")
    } else if (media >= 5){
       	print("Média: $media, Exame.")
    } else{
		print("Média: $media, Reprovado")
    }
}
```

## Exercício 32 - Ordenação de 3 Números Inteiros 3️⃣
```
fun main(){
	var n1 = 5
    var n2 = 2
    var n3 = 7
    var temp:Int
    
    if (n1 > n2){
		temp = n1
        n1 = n2
        n2 = temp
    } else if(n1 > n3){
		temp = n1
        n1 = n3
        n3 = temp
    } else if(n2 > n3){
		temp = n2
        n2 = n3
        n3 = temp
    } else{
		print("Erro")
    }
    
    print("$n1, $n2, $n3")
}
```
