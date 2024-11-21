# Web Moderna

## AUTOR

- ***Nombre completo: YSRAEL ROJAS ROJAS***
- ***Nombre del curso: CODE 201***
- ***Email: <yrra.rojas@gmail.com>***
- ***Fecha creacion proyecto: 19/11/2024***

## SOBRE EL PROYECTO

La web moderna es interactiva, dinámica y centrada en el usuario. Se basa en tecnologías como HTML5, CSS3 y JavaScript, complementadas por frameworks y bibliotecas como React, Vue, y Angular para crear experiencias rápidas y responsivas. Usa APIs para integrarse con servicios externos, y la nube para escalabilidad y almacenamiento. La seguridad (HTTPS) y el diseño adaptable (responsive) son esenciales, optimizando la experiencia en múltiples dispositivos. También incluye características avanzadas como aplicaciones progresivas (PWAs), accesibilidad (WCAG) y uso de IA en interfaces inteligentes.

## ESLINTRC

### Configuracion General

```json
"env": {
  "browser": true,
  "es2021": true
}
```

1. ***env:*** Define los entornos en los que el código será ejecutado.

- ***browser:true*** Indica que el código se ejecutará en un navegador, habilitando globales como window y document.
- ***es2021:true*** Especifica que el código utiliza características de ECMAScript 2021 (ES12), como Promise.any o WeakRefs.

```json
"extends": ["eslint:recommended"]

```

2.***extends***: Indica que este archivo hereda reglas base.

- ***eslint:recommended***: Incluye un conjunto predeterminado de reglas recomendadas por ESLint para buenas prácticas y evitar errores comunes.

```json
"parserOptions": {
  "ecmaVersion": "latest",
  "sourceType": "module"
}

```

3.***parserOptions***: Configura cómo ESLint analiza el código.

- ***ecmaVersion: "latest"***: ESLint usará la versión más reciente de ECMAScript para interpretar el código.

- ***sourceType: "module"***: Declara que el código utiliza módulos de ES6 (import/export) en lugar de scripts clásicos.

### Reglas Personalizadas

```json
"rules": {
  "indent": ["error", 2],
  "linebreak-style": ["error", "unix"],
  "quotes": ["error", "single"],
  "semi": ["error", "always"],
  "no-unused-vars": "warn",
  "no-console": "warn"
}

```

4.***rules***: Define reglas específicas que ESLint debe aplicar al código.

- ***indent: ["error", 2]***: Enforce indentación de 2 espacios.

***"error"***: Marcará como error cualquier indentación incorrecta.
***2***: Define el número de espacios para cada nivel de indentación.

- ***linebreak-style: ["error", "unix"]***: Exige que las líneas terminen con saltos de línea tipo UNIX (\n).

***"unix"***: Especifica este formato (en lugar de windows que usa \r\n).

- ***quotes: ["error", "single"]***: Requiere el uso de comillas simples (') para cadenas de texto.

***"error"***: Lanzará un error si se usan comillas dobles sin justificación.

- ***semi: ["error", "always"]***: Obliga el uso de punto y coma (;) al final de cada sentencia.

***"always"***: Indica que siempre se debe usar el punto y coma.

- ***no-unused-vars: "warn"***: Lanza una advertencia si hay variables declaradas pero no utilizadas.

- ***no-console: "warn"***: Lanza una advertencia si se usa console (ej. console.log), ya que suele evitarse en código de producción.

## DESPLIEGUE

🏠 [***GitHub Pages***](https://ysrael-rojas.github.io/web-moderna/)
