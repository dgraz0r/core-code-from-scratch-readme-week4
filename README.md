# core-code-from-scratch-readme-week4

## AVERAGE SALE AND COMMISSION

Algoritmo Sales
	
	Escribir "Ingrese el numero de ventas realizadas: "
	Leer ventas
	Total = 0
	Para cont<-1 Hasta ventas Con Paso 1 Hacer
		Escribir "Ingrese el valor de la venta: ", ConvertirATexto(cont)
		Leer valorventa
		Total <- total + valorventa
	Fin Para
	Avg <- total/ventas
	Escribir "La venta promedio fue por un valor de: ", ConvertirATexto(Avg)
	
	Si ventas >= 5 Entonces
		com15 <- Total * 0.15
		Escribir "La comision para el vendedor es de: ", ConvertirATexto(com15)
	SiNo
		com10 <- Total * 0.10
		Escribir "La comision para el vendedor es de: ", ConvertirATexto(com10)
	Fin Si
	
FinAlgoritmo


## EVEN OR ODD

Algoritmo EvenOdd

	Repetir
		Escribir "Ingrese un numero entre 1 y 50"
		Leer num
		Si num >= 1 & num <= 50 Entonces
			Si num % 2 = 0 Entonces
				par = 0
				Para i=0 Hasta num Con Paso (par + 2) Hacer
					Escribir ConvertirATexto(i)
				Fin Para
			SiNo
				impar = 1
				Para i=1 Hasta num Con Paso (impar + 2) Hacer
					Escribir ConvertirATexto(i)
				Fin Para
			Fin Si
		SiNo
			Escribir "Numero invalido"
		Fin Si
	Mientras Que num < 1 | num > 50
	
FinAlgoritmo


## FULL NAME

Algoritmo nombre

	Escribir "Ingrese su primer nombre"
	Leer nom
	Escribir "Ingrese su apellido"
	leer ape
	name = Mayusculas(Subcadena(nom,0,0)) + Minusculas(Subcadena(nom,1,Longitud(nom)-1))
	apellido = Mayusculas(Subcadena(ape,0,0)) + Minusculas(Subcadena(ape,1,Longitud(ape)-1))
	Escribir name, " " , apellido
	
FinAlgoritmo


