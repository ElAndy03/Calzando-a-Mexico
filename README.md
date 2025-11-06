# Calzando-a-Mexico
Repositorio para el Hackhaton UPIICSA, de parte del equipo HBD

#  Sistema de Control de Inventario — *Calzando a México*

##  Descripción del Problema
Las tiendas de Calzando a México enfrentaban una fuerte desconexión entre el inventario registrado y las ventas reales.  
A pesar de contar con grandes volúmenes de mercancía en bodega, los clientes frecuentemente no encontraban los modelos o tallas que buscaban.  

Se identificaron los siguientes problemas:
- Sobreinventario en bodega y productos obsoletos sin salida.  
- Datos inconsistentes o fantasmas en el sistema de inventario.  
- Conteos manuales poco frecuentes que generaban errores.  
- Mermas y daños no registrados oportunamente.  

Todo esto resultaba en pérdidas económicas, saturación de espacios y una operación ineficiente.

---

##  Objetivo del Proyecto
Diseñar un sistema de gestión de inventario centralizado que permita:
1. Registrar con precisión todos los movimientos de entrada y salida de mercancía por tienda.  
2. Eliminar productos fantasma y mantener información actualizada.  
3. Detectar y controlar muestras, mermas o productos dañados.  
4. Generar reportes confiables para una toma de decisiones más eficiente.  
5. Servir como base de datos estructurada para futuras integraciones con otros sistemas.  

---

##  Descripción de la Solución
El sistema propuesto no es un punto de venta, sino una herramienta administrativa para controlar y auditar el flujo de inventario en cada tienda.

### Características
- Registro estructurado de:
  - Entradas de mercancía (nuevos lotes).  
  - Salidas de mercancía (ventas).  
- Validación de datos para evitar registros duplicados o inconsistentes.  
- Detección de diferencias entre stock teórico y stock real.  
- Interfaz simple y enfocada en la trazabilidad del producto.  

---
calzando-inventario/
├── src/                 
│   ├── database/       
│   ├── modules/         
│   └── app.py          
├── docs/                
├── tests/               
├── .gitignore          
├── LICENSE              
└── README.md     

## Base de Datos
La base de datos almacena toda la información proveniente de la empresa, incluyendo:
- Tiendas  
- Productos (modelo, talla, tipo, estado)  
- Movimientos de inventario (entradas y salidas)  
- Usuarios del sistema (vendedores, gerentes, supervisores)

- ## Tecnologías Utilizadas
- MySQL — gestión y almacenamiento de datos.  
- Python — backend para manejo de registros.  
- GitHub — control de versiones.

- ## Resultados Esperados
- Eliminación de productos fantasma mediante control cruzado de entradas y salidas.  
- Actualización continua del inventario real por tienda.  
- Disminución de mermas no registradas.  
- Mayor transparencia y trazabilidad en el flujo de productos.  
- Base sólida para una futura integración con el punto de venta o ERP.

**Autores:**  
- Andrés Domínguez Morales
- Berenice Chavez Bedoya
- Gamaliel Callejas Maceda 
- Sherlin Citlalli Martinez Olvera
