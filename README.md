# dualPlaywright
Repo for Dualboot Challenge
Automatización de pruebas:
El objetivo de este ejercicio es evaluar las habilidades técnicas del candidato en la
automatización de pruebas, su capacidad para analizar y resolver problemas, y su manejo de
herramientas y buenas prácticas en el desarrollo de scripts de testing. Queremos ver cómo
aborda un flujo realista de pruebas sobre una aplicación web, incluyendo validaciones positivas,
negativas y el uso eficiente de la tecnología que elija.
NOTA: Para este ejercicio utilizaremos Demoblaze (Siéntase libre de usar cualquier tecnología)
Parte 1: Setup Básico
Instrucciones:
● Configurar el entorno y preparar el script para automatizar pruebas en Demoblaze.
Criterios:
● Correcta instalación de dependencias y configuración del entorno.
● README que detalle las instrucciones para ejecutar las pruebas.
Parte 2: Casos de Prueba Escenciales
1- Login:
● Validar el login con credenciales válidas (user: admin, password: admin).
● Validar login fallido con credenciales incorrectas.
2- Validación de Categorías:
● Verificar que existen las categorías: Phones, Laptops, Monitors.
● Validar que cada categoría muestra productos correctos.
3- Flujo de Compra Completo:
● Agregar un producto al carrito.
● Proceder al checkout y verificar que el pedido se complete con éxito.
4- Modificación de Datos Personales:
● Simular un cambio en los datos personales del usuario y verificar que los cambios
persisten.
Parte 3: Casos de Prueba Extendidos
1- Caso Negativo: Compra sin Producto
● Intentar proceder al checkout sin agregar productos al carrito y validar el mensaje de
error.
2- Validación Dinámica:
● Cambiar la cantidad de un producto en el carrito y validar que el precio total se actualiza
correctamente.
Parte 4: Bonus Opcional
Reporte Automatizado:
● Generar un reporte detallado de los resultados de las pruebas, con capturas de pantalla
en caso de fallos.
