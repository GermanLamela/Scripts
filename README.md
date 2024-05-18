



![Portada](image.png)

## Índice

1. [Ejercicio 1](#enunciado-ejercicio-1)
2. [Ejercicio 2](#enunciado-ejercicio-2)
3. [Ejercicio 3](#enunciado-ejercicio-3)
4. [Ejercicio 4](#enunciado-ejercicio-4)
5. [Ejercicio 5](#enunciado-ejercicio-5)
6. [Bibliografía](#bibliografia)
7. [Conclusiones](#conclusiones)

---

## Contenido

### <a name="enunciado-ejercicio-1"></a>Ejercicio 1

#### Enunciado

Realiza un script llamado comprobarApache.sh, que compruebe cada minuto si el 
servicio apache2 está activo (running). 

Si está parado, entonces:

>1.- Introduce una línea: “Error-Apache: Fecha y hora actual” en /root/ApacheError.tmp, 
>donde FechaActual, representa día, mes, año, hora y minuto.

>2.- Reinicia el servicio apache2
>Para comprobarlo, para el servicio. Ejecuta el script en segundo plano y observa si lo 
>reinicia y crea el archivo.

>3.- Además del script, crea una tarea programada, de forma que ese script se ejecute cada 
>6 horas, todos los días. Y si el ordenador está apagado, se debe ejecutar la próxima vez 
>que se inicie, transcurrido cinco minutos.

#### Desarrollo

[Detalle del desarrollo del ejercicio 1, incluyendo problemas encontrados y soluciones propuestas.]

#### Solución final

[Presentación de la solución final del ejercicio 1, acompañada de capturas de pantalla verificando su correcto funcionamiento.]

---

### <a name="enunciado-ejercicio-2"></a>Ejercicio 2

#### Enunciado

Realiza un script llamado usuariosBloqueados.sh, que nos muestre un menú:


  >1.- Usuarios Bloqueados.
  
  >2.- Bloquear un usuario.
  
  >3.- Desbloquear usuario.
  
  >4.- Cerrar sesión usuario
  
  >5.- Salir

  
Cada opción del menú corresponde con una función.

UsuariosBloqueados → nos muestra en pantalla los usuarios (uid>1000 y <2000) que 
tengan la cuenta bloqueada.

BloquearUsuario → Nos pregunta el nombre de un usuario y lo bloqueamos.

DesbloquearUsuario → Nos pregunta el nombre de un usuario y lo desbloqueamos.

CerrarSesion → Nos pregunta el nombre de un usuario, y si el usuario lleva más de 30 
minutos (1800 seg) sin actividad, se le cierra la sesión.


#### Desarrollo

[Detalle del desarrollo del ejercicio 2, incluyendo problemas encontrados y soluciones propuestas.]

#### Solución final

[Presentación de la solución final del ejercicio 2, acompañada de capturas de pantalla verificando su correcto funcionamiento.]

---

### <a name="enunciado-ejercicio-3"></a>Ejercicio 3

#### Enunciado

Realiza un script llamado crearBorrarUsuarios.sh, que nos muestre un menú:

>1.- Crear Usuarios.

>2.- Borrar Usuarios.

>3.- Salir

CrearUsuarios → Crea de forma masiva usuarios almacenados en el fichero 
/root/usuarios.csv

Los campos son los siguientes:

- El campo 1 representa el nombre de usuario.
- El campo 2 representa la contraseña.
- El campo 3 representa el nombre.
- El campo 4 representa su primer apellido.
- El campo 5 representa su correo electrónico.
  
Además, queremos que esas cuentas queden inactivas el 30 de junio de 2024.

BorrarUsuarios → Borra de forma masiva usuarios almacenados en el fichero 
/root/usuarios.csv.

#### Desarrollo

[Detalle del desarrollo del ejercicio 3, incluyendo problemas encontrados y soluciones propuestas.]

#### Solución final

[Presentación de la solución final del ejercicio 3, acompañada de capturas de pantalla verificando su correcto funcionamiento.]

---

### <a name="enunciado-ejercicio-4"></a>Ejercicio 4

#### Enunciado

Crea en un script llamado crearUsuarios.sh que permita crear usuarios de forma 
automática. Indicaciones: 

>1.- Al script se le pasa dos parámetros: 

>>a) El primer parámetro representa el nombre de un usuario genérico.
>>
>>b) El segundo parámetro representa el número de usuarios que quiere crearse.

>2.- A cada usuario se le asigna la contraseña que coincida con el nombre de usuario. 
>3.- Al usuario se le obliga a cambiar de contraseña, cuando se loguee. 
>4.- Se crea un archivo: usuariosCreados-FechaActual.tmp con el nombre de los usuarios 
>creados y la contraseña asignado, separados por “:”. 
>5.- El archivo usuariosCreados-FechaActual.tmp tiene que ser mostrado en pantalla tras 
>la ejecución del script. 

#### Desarrollo

[Detalle del desarrollo del ejercicio 4, incluyendo problemas encontrados y soluciones propuestas.]

#### Solución final

[Presentación de la solución final del ejercicio 4, acompañada de capturas de pantalla verificando su correcto funcionamiento.]

---

### <a name="enunciado-ejercicio-5"></a>Ejercicio 5

#### Enunciado

Partimos de que tenemos varios usuarios: usuario1, usuario2, usuario3.  

Al usuario1, se le ha establecido una cuota de disco: 40k y 100K (soft y hard 
respectivamente).  

Realiza un script llamado cuotasUsuarios.sh, que nos copie la cuota del usuario1 a todos 
los usuarios cuyo uid >1000 y uid<2000.

#### Desarrollo

[Detalle del desarrollo del ejercicio 5, incluyendo problemas encontrados y soluciones propuestas.]

#### Solución final

[Presentación de la solución final del ejercicio 5, acompañada de capturas de pantalla verificando su correcto funcionamiento.]

---

## <a name="bibliografia"></a>Bibliografía

[Referencias bibliográficas utilizadas.]

---

## <a name="conclusiones"></a>Conclusiones

[Conclusiones del trabajo realizado.]

