# Kotlin
Programa capaz de ler três números inteiros que representam os lados de um triângulo


fun quadrado() {
    print("Informe o lado 1: ")
    val lado1 = readLine()

    print("Informe o lado 2: ")
    val lado2 = readLine()

    if (lado1 != null && lado1 != "" && lado2 != null && lado2 != "") {
        val x = lado1.toInt()
        val y = lado2.toInt()

        if (x == y) {
            println("É um quadrado.")
        } else {
            println("Não é um quadrado.")
        }
    }
}

fun main() {
    quadrado()

}
