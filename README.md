# Routing_app
## Tabla de contenido
- [Descripción](#Descripción)
- [¿Qué es el problema de ruteo de vehículos?](#¿Qué-es-el-problema-de-ruteo-de-vehículos?)
- [¿Descripción gráfica del problema de ruteo de vehículos](#Descripción-gráfica-del-problema-de-ruteo-de-vehículos)
- [Alcance](#Alcance)
  
***

### Descripción
Este proyecto contempla la creación de una app para el **VRP (***Vehicle Routing Problem***)**, donde las empresas de logística podrán definir su sistema de clientes y depósitos que serán entregados a una API que determinará el sistema de rutas óptimo.

***

### ¿Qué es el problema de ruteo de vehículos?
El problema de ruteo de vehículos o VRP; por sus siglas en inglés ***Vehicle Routing Problem***, es un problema de logística de última milla en la cadena de suministro, con complejidad combinatorial NP. Su propósito de estudio se centra en determinar la cantidad de vehículos necesarios para cubrir un sistema de clientes ubicados geográficamente, teniendo en cuenta que la distancia que estos deben recorrer debe ser mínima, optimizando así los costos operativos de la flota usada.

***

### Descripción gráfica del problema de ruteo de vehículos
![diagrama](https://github.com/Alejandro-Ospina/Routing_app/assets/133997055/8bc8150c-a05c-47dd-8377-db2c7b1ba263)

Como se observa en la gráfica anterior, el **VRP** se puede representar geométricamente como un grafo orientado débilmente conexo, donde el sistema de flotas inicia en el centro de distribución (depósito), y termina en el mismo. Esta última condición puede variar, ya que puede darse el caso en que el sistema de flotas usado por la empresa de logística sea tercerizado, por lo cual no es necesario que la flota empleada retorne al nodo origen (depósito). Este último detalle, sugiere que el **VRP** está sujeto a múltiples variaciones; sin embargo, esta aplicación no evaluará a priori todas las posibles variantes, ya que el objetivo central es consolidar una API que permita resolver el problema básico.

**NOTA:** No se descarta que a posteriori, la aplicación pueda escalar para incluir más variantes del problema tradicional.

***

### Alcance

Esta aplicación está pensada para empresas de logística y/o organizaciones que necesiten de soluciones efectivas para casos de prueba pequeños y medianos. Se entiende que la capacidad del servidor es un factor importante al momento de consumir la API, y es por eso que la app no pretende extender funciones complejas a casos considerablemente complejos. **Routing_app** está pensada para funcionar como herramienta de comparación, estudio y uso de empresas de logística y organizaciones que la necesiten.
