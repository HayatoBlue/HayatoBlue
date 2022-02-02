E aí pessoal,
Estou entrando de cabeça nos estudos de logica da programação.
Vou começar a usar para ir me acostumando.



primeiro codigo, atividade do BeeCrowd: 1012


def area_t_ret(a, c):
    return a * c / 2

def area_circulo(c):
    return 3.14159 * c ** 2

def area_trapezio(a, b, c):
    return (a + b) / 2 * c

def main():
    x = input().split(" ")
    a = float(x [0])
    b = float(x [1])
    c = float(x [2])
    primeira_area = area_t_ret(a, c)
    segunda_area = area_circulo(c)
    terceira_area = area_trapezio(a, b, c)
    area_quadrado = b ** 2
    area_retangulo = a * b
    print(f"TRIANGULO: {primeira_area:.3f}\nCIRCULO: {segunda_area:.3f}\nTRAPEZIO: {terceira_area:.3f}\nQUADRADO: {area_quadrado:.3f}\nRETANGULO: {area_retangulo:.3f}")


main()
