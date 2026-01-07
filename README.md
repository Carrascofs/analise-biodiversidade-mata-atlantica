# analise-biodiversidade-mata-atlantica
Análise de dados de biodiversidade da Mata Atlântica usando dados do ICMBio

# Análise de Biodiversidade da Mata Atlântica

## Sobre o Projeto
Análise exploratória de dados sobre espécies ameaçadas da Mata Atlântica brasileira utilizando dados oficiais do ICMBio. Este projeto demonstra a aplicação de técnicas de ciência de dados para insights de conservação ambiental.

## Objetivos
- Identificar padrões de distribuição de espécies ameaçadas
- Analisar efetividade das Unidades de Conservação
- Desenvolver insights para políticas de conservação
- Mapear hotspots de biodiversidade por estado e unidade de conservação.
- Avaliar endemismo brasileiro e suas implicações para conservação

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
│   └── processed/           # Dados processados
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
*Em Desenvolvimento* - Última atualização: [07/01/2026]

---

*Este projeto faz parte do meu portfólio de transição de carreira para ciência de dados, demonstrando a aplicação de técnicas analíticas em dados biológicos e ambientais.*