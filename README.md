# Aumento de datos en Retinopatía Diabética implementando DCGAN y cWGAN-GP

En este trabajo se estudia la generación de retinografías sintéticas a partir de datasets públicos de Kaggle, evaluando modelos basados en GANs para apoyar estrategias de aumento de datos en clasificación de retinopatía diabética. Se implementa un flujo de preprocesamiento de imágenes y se entrenan modelos generativos (DCGAN y cWGAN-GP). Los resultados se analizan visualmente y se discuten las diferencias de estabilidad y calidad de generación entre los enfoques evaluados.

## Estructura del repositorio
- `informe/`
  - Informe final del proyecto en PDF
- `notebooks/`
  - `cWGAN-GP/`
    - `Preprocesamiento_Dataset_APTOS_120x120_cWGAN.ipynb`
    - `cWGAN-GP_APTOS_Retinal_Image_Generation.ipynb`
  - `DCGAN/`
    - `DCGAN_APTOS_Sev4_256x256.ipynb`

## Orden sugerido de lectura y ejecución
1. `notebooks/cWGAN-GP/Preprocesamiento_Dataset_APTOS_120x120_cWGAN.ipynb`
2. `notebooks/cWGAN-GP/cWGAN-GP_APTOS_Retinal_Image_Generation.ipynb`
3. `notebooks/DCGAN/DCGAN_APTOS_Sev4_256x256.ipynb`

## Requisitos
- Python 3.9+
- PyTorch, torchvision
- numpy, pandas, matplotlib
- Pillow
- tqdm

> Nota: Los notebooks fueron ejecutados con GPU (CUDA).

## Datasets
Por motivos de tamaño y licencia, los datasets no se incluyen en este repositorio. En el informe se incluyen los enlaces a Kaggle.

## Autora
Karina Cardozo
