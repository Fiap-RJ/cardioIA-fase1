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
**Arquivo:** `dataset_pacientes.csv`
**Origem dos Dados:** [Arthur: Inserir a fonte, ex: Kaggle, PhysioNet ou se foi simulado]

**Justificativa Clínica e Relevância para IA:**
[Arthur: Colar aqui a explicação sobre as variáveis clínicas escolhidas e como elas alimentam os modelos preditivos.]

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
**Arquivos:** 100 imagens de exames cardiológicos (localizadas no Drive e listadas na subpasta `assets/`)
**Origem dos Dados:** [Nathalia: Inserir a fonte, ex: Mendeley, Kaggle]

**Justificativa Clínica e Relevância para IA:**
[Nathalia: Colar aqui a explicação de como a IA pode analisar essas imagens usando visão computacional para detecção de anomalias.]

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