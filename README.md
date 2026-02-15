# ProyectoFinal_Redes-neuronales-generativas-profundas

Este repositorio contiene el informe final y los notebooks del proyecto de redes generativas aplicadas a retinografías, con el objetivo de explorar la generación de imágenes sintéticas condicionadas y su potencial uso para aumento de datos en retinopatía diabética.

## Resumen
En este trabajo se estudia la generación de retinografías sintéticas a partir de datasets públicos de Kaggle, evaluando modelos basados en GANs para apoyar estrategias de aumento de datos en clasificación de retinopatía diabética. Se implementa un flujo de preprocesamiento de imágenes y se entrenan modelos generativos (DCGAN y cWGAN-GP). Los resultados se analizan visualmente y se discuten las diferencias de estabilidad y calidad de generación entre los enfoques evaluados.

## Estructura del repositorio
- `informe/`
  - Informe final del proyecto en PDF.
- `notebooks/`
  - `cWGAN-GP/`
    - `cWGAN-GP_APTOS_Retinal_Image_Generation.ipynb`
    - `Preprocesamiento_Dataset_APTOS_120x120_cWGAN.ipynb`
  - `DCGAN/`
    - `DCGAN_APTOS_Sev4_256x256.ipynb`

## Orden sugerido de lectura/ejecución
1. `notebooks/cWGAN-GP/Preprocesamiento_Dataset_APTOS_120x120_cWGAN.ipynb`
2. `notebooks/cWGAN-GP/cWGAN-GP_APTOS_Retinal_Image_Generation.ipynb`
3. `notebooks/DCGAN/DCGAN_APTOS_Sev4_256x256.ipynb`

## Requisitos
- Python 3.9+
- PyTorch, torchvision
- numpy, pandas, matplotlib
- PIL (Pillow)
- tqdm

> Nota: Los notebooks fueron ejecutados en entorno con GPU (CUDA) cuando estuvo disponible.

## Dataset
Por motivos de tamaño/licencia, los dataset no se incluyen dentro de este repositorio, pero en el informe se puede acceder al link de Kaggle.

## Autora
Karina Cardozo
