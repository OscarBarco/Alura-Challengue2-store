# Análisis Comparativo de Tiendas de Alura Store - Challenge Data Science ONE Latam

##  Descripción del Proyecto

El presente proyecto se enmarca en el **Challenge de Data Science organizado por Alura Latam y Oracle Next Education (ONE)**. Su finalidad es desarrollar un análisis comparativo del desempeño de cuatro sucursales pertenecientes a la cadena ficticia "Alura Store", con el objetivo de brindar al propietario, el Sr. Juan, información clave que le permita tomar una decisión informada respecto a la venta de una de las tiendas, con miras a reinvertir en un nuevo emprendimiento.


##  Objetivo del Análisis

Identificar cuál de las sucursales de Alura Store presenta el rendimiento general más bajo, tomando como referencia indicadores clave como los ingresos, la satisfacción del cliente y la eficiencia operativa, con el propósito de ofrecer al Sr. Juan una recomendación sólida y basada en datos.

## Base de datos utilizado

Los datos provienen de cuatro archivos CSV distintos,  obtenidos del repositorio de GitHub proporcionado por Alura Latam.

Las columnas principales analizadas incluyen:
*   `Producto`: Nombre del artículo vendido.
*   `Categoría del Producto`: Clasificación del producto.
*   `Precio`: Valor de la venta.
*   `Costo de envío`: Gasto asociado al envío.
*   `Fecha de Compra`: Información temporal.
*   `Lugar de Compra`: Información geográfica general.
*   `Calificación`: Evaluación del cliente (1-5).
*   `Método de pago`: Forma de pago utilizada.
*   `Cantidad de cuotas`: Número de pagos (si aplica).
*   `lat`, `lon`: Coordenadas geográficas de la compra.

##  Análisis Realizado

Se llevaron a cabo los siguientes análisis comparativos entre las cuatro tiendas:

1.  **Ingreso Total por Tienda:** Cálculo de la facturación total (`Precio`).
2.  **Ventas por Categoría:** Conteo de unidades vendidas por `Categoría del Producto`.
3.  **Calificación Promedio de Clientes:** Cálculo del promedio de `Calificación`.
4.  **Productos Más y Menos Vendidos:** Identificación y conteo de unidades por `Producto`.
5.  **Costo Promedio y Distribución de Envío:** Cálculo del promedio y análisis de la distribución del `Costo de envío`.
6.  **(Opcional) Análisis Geográfico:** Visualización de ventas (`lat`, `lon`) por tienda, densidad y calificación.


## 💻 Tecnologías Utilizadas

*   **Lenguaje:** Python 3
*   **Bibliotecas:** Pandas, Matplotlib
*   **Control de Versiones:** Git y GitHub


----
*Proyecto realizado como parte del Challenge Data Science ONE (Oracle Next Education + Alura Latam).*

-----
