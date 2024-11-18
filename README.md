# Sistema de Recomendación de Películas Basado en Análisis de Sentimientos

## Descripción del Caso de Uso

En el contexto actual del cine, la gran cantidad de películas disponibles puede resultar abrumadora para los espectadores, quienes a menudo buscan recomendaciones personalizadas que se alineen con sus gustos. Un sistema de recomendación de películas bien diseñado no solo mejora la experiencia del usuario al sugerir contenido relevante, sino que también ayuda a las plataformas a maximizar la retención de clientes y aumentar el tiempo de visualización, factores críticos para su éxito comercial. Sin un sistema efectivo, los usuarios podrían sentirse frustrados al buscar nuevas películas o abandonar la plataforma debido a una falta de conexión con el contenido disponible.

Este proyecto tiene como objetivo desarrollar un sistema de recomendación basado en Procesamiento de Lenguaje Natural (NLP) que analice críticas cinematográficas en español, facilitando la elección de contenidos y mejorando la experiencia del usuario. La necesidad de un sistema de recomendación es especialmente relevante en un mercado saturado, donde múltiples plataformas compiten por atraer a los espectadores. Como señala Paschos (2023), *"los sistemas de recomendación abordan el problema de la sobrecarga de información al filtrar contenido según los intereses y preferencias del usuario, lo que es crucial para mejorar la experiencia del cliente en plataformas digitales"*. De este modo, nuestra propuesta ayudará a los espectadores a evitar la tediosa tarea de navegar entre la vasta cantidad de contenido disponible en línea.

### Preguntas de Investigación
1. **¿Cómo se pueden clasificar las críticas de películas en categorías como "positivas", "neutras" y "negativas"?**  
   La clasificación de las críticas de películas en estas categorías es un problema típico de análisis de sentimientos dentro del campo de la Minería de Texto y NLP. Este proceso implica analizar el texto de las críticas para determinar la polaridad de cada comentario, es decir, si refleja una percepción favorable, neutral o desfavorable sobre la película. Para esta pregunta, aplicaremos técnicas de NLP como el análisis de sentimientos.
   
2. **¿Es posible clasificar las películas o incluso los géneros en función de las emociones expresadas en las críticas de los usuarios?**  
   El enfoque de análisis de sentimientos se puede extender para clasificar películas o géneros basados en las emociones expresadas en las críticas. Mientras que el análisis de polaridad clasifica los textos en "positivo", "neutral" o "negativo", el análisis de emociones identifica categorías emocionales más detalladas, como "alegría", "tristeza", "ira", "miedo", "sorpresa" o "disgusto". Para esta pregunta, agruparemos las películas y posteriormente los géneros según las categorías emocionales derivadas del análisis de las críticas.

---

## Descripción del Conjunto de Datos (Dataset)

Para este proyecto, utilizaremos dos datasets obtenidos de la plataforma Kaggle. A continuación, se proporciona una breve descripción de cada uno:

### 1. Primer Dataset: Críticas de Películas en Filmaffinity
- **Autor**: Moya R. (2021)
- **Descripción**: Este dataset incluye críticas de películas en español obtenidas del sitio web Filmaffinity, con opiniones sobre más de 50 películas españolas.
- **Campos**: `film_name`, `gender`, `film_avg_rate`, `review_rate`, `review_title`, `review_text`.

### 2. Segundo Dataset: Críticas Filmaffinity Netflix
- **Autor**: Mos A. (2024)
- **Descripción**: Contiene críticas en español del sitio web Filmaffinity sobre 1,000 películas y series españolas disponibles en la plataforma NETFLIX. Este dataset fue inspirado en el primero y tiene una estructura similar en cuanto a los campos y atributos que contiene.
- **Campos**: `film_name`, `gender`, `film_avg_rate`, `review_rate`, `review_title`, `review_text`.

### Atributos Comunes de los Datasets
| **Atributo**       | **Descripción**                                             |
|--------------------|-------------------------------------------------------------|
| `film_name`        | Título de la película.                                      |
| `gender`           | Género de la película (comedia, terror, acción, etc.).      |
| `film_avg_rate`    | Nota media de la película (votos de todos los usuarios).    |
| `review_rate`      | Nota que el usuario que hace la crítica pone a la película. |
| `review_title`     | Título de la crítica.                                       |
| `review_text`      | Crítica de la película.                                     |

Ambos datasets fueron diseñados como un aporte a la comunidad hispanohablante, orientándose a ser de utilidad en tareas de Procesamiento de Lenguaje Natural (NLP) en español.

---

## Conclusión

Este proyecto tiene como objetivo abordar el problema de la sobrecarga de información en plataformas de streaming mediante un sistema de recomendación basado en análisis de sentimientos. La implementación de este sistema no solo mejorará la experiencia del usuario, sino que también proporcionará insights valiosos para las plataformas que buscan optimizar el tiempo de visualización y la retención de clientes.

---

## Licencia

Este proyecto está licenciado bajo la **Licencia MIT**. Puedes usar, modificar y distribuir el contenido de este repositorio de acuerdo con los términos de esta licencia.

---

**¡Gracias por tu interés en nuestro proyecto!**  
Si tienes preguntas, comentarios o sugerencias, no dudes en abrir un *issue* o ponerte en contacto con nosotros.
