# Generative Adversarial Networks (GANs)
 - Las Redes Generativas Adversariales (GANs) son un tipo de arquitectura de redes neuronales profundas utilizadas para generar datos sintéticos, como imágenes, música o texto. Fueron propuestas por Ian Goodfellow y su equipo en 2014.

# ¿Cómo funcionan las GANs?
## Generador (Generator):
- *El generador crea datos sintéticos a partir de ruido aleatorio (por ejemplo, vectores de números).
Inicialmente, el generador produce datos de baja calidad*.
A medida que se entrena, mejora su capacidad para generar datos más realistas.
## Discriminador (Discriminator):
- *El discriminador es otro modelo que evalúa si un dato es real o generado.
Inicialmente, el discriminador no es muy bueno en distinguir entre datos reales y falsos*.
A medida que se entrena, se vuelve más preciso en su clasificación.
# Entrenamiento adversarial:
- El generador y el discriminador se entrenan en un proceso adversarial.
- El generador intenta engañar al discriminador generando datos más realistas.
- El discriminador aprende a ser más preciso en su clasificación.

# Equilibrio y convergencia:
- Durante el entrenamiento, el generador y el discriminador se ajustan mutuamente.
Idealmente, llegan a un equilibrio en el que el generador produce datos indistinguibles de los reales.
# Aplicaciones de las GANs:
1. Generación de imágenes(En este caso): Las GANs pueden crear imágenes realistas de personas, paisajes, objetos, etc.
2. Edición de imágenes: Pueden modificar imágenes existentes (por ejemplo, cambiar el fondo o añadir elementos).
3. Síntesis de voz y música: Generan voces o melodías sintéticas.
4. Traducción de estilo: Transforman una imagen en el estilo de otra (por ejemplo, convertir una foto en un estilo de pintura famoso).
