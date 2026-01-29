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
