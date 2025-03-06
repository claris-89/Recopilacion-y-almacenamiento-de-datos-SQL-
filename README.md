# Recopilacion-y-almacenamiento-de-datos-SQL-

### Descripción del Proyecto
Este proyecto analiza datos relacionados con los viajes de taxis en Chicago para ayudar a Zuber, una nueva empresa de viajes compartidos, a entender las preferencias de los pasajeros y cómo factores externos, como el clima, impactan la frecuencia y duración de los viajes. Utilizando análisis de datos y pruebas estadísticas, el objetivo es descubrir patrones clave para optimizar sus estrategias de negocio.

### Objetivos
1. Explorar y analizar datos de competencia: Examinar las principales empresas de taxis en Chicago y su desempeño.
2. Estudiar factores externos: Evaluar el impacto de condiciones climáticas sobre la duración de los viajes.
3. Visualizar patrones clave: Crear gráficos representativos de las tendencias de viajes.
4. Probar hipótesis críticas: Validar si el clima afecta la duración promedio de los viajes desde áreas específicas de la ciudad.

5. Metodología
Etapa 1: Análisis del Clima
- Descargar y analizar datos climáticos de Chicago para noviembre de 2017.
- Evaluar cómo las condiciones climáticas varían en el período.

Etapa 2: Análisis Exploratorio de Datos
- Contar el número total de viajes por empresa entre el 15 y 16 de noviembre de 2017.
- Analizar empresas con nombres que incluyan "Yellow" o "Blue" del 1 al 7 de noviembre.
- Identificar las empresas de taxis líderes, agrupando las demás bajo "Other".
- Investigar patrones de viajes agrupados por condiciones climáticas.

Etapa 3: Prueba de Hipótesis
- Evaluar si la duración promedio de los viajes entre el barrio Loop y el Aeropuerto Internacional O'Hare cambia durante sábados lluviosos.
    - Hipótesis nula: La duración promedio de los viajes no cambia entre condiciones climáticas buenas y malas.
    - Hipótesis alternativa: La duración promedio de los viajes cambia en condiciones lluviosas.

Etapa 4: Visualización y Conclusiones
- Importar y analizar dos conjuntos de datos adicionales:
- Cantidad de viajes por empresa de taxis (project_sql_result_01.csv).
- Promedio de finalizaciones de viajes por barrios (project_sql_result_04.csv).
- Crear gráficos para representar:
- Número de viajes por empresa de taxis.
- Los 10 barrios principales según el promedio de viajes finalizados.

Herramientas Utilizadas
- SQL: Para consultas y análisis inicial de la base de datos.
- Python (Pandas, Matplotlib, Seaborn): Para procesamiento de datos, gráficos y pruebas estadísticas.

### Conclusión
Según los datos expuestos, se concluye que conocer herramientas como SQL, relaciones entre tablas y recuperación de datos es posible profundizar aún más en el análisis de datos, conocer y usar estas herramientas me ha permitido ampliar mis conocimientos, aunque me ha resultado retador poner en práctica estos nuevos conocimientos quiero seguir aprendiendo y practicando para seguir mejorando. Los resultados muestran que las condiciones climáticas tienen un impacto significativo en la duración de los viajes. Esto puede deberse a factores como tráfico más lento, reducción de velocidad por precaución o alteraciones en las rutas habituales durante días lluviosos. Para Zuber, es crucial considerar estos efectos climáticos al planificar tiempos de viaje estimados o ajustar estrategias para mejorar la experiencia del cliente durante condiciones adversas.

