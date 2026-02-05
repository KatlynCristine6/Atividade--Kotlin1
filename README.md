
# Atividades 

1-

fun main() {
    
    var entrada_celsius = 30
    
    //F = C * 9/5 + 32
    var F = entrada_celsius * 9 / 5 + 32
    
    print(F)
}

2- 


fun main() {
    
    var entrada_Fahrenheit = 77
    
    //C = (F - 32) * 5/9 
    var celsius = (entrada_Fahrenheit - 32) * 5 / 9.0
    
    print(celsius)
}

3-

fun main() {
    
    var raio_base = 5
    var altura = 10
    
    // V = π * raio^2 * altura
    var Volume = Math.PI * raio_base* raio_base * altura
    
    print(Volume)
}

4-

fun main() {
    
    var distância_percorrida = 240
    var consumo_veículo = 12
    
    // litros = distância / consumo
    var litros = distância_percorrida / consumo_veículo 
    
    println(" A quantidade de combustível gasta na viagem é de: $litros")
}

5-

fun main() {
    
    var valor_original_prestação = 1500
    var número_meses_atraso = 5
    var taxa_juros_mensal = 1.0
    
    // valor = valor_original * (1 + (taxa_juros / 100) * meses_atraso)
    var Valor = valor_original_prestação * (1 + (taxa_juros_mensal / 100) * número_meses_atraso)
    
    println("O valor da prestação em atraso é de: $Valor")
}

7- 


fun main() {
    
    var variavel_1 = 1
    var variavel_2 = 2
    var variavel_3 = 3
    var variavel_4 = 4
    
    
    var adição = (variavel_1 + variavel_2 + variavel_3 + variavel_4)
    
    var multiplicação = (variavel_1 * variavel_2 * variavel_3 * variavel_4)
    
    println("O resultado da adição é: $adição")
    
    println("O resultado da multiplicação é: $multiplicação")
}

8- 

fun main() {
    
    var valor_comprimento_caixa = 5
    var valor_largura_caixa = 3
    var valor_altura_caixa = 2
    
    //volume = comprimento * largura * altura
    var volume = valor_comprimento_caixa * valor_largura_caixa * valor_altura_caixa
    
    print(volume)
}

9- 

fun main() {
    
    var entrada_valor_numerico = -3
    
    // o quadrado do número lido
    var saída = entrada_valor_numerico * entrada_valor_numerico
    
    print(saída)
}

10- 

fun main() {
    
    var valor_numerico1 = -3
    var valor_numerico2 = 8
   
    
    var subtração = (valor_numerico1 - valor_numerico2)
    
    
    println("O resultado da subtração é: $subtração")
    
}

11-

fun main() {
    
    var valor_dólar = 50
    
    var valor_real = (valor_dólar * 5.60)
    
    
    print(valor_real)
    println(" valor em real, considerando a cotação de 5.60")

    
}

12- 

fun main() {
    
    var valor_real = 100
    
    var valor_dólar = (valor_real / 5.60)
    
    
    print(valor_dólar)
    println(" valor em dólar, considerando a cotação de 5.60")

}

13-


fun main() {
    
    var valor_númerico1 = 1
    var valor_númerico2 = 5
    var valor_númerico3 = 6
    
    var soma_dos_quadrados = (valor_númerico1 * valor_númerico1) + (valor_númerico2 * valor_númerico2)  + (valor_númerico3 * valor_númerico3)
    

    print(soma_dos_quadrados)
  

    
}

14-

fun main() {
    
    var valor_númerico1 = 2
    var valor_númerico2 = 3
    var valor_númerico3 = 4
    
    var soma_dos_valores = (valor_númerico1 + valor_númerico2 + valor_númerico3)
    
    var resultado = (soma_dos_valores * soma_dos_valores)
    

    print(resultado)
  

    
}

15-

fun main() {
    
    var valor_1 = 2
    var valor_2 = 3
    var valor_3 = 4
    var valor_4 = 5
    
    var produto = (valor_1 * valor_3)
    
    var soma = (valor_2 + valor_4)
    

    println("Produto é igual: $produto, Soma é igual: $soma")
   
}

16-

fun main() {
    
    var salario_mensal = 1000.0
    var porcentagem_aumento = 10.0
    
    // Calcule o valor do aumento usando a fórmula
    var aumento = salario_mensal * (porcentagem_aumento / 100)
    
    var novo_salario = (salario_mensal + aumento)
    

    print(novo_salario)
   
}

17-


fun main() {
    
    var raio_circunferência = 5
    
    // Calcule a área da circunferência usando a fórmula
    var area = 3.141 * raio_circunferência * raio_circunferência

    print(area)
    println("(área calculada)")
}

18- 

fun main() {
    
    var candidato_1 = 200
    var candidato_2 = 150
    var candidato_3 = 100
    var votos_nulos = 50
    var votos_em_branco = 30
    
    
    var total_eleitores = candidato_1 + candidato_2 + candidato_3 + votos_nulos + votos_em_branco
    
    println("O total de eleitores é de: $total_eleitores")
    
    println("Percentual de votos válidos:")
    var percentual_candidato1 = (candidato_1 * 100.0) / total_eleitores
    var percentual_candidato2 = ( candidato_2 * 100.0) / total_eleitores
    var percentual_candidato3 = ( candidato_3 * 100.0) / total_eleitores
    var percentual_nulos = (votos_nulos * 100.0) / total_eleitores
    var percentual_branco = (votos_em_branco * 100.0) / total_eleitores
    
    println("candidato 1 = %.2f%%".format(percentual_candidato1))
    println("candidato 2 = %.2f%%".format(percentual_candidato2))
    println("candidato 3 = %.2f%%".format(percentual_candidato3))
    println("Percentual de votos nulos = %.2f%%".format(percentual_nulos))
    println("Percentual de votos em branco = %.2f%%".format(percentual_branco))
}

19-

fun main() {
    
    var valor_1 = 10
    var valor_2 = 5
    
    
    var adição = (valor_1 + valor_2)
    
    println("Adição: $valor_1 + $valor_2 = ${valor_1 + valor_2}")
    
    var subtração = (valor_1 - valor_2)
    
    println("subtração: $valor_1 - $valor_2 = ${valor_1 - valor_2}")
    
    var multiplicação = (valor_1 * valor_2)
    
    println("multiplicação: $valor_1 * $valor_2 = ${valor_1 * valor_2}")
    
    var divisão = (valor_1 / valor_2)
    
    println("divisão: $valor_1 / $valor_2 = ${valor_1 / valor_2}");
}

26-

fun main() {
    var valor_númerico1 = 10
    var valor_númerico2 = 2
    
    //Calcule a divisão do primeiro número pelo segundo número.
    var resultado_divisão = valor_númerico1 / valor_númerico2 
    
    //Calcule o quadrado do resultado da divisão.
    var resultado_quadrado = resultado_divisão * resultado_divisão
    
    print(resultado_quadrado)
    println ("($valor_númerico1 / $valor_númerico2 = $resultado_divisão, $resultado_divisão * $resultado_divisão = $resultado_quadrado)")

}
