# Patricia Fuxi Alcalde Benítez - TFG

# Generación de prendas de moda mediante IA generativa

Este proyecto es el Trabajo de Fin de Grado (TFG) de Patricia Fuxi Alcalde Benítez, presentado en la Universidad Politécnica de Madrid (UPM). El objetivo principal es investigar y comparar distintas técnicas de inteligencia artificial generativa aplicadas al diseño de moda de lujo.

## Estructura del proyecto

- **/data**: Conjunto de imágenes extraídas mediante scraping de Farfetch y Vogue Runway.
- **/models**: Implementaciones de modelos DCGAN, VAE y de difusión.
- **/results**: Imágenes generadas y gráficas de pérdida durante el entrenamiento.
- **/scraper**: Scripts de scraping y preprocesamiento.
- **/figures**: Figuras empleadas en la memoria del proyecto.

## Modelos implementados

- **DCGAN**: Implementado en TensorFlow, con y sin técnicas de *data augmentation*.
- **VAE**: Con arquitecturas compactas y profundas, usando técnicas probabilísticas para generar muestras.
- **Modelo de difusión**: Basado en PyTorch con arquitectura tipo U-Net y *forward denoising*.

## Evaluación

- Se analizan los resultados visuales generados por cada técnica.
- Se comparan las funciones de pérdida y las imágenes resultantes.
- Se discuten ventajas, limitaciones y líneas futuras de investigación.

## Objetivos

1. Implementar y comparar tres técnicas generativas de vanguardia.
2. Analizar el impacto de *data augmentation* en la generación de moda.
3. Reflexionar sobre el papel ético, social y medioambiental de la IA generativa en la industria textil.

## Licencia

Este trabajo está bajo una licencia Creative Commons «Atribución-NoComercial-CompartirIgual 4.0 Internacional». Obra derivada de [UPM-Report-Template](https://github.com/blazaid/UPM-Report-Template).

---
