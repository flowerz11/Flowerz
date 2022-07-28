[regresar](miercoles.md)
# Ejercicio MIPS

## Ayuda
1. [Toma en cuenta esto](https://www.schoolcoders.com/data-representation/binary/powers-of-two/)
2. [Más información sobre binario](https://www.youtube.com/watch?v=LpuPe81bc2w)
3. [Aprende a convertir un número decimal a un número binario](https://www.youtube.com/watch?v=LpuPe81bc2w)

## Solucion
1. Cree un programa que agregue dos números proporcionados por el usuario<br>


    """ .assembly<br>
    
        .data
	      number1: .asciiz "\nIngrese el primer numero: "
	      number2: .asciiz "\nIngrese el segundo numero: "
        .text
	      main:
              li $v0, 4
              la $a0, number1
              syscall

              li $v0, 5
              syscall

              move $t0, $v0

              li $v0, 4
              la $a0, number2
              syscall

              li $v0, 5
              syscall

              move $t1, $v0

              li $v0, 1
              move $a0, $t0
              syscall
              
              li $v0, 1
              move $a0, $t1
              syscall
        """
2. Crea un programa que muestre tu nombre<br>


    """ .assembly<br>

        .data
            message: .asciiz "\nHello, World!\n"
            message1: .asciiz "\nSAMUEL\n"
        .text
             main:

              li $v0, 4
              la $a0, message
              syscall
              
              li $v1, 5
              la $a0, message1
              syscall
        """