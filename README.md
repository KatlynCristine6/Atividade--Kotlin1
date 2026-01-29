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
    
    print(litros)
}

5-

fun main() {
    
    var valor_original_prestação = 1500
    var número_meses_atraso = 5
    var taxa_juros_mensal = 1.0
    
    // valor = valor_original * (1 + (taxa_juros / 100) * meses_atraso)
    var Valor = valor_original_prestação * (1 + (taxa_juros_mensal / 100) * número_meses_atraso)
    
    print(Valor)
}
