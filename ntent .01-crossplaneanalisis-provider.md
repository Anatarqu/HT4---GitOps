[1mdiff --cc 01-crossplane/analisis-provider.md[m
[1mindex a3ff6d0,3d721a3..0000000[m
[1m--- a/01-crossplane/analisis-provider.md[m
[1m+++ b/01-crossplane/analisis-provider.md[m
[36m@@@ -14,4 -14,4 +14,8 @@@[m
  [m
  ### 3. Información requerida por el ProviderConfig[m
  [m
[32m++<<<<<<< HEAD[m
[32m +<!-- el ProviderConfig actúa exclusivamente como un apuntador hacia un Secret de Kubernetes, requiere una referencia a un Secreto apuntando a una llave específica donde se almacena un bloque de texto plano con la configuración del motor. Necesita host, port, user, password, sslmode  -->[m
[32m++=======[m
[32m+ <!-- el ProviderConfig actúa exclusivamente como un apuntador hacia un Secret de Kubernetes, requiere una referencia a un Secreto apuntando a una llave específica donde se almacena un bloque de texto plano con la configuración del motor. Necesita host, port, user, password, sslmode -->[m
[32m++>>>>>>> f4a4d94 (Trabajo estudio)[m
