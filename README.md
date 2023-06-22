# TRI - Equalização

Notebook para comparação dos diferentes tipos de equalização.

<!-- TABLE OF CONTENTS -->
## Conteúdos

  * [TRI - Equalização](#tri---equalização)
  * [Pré Requisitos](#pré-requisitos)
  * [Preparação do Ambiente](#preparação-do-ambiente)
  * [Execução do código](#execução-do-código)
  * [Contribuições](#contribuições)


<!-- REQUIREMENTS -->
## Pré Requisitos
  - [Instalação do Git](https://git-scm.com/downloads)>2.40
  - [Instalação do R](https://cran.r-project.org/)>4.2
    1. Uma IDE, como o [RStudio](https://posit.co/download/rstudio-desktop/) ou [VS Code](https://code.visualstudio.com/) facilita a programação em R
  - [Instalação do Python](https://www.python.org/downloads/)>3.10
    1. Assim como em R, o [VS Code](https://code.visualstudio.com/) facilita a programação em Python
  - [Instalção do Jupyter Notebook](https://jupyter.org/install)
    1. É possível abrir arquivos `.ipynb` através de IDEs, como o [VS Code](https://code.visualstudio.com/)

<!-- SETTING THE ENVIRONMENT -->
## Preparação do Ambiente

Depois de instalar todos os pré requisitos, iremos fazer as preparações de ambiente necessárias. Escolha uma pasta para instalar este repositório.
  
  1. [Configuração do Git](https://docs.github.com/en/get-started/quickstart/set-up-git#setting-up-git)
  
  2. Com o Git configurado, dê cd na pasta
  
  ```git
  cd pasta
  ```
   
  3. Clone este repositório
  
  ```git
  git clone https://github.com/gcastro-vish/estimativa-traco-latente
  ```
  
  4. Adicione o R ao Kernel do Jupyter

 ```
 install.packages('IRkernel')
 IRkernel::installspec()
 ```
Mais detalhes sobre como adicionar o R no kernel do Jupyter [aqui](https://irkernel.github.io/installation/).
<!-- HOW TO RUN -->
## Execução do código

Depois de todas as configurações de ambientes, para executar o aplicativo basta abrir o notebook `estudos equalizacao.ipynb`.

<!-- HOW TO UPDATE -->
## Contribuições

Toda contribuição é bem-vinda! Para sugerir modificações, crie e uma _branch_ com o nome `develop-nome-modificacao` (deve necessariamente começar com _**develop**_) e altere para dentro dela. Faça as as modificações necessárias, lembrando de dar _commit_ com as mensagens de mudança e crie um _pull request_. Mais informações sobre como fazer isso estão disponíveis [aqui](https://docs.github.com/en/get-started/quickstart/contributing-to-projects). Além disso, é possível utilizar o [VS Code como uma interface gráfica para o Git](https://code.visualstudio.com/docs/sourcecontrol/overview)
