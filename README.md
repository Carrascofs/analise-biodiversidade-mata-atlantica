# analise-biodiversidade-mata-atlantica
Análise de dados de biodiversidade da Mata Atlântica usando dados do ICMBio

# Análise de Biodiversidade da Mata Atlântica

## Sobre o Projeto
Análise exploratória de dados sobre espécies ameaçadas da Mata Atlântica brasileira utilizando dados oficiais do ICMBio. O projeto une o domínio científico da biologia com técnicas avançadas de manipulação de dados para identificar gargalos na conservação ambiental.

## Objetivos
- Mapeamento de Hotspots: Identificação de polos de biodiversidade ameaçada por estado e região, utilizando técnicas de limpeza e expansão de dados geográficos (explode).

- Análise de Distribuição e Endemismo: Comparação entre espécies endêmicas da Mata Atlântica e o cenário geral brasileiro, avaliando padrões de criticidade (CR, EN, VU).

## Fontes de Dados
- *ICMBio SALVE*: Sistema de Avaliação do Risco de Extinção da Biodiversidade

## Tecnologias Utilizadas
- *Python 3.8+*
- *Pandas & NumPy* - manipulação e análise de dados
- *Matplotlib & Seaborn* - visualizações
- *GeoPandas & Folium* - análise geoespacial
- *Jupyter Notebooks* - desenvolvimento interativo

## Estrutura do Projeto
```
analise-biodiversidade-mata-atlantica/
│ 
├── data/
│   ├── raw/                 # Dados originais
│   └── processed/           # Dados limpos e normalizados
├── notebooks/
│   ├── 01_limpeza_e_exploracao.ipynb
│   ├── 02_analise_geografica.ipynb
│   └── 03_visualizacoes_insights.ipynb
├── src/
│   ├── data_collection.py
│   ├── data_processing.py
│   └── visualization.py
├── images/
│   └── [gráficos e visualizações]
├── requisitos.txt
└── README.md
```

## Como Executar

### Pré-requisitos
- Python 3.8 ou superior
- Git

### Instalação
```bash
# Clonar repositório
git clone https://github.com/Carrascofs/analise-biodiversidade-mata-atlantica.git
cd analise-biodiversidade-mata-atlantica

# Instalar dependências
pip install -r requisitos.txt

# Iniciar Jupyter
jupyter notebook

Abra o jupyter notebook na pasta raiz do projeto
```

## Principais Análises
1. Distribuição por Categoria de Ameaça
Análise das categorias de risco (CR, EN, VU, etc.) segundo critérios da IUCN.
2. Hotspots de Biodiversidade
Identificação dos estados, regiões e biomas com maior concentração de espécies ameaçadas.
3. Endemismo Brasileiro
Comparação entre espécies endêmicas e não-endêmicas, avaliando padrões de ameaça.
4. Efetividade das Unidades de Conservação
Avaliação da cobertura de espécies ameaçadas por UCs federais, estaduais e RPPNs.

## Principais Descobertas
*Em desenvolvimento - será atualizado conforme a análise avança*

## Sobre o Autor
Biólogo com mestrado em transição para Ciência de Dados, aplicando conhecimento científico para resolver problemas com dados.

- **LinkedIn**: [(https://www.linkedin.com/in/felipe-dos-santos-carrasco/)]
- **Email**: [carrascofs@gmail.com]

## Status do Projeto
Fase de Exploração e Geografia Concluída. Iniciando Análise de Efetividade de UCs.

Última atualização: 27/03/2026


---

*Este projeto faz parte do meu portfólio de transição de carreira para ciência de dados, demonstrando a aplicação de técnicas analíticas em dados biológicos e ambientais.*