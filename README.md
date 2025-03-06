
# EduClima: Generación de Contenido Educativo sobre Cambio Climático utilizando Fast Prompting con Groq

## Introducción

Este proyecto busca mejorar la generación de contenido educativo sobre cambio climático mediante técnicas avanzadas de Fast Prompting con la plataforma Groq. Utiliza Zero-Shot y Few-Shot prompting para optimizar respuestas relevantes y útiles en el contexto educativo.

## Objetivos

- **Demostrar comprensión profunda sobre Fast Prompting** aplicado al contexto educativo ambiental.
- **Experimentar diferentes configuraciones** para maximizar eficacia en respuestas generadas por AI.
- **Preparar demostraciones efectivas** usando Jupyter Notebooks mostrando funcionalidades reales del sistema propuesto.

## Metodología

1. **Investigación previa**: Revisión exhaustiva sobre técnicas avanzadas de prompting.
2. **Implementación práctica**: Uso de Jupyter Notebooks para integrar Groq API.
3. **Evaluación**: Comparativa entre diferentes configuraciones.

## Herramientas y Tecnologías

- **Groq API**: Utilizada para modelos texto-texto.
- **Leonardo AI**: Utilizada para la generación de imágenes educativas.


## Implementación

### Código de Ejemplo

from groq import Groq

Inicializar cliente con API Key
cliente = Groq(api_key="xxxxxxxxxxxxxxxxxxxxxx")

Configuración del prompt few-shot
prompt_few_shot = [
{"role": "assistant", "content": "- Las principales causas incluyen la quema de combustibles fósiles, la deforestación y procesos industriales."},
{"role": "user", "content": "- ¿Cómo afecta el cambio climático a los ecosistemas acuáticos?"},
# ... (resto de la secuencia)
]

Solicitud final
respuesta_final = cliente.chat.completions.create(
model="llama3-8b-8192",
messages=prompt_few_shot,
)

print(respuesta_final.choices.message.content)

### Visualización de Imágenes
### [Generación de Imágenes con Leonardo AI](pplx://action/followup)

Se utilizó Leonardo AI para crear imágenes educativas que ilustran conceptos clave sobre cambio climático. Estas imágenes se generaron a partir de descripciones específicas diseñadas para complementar el contenido textual.

**[Descripción de la Imagen](pplx://action/followup):**
"Un estudiante frente a una computadora, rodeado de libros sobre sostenibilidad y un póster grande sobre cambio climático en el fondo. La iluminación es cálida y acogedora."

## [Resultados](pplx://action/followup)

El proyecto demuestra cómo las técnicas de Fast Prompting pueden mejorar significativamente la calidad del contenido educativo sobre cambio climático. Las respuestas generadas son relevantes y útiles para estudiantes interesados en el tema. Las imágenes generadas por Leonardo AI complementan efectivamente el aprendizaje visual.

## [Conclusiones](pplx://action/followup)

Este proyecto muestra el potencial de las técnicas de Fast Prompting para mejorar la educación ambiental. Las acciones individuales pueden influir en políticas públicas más amplias si son adoptadas por comunidades enteras.

## [Referencias](pplx://action/followup)

- [Groq API Documentation](https://console.groq.com/docs/prompting)
- [Leonardo AI](https://leonardo.ai/) - Herramienta utilizada para la generación de imágenes.

## [Contribuciones](pplx://action/followup)

Si deseas contribuir a este proyecto, puedes mejorar la secuencia de prompts o integrar nuevas herramientas para texto-imagen.


## Contacto
Para preguntas o más información sobre este proyecto, puedes contactarme a través de mi correo electrónico: [dario@galant.com]. 


 
## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

blue
m jk

## Demo

Insert gif or link to demo


## Documentation

[Documentation](https://linktodocumentation)


## FAQ

#### Question 1

Answer 1

#### Question 2

Answer 2


## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?


## Roadmap

- Additional browser support

- Add more integrations


![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


## Usage/Examples

```javascript
import Component from 'my-project'

function App() {
  return <Component />
}
```

