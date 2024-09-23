# recursividad

fun numerosDesc(n: Int) {
    if (n <= 0) {
        return
    }
    println(n)
    numerosDesc(n - 1)
}

fun main() {
    val num = 5 // Corregido: usar '=' en lugar de '-'
    numerosDesc(num)
}
