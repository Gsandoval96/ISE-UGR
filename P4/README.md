# Práctica 4. Benchmarking y Ajuste del Sistema
Realizada Guillermo Sandoval Schmidt.

## Objetivos
+ Conocer varios benchmarks para diferentes servicios.
+ Saber comparar distintas configuraciones (o implementaciones) de servicios en base
a benchmarks.
+ Aplicar un test de carga a una aplicación basada en microservicios.
+ Conocer y saber cómo modificar el valor algunos parámetros que pueden mejorar
las prestaciones.

# Notas

## Phoronix

### Anfitrión

Nos decargamos el paquete desde:

https://www.phoronix-test-suite.com/

Para instalarlo ejecutamos:

`sudo dpkg -i phoronix-test-suite_9.0.1_all.deb `

Podemos ejecutar un benchmark (en este caso smallpt):

`phoronix-test-suite benchmark smallpt`

### Ubuntu

~~~
wget https://phoronix-test-suite.com/releases/phoronix-test-suite-9.0.1.tar.gz

tar xvf phoronix-test-suite-9.0.1.tar.gz

cd phoronix-test-suite/

sudo ./install-sh

~~~

Podemos ejecutar un benchmark (en este caso smallpt):

`phoronix-test-suite benchmark smallpt`

### CentOS

Recordar entrar como root al inciar sesión.

~~~

wget https://phoronix-test-suite.com/releases/phoronix-test-suite-9.0.1.tar.gz

tar xvf phoronix-test-suite-9.0.1.tar.gz

cd phoronix-test-suite/

./install-sh

~~~

Podemos ejecutar un benchmark (en este caso smallpt):

`phoronix-test-suite benchmark smallpt`

### Bibliografía

+ https://www.phoronix-test-suite.com/
+ https://openbenchmarking.org/test/pts/smallpt

---

[![Creative Commons License][image-1]][1]  
This work is licensed under a [Creative Commons Attribution 4.0 Unported License][1].

[1]:    http://creativecommons.org/licenses/by/4.0/deed.en_US

[image-1]:    http://i.creativecommons.org/l/by/4.0/80x15.png

Guillermo Sandoval Schmidt
