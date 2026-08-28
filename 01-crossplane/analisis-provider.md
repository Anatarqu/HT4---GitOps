# =====================================================================
# Análisis del Provider PostgreSQL
# =====================================================================

## Provider: tages/provider-postgresql v0.1.0

### 1. Managed Resources disponibles

<!-- Este proveedor cuenta con 17 Managed Resources. Los principales y más utilizados para administrar el ciclo de vida dentro de una instancia de PostgreSQL: Database, Extensiom, Function, Grant, Mapping, Privileges, ProviderConfig, ProviderConfigUsage, Publication, ReplicationSlot, Role, Shcema, Server, Slot, StoreConfig, Subscription-->

### 2. Campos requeridos del recurso Database

<!--Campos requeridos (name) y campos opcionales (owner, lc Caollate, lcCtype, tablespaceName, template)-->

### 3. Información requerida por el ProviderConfig

<!-- el ProviderConfig actúa exclusivamente como un apuntador hacia un Secret de Kubernetes, requiere una referencia a un Secreto apuntando a una llave específica donde se almacena un bloque de texto plano con la configuración del motor. Necesita host, port, user, password, sslmode  -->
