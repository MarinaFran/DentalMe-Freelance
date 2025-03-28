# 🚀 Getting Started

## 📥 Install App

Antes de instalar las dependencias, asegúrate de que las versiones de los paquetes de React sean compatibles con la versión de Node.js que estás utilizando. La versión de React utilizada en este proyecto se encuentra especificada en el archivo `package.json`.

### 📌 Instalación de dependencias
Ejecuta el siguiente comando para instalar todas las dependencias necesarias:
```sh
npm install
```

## 🏃‍♂️ Run Scripts

### ▶️ `npm start`

Inicia la aplicación en modo de desarrollo.
Abre [http://localhost:3000](http://localhost:3000) en tu navegador para verla en ejecución.

## 🔧 Construcción y despliegue

Para que el hosting pueda subir los archivos, necesitamos generar el directorio `build` ejecutando el siguiente comando:
```sh
npm run build
```

Para sincronizar los cambios en Firebase, ejecuta el siguiente comando:
```sh
firebase deploy --only hosting
```

## ⚠️ Opción de Eject

### 🔄 `npm run eject`

**⚠️ Nota: esta es una operación irreversible. Una vez que ejecutes `eject`, no podrás revertir los cambios.**

Si no estás satisfecho con la herramienta de construcción y las opciones de configuración predeterminadas, puedes ejecutar `eject` en cualquier momento. Este comando eliminará la dependencia única de `react-scripts` y copiará todos los archivos de configuración y dependencias transitivas (webpack, Babel, ESLint, etc.) directamente en tu proyecto para que tengas control total sobre ellas.

Todos los comandos, excepto `eject`, seguirán funcionando, pero apuntarán a los scripts copiados, permitiéndote personalizarlos según sea necesario.

No es obligatorio usar `eject`. La configuración predeterminada es adecuada para la mayoría de los despliegues pequeños y medianos. Sin embargo, entendemos que esta herramienta puede ser útil si necesitas una mayor personalización.

## 🌍 Deployment

Para más detalles sobre el despliegue, visita: [📖 Guía de despliegue de Create React App](https://facebook.github.io/create-react-app/docs/deployment)

## 🛠️ Solución de problemas

Si `npm run build` falla al minificar, consulta la siguiente sección de la documentación oficial:
[🔍 Solución de problemas](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

