# desafio1
Desafio 1 do curso DIO de temperatura linguagem GO


package main

import "fmt"

const ebulicaoK float64 = 273.0

func main()  {

	tempK := ebulicaoK
	tempC := tempK - 273.0

	fmt.Printf("A temperatura de ebulição da água em K é = %g e temperatura de ebulição da água em C = %g ", tempK, tempC)
	
}
