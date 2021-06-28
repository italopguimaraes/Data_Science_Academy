# Deploy de Modelo de Machine Learning em Producao com App Web

*reconhecendo digitos manuscritos usando deep learning*

O objetivo desse projeto é desenvolver uma aplicação web para reconhecer digitos manuscritos usando redes neurais convolucionais, ao executar a aplicação no navegador o usuário desenha do digito usando o mouse na área indicada pelo retângulo e após clicar em prever, será exibido a previsão do digito.
O modelo foi pré-treinado e será carregado apenas no momento de realizar a previsão, a interface foi desenvolvida usando HTML, CSS e JavaScript.

Esse projeto é parte da Data Science Academy

## Software Dependencies

Make sure the `opencv-python`, `numpy`, `pandas`, `ipykernel`, `tensorflow`, `matplotlib` and `jupyter notebook` are installed:

`conda install opencv-python numpy pandas ipykernel tensorflow matplotlib jupyter notebook`

To check the software dependencies used in this project, see the link below: 

[requirements](requirements.txt)

To install software dependencies:

`conda install requirements.txt`

## Project Instructions

1. Clone the repository and navigate to the downloaded folder.

```
git clone https://github.com/Italo-Pereira-Guimaraes/Deep-Learning-Nanodegree.git
cd Project 3 - Teaching a Flying Quaricopter
```

2. Create and activate a new environment.

```
conda create -n quadcop python=3.6 matplotlib numpy pandas
source activate quadcop
```

3. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `quadcop` environment. 
```
python -m ipykernel install --user --name quadcop --display-name "quadcop"
```

4. Open the notebook.
```
jupyter notebook Quadcopter_Project.ipynb
```

5. Before running code, change the kernel to match the `quadcop` environment by using the drop-down menu (**Kernel > Change kernel > quadcop**). Then, follow the instructions in the notebook.

## Evaluation

The project was evaluated according to the following [rubric](https://review.udacity.com/#!/rubrics/1189/view)

## license
 
For more information see:

[license](LICENSE.txt)
