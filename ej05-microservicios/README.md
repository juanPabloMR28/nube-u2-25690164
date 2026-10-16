microservicios + gateway

1. Separa la API del ej. 3 en servicio de ventas y servicios de IA
2. Entrena un modelo sencillo (p. ej. LinearRegression con datos sinteticos de ventas) y guradalo con joblib
3. Agrega un getaway y levanta todo con docker compose
4. ejecuta carga.py con 1 y con 3 replicas; reporta rps, p50 y p95
5. Ejecuta el mismo compose en GitHub Codespaces con el puerto publico (Practica 2)