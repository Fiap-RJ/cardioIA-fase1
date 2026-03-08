# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# CardioIA: A Nova Era da Cardiologia Inteligente

## Nome do grupo

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/michaelrodriguess/">Michael Rodrigues</a>
- <a href="https://www.linkedin.com/in/arthur-alentejo/">Arthur Alentejo</a>
- <a href="">Nathalia</a> 

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="#">Nome do Tutor</a>
### Coordenador(a)
- <a href="#">Nome do Coordenador</a>

## 📜 Descrição

O CardioIA é um projeto acadêmico focado em desenvolver uma plataforma digital inteligente que simula o ecossistema de uma cardiologia moderna. O sistema integrará dados clínicos, modelos de Machine Learning, Visão Computacional, IoT e agentes inteligentes para auxiliar na triagem, diagnóstico, monitoramento e previsão médica de pacientes com doenças cardiovasculares. O objetivo é construir soluções tecnológicas baseadas em dados rigorosos e governança ética para impactar positivamente a saúde pública.

## 🚀 Entregas da Fase 1 - Batimentos de Dados
**Link Público para o Repositório de Dados Brutos:**
[Arthur/Nathalia: Inserir aqui o link do Google Drive/OneDrive contendo todos os dados pesados do grupo]

### Parte 1 – Dados Numéricos (IoT)
**Responsável:** Arthur

**Arquivo:** `assets/heart.csv`

**Origem dos Dados:** Kaggle – Heart Failure Prediction Dataset, disponível em: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

O arquivo também está disponível no Google Drive do grupo: https://drive.google.com/file/d/1qzpiRp4aexobUvWCXbXy9Q9lRyPpGpBx/view?usp=sharing

Este dataset foi criado pela combinação de 5 bases de dados já existentes, totalizando a maior base de dados de doenças cardíacas disponível para pesquisa. As bases combinadas são: Cleveland (303 observações), Hungarian (294 observações), Switzerland (123 observações), Long Beach VA (200 observações) e Stalog Heart Data Set (270 observações).

**Justificativa Clínica e Relevância para IA:**
As doenças cardiovasculares (DCVs) são a principal causa de morte no mundo, responsáveis por aproximadamente 17,9 milhões de vidas por ano — 31% de todas as mortes globais. Quatro em cada cinco mortes por DCV ocorrem por ataques cardíacos e derrames, e um terço delas acontece prematuramente em pessoas com menos de 70 anos. A detecção precoce é essencial, e este dataset oferece 11 variáveis clínicas altamente relevantes para alimentar modelos preditivos de Machine Learning:

- **Age**: idade do paciente em anos — fator de risco crescente para DCVs.
- **Sex**: sexo do paciente (M: Masculino, F: Feminino) — permite identificar padrões de apresentação diferenciados entre gêneros.
- **ChestPainType**: tipo de dor torácica (TA: Angina Típica, ATA: Angina Atípica, NAP: Dor Não-Anginal, ASY: Assintomático) — forte indicador clínico de isquemia.
- **RestingBP**: pressão arterial em repouso (mm Hg) — hipertensão é um dos principais fatores de risco cardiovascular.
- **Cholesterol**: colesterol sérico (mm/dl) — hiperlipidemia contribui diretamente para o desenvolvimento de aterosclerose.
- **FastingBS**: glicemia em jejum (1: se > 120 mg/dl, 0: caso contrário) — a diabetes é comorbidade frequente e agravante de DCVs.
- **RestingECG**: resultado do eletrocardiograma em repouso (Normal, ST: anormalidade de onda ST-T, LVH: hipertrofia ventricular esquerda) — evidencia alterações elétricas do coração.
- **MaxHR**: frequência cardíaca máxima atingida (60–202 bpm) — indicador de capacidade funcional cardíaca.
- **ExerciseAngina**: angina induzida por exercício (Y: Sim, N: Não) — sintoma clínico de isquemia sob esforço.
- **Oldpeak**: depressão do segmento ST induzida por exercício — quanto maior, mais indicativo de isquemia miocárdica.
- **ST_Slope**: inclinação do segmento ST no pico do exercício (Up: ascendente, Flat: plano, Down: descendente) — padrões distintos associados a diferentes graus de comprometimento coronariano.

A combinação dessas variáveis permite treinar modelos de classificação binária (HeartDisease: 1 = doença, 0 = normal) com alta capacidade preditiva, servindo como base para o módulo de triagem inteligente do CardioIA.

### Parte 2 – Dados Textuais (NLP) e Governança
**Responsável:** Michael

**Arquivos:** `texto_insuficiencia_cardiaca.txt` e `texto_hipertensao.txt` (localizados na subpasta `assets/`)

**Fontes:** Diretrizes da Sociedade Brasileira de Cardiologia e Manuais do Ministério da Saúde (SUS).
* Link SUS: https://www.gov.br/conitec/pt-br/midias/protocolos/pcdt-de-insuficiencia-cardiaca
* Link SBC: https://www.scielo.br/j/abc/a/XkVKFb4838qXrXSYbmCYM3K/?lang=pt

**Justificativa Clínica e Aplicação em Inteligência Artificial (NLP):**
Os dados textuais coletados consistem em diretrizes clínicas e manuais médicos focados em Insuficiência Cardíaca e Hipertensão Arterial Sistêmica. A utilização desses arquivos puros é essencial para alimentar modelos de Processamento de Linguagem Natural (NLP) dentro do ecossistema do CardioIA. Através de técnicas como o Reconhecimento de Entidades Nomeadas (NER), os algoritmos podem ser treinados para extrair automaticamente sintomas (ex: "ortopneia", "dispneia"), comorbidades e medicamentos (ex: "Enalapril", "Betabloqueadores") diretamente de textos não estruturados, como prontuários eletrônicos. Além disso, esses textos de referência servem como base de conhecimento para a classificação de tópicos e o treinamento de assistentes virtuais voltados à triagem inteligente, permitindo que a IA compreenda o jargão médico e relacione queixas de pacientes a possíveis agravos cardiovasculares de forma ágil e padronizada.

**Governança de Dados e Ética em IA:**
Em um ecossistema de saúde moderno, a curadoria desses dados deve ser acompanhada de rigorosa Governança. Para garantir a eficácia e a ética do CardioIA, é fundamental evitar vieses algorítmicos garantindo que os textos e dados que alimentam o modelo representem a diversidade demográfica real da população (evitando que a IA seja treinada apenas com perfis de um gênero ou etnia específicos, o que pode mascarar apresentações atípicas de infarto, por exemplo). Adicionalmente, caso sejam utilizados dados reais de prontuários em fases futuras, protocolos estritos de anonimização e mascaramento de dados sensíveis devem ser aplicados para proteger a privacidade dos pacientes, em total conformidade com a Lei Geral de Proteção de Dados (LGPD) e diretrizes bioéticas.

### Parte 3 – Dados Visuais (Visão Computacional)
**Responsável:** Nathalia

**Arquivos:** Para o treinamento e teste, a base de dados de imagens foi salva em: https://drive.google.com/drive/folders/1SAV1e8cRUYLMI_qkfReXNKHfManCMeAo?usp=sharing

**Origem dos Dados:** O Dataset de imagens selecionado foi o ECG Images Dataset , disponível em: https://www.kaggle.com/datasets/jayaprakashpondy/ecgimages/data

**Justificativa Clínica e Relevância para IA:**
Este banco de dados foi escolhido por haver imagens de eletrocardiogramas identificados como normais, com infarto do miocárdio, com batimentos cardíacos anormais e de pessoas com histórico de infarto do miocárdio. Esta variedade de categorias auxilia no treinamento de modelos de marchine learning.
Considerando que o dataset é composto por representações visuais de sinais biológicos, as opções de Visão Computacional (CV) para o CardioIA abrangem desde o processamento de imagem clássico até arquiteturas avançadas de Deep Learning. Inicialmente, levanta-se a hipótese de que técnicas de detecção de bordas, como os filtros de Sobel ou o algoritmo de Canny, associadas a operações morfológicas, possam ser utilizadas para isolar o traçado do sinal do fundo milimetrado da imagem, removendo ruídos de digitalização. Uma opção robusta para a análise morfológica é o uso de Segmentação Semântica (como arquiteturas U-Net), que permitiria separar cada componente do ciclo cardíaco (Onda P, complexo QRS e Onda T) em máscaras distintas, facilitando a medição de intervalos temporais e amplitudes elétricas. Para a classificação das patologias presentes nas pastas do dataset, as opções mais eficazes envolvem o uso de Redes Neurais Convolucionais (CNNs) com Aprendizado por Transferência (Transfer Learning), utilizando modelos como ResNet ou EfficientNet pré-treinados para identificar padrões geométricos de arritmias e isquemias. Além disso, projeta-se a aplicação de Mecanismos de Atenção (Attention Maps), que permitem visualizar quais áreas do ECG a IA considerou mais relevantes para o diagnóstico, garantindo a interpretabilidade necessária para a aceitação médica do sistema.

---

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>.github</b>: Nesta pasta ficarão os arquivos de configuração específicos do GitHub que ajudam a gerenciar e automatizar processos no repositório.
- <b>assets</b>: aqui estão os arquivos relacionados a elementos não-estruturados deste repositório, como imagens e os arquivos de texto curados para NLP.
- <b>config</b>: Posicione aqui arquivos de configuração que são usados para definir parâmetros e ajustes do projeto.
- <b>document</b>: aqui estão todos os documentos do projeto que as atividades poderão pedir. Na subpasta "other", adicione documentos complementares e menos importantes.
- <b>scripts</b>: Posicione aqui scripts auxiliares para tarefas específicas do seu projeto. Exemplo: deploy, migrações de banco de dados, backups.
- <b>src</b>: Todo o código fonte criado para o desenvolvimento do projeto ao longo das 7 fases.
- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

## 🔧 Como executar o código

*A aplicação de código será desenvolvida a partir da Fase 2. No momento, o repositório contém apenas os ativos de dados estruturados e não-estruturados.*

## 🗃 Histórico de lançamentos

* 0.1.0 - 10/03/2026
    * Entrega da Fase 1: Levantamento, organização e curadoria de dados numéricos (IoT), textuais (NLP) e visuais (Visão Computacional) do projeto CardioIA.

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>