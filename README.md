# FundamentosProgramaci-nActividad4
Repositorio de ejercicios de estructuras con JavaScript

Ejercicio1
Para este ejercicio usé un bucle while, que fue explicado por la profesora Tatiana en una de las sesiones y cual era su funcionamiento. Me permitió repetir el proceso de pedir un número y calcular su cuadrado mientras el número fuera positivo. Cuando el usuario introducía un número negativo, el bucle se detenía. Esta fue una buena forma de practicar la lectura de datos y el uso de bucles.

Codigo del ejericio:
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Ejercicio 1</title>
</head>
<body>
    <h1>Ejercicio 1: Cuadrado de un número</h1>
    <p>Introduce un número (negativo para salir):</p>
    <input type="number" id="inputNumero">
    <button onclick="procesarNumero()">Calcular</button>
    <p id="resultado"></p>

    <script src="ejercicio1.js"></script>
</body>
</html>

Enlace del ejercicio:
http://127.0.0.1:5500/index1.html

Ejercicio2
Aquí usé un número secreto que se comparaba con los intentos del usuario. Utilicé if para decir si el número era mayor o menor al que se debía adivinar. El bucle se repetía hasta que el número fuera igual. Fue útil para trabajar comparaciones y bucles con condiciones.

Codigo del ejericio:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 2</title>
</head>
<body>
    <h1>Ejercicio 2: Adivina el número</h1>
    <script src="ejercicio2.js"></script>
</body>
</html>

Enlace del ejercicio:
http://127.0.0.1:5500/index2.html

Ejercicio3
En este ejercicio usé un bucle for que también fue explicado por la profesora y recorre los 10 primeros números impares (1, 3, 5, ..., 19) y fui multiplicándolos acumulativamente. Este ejercicio y lo que vi en los encuentros me ayudó a entender mejor cómo calcular productos de forma secuencial con bucles.

Codigo del ejericio:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 3</title>
</head>
<body>
    <h1>Ejercicio 3: Producto de los 10 primeros impares</h1>
    <script src="ejercicio3.js"></script>
</body>
</html>

Enlace del ejercicio:
http://127.0.0.1:5500/index3.html

Ejercicio4
Pedí un número y luego utilicé un bucle for para multiplicar desde 1 hasta ese número, guardando el resultado en una variable factorial. Este ejercicio reforzó el uso de bucles y cómo aplicar matemáticas básicas con JavaScript.

Codigo del ejericio:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 4</title>
</head>
<body>
    <h1>Ejercicio 4: Calcular el Factorial de un Número</h1>
    <script src="ejercicio4.js"></script>
</body>
</html>

Enlace del ejercicio:
http://127.0.0.1:5500/index4.html

Ejercicio5
Para este ejercicio pedí 10 números y los clasifiqué usando condicionales: si eran mayores que 0, menores que 0 o igual a 0. Fui sumando los positivos y negativos y contándolos, luego calculé las medias dividiendo la suma por la cantidad. Aprendí a usar contadores y cómo manejar varias condiciones en un mismo bucle.

Codigo del ejericio:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 5</title>
</head>
<body>
    <h1>Ejercicio 5: Media de Positivos, Negativos y Cerros</h1>
    <script src="ejercicio5.js"></script>
</body>
</html>

Enlace del ejercicio:
http://127.0.0.1:5500/index5.html

Ejercicio6

Este ejercicio me permitió aplicar conceptos fundamentales de JavaScript, como la estructura condicional if y el ciclo for, para resolver un problema práctico: generar la tabla de multiplicar de un número ingresado por el usuario. Además, reforcé el uso de las funciones prompt y alert para interactuar con el usuario desde el navegador. Considero que esta actividad fue útil para entender mejor cómo validar datos de entrada y automatizar cálculos repetitivos. En general, fue una experiencia sencilla pero valiosa para afianzar la lógica de programación y la relación entre JavaScript y el entorno del navegador.

Codigo del ejericio:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 6</title>
</head>
<body>
    <h1>Ejercicio 6: Tabla de Multiplicar</h1>
    <script src="ejercicio6.js"></script>
</body>
</html>

Enlace del ejercicio:
http://127.0.0.1:5500/index6.html

Ejercicio7
Este ejercicio fue una oportunidad para integrar conocimientos de HTML y JavaScript en un proyecto más funcional y orientado a la práctica. A través del desarrollo de un formulario interactivo para registrar facturas, aprendí a manejar eventos del formulario, capturar datos ingresados por el usuario y actualizar dinámicamente el contenido del DOM. También trabajé con estructuras de control para realizar cálculos como la facturación total, el conteo de litros vendidos para un artículo específico y el número de facturas que superan los $600.

Además de fortalecer la lógica de programación, este ejercicio me ayudó a comprender cómo estructurar interfaces que sean útiles en contextos reales como la gestión de ventas o inventarios. Considero que fue una experiencia clave para visualizar cómo los conocimientos teóricos pueden aplicarse en el desarrollo de soluciones prácticas usando tecnologías web.

Codigo del ejericio:
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Gestión de Facturas</title>
</head>
<body>
  <h1>Gestión de Facturas</h1>

  <form id="facturaForm">
    <input type="text" id="codigoArticulo" placeholder="Código del artículo (1 o 2)" required><br>
    <input type="number" id="litrosVendidos" placeholder="Litros vendidos" required><br>
    <input type="number" id="precioPorLitro" placeholder="Precio por litro" required><br>
    <button type="submit">Registrar Factura</button>
  </form>

  <p id="facturacionTotal">Facturación Total: $0.00</p>
  <p id="litrosArticulo1">Litros vendidos del artículo 1: 0</p>
  <p id="facturas600">Facturas con más de $600: 0</p>

  <table border="1">
    <thead>
      <tr>
        <th>#</th>
        <th>Código</th>
        <th>Litros</th>
        <th>Precio</th>
        <th>Total</th>
      </tr>
    </thead>
    <tbody id="tablaFacturas"></tbody>
  </table>

  <!-- Enlace correcto al archivo externo -->
  <script src="script.js"></script>
</body>
</html>

Enlace del ejercicio:
http://127.0.0.1:5500/index7.html

Nota: En este ejercicio al parecer no queda funcionando la ejecución despues de colocar valores me di cuenta al ejecutarlo no daba ningun valor en las casillas facturación, facturación total y litros pero buscando varias soluciones y aplicandolas no encontre cual fue el error revise con el cache del explorador cambiando el codigo pero finalmente no se pudo ejecutar

Ejercicio8

Primero pedí cuántos sueldos se iban a ingresar y generé dinámicamente los campos de entrada. Luego, al hacer clic en calcular, obtuve el sueldo máximo con una comparación simple. Este ejercicio me enseñó a generar inputs dinámicamente y a manejar datos desde varios campos al mismo tiempo.

Además, desarrollé un pequeño contador que iba del 00000 al 99999, reemplazando cualquier número 3 por la letra E. Fue una manera interesante de trabajar con cadenas y formateo.

Codigo del ejericio:

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio Sueldos</title>
</head>
<body>
    <h1>Ejercicio 1: Sueldos</h1>

    <label for="numSueldo">¿Cuántos sueldos vas a introducir? </label>
    <input type="number" id="numSueldo" min="1"><br><br>
    <button onclick="pedirSueldos()">Introducir sueldos</button>

    <div id="resultados">
        <p><strong>Sueldo máximo: </strong><span id="sueldoMaximo">0</span></p>
    </div>

    <h2>Ejercicio 2: Contador</h2>
    <div id="contador"></div>

    <script>
        // Parte 1: Pedir los sueldos y mostrar el sueldo máximo
        function pedirSueldos() {
            const numSueldo = parseInt(document.getElementById('numSueldo').value);
            if (isNaN(numSueldo) || numSueldo <= 0) {
                alert('Por favor, introduce un número válido para N');
                return;
            }

            let sueldoMaximo = 0;
            for (let i = 1; i <= numSueldo; i++) {
                const sueldo = parseFloat(prompt(`Introduce el sueldo ${i}:`));
                if (isNaN(sueldo)) {
                    alert(`El valor ${i} no es un número válido.`);
                    return;
                }
                if (sueldo > sueldoMaximo) {
                    sueldoMaximo = sueldo;
                }
            }

            document.getElementById('sueldoMaximo').textContent = sueldoMaximo;
        }

        // Parte 2: Contador que sustituye 3 por 'E'
        let contador = 0;
        setInterval(() => {
            let contadorStr = contador.toString().padStart(5, '0');  // Rellenar con ceros a la izquierda
            contadorStr = contadorStr.replace(/3/g, 'E');  // Sustituir 3 por E
            document.getElementById('contador').textContent = contadorStr;
            contador = (contador + 1) % 100000;  // Mantener el contador dentro de 00000 a 99999
        }, 1000);  // Actualizar cada 1 segundo
    </script>
</body>
</html>

Enlace del ejercicio:
http://127.0.0.1:5500/index8.html

Conclusión
Resalto lo que dice la profesora de trabajar en equipo ya que no solo ayuda a mejorar los tiempos de trabajo y también la carga de estos. Ya que hice estos ejercicios solo y me costo bastante no solo tuve que leer las guias de la universidad ver los encuentros de la profe Tatiana y también  pedir ayuda a mis compañeros de trabajo que son programadores y tienen más experiencia en el tema.
