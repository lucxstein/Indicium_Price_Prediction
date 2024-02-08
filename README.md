## Instalação

### Python

 Certifique-se de ter o Python instalado em sua máquina. Se você não tiver o Python instalado, pode baixá-lo em [python.org](https://www.python.org/).

### Jupyter Notebook

Caso não tenha o Jupyter instalado, você pode usar o pip para fazê-lo, o gerenciador de pacotes do Python. Execute o seguinte comando no terminal:

    
    pip install jupyter
    

## Executando o Projeto

1. Clone o repositório para o seu ambiente local:

    
    git clone https://github.com/lucxstein/Indicium_Price_Prediction.git
    

2. Navegue até o diretório do projeto:

    
    cd Indicium_Price_Prediction
    

3. Instale as dependências usando pip e o arquivo requirements.txt fornecido:

    
    pip install -r requirements.txt
    

4. Inicie o Jupyter Notebook:

    
    jupyter notebook
    

5. No navegador da web que se abrirá, localize o arquivo Projeto_Indicium.ipynb e clique nele para abrir o notebook.

6. Siga as instruções no notebook para executar o código do projeto e interagir com o modelo de machine learning.

## Arquivo PKL

O repositório também inclui um arquivo LH_CD_LucasStein.pkl, que é um arquivo serializado contendo o modelo de machine learning treinado. Você pode carregar este arquivo usando a biblioteca joblib ou pickle para fazer previsões com o modelo treinado sem a necessidade de re-treiná-lo.
