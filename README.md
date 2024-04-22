# SISPRECAS-Soft

# Carpetas del proyecto

proyecto-elecciones
├── .git
│  ├── hooks
│  │  ├── applypatch-msg.sample
│  │  ├── commit-msg.sample
│  │  ├── fsmonitor-watchman.sample
│  │  ├── post-update.sample
│  │  ├── pre-applypatch.sample
│  │  ├── pre-commit.sample
│  │  ├── pre-merge-commit.sample
│  │  ├── pre-push.sample
│  │  ├── pre-rebase.sample
│  │  ├── pre-receive.sample
│  │  ├── prepare-commit-msg.sample
│  │  ├── push-to-checkout.sample
│  │  └── update.sample
│  ├── info
│  │  └── exclude
│  ├── logs
│  │  ├── refs
│  │  │  └── heads
│  │  │     └── main
│  │  └── HEAD
│  ├── objects
│  │  ├── info
│  │  └── pack
│  ├── refs
│  │  ├── heads
│  │  │  └── main
│  │  └── tags
│  ├── COMMIT_EDITMSG
│  ├── HEAD
│  ├── config
│  ├── description
│  └── index
├── controllers
│  ├── candidatos.js
│  ├── consultas.js
│  ├── departamentos.js
│  ├── formularioe14.js
│  ├── login.js
│  ├── mesas.js
│  ├── municipios.js
│  ├── partidos.js
│  ├── puestosdevotacion.js
│  ├── register.js
│  ├── roles.js
│  ├── usuarios.js
│  └── zonas.js
├── db
│  ├── connection.js
│  ├── queries.sql
│  ├── tesis.sql
│  ├── update-candidatos.sql
│  └── views.sql
├── frontend
│  ├── public
│  │  ├── images
│  │  │  ├── opciones-de-voto
│  │  ├── favicon.ico
│  │  ├── index.html
│  │  ├── logo.png
│  │  ├── logo192.png
│  │  ├── logo512.png
│  │  ├── manifest.json
│  │  ├── robots.txt
│  │  └── user.png
│  ├── src
│  │  ├── components
│  │  │  ├── common
│  │  │  │  ├── CardsResultados.js
│  │  │  │  ├── DocPdf.js
│  │  │  │  ├── FormUsuario.js
│  │  │  │  └── VistaPdf.js
│  │  │  ├── hooks
│  │  │  │  ├── CandidatosProvider.js
│  │  │  │  ├── FiltrosProvider.js
│  │  │  │  ├── FormularioProvider.js
│  │  │  │  ├── MesasProvider.js
│  │  │  │  ├── ResultadosProvider.js
│  │  │  │  └── UsuariosProvider.js
│  │  │  ├── pages
│  │  │  │  ├── AgregarUsuario.js
│  │  │  │  ├── Consultas.js
│  │  │  │  ├── ConsultasMesasEnviadas.js
│  │  │  │  ├── DetalleUsuario.js
│  │  │  │  ├── EditarUsuario.js
│  │  │  │  ├── Envios.js
│  │  │  │  ├── Error404.js
│  │  │  │  ├── FormularioE14.js
│  │  │  │  ├── Inicio.js
│  │  │  │  ├── Login.js
│  │  │  │  ├── Perfil.js
│  │  │  │  ├── Resultados.js
│  │  │  │  └── Usuarios.js
│  │  │  ├── tests
│  │  │  │  ├── inicio.test.js
│  │  │  │  ├── resultados.test.js
│  │  │  │  └── usuario.test.js
│  │  │  ├── ui
│  │  │  │  ├── Footer.js
│  │  │  │  ├── Header.js
│  │  │  │  ├── Modal.js
│  │  │  │  ├── Notificacion.js
│  │  │  │  └── Spinner.js
│  │  │  ├── App.js
│  │  │  ├── Layout.js
│  │  │  └── ProtectRoute.js
│  │  ├── images
│  │  │  ├── opciones-de-voto
│  │  │  │  ├── user.png
│  │  │  │  ├── votos-blancos.png
│  │  │  │  ├── votos-no-marcados.png
│  │  │  │  └── votos-nulos.png
│  │  │  ├── bg-home.jpg
│  │  │  ├── candidato-lider.png
│  │  │  ├── logo-elecciones.png
│  │  │  ├── logo-full.png
│  │  │  ├── logo-sisprecas-soft.png
│  │  │  ├── politico.png
│  │  │  └── user-icon.png
│  │  ├── services
│  │  │  ├── mesas.js
│  │  │  └── usuarios.js
│  │  ├── utils
│  │  │  └── utils.js
│  │  ├── index.css
│  │  └── index.js
│  ├── LICENSE
│  ├── package-lock.json
│  ├── package.json
│  ├── postcss.config.js
│  └── tailwind.config.js
├── tests
│  ├── teardown.js
│  └── usuarios_api.test.js
├── uploads
│  └── images
│     ├── candidatos
│     │  ├── alba-rocio-romero-garcia.png
│     │  ├── cesar-augusto-ortiz-zorro.png
│     │  ├── guillermo-alexander-velandia-granados.png
│     │  ├── hector-manuel-balaguera-quintana.png
│     │  ├── jacobo-rivera-gomez.png
│     │  ├── joel-olmos-cordero.png
│     │  ├── luis-alexis-garcia-barrera.png
│     │  ├── marisela-duarte-rodriguez.png
│     │  └── rubiela-benitex-enriquez.png
│     ├── partidos
│     │  ├── centro-democratico.jpg
│     │  ├── coalicion-por-casanare.png
│     │  ├── firmes-por-el-cambio.png
│     │  ├── fuerza-ciudadana.jpg
│     │  ├── fuerza_democratica.jpg
│     │  ├── la-fuerza-de-la-paz.jpg
│     │  ├── liga-anticorrupcion.jpg
│     │  ├── pacto-historico.png
│     │  └── salvacion-nacional.jpg
│     ├── users
│  ├── config.js
│  ├── logger.js
│  └── middleware.js
├──  .eslintrc.js
├── LICENSE
├── README.md
├── app.js
├── index.js
├── jest.config.js
├── package-lock.json
├── package.json
└── vercel.json



## Backend

### 1. Crear una base de datos con PostgreSQL

Usar el script de la ubicación /db/tesis.sql

### 2. Crear un archivo .env en la raíz del proyecto:

### 3. Definir las variables de entorno:

- PORT : Puerto que usuará Express para iniciar el proyecto en local, en caso de estar ejecutandose en producción, este se ajustará automáticamente según el entorno en producción, a menos que el servidor donde se vaya a alojar indique que se debe especificar, en caso tal se usará no solamente en local, sino también en producción.
- DB_USER : Usuario con permisos para utilizar la base de datos
- DB_USER_PASSWORD : Contraseña de usuario con acceso a la base de datos
- DB_DATABASE = Nombre de la base de datos
- DB_HOST = Hostname o IP de la base de datos. Por defecto es 'localhost'
- DB_PORT = Puerto de postgreSQL. Por defecto 5432
- TEST_PORT = Puerto de postgreSQL para testing. Por defecto 5432
- TEST_DB_USER = Usuario de la base de datos con permisos sobre la base de datos de testing
- TEST_DB_USER_PASSWORD = Contraseña de usuario de la base de datos de testing
- TEST_DB_DATABASE = Nombre de base de datos de testing
- TEST_DB_HOST = Hostname o IP de la base de datos de testing. Por defecto es 'localhost'
- TEST_DB_PORT =5432
- SECRET = Frase de seguridad de su preferencia, para codificar y decodificar el token generado para autenticación. ESTE PASO ES ESENCIAL, PARA PODER GESTIONAR LA SEGURIDAD DE LA AUTENTICACIÓN. Nunca revele este código o lo deje visible ene el código. 

```bash
    PORT =4000
    DB_USER =
    DB_USER_PASSWORD =
    DB_DATABASE =
    DB_HOST ='localhost'
    DB_PORT =5432
    TEST_PORT =
    TEST_DB_USER =
    TEST_DB_USER_PASSWORD = 
    TEST_DB_DATABASE =
    TEST_DB_HOST = 'localhost'
    TEST_DB_PORT =5432
    SECRET = 'colombia_patria_mia'
```

### 4. Incluir el archivo .env en el archivo .gitignore

Para prevenir filtrar información sensible del proyecto como APIS, claves, frases SECRET, tokens, urls de conexión se debe realizar este proceso:

```bash
# .gitignore
.env
```

### 5. Crear una cuenta en Cloudinary

Dado que se va ha utilizar un serveless, como vercel, vamos en este caso a manejar los archivos en el servicio de Cloudinary, usando la API que ellos proveen y que en este caso se va ha integrar con Node (backend Express). Para esto es necesario agregar los datos provistos por Cloudinary a nuestro archivo .env del backend y que se pueden encontrar en la sección "Dashboard" de esa plataforma:

```bash
CLOUD_NAME = nameCloudinary 
API_KEY = apiKeyCloudinary
API_SECRET = apiSecretCloudinary 
```

**NOTA**: Para crear el archivo .env puede usar el archivo .env.example como plantilla, sino puede usar la información ya indicada para definir las variables de entorno. Recuerde que los valores de estas variables son personalizados a su proyecto.

## Ejecutar proyecto

### Backend

Usando la terminal, ejecutar:

```bash
npm run dev
```

Url por defecto: http://localhost:4000



### Frontend

**NOTA**: Antes de ejecutar el proyecto, asegurese de que el proyecto backend se esté ejecundo.

Situarse en la raiz del directorio frontend en la terminal y ejecutar:

```bash
cd frontend
npm install # La primera vez para descargar las dependencias
npm start 
```

Url por defecto: http://localhost:3000

### Generar usuario Administrador

Usando POSTMAN, o su cliente de preferencia, realice un petición POST a la URL 'http://localhost:4000/register', enviando en el body como raw/json el siguiente json personalizado con sus datos:

```JSON
{
    "nom_usuario": "su_nombre",
    "clave_usuario": "su_contraseña",
}
```

**NOTA**: Está opción se podrá usar una única vez.

Ahora podrá loguearse desde 'http://localhost:4000/login' con los datos:

**Correo electrónico**: 'admin@gmail.com',
**Contraseña**: 'la asignada en el paso anterior'

**JOIN**
