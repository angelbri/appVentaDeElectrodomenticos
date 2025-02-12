# appVentaDeElectrodomenticos 
## Introducción

El presente proyecto tiene como objetivo el desarrollo de una estrategia efectiva para la comercialización de electrodomésticos, abordando aspectos clave como la identificación de la demanda del mercado, la optimización de los canales de venta y la mejora en la experiencia del cliente. En un mundo donde la tecnología avanza constantemente, los electrodomésticos desempeñan un papel fundamental en la vida cotidiana, ofreciendo comodidad y eficiencia en los hogares y negocios.

### Propósito

El propósito principal de este proyecto es diseñar e implementar un plan de ventas de electrodomésticos que permita maximizar la rentabilidad y posicionar la marca en el mercado. Para ello, se pretende analizar las tendencias de consumo, establecer estrategias de promoción efectivas y garantizar la disponibilidad de productos innovadores que respondan a las necesidades del cliente.

### Objetivos
- **Incrementar las ventas de electrodomésticos** mediante estrategias de marketing digital y promoción en puntos de venta físicos.
- **Optimizar la gestión del inventario** asegurando la disponibilidad de productos de alta demanda.
- **Mejorar la experiencia del cliente** a través de asesoramiento especializado y atención personalizada.
- **Establecer alianzas estratégicas** con proveedores y distribuidores para obtener mejores precios y ampliar el portafolio de productos.

## Contexto del Problema

El mercado de electrodomésticos ha experimentado un crecimiento constante en los últimos años, impulsado por la digitalización y la necesidad de productos más eficientes y sostenibles. Sin embargo, la competencia en este sector es intensa, con múltiples empresas ofreciendo productos similares a precios competitivos. Esto obliga a las empresas a diferenciarse mediante estrategias de valor agregado, como servicios postventa, garantías extendidas y financiamiento accesible para los clientes.

### Definición del problema

A pesar del crecimiento del sector, muchas empresas enfrentan desafíos como la falta de diferenciación de productos, estrategias de marketing ineficientes y dificultades para fidelizar a los clientes. Además, factores como el incremento en los costos de importación y la variabilidad en la demanda pueden afectar la rentabilidad del negocio. En este sentido, es crucial diseñar un plan de ventas basado en un análisis detallado del mercado y en estrategias innovadoras que permitan captar y retener clientes.

### Justificación del proyecto

El desarrollo de una estrategia de ventas para electrodomésticos es esencial para fortalecer la presencia de la empresa en el mercado y garantizar su crecimiento sostenible. Implementar acciones orientadas a la satisfacción del cliente, optimizar la gestión de inventario y utilizar herramientas digitales para mejorar la visibilidad de los productos son medidas clave para alcanzar los objetivos comerciales. Además, la implementación de tecnologías en el proceso de ventas permitirá ofrecer una experiencia más eficiente y personalizada a los consumidores.

## Análisis de Requerimiento

Para llevar a cabo una estrategia de ventas efectiva, es fundamental considerar una serie de requerimientos clave que garantizarán el éxito del proyecto:

### Requerimientos funcionales:
- Plataforma de comercio electrónico optimizada para la venta de electrodomésticos.
- Sistema de gestión de inventario en tiempo real para evitar desabastecimientos o sobrestock.
- Canales de atención al cliente (chat en línea, redes sociales, call center) para mejorar la experiencia del comprador.
- Estrategias de fidelización como programas de recompensas o descuentos exclusivos para clientes frecuentes.

### Requerimientos no funcionales:
- Seguridad en las transacciones en línea para garantizar la confianza de los clientes.
- Tiempo de respuesta eficiente en la gestión de pedidos y entregas.
- Diseño de experiencia de usuario intuitiva en la plataforma digital.
- Cumplimiento con normativas de calidad y seguridad en los productos comercializados.

## Modelo Relacional en Mysql 
 ![imagen](https://github.com/angelbri/appVentaDeElectrodomenticos/blob/main/modelo%20relacional.JPG)

## Descripción de las tablas principales


1. **Clientes**: 
   - Propósito: Almacena información sobre los clientes de la empresa. Contiene detalles como nombre, dirección, teléfono, y correo electrónico.
   - Relevancia: Es crucial para registrar quiénes realizan los pedidos y poder asociarlos con sus datos personales y contacto.

2. **Empleados**:
   - Propósito: Contiene información sobre los empleados, como nombre, dirección, teléfono y correo electrónico.
   - Relevancia: Permite registrar qué empleado está a cargo de procesar o gestionar cada pedido.

3. **Pedidos**:
   - Propósito: Representa las órdenes realizadas por los clientes. Incluye información como la fecha del pedido, el cliente que lo realizó y el empleado encargado.
   - Relevancia: Es el núcleo del sistema, ya que conecta los clientes con los productos y empleados.

4. **Detalle_Pedido**:
   - Propósito: Registra los productos específicos que forman parte de cada pedido, junto con la cantidad, el precio unitario y el subtotal por producto.
   - Relevancia: Permite desglosar cada pedido en sus componentes específicos, proporcionando detalles esenciales para el cálculo del total y la gestión de inventarios.

5. **Productos**:
   - Propósito: Almacena información sobre los productos disponibles, como su nombre, descripción, precio, stock, categoría y marca.
   - Relevancia: Es fundamental para gestionar el inventario y para asociar los productos a los pedidos.

6. **Categoría**:
   - Propósito: Define las categorías a las que pertenece cada producto.
   - Relevancia: Ayuda a organizar los productos para facilitar su búsqueda y análisis.

7. **Marcas**:
   - Propósito: Almacena las marcas relacionadas con los productos.
   - Relevancia: Es útil para identificar productos de una marca específica, lo que puede ser importante para promociones o análisis de ventas.

