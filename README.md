# parcialtercercorteparalela

Universidad: Sergio Arboleda Programa: Ingeniería de Sistemas y Telecomunicaciones Autores: Maria Paula Parra

Comparación de rendimiento entre Python y Cython con Fibonacci

add Codeadd Markdown
En el siguiente trabajo se realizó una comparación entre los lenguajes de programación Python y Cython. Para ello, se realizó una serie de pruebas con el conocido algoritmo de Fibonacci, la serie de Fibonacci es una de las secuencias de números más famosas de la historia. Le llaman "el código secreto de la naturaleza" o la "secuencia divina", porque aparece una y otra vez en estructuras naturales, como los pétalos de un girasol o la cáscara de una piña. Este algoritmo se pudo evidenciar en Cython y python para mostrar el rendimiento de cada uno de los lenguajes de programación anteriormente mencionados

add Codeadd Markdown
¿Qué es Cython?

Cython pretende ser el superconjunto del lenguaje de programación Python. Está diseñado para ofrecer un rendimiento similar al de C junto con códigos escritos principalmente en el lenguaje Python que permiten una sintaxis adicional inspirada en C. Cuando Cython se compila, ofrece módulos de extensión CPython. Proporciona una menor sobrecarga computacional que Python en tiempo de ejecución. Los códigos C y C++ pueden ser envueltos en los módulos de Cython. Cython depende del intérprete y la biblioteca estándar de Python. Cython emplea optimizaciones optimistas, inferencia de tipos opcional, baja sobrecarga de estructuras de control y baja sobrecarga de llamadas a funciones. Su rendimiento depende de la generación e implementación de los códigos C. El lenguaje de programación Cython se parece mucho a Python con muy pocas diferencias. Para entender esto, tomemos, por ejemplo, el código de Python y su correspondiente código de Cython.

add Codeadd Markdown
¿Qué es Python?

Python es un lenguaje de programación de alto nivel, de propósito general y muy popular. El lenguaje de programación Python se utiliza en el desarrollo web, aplicaciones de aprendizaje automático, junto con toda la tecnología de vanguardia en la industria del software. El lenguaje de programación Python es muy adecuado para principiantes, también para programadores experimentados con otros lenguajes de programación como C++ y Java.

add Codeadd Markdown
¿Que es una serie de fibonacci?

La Sucesión o Algoritmo de Fibonacci se caracteriza por el hecho de que cada número en ella es igual a la suma de los anteriores:

0, 1, 1, 2, 3, 5, 8, 13, 21…..

Es decir que:

(0+1=1 / 1+1=2 / 1+2=3 / 2+3=5 / 3+5=8 / 5+8=13 / 8+13=21 / 13+21=34…)

Así sucesivamente, hasta el infinito. Por regla, la sucesión de Fibonacci se escribe así:

n = n-1 + n-2.


