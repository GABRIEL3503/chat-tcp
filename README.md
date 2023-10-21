# 🚀 **TCP-Chat**

Una aplicación simple de chat que utiliza el **Protocolo de Control de Transmisión (TCP)** para establecer comunicaciones bidireccionales entre un servidor y un cliente. Además, cuenta con una API HTTP para consultar mensajes.

---

## 🛠 **Instalación**

- **Clonar el Repositorio**:
  ```bash
  git clone [URL_DEL_REPO]

Instalar Dependencias:
npm install

Configurar Variables de Entorno:
Editar el archivo .env con los valores adecuados para tu entorno.
🖥 Uso
Iniciar el Servidor TCP:
npm run server

Iniciar el Cliente TCP:
npm run client
Iniciar el Servidor HTTP:
npm run httpServer

📚 Descripción Técnica
1. Servidor TCP (server.js):
Acepta conexiones de clientes.
Recibe y muestra mensajes del cliente.
Espera la respuesta del operador y la envía al cliente.
Guarda los mensajes utilizando la función saveMessage.
2. Cliente TCP (client.js):
Establece conexión con el servidor.
Envía y recibe mensajes del servidor.
Guarda los mensajes usando saveMessage.
3. Servidor HTTP (serverHttp/index.js):
Proporciona una API HTTP con dos endpoints.
Retorna información sobre la API y los mensajes guardados.
📦 Dependencias
cors: Permite habilitar CORS en la API HTTP.
dotenv: Gestiona variables de entorno desde .env.
express: Framework para construir la API HTTP.
readline-sync: Permite interacciones de línea de comando con el usuario.

