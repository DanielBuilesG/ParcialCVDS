## Escuela Colombiana de Ingeniería

### PDSW – Procesos de desarrollo de Software
### Parcial Segundo Tercio

### Daniel Builes Gonzalez 

*Primero corremos el codigo usando los comandos 

    ```bash
    $ mvn compile
    ```
    ```bash
    $ mvn tomkat7:run
    ```

![](./img/foto1.png)

*Luego en internet aparece lo siguiente con la direccion http://localhost:8080/faces/consultaPaciente.xhtml

![](./img/foto2.png)

*Para crear la consulta la hacemos en la funcion PacienteMapper.xml en la carpeta resources/mappers

![](./img/foto3.png)

*Luego creamos un metodo que llama a la consulta desde la interfaz PacienteMapper, el metodo tiene como nombre ObtenerPacienteID

![](./img/foto4.png)

*Por ultimo la reflejamos en la clase y en la interfaz MyBatisDAOPaciente y DaoPaciente respectivamente

![](./img/foto5.png)
