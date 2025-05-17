# Dataset HCC

- HCC, Carcinoma Hepatocelular, é o sexto cancro mais frequentemente diagonosticado, representa mais de 90% dos principais cancros do fígado. O tratamento utilizado para combater o cancro pode não ser o mesmo para pacientes específicos devido as avalições clínicas e as diferenças biológicas entre os pacientes. Devido a esta particularidade vários estudos têm sido realizados para ajudar no diagnóstico desta doença.   

- Neste projeto foi utilizado o dataset HCC. O dataset foi feito pelo Centro Universitario e pelo Hospital de Coimbra, que contem dados clinicos de pacientes diagnosticados com HCC. O objetivo principal é criar uma inteligência artificial capaz de prever se um paciente diagnosticado com HCC irá sobreviver após 1 ano.

## Download do programa e sua execução

- Para que o programa seja executado é necessário que tenha o python instalado; caso não tenha, escreva no terminal o seguinte código:

		$ sudo apt install python3

- É necessário ter o jupyter instalado no seu computador; caso não tenha, escreva no terminal o seguinte codigo:

        $ pip install jupyter

- Além disso, é necessário ter as bibliotecas matmatplotlib, scikit-learn, pandas, seaborn e numpy; caso não tenha as bibliotecas digite no terminal os seguintes comandos:

        $ pip install matplotlib==3.8.4
        $ pip install scikit-learn==1.4.2
        $ pip install seaborn==0.13.2
        $ pip install pandas==2.2.2
        $ pip install numpy==1.26.4

- Para usar o notebook é necessário que o dataset tenha a extensão .csv e esteja no mesmo diretório que o notebook.

- Após certeficar-se que tem todos os requisitos necessários pode executar o programa abrindo o ficheiro trabalho.ipynb no VsCode e utilize o botão "Executar Tudo".


## Características do Projeto

- Neste projeto foi utilizado 2 algorítmos de supervised learning, Decision Tree e o K-NN. 
Comparamos as efeciências de ambos os algoritmos através de vários metodos como por exemplo matriz de confusão, o ROC/AUC e curva de aprendizagem.

# Créditos 

Criado por Paulo Diogo Lopes Pinto (Diogoxyz), Filipe Neto Leão (Filipe-Leao), João Pedro Nunes Rocha (jpnr05).
