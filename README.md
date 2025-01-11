# Classificação Multiclasse em Sistemas de Interface Cérebro-Máquina Baseados em Potenciais Visualmente Evocados
Este repositório contém a implementação de uma abordagem para classificação multiclasse em sistemas de Interface Cérebro-Máquina (ICM) baseados em Potenciais Visualmente Evocados de Estado Estável (SSVEP). O objetivo principal é explorar técnicas avançadas de processamento de sinais e machine learning para classificar estímulos visuais registrados em sinais de Eletroencefalograma (EEG). As Interfaces Cérebro-Máquina são ferramentas inovadoras que permitem o controle de dispositivos externos por meio da atividade cerebral, sendo particularmente úteis para pessoas com limitações motoras. Neste projeto, utilizamos o potencial do SSVEP, que usa respostas cerebrais a estímulos visuais constantes, para viabilizar o reconhecimento e controle de comandos. O trabalho envolve as etapas fundamentais:
  - Aquisição dos Sinais EEG - Captura da atividade cerebral utilizando dispositivos de EEG.
  - Pré-Processamento - Filtragem e manipulação dos sinais para remoção de ruídos.
  - Extração de Características - Identificação de padrões relevantes nos sinais cerebrais.
  - Classificação Multiclasse - Uso de técnicas de aprendizado de máquina para classificar diferentes estímulos visuais.
  - Técnicas de Ensemble - Combinação de classificadores para melhorar a precisão e robustez do modelo.

# Estrutura do Repositório
- notebooks/: Contém os notebooks .ipynb com as implementações completas das etapas do projeto, desde o pré-processamento até a classificação.
- PDF: Artigo realizado a partir das analises.
- README.md: Este arquivo.

# Tecnologias e Ferramentas Utilizadas
- As principais bibliotecas e tecnologias empregadas neste projeto incluem:
  - Manipulação e Processamento de Sinais: scipy, numpy, matplotlib, seaborn
  - Aprendizado de Máquina: scikit-learn (Logistic Regression, SVM, Random Forest, AdaBoost, Gradient Boosting, lightgbm)
  - Técnicas de Ensemble: Voting Classifier, Boosting..
  - Métricas de Avaliação: accuracy_score, confusion_matrix, classification_report

#Como Utilizar
- Clone o Repositório : git clone https://github.com/seu-usuario/seu-repositorio.git
- Instale as Dependências

# Contribuições
- Contribuições são bem-vindas! Se você deseja melhorar este projeto, abra uma issue ou envie um pull request.
