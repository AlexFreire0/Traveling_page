# Agencia de Viajes 2025 - Prototipo UI

Este repositorio contiene un prototipo de interfaz para la "Agencia de Viajes 2025". Muestra la estructura y navegabilidad entre pantallas: Inicio, Destinos, Ofertas y Reservas.

Archivos principales:
- Index.html - Ventana principal / menu de inicio.
- destinos.html - Listado de destinos (usa componente reutilizable).
- ofertas.html - Listado de ofertas y destinos en promocion (usa componente reutilizable).
- reservas.html - Formulario de reserva (nombre, destino, fecha) con confirmacion.
- css/styles.css - Estilos globales y del componente.
- js/common.js - Logica minima: carga de componente y manejo del formulario.
- components/destination-card.html - Componente visual reutilizable (tarjeta de destino).

Como usar:
1. Abrir los archivos .html en un navegador (doble clic en Windows).
2. Navegar entre las paginas mediante la barra superior.
3. En "Reservas" rellenar el formulario y pulsar "Confirmar reserva" para ver la alerta de confirmacion.

Subir a GitHub:
1. Inicializar repositorio local:
   git init ; git add . ; git commit -m "Initial prototype"
2. Crear un repositorio en GitHub y seguir las instrucciones para anadir el remoto origin y hacer git push.
