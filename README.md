# Gestion-de-pagos
 Calcula el pago a los clientes
 Manual de Uso - Asistente de Pagos v1.0beta

1. Introducción
Este manual detalla el uso del Asistente de Pagos, una aplicación diseñada para gestionar el rendimiento de múltiples carteras de USDT.

2. Funcionalidades Principales
2.1 Carga de Datos
2.2 Visualización y Edición de Datos
2.3 Cálculos Automáticos
2.4 Descarga de Datos
2.5 Modo Oscuro

3. Instrucciones de Uso

3.1 Carga de Datos
- Haga clic en el botón "Seleccionar archivo" para elegir un archivo CSV.
- El archivo CSV debe contener dos columnas: "Cartera" e "Importe a pagar".
- Una vez seleccionado el archivo, haga clic en "Upload CSV" para cargar los datos.

Ejemplo de contenido del CSV:
Cartera,Importe a pagar
Cartera1,1000
Cartera2,2000

3.2 Visualización y Edición de Datos
- Los datos cargados se mostrarán en una tabla editable.
- Puede editar manualmente los campos: "Fecha Inicio", "Nombre", "Cartera", "Cap. Inicial", "Porcentaje retorno", "Fecha Próximo Pago" y "Notas".
- Los campos "Fin de carencia" y "Total a Pagar" se calculan automáticamente.

3.3 Cálculos Automáticos
- "Fin de carencia": Se calcula automáticamente sumando 30 días a la "Fecha Inicio".
- "Total a Pagar": Se calcula como el "Porcentaje retorno" del "Cap. Inicial".
- "Fecha Próximo Pago": Se establece automáticamente como el próximo lunes.

3.4 Descarga de Datos
- "Download CSV": Descarga toda la tabla en formato CSV.
- "Descarga archivo Pagos": Descarga un CSV con solo las columnas "Portfolio" y "Total to Pay".

3.5 Otras Funcionalidades
- "PAID": Borra todos los campos de "Total a Pagar".
- Modo Oscuro: Haga clic en el icono de luna en la esquina superior derecha para cambiar entre modo claro y oscuro.

4. Ejemplos de Uso

4.1 Carga y Edición de Datos
1. Cargue un archivo CSV con los datos de las carteras.
2. En la tabla resultante, haga clic en una celda de "Fecha Inicio" e introduzca una fecha, por ejemplo, "2023-05-01".
3. Observe cómo "Fin de carencia" se actualiza automáticamente a "2023-05-31".
4. Introduzca un valor en "Cap. Inicial", por ejemplo, 10000.
5. Introduzca un valor en "Porcentaje retorno", por ejemplo, 5.
6. Observe cómo "Total a Pagar" se actualiza automáticamente a 500.

4.2 Descarga de Datos
1. Después de editar los datos, haga clic en "Download CSV" para obtener un archivo con todos los datos de la tabla.
2. Si solo necesita la información de pagos, haga clic en "Descarga archivo Pagos" para obtener un CSV con las columnas "Portfolio" y "Total to Pay".

4.3 Uso del Modo Oscuro
1. Haga clic en el icono de luna en la esquina superior derecha de la página.
2. Observe cómo cambia el esquema de colores de la aplicación.
3. Vuelva a hacer clic en el icono para regresar al modo claro.

5. Solución de Problemas
- Si los cálculos automáticos no se actualizan, intente hacer clic fuera del campo que acaba de editar.
- Si la tabla no se desplaza automáticamente, asegúrese de mover el cursor del ratón cerca de los bordes de la tabla.
- Si tiene problemas para cargar el archivo CSV, asegúrese de que tiene el formato correcto (dos columnas: "Cartera" e "Importe a pagar").

Para cualquier problema adicional o sugerencia de mejora, por favor contacte con el soporte técnico.
