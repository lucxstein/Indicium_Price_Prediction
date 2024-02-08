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
    

3. Instale as dependências usando pip e o arquivo requirements.txt fornecido nesse repositório:

    
    pip install -r requirements.txt
    

4. Inicie o Jupyter Notebook:

    
    jupyter notebook
    

5. No navegador da web que se abrirá, localize o arquivo Projeto_Indicium.ipynb e clique nele para abrir o notebook.

6. Siga as instruções no notebook para executar o código do projeto e interagir com o modelo de machine learning.

## Arquivos no Repositório

O repositório inclui os seguintes arquivos:

- Projeto_Indicium.ipynb: O notebook Jupyter contendo a EDA e o código do modelo de machine learning.
- LH_CD_LucasStein.pkl: O arquivo serializado contendo um modelo de machine learning já treinado e pronto para ser utilizado através de uma API.
- teste_indicium_precificacao.csv: O arquivo CSV contendo os dados usados no projeto.
- requirements.txt: O arquivo txt com todos os pacotes e suas respectivas versões utilizadas no projeto.
