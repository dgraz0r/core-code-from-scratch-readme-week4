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

