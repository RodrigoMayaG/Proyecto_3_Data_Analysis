Iniciamos el proyecto de desarrollo de habilidades para data analysis

Ahora tomaremos una metodologia diferente para analizar esta data, la misma del proyecto 2.

La metdologia principal es revisar la data y como actualmente no tenemos una pregunta o algun problema que resolver realizamos una creación de KPIs bases con un objetivo y en base a ello buscamos areas de oportunidad.

Definiremos los KPIS:
1. por pais en cantidad de ordenes obvio, porcentaje y lo desglozaremos por mes, la fecha que usaremos es el de shipping para tener un rango de mes-año
2. Podemos hacer algo con day of shipping real y shcedule, aun no se que, a lo mejor diferencia de días por orden
3. Por categoria.
4. En ingreso por pais, orden, etc.
5. Order creada vs shipping date
6. El metodo que mas se usa para pagar.

Hagamos estos KPIs y veamos que no salen.
a ver primordialmente vimos la distribución de ordenes por pais, observando que Estados Unidos tienen la mayor cantidad con un 12%
Decidimos ver con la columna de shipping date por mes como se desgloza esa cantidad por pais y revisar su comportamiento los primeros 3 meses vs los ultimos 3 meses para ver su comportamiento.
Y observamos los 30

Observando el mapa de calor podemos ver muy claro que algunos paises tienen bloques de meses con creacion de ordenes y de repente nada.
Podemos observar que Nueva Zelanda solo tuvo dos meses con ordenes y de ahi nada.

Okey plantenado como observación estaods unidos o la distribución de algunos paises que solo tienen ordenes por ciertos lapzos de meses afecta a algun KPI?
No solo es la distribución de las ordenes pero veamoslo por ingreso.

La hipotesis diria que como estados unidos tiene la mayor cantidad de ordenes, veamos en ingresos debe estar a la par comprobemoslo.

En efecto estaods unidos tiene la mayor cantidad en ingresos, entonces en cantidad de ordenes e ingreso no encuentro un area de oportunidad pero pasemos al analisis de tiempos de entrega como nos encontramos.

Primero saquemos el porcentaje de ordenes por shipping Status

Aqui podemos observar que en el 54.82% de las ordenes llegamos tarde eso es mucho la mitad de nuestras ordenes llegan tarde.
Veamos el promedio de días que demoramos en entregar las ordenes.
Tenemos un promedio de 0.56 días de retraso eso quiere decir que aporximadamente tardamos medío día.
Sin embargo por que la mitad de nuestros productos llegan tarde?

**55% de nuestras ordenes llegan tarde con un promedio de 1.6 días, sobre una promesa de 2.47 días**