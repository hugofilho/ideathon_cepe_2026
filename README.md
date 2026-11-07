# Ideathon Ceres 2026 - Avaliação e Resultados do Projeto de Extensão

Este repositório contém os dados, análises e relatórios referentes ao **Ideathon de Inovação em Saúde**, realizado em outubro de 2026 na região de Ceres (GO). O evento foi concebido como um projeto de extensão universitária voltado à cocriação de soluções tecnológicas e sociais para otimização dos serviços de saúde pública locais (vinculados ao SUS).

---

## 📋 Sobre o Projeto

O **Ideathon** reuniu estudantes, profissionais da saúde, gestores públicos, demandantes locais e mentores/moderadores com o objetivo de formular propostas inovadoras voltadas para os desafios reais da rede de saúde de Ceres. A iniciativa promoveu a integração ensino-serviço-comunidade e estimulou a cultura de inovação social direcionada ao SUS.

### Principais Objetivos:
- **Mapear e Compreender:** Analisar os principais gargalos da saúde pública em Ceres (GO).
- **Criação Rápida (Design Sprint):** Desenvolver propostas de soluções viáveis em curto período de tempo.
- **Integração e Aprendizado:** Fortalecer o espírito de equipe, interdisciplinaridade e engajamento social.

---

## 📊 Análise dos Dados de Avaliação

Abaixo está o comparativo das médias gerais atribuídas por cada grupo em suas respectivas escalas de avaliação de impacto e satisfação:

![Comparativo de Avaliações por Grupo](comparativo_avaliacoes.png)

### 1. Participantes (Estudantes / Comunidade) - N = 34
Os participantes avaliaram sua experiência em uma escala Likert de 1 a 5:
- **Aprendizado sobre problemas locais:** Média de **4.12** (forte compreensão do cenário do SUS regional).
- **Integração com a equipe:** Média de **4.00**.
- **Desafio de curto tempo:** Média de **3.88**.
- **Interesse em novos projetos de inovação social/saúde:** Média de **4.29**.
- **Diferencial das Soluções Criadas:**
  - *Modernização dos processos internos dos postos/hospitais:* 13 menções
  - *Redução do tempo de espera nas Unidades de Saúde:* 10 menções
  - *Facilidade de uso pelo cidadão:* 9 menções
  - *Promoção de hábitos saudáveis e prevenção:* 2 menções

### 2. Demandantes (Gestão Pública & Rede Hospitalar) - N = 2
- **Aderência às demandas reais:** Classificações de **4.0** e **5.0** (Média: **4.50**).
- **Viabilidade financeira de implementação:** Média de **3.00**.
- **Alinhamento às normas do SUS:** Média de **3.50**.
- **Facilidade de adesão pelas equipes de saúde atuais:** Média de **3.00**.
- **Categorias mais promissoras:** *Gestão de dados/prontuários integrados* e *Comunicação direta/engajamento do paciente*.

### 3. Moderadores e Mentores - N = 2
- **Evolução do projeto do início ao fim:** Média de **3.50**.
- **Fundamentação coerente com a realidade do SUS:** Média de **4.50**.
- **Nível de maturidade para incubação/piloto:** Média de **3.50**.

---

## 🛠️ Tecnologias e Ferramentas

A análise dos dados de avaliação e o desenvolvimento dos dashboards de acompanhamento utilizaram as seguintes tecnologias:
- **Python 3.10+**
- **Pandas** (Tratamento e consolidação dos dados)
- **Matplotlib / Seaborn** (Geração de gráficos e visualização científica)
- **Jupyter Notebooks / Google Colab** (Ambiente de desenvolvimento)

---

## 📂 Estrutura do Repositório

```bash
├── data/
│   └── Avaliacao_Ideathon_Cers_Out_26.xlsx  # Dados brutos das avaliações
├── notebooks/
│   └── analise_avaliacao_ideathon.ipynb     # Script de análise e estatística descritiva
├── docs/
│   └── painel_ideathon_iut_26_ceres.pdf     # Documento de apresentação do painel consolidado
├── comparativo_avaliacoes.png               # Imagem do gráfico comparativo
└── README.md                                # Documentação do projeto
```

---

## 🚀 Como Executar as Análises

1. Clone este repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO_NO_GITLAB>
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install pandas openpyxl matplotlib seaborn
   ```
3. Execute o notebook de análise localizado em `/notebooks/` para reproduzir os gráficos e estatísticas apresentadas.

---

## 👥 Créditos e Realização

Este projeto de extensão foi realizado através da colaboração coletiva de diversas entidades dedicadas à educação, inovação e saúde no estado de Goiás. Agradecemos a todos os estudantes, mentores, avaliadores e à Secretaria Municipal de Saúde de Ceres pelo apoio fundamental na realização do evento.
