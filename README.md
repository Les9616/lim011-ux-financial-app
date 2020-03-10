# Aplicación financiera : Banqui

## Índice
 
* [1. El proyecto](#1-el-proyecto)
* [2. Objetivos iniciales del proyecto](#2-objetivos-iniciales-del-proyecto)
* [3. Implementación](#3-implementación)
* [4. Descubrimiento e investigación](#4-descubrimiento-e-investigación)
* [5. Síntesis](#5-síntesis)
* [6. Definición de la solución](#6-definición-de-la-solución)
* [7. Ideación ](#7-ideación)
* [8. Prototipado](#9-prototipado)
* [9. Recomendaciones de próximos pasos para el banco con respecto a la app](#10-recomendaciones-de-próximos-pasos-para-el-banco-con-respecto-a-la-app)
* [10. Links](#10-Links)

***

## 1. El proyecto

El banco Pichincha, siguiendo las tendencias de otros países, está
planeando lanzar un banco 100% digital bajo otro nombre: "Banqui". Su principal
objetivo es tener un banco que sea más cercano a las necesidades del público más
joven del país. Para ello han venido piloteando un app con un número pequeño de
usuarios. Los resultados de este piloto son mixtos, hay algunas cosas que han
sido bien recibidas por los usuarios, y hay otras que se tienen que mejorar aún.

## 2. Objetivos iniciales del proyecto

- Analizar la data que nos fue brindada.
- Testear el prototipo inicial e identificar los puntos de dolor.
- Rediseñar la aplicación con los hallazgos de la investigación.

## 3. Implementación 

Para iniciar el proyecto se definieron las actividades y herramientas que se utilizarían:
![Tabla de implementación](https://github.com/Les9616/lim011-ux-financial-app/blob/master/entregables.JPG)

## 4. Descubrimiento e investigación
###   Entendimiento del problema, industria y contexto

Según Asbanc, al cierre del 2018 en el Perú, se realizaron 1,187 millones
de transacciones monetarias, cifra superior en 16.98% respecto al 2017. 
Según canal de atención, la banca móvil, internet del comercio (e-commerce) y la banca
por internet han sido los canales con mejor desempeño en el periodo señalado.

![Asbanc](https://github.com/Les9616/lim011-ux-financial-app/blob/master/asbanc.JPG)

Según un reporte de Deloitte, la tecnología móvil ofrece una oportunidad
de crecimiento sin precedentes para la banca en Latinoamérica, ya que a medida que 
las economías de la región siguen prosperando, los consumidores,particularmente los 
no bancarizados podrían generar una demanda de nuevos productos y servicios
financieros. Otro factor que influye positivamente en este escenario es que existe un 
importante porcentaje de la población que tiene un teléfono celular, pero no
cuentas bancarias. Precisamente por esta situación es que el canal móvil proporciona una 
forma efectiva para hacerlos partícipes del mercado de los servicios financieros.

###   Entrevista con el cliente

Durante la primera semana de entendimiento de los requerimientos, se realizó la entrevista 
al cliente y se determinaron los siguientes objetivos:

- Que el usuario se sienta en comodidad de poder acceder a todas las funciones del banco sin
  tener que acercarse a una agencia.
- Validar si la aplicación es lo que esperaba el usuario. 
- Confirmar que funcionalidades prefieren.
- Que el cliente aún conserve esa cercanía con la banca presencial.
- Identificar el Look and feel del producto.

###   Entrevista con usuarios

Se realizaron 5 entrevistas con usuarios y estos fueron los princippales hallazgos:

- Los usuarios buscan seguridad tanto en la aplicación como en el banco al que se afilien.
- Los usuarios se muestran dispuestos a probar nuevas alternativas de servicios financieros
  que les brinden confianza o que sean respalddos por entidades conocidas.
- Los usuarios quieren servicios que les eviten dirigirse a los bancos porque disponen de 
  muy poco tiempo y/o les genera molestia.
- Los usuarios buscan realizar la mayor cantidad de acciones a través de sus aplicaciones 
  bancarias, es por ello que la app debe ser muy intuitiva y clara.
  
### Análisis de la data

De acuerdo a la data de uso del MVP de los primeros 6 meses, estos son los principales hallazgos:

- El número de instalaciones creció en los últimos  meses.
- El uso activo va aumentando progresivamente, esto se debe también al aumento de instalaciones 
  de la aplicación.
- La cantidad de dispositivos activos aumenta cada inicio, quincena o fin de mes.
- El número de sesiones es mayor que los dispositivos activos lo que indicaría que los usuarios 
  ingresan a la app más de una vez.
  
 ![Data](https://github.com/Les9616/lim011-ux-financial-app/blob/master/data.JPG)

## 5. Síntesis

Se realizaron 17 testeos del prototipo actual con Maze.

 ![Misiones](https://github.com/Les9616/lim011-ux-financial-app/blob/master/misiones.JPG)
 
### Affinity map

Se realizó la sintesís de las entrevistas y testeos a través de Miró.

![AM User Persona](https://github.com/Les9616/lim011-ux-financial-app/blob/master/AM%20User%20Persona.PNG)

![AM Banco](https://github.com/Les9616/lim011-ux-financial-app/blob/master/AM%20Banco.PNG)

![AM Banqui](https://github.com/Les9616/lim011-ux-financial-app/blob/master/AM%20Banqui.PNG)

### User Persona

![User Persona](https://github.com/Les9616/lim011-ux-financial-app/blob/master/user%20persona.jpg)

### Costumer Journey Map

![CJM Banqui](https://github.com/Les9616/lim011-ux-financial-app/blob/master/CJM-Banqui.PNG)

## 6. Definición de la solución

### Problem Statements

- Maria necesita tener la certeza de que la app y las operaciones que realiza con ella 
  son seguras para querer utilizarlo.
- Maria necesita poder realizar varias operaciones que se hacen en su banco pero desde 
  su aplicacion de banca movil para querer utilizar la app.
- Maria necesita ahorrar para sus estudios y educación de sus hijos.
- Maria necesita ver el detalle de sus gastos para verificar sus movimientos.
- Maria necesita encontrar sus operaciones mas recurrentes porque no dispone de tiempo.

### How Might We?

- HMW darle seguridad a la aplicacion?
- HMW darle seguridad a las operaciones que se realizan en la app?
- HMW facilitar la ubicación de las operaciones dentro de la app?
- HMW mostrar las operaciones mas recurrentes del usuario en la vista principal?
- HMW ver el detalle de los gastos?
- HMW verificar los movimientos que realiza el usuario?
- HMW crearle el habito del ahorro?
- HMW hacer que ahorrar sea divertido?

### What if

- ¿Que tal si confirmaramos los pagos para que se vean las transacciones seguras?
- ¿Que tal si mostraramos una opcion de operaciones recurrentes?
- ¿Que tal si colocaramos el detalle de sus gastos de una forma mas entendible?
- ¿Que tal si podemos mover los iconos del menú?
- ¿Que tal si puedo hacer transferencias con el número de celular?
- ¿Que tal si puedo ahorrar pequeños montos a plazo fijo?

## Ideación y prototipado

Para la ideación utilizamos la herramienta Crazy8: 

![Crazy8](https://github.com/Les9616/lim011-ux-financial-app/blob/master/crazy8.jpeg) ![Crazy8s](https://github.com/Les9616/lim011-ux-financial-app/blob/master/crazy8s.jpeg)

### Prototipo de alta fidelidad

![Inicio](https://github.com/Les9616/lim011-ux-financial-app/blob/master/inicio.JPG)
![Movimientos](https://github.com/Les9616/lim011-ux-financial-app/blob/master/movimientos.JPG)
![Ahorro](https://github.com/Les9616/lim011-ux-financial-app/blob/master/ahorros.JPG)
![Balance](https://github.com/Les9616/lim011-ux-financial-app/blob/master/balance.JPG)
![Token](https://github.com/Les9616/lim011-ux-financial-app/blob/master/token.JPG)
![Contacto](https://github.com/Les9616/lim011-ux-financial-app/blob/master/contacto.JPG)

## 10. Links

- Prototipo navegable [Figma]()

- Carpeta compartida [Drive](https://drive.google.com/drive/folders/1IMn8oNwX12JsH-ibtmlFWmbQ2mOV25nB?usp=sharing).

