# IT Salary Analysis

## Descrição do Projeto

Este projeto analisa tendências salariais na indústria de tecnologia, explorando como fatores como cargo, nível de experiência, educação, tamanho da empresa e região influenciam a remuneração. O objetivo é extrair insights significativos de dados brutos e apresentá-los de forma clara e visual.

O conjunto de dados contém registros salariais de múltiplas funções de TI, incluindo Engenheiros de Software, Cientistas de Dados, DevOps, Engenheiros de Nuvem e mais. A análise abrange limpeza e pré-processamento de dados, distribuição salarial por função e senioridade, comparações regionais e por país, impacto do tamanho da empresa e trabalho remoto na remuneração, e correlação entre nível educacional e salário.

## Conjunto de Dados

### Fonte
O conjunto de dados `job_salary.csv` contém informações salariais de profissionais de TI. (Fonte não especificada no projeto; assumido como dados simulados ou coletados para fins de análise.)

### Estrutura
O arquivo CSV possui as seguintes colunas:

- `job_title`: Título do cargo (ex.: AI Engineer, Data Analyst, Frontend Developer)
- `experience_years`: Anos de experiência
- `education_level`: Nível educacional (ex.: Bachelor, Master, PhD, High School, Diploma)
- `skills_count`: Número de habilidades listadas
- `industry`: Setor da indústria (ex.: Healthcare, Telecom, Media, Retail)
- `company_size`: Tamanho da empresa (ex.: Small, Medium, Large, Enterprise, Startup)
- `location`: Localização (países ou regiões como India, Australia, Singapore, Canada, etc.)
- `remote_work`: Tipo de trabalho remoto (ex.: Hybrid, No, Yes)
- `certifications`: Número de certificações
- `salary`: Salário em moeda não especificada (assumido como USD ou equivalente)

### Tamanho
- **Linhas**: 250.000 registros de dados + 1 linha de cabeçalho
- **Colunas**: 10

### Amostra de Dados
```
job_title,experience_years,education_level,skills_count,industry,company_size,location,remote_work,certifications,salary
AI Engineer,10,Bachelor,2,Healthcare,Medium,India,Hybrid,2,109413
Data Analyst,5,Bachelor,17,Telecom,Small,Australia,No,0,93764
...
```

## Perguntas Analíticas
O projeto aborda as seguintes questões:

- O salário cresce consistentemente com `experience_years`, ou há um ponto de saturação?
- O `education_level` impacta significativamente o salário, ou é secundário comparado ao cargo?
- Em que ponto o `skills_count` começa a gerar aumentos salariais notáveis?
- Quais indústrias oferecem os salários mais altos, e como isso varia por localização?
- O trabalho remoto versus presencial afeta o salário no mesmo nível de experiência?
- As certificações aumentam o salário independentemente da experiência?

## Tecnologias Utilizadas
- **Python**: Linguagem principal
- **Pandas**: Manipulação e análise de dados
- **NumPy**: Computação numérica
- **Matplotlib**: Visualização de dados
- **Seaborn**: Visualização estatística
- **Jupyter Notebook**: Ambiente interativo para análise

## Instalação e Configuração

### Pré-requisitos
- Python 3.7 ou superior
- Jupyter Notebook ou JupyterLab

### Passos de Instalação
1. Clone o repositório:
   ```
   git clone <URL do repositório>
   cd job_salary
   ```

2. Instale as dependências:
   ```
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Abra o notebook:
   ```
   jupyter notebook analysis.ipynb
   ```

## Uso
1. Execute as células do notebook `analysis.ipynb` em ordem.
2. As células contêm código para limpeza de dados, análises e visualizações.
3. Os resultados incluem gráficos e estatísticas sobre tendências salariais.

### Principais Achados (Baseado na Análise)
- [Inserir resumos breves dos achados se disponíveis; baseado no notebook, há gráficos de distribuição salarial, correlações, etc.]

## Estrutura do Projeto
```
job_salary/
├── analysis.ipynb          # Notebook principal com análise
├── data/
│   └── job_salary.csv      # Conjunto de dados
├── README.md               # Este arquivo
└── LICENSE                 # Licença do projeto
```

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

## Contato
Para dúvidas ou sugestões, entre em contato via [seu email ou GitHub].