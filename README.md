# 🌎 Web3 para Latinoamérica | Aplicación DeFi desde cero

Este repositorio contiene el desarrollo de una aplicación **Web3** construida desde cero con un enfoque en **Latinoamérica**. Nuestra misión es aprovechar todo el potencial de las **finanzas descentralizadas (DeFi)** para brindar acceso justo, transparente y seguro a herramientas financieras a cualquier persona, sin importar su nivel técnico o situación económica.

## ✨ Características principales

- 🌐 Plataforma accesible y fácil de usar  
- 🔗 Integración con protocolos DeFi líderes  
- 🌎 Funcionalidades pensadas para el contexto latinoamericano  
- 📚 Educación y empoderamiento financiero  

## 🚀 Nuestra visión

Creemos que el futuro financiero es **abierto, inclusivo y descentralizado**. Este proyecto es un paso hacia esa visión.  
¡Súmate, contribuye o simplemente échale un vistazo!

---

📬 ¿Preguntas o ideas? ¡Estamos abiertos a colaboraciones!

# Guía de Configuración de Proyecto React

## Requisitos Previos

1. **Instalación de Node.js**:
   - Visita [https://nodejs.org/](https://nodejs.org/)
   - Descarga e instala la versión LTS (Soporte a Largo Plazo)
   - Después de la instalación, cierra y vuelve a abrir tu terminal

## Configuración del Proyecto

### 1. Crear el Proyecto

```bash
# Crear un nuevo proyecto React con TypeScript
npm create vite@latest . -- --template react-ts

# Instalar dependencias básicas
npm install

# Instalar paquetes adicionales útiles
npm install react-router-dom @types/react-router-dom  # Para la navegación entre páginas
npm install axios                                     # Para hacer llamadas a APIs
npm install @mui/material @emotion/react @emotion/styled  # Para componentes de UI
npm install @mui/icons-material                        # Para iconos
```

### 2. Estructura de Carpetas

```bash
# Crear estructura de carpetas
mkdir src/components
mkdir src/pages
mkdir src/services
mkdir src/hooks
mkdir src/utils
mkdir src/types
mkdir src/styles
```

### 3. Estructura del Proyecto

```
├── src/                      # Carpeta principal del código fuente
│   ├── assets/              # Para imágenes, fuentes y otros recursos estáticos
│   ├── components/          # Componentes reutilizables (botones, formularios, etc.)
│   ├── pages/              # Componentes de páginas completas
│   ├── services/           # Servicios para llamadas a API y lógica de negocio
│   ├── hooks/              # Hooks personalizados de React
│   ├── utils/              # Funciones de utilidad
│   ├── types/              # Definiciones de tipos de TypeScript
│   ├── styles/             # Estilos globales y temas
│   ├── App.tsx             # Componente principal de la aplicación
│   └── main.tsx            # Punto de entrada de la aplicación
├── public/                 # Archivos públicos estáticos
├── index.html             # Archivo HTML principal
├── package.json           # Configuración del proyecto y dependencias
├── tsconfig.json          # Configuración de TypeScript
├── vite.config.ts         # Configuración de Vite
└── README.md              # Documentación del proyecto
```

## Explicación de Tecnologías y Herramientas

### TypeScript
- Lenguaje que añade tipos a JavaScript
- Ayuda a detectar errores antes de ejecutar el código
- Mejora la experiencia de desarrollo con mejor autocompletado

### React Router
- Maneja la navegación entre páginas
- Permite crear URLs amigables
- Gestiona el historial del navegador

### Material-UI (MUI)
- Biblioteca de componentes pre-diseñados
- Proporciona un diseño consistente y profesional
- Incluye temas personalizables
- Tiene componentes responsivos

### Axios
- Cliente HTTP para hacer peticiones a APIs
- Más fácil de usar que fetch
- Maneja automáticamente errores y transformaciones

### Estructura de Carpetas Detallada

#### components/
- Componentes pequeños y reutilizables
- Ejemplo: botones, formularios, tarjetas

#### pages/
- Componentes que representan páginas completas
- Ejemplo: Home, About, Contact

#### services/
- Lógica de negocio y llamadas a API
- Ejemplo: autenticación, llamadas a backend

#### hooks/
- Lógica reutilizable entre componentes
- Ejemplo: useAuth, useForm

#### utils/
- Funciones auxiliares
- Ejemplo: formateo de fechas, validaciones

#### types/
- Definiciones de tipos de TypeScript
- Ejemplo: interfaces, tipos personalizados

#### styles/
- Estilos globales y temas
- Ejemplo: variables CSS, temas MUI

### Vite
- Herramienta de construcción moderna y rápida
- Mejor rendimiento que Create React App
- Hot Module Replacement (HMR) más rápido
- Configuración más simple

## Beneficios de esta Estructura

- **Escalabilidad**: Crece bien con proyectos grandes
- **Organización**: Mantiene el código ordenado y fácil de encontrar
- **Mantenibilidad**: Facilita el mantenimiento del código
- **Mejores Prácticas**: Sigue las convenciones de React
- **Desarrollo en Equipo**: Facilita el trabajo colaborativo

## Comandos Útiles

```bash
# Iniciar el servidor de desarrollo
npm run dev

# Construir para producción
npm run build

# Previsualizar la versión de producción
npm run preview

# Ejecutar pruebas
npm run test
```

## Recursos Adicionales

- [Documentación de React](https://reactjs.org/)
- [Documentación de TypeScript](https://www.typescriptlang.org/)
- [Documentación de Material-UI](https://mui.com/)
- [Documentación de Vite](https://vitejs.dev/)
