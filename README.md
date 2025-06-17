# Formulario_avanzado
Formulario Avanzado de Registro
Este es un formulario de registro avanzado que implementa validaciones en tiempo real para proporcionar una experiencia de usuario fluida y robusta. Incluye características como:

- Validación de campos obligatorios: Nombres, apellidos, correo, contraseña, teléfono y fecha de nacimiento.
- Validación de formato: Para correos electrónicos y números de teléfono (con formato automático).
- Confirmación de campos: Correo y contraseña.
- Indicador de fortaleza de contraseña: Te ayuda a crear contraseñas seguras.
- Restricción de edad: Solo permite el registro a mayores de 18 años.
- Contador de caracteres: Para el campo de comentarios.
- Barra de progreso: Muestra el porcentaje de campos válidos completados.
- Resumen de datos: Muestra la información enviada tras una validación exitosa.

## Tecnologías Utilizadas
HTML5: Estructura del formulario.
CSS: Estilos básicos para la apariencia y los indicadores visuales.
JavaScript (Vanilla JS): Toda la lógica de validación, interactividad y manejo del formulario.

## Estructura del Proyecto

Formulario_avanzado/      
├── _css/
│   └── styles.css    
├── index.html  
└── README.md

# Puntos Destacados del Código
El corazón de la funcionalidad reside en el script de JavaScript incrustado en index.html:

- Validación Campo a Campo: Cada campo tiene un EventListener que valida su entrada en tiempo real.
- estadoValidacion: Un objeto clave para el control de la validez general del formulario.
- Funciones Auxiliares: mostrarError(), mostrarExito(), marcarCampo(), actualizarProgreso(), actualizarBotonEnvio(), y calcularFortalezaPassword() manejan la lógica de la interfaz y la validación.
- Manejo del submit: Previene el envío por defecto, realiza una validación final y muestra un resumen de los datos.

Autor: Alex Jhair Obando Zuñiga
Ficha: 3147235
