# AWS-AutoScaling

### Ingresar a AWS console, en los servicios buscar AWS Auto Scaling.

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/1.png)

### Dar click en Get Started donde se encuentran las siguientes opciones.

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/2.png)

### Encontramos que existe una opción utilizando una instancia EC2 que procederemos a crear, nos dirigimos al servicio de EC2 y seleccionamos plantillas de lanzamiento y damos click en crear plantilla de lanzamiento.

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/3.png)

### Llenaremos el formulario de la siguiente manera.

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/4.png)

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/5.png)

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/6.png)

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/7.png)

### Ahora una vez creada la instancia debemos crear un grupo de esclamiento que sera donde definiremos la configuracion y en donde se generaran las nuevas instancias cuando sea necesario.

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/8.png)

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/9.png)

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/10.png)

### Seleccionaremos en la subnet los lugares en donde queremos que se lancen las instancias cuando la demanda se encuentre utilizando el 70% de la principal

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/11.png)

### Seleccionamos el numero de instancias que queremos crear en los momentos determinados y adicionalmente el maximo de instancias que le permitiremos crear automaticamente.

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/12.png)

### Podemos configurar que AWS nos avise cuando esta sucediendo el proceso de iniciar nuevas instancias para poder conocer el estado de las instancias.

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/13.png)

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/14.png)

### Debido a que es una cuenta de AWS Educate esta restringirida para la creacion de grupos de escalamiento.

![](https://github.com/CAndresRa/AWS-AutoScaling/blob/master/Img/15.png)
