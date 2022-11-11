# Programa em Go para Conversão de Escalas Termometricas
Descrição do Desafio:  
Um professor de ensino medio solicitou aos seus alunos que desenvolvessem um programa para converter o valor do ponto de ebulição da água de Kelvin para Graus Celsius.

Dica: C = K - 273



// declarar meu pacote principal
package main

//importar função fmt
import "fmt"

//declaração da variável CONST do ponto de ebulição da água em F
const ebulicaoK = 373.0

//função principal
func main() {

	tempk := ebulicaoK
	tempC := tempk - 273.0

	fmt.Printf("A temperatura de Ebulição da água em K = %g , e a Temperatura de Ebulição da água  em °C = %g", tempk, tempC)

}

