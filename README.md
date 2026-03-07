# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Nome do projeto

## Nome do grupo

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/company/inova-fusca">Nome do integrante 1</a>
- <a href="https://www.linkedin.com/company/inova-fusca">Nome do integrante 2</a>
- <a href="https://www.linkedin.com/company/inova-fusca">Nome do integrante 3</a> 
- <a href="https://www.linkedin.com/company/inova-fusca">Nome do integrante 4</a> 
- <a href="https://www.linkedin.com/company/inova-fusca">Nome do integrante 5</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/company/inova-fusca">Nome do Tutor</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/company/inova-fusca">Nome do Coordenador</a>


## 📜 Descrição

O Dataset de imagens selecionado foi o ECG Images Dataset , disponível em:  https://www.kaggle.com/datasets/jayaprakashpondy/ecgimages/data

Este banco de dados foi escolhido por haver imagens de eletrocardiogramas identificados como normais, com infarto do miocárdio, com batimentos cardíacos anormais e de pessoas com histórico de infarto do miocárdio. Esta variedade de categorias auxilia no treinamento de modelos de marchine learning. 

Considerando que o dataset é composto por representações visuais de sinais biológicos, as opções de Visão Computacional (CV) para o CardioIA abrangem desde o processamento de imagem clássico até arquiteturas avançadas de Deep Learning. Inicialmente, levanta-se a hipótese de que técnicas de detecção de bordas, como os filtros de Sobel ou o algoritmo de Canny, associadas a operações morfológicas, possam ser utilizadas para isolar o traçado do sinal do fundo milimetrado da imagem, removendo ruídos de digitalização. Uma opção robusta para a análise morfológica é o uso de Segmentação Semântica (como arquiteturas U-Net), que permitiria separar cada componente do ciclo cardíaco (Onda P, complexo QRS e Onda T) em máscaras distintas, facilitando a medição de intervalos temporais e amplitudes elétricas. Para a classificação das patologias presentes nas pastas do dataset, as opções mais eficazes envolvem o uso de Redes Neurais Convolucionais (CNNs) com Aprendizado por Transferência (Transfer Learning), utilizando modelos como ResNet ou EfficientNet pré-treinados para identificar padrões geométricos de arritmias e isquemias. Além disso, projeta-se a aplicação de Mecanismos de Atenção (Attention Maps), que permitem visualizar quais áreas do ECG a IA considerou mais relevantes para o diagnóstico, garantindo a interpretabilidade necessária para a aceitação médica do sistema.

Para o treinamento e teste, a base de dados de imagens foi salva em: https://drive.google.com/drive/folders/1SAV1e8cRUYLMI_qkfReXNKHfManCMeAo?usp=sharing


## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>.github</b>: Nesta pasta ficarão os arquivos de configuração específicos do GitHub que ajudam a gerenciar e automatizar processos no repositório.

- <b>assets</b>: aqui estão os arquivos relacionados a elementos não-estruturados deste repositório, como imagens.

- <b>config</b>: Posicione aqui arquivos de configuração que são usados para definir parâmetros e ajustes do projeto.

- <b>document</b>: aqui estão todos os documentos do projeto que as atividades poderão pedir. Na subpasta "other", adicione documentos complementares e menos importantes.

- <b>scripts</b>: Posicione aqui scripts auxiliares para tarefas específicas do seu projeto. Exemplo: deploy, migrações de banco de dados, backups.

- <b>src</b>: Todo o código fonte criado para o desenvolvimento do projeto ao longo das 7 fases.

- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

## 🔧 Como executar o código

*Acrescentar as informações necessárias sobre pré-requisitos (IDEs, serviços, bibliotecas etc.) e instalação básica do projeto, descrevendo eventuais versões utilizadas. Colocar um passo a passo de como o leitor pode baixar o seu código e executá-lo a partir de sua máquina ou seu repositório. Considere a explicação organizada em fase.*


## 🗃 Histórico de lançamentos

* 0.5.0 - XX/XX/2024
    * 
* 0.4.0 - XX/XX/2024
    * 
* 0.3.0 - XX/XX/2024
    * 
* 0.2.0 - XX/XX/2024
    * 
* 0.1.0 - XX/XX/2024
    *

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>


