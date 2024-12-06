# AI Profile Questionnaire

Una aplicación interactiva que ayuda a los usuarios a descubrir su perfil de uso de Inteligencia Artificial y obtener recomendaciones personalizadas para herramientas y proyectos.

## 🎯 Objetivo

Ayudar a los participantes a:
- Identificar qué herramientas de IA se adaptan mejor a su perfil
- Descubrir proyectos potenciales que pueden desarrollar
- Mejorar su capacidad para estructurar prompts efectivos
- Encontrar su camino en diferentes campos profesionales:
  - Artes visuales y diseño
  - Tecnología y ciencia
  - Negocios y gestión
  - Ciencias sociales
  - Contenido multimedia

## 🏗 Estructura del Proyecto

### Sistema de Análisis de Prompts
```
src/utils/prompts/
  ├── analysis/           # Módulos de análisis avanzado
  │   ├── contextAnalyzer.ts    # Análisis de contexto y propósito
  │   ├── semanticAnalyzer.ts   # Análisis semántico y coherencia
  │   └── structureAnalyzer.ts  # Análisis de estructura y formato
  ├── promptScoring.ts    # Sistema de puntuación
  ├── promptValidation.ts # Validación de prompts
  ├── promptSuggestions.ts # Generación de sugerencias
  └── types.ts           # Definiciones de tipos
```

### Componentes Principales
```
src/
  ├── components/
  │   ├── forms/         # Componentes de formulario reutilizables
  │   │   └── specialized/ # Formularios específicos por área
  │   ├── sections/      # Secciones principales del cuestionario
  │   │   ├── prompts/   # Componentes de evaluación de prompts por área
  │   │   └── areas/     # Componentes de áreas de aplicación por especialidad
  │   └── layout/        # Componentes de estructura y navegación
  ├── utils/             # Utilidades y funciones auxiliares
  ├── types/             # Definiciones de tipos TypeScript
  ├── store/             # Estado global con Zustand
  └── constants/         # Constantes y configuraciones
```

### Sistema de Evaluación de Prompts

#### Análisis Contextual
- Detección automática del área temática
- Evaluación del nivel de complejidad
- Identificación del propósito del prompt

#### Análisis Semántico
- Evaluación de claridad y coherencia
- Medición de relevancia contextual
- Análisis de intencionalidad

#### Análisis Estructural
- Detección del formato utilizado
- Evaluación de complejidad estructural
- Análisis de organización y completitud

## 💻 Tecnologías Utilizadas

- React + TypeScript
- Tailwind CSS para estilos
- Zustand para gestión de estado
- Sistema avanzado de análisis de prompts
- Vite como bundler

## 🚀 Características

- Interfaz intuitiva y responsiva
- Sistema de análisis de prompts multicapa
- Evaluación especializada por área
- Recomendaciones contextualizadas
- Diseño moderno y accesible
- Formularios dinámicos especializados
- Sistema de tipos robusto
- Arquitectura modular y mantenible

## 📋 Perfiles de Usuario

### Perfil Artístico Visual
- Enfoque en artes visuales y diseño
- Herramientas: DALL-E, Midjourney, Stable Diffusion
- Evaluación de capacidades creativas
- Recomendaciones de proyectos artísticos

### Perfil Técnico/Científico
- Enfoque en desarrollo y ciencia
- Herramientas: TensorFlow, PyTorch, Scikit-learn
- Evaluación de capacidades técnicas
- Proyectos de machine learning y análisis

### Perfil Empresarial
- Enfoque en negocios y gestión
- Herramientas: Tableau, Power BI, Salesforce Einstein
- Evaluación de necesidades comerciales
- Proyectos de optimización y análisis

### Perfil Científico Social
- Enfoque en investigación social
- Herramientas: SPSS, NVivo, ATLAS.ti
- Evaluación de metodologías
- Proyectos de investigación social

### Perfil Multimedia
- Enfoque en contenido digital
- Herramientas: Runway ML, Soundraw, Synthesia
- Evaluación de producción multimedia
- Proyectos de contenido digital

## 🌟 Beneficios

- Orientación especializada por área
- Desarrollo de habilidades específicas
- Descubrimiento de herramientas relevantes
- Plan de desarrollo personalizado
- Recursos focalizados por especialidad

## 🛠 Desarrollo Local

1. Clonar el repositorio
2. Instalar dependencias:
```bash
npm install
```
3. Iniciar el servidor de desarrollo:
```bash
npm run dev
```

## 📚 Recursos Adicionales

El cuestionario incluye por área:
- Ejemplos prácticos especializados
- Ejercicios interactivos adaptados
- Guías de mejora específicas
- Recursos de aprendizaje personalizados
- Comunidad de práctica

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor:
1. Haz fork del repositorio
2. Crea una rama para tu feature
3. Envía un pull request con tus cambios

## 📝 Licencia

MIT License - siéntete libre de usar y modificar este proyecto para tus necesidades.