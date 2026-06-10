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
│   
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

A análise dos dados do Sistema SALVE (ICMBio) revelou um cenário crítico de vulnerabilidade para a biodiversidade da Mata Atlântica:

- **Endemismo em Risco Extremo:** As espécies endêmicas do bioma estão sob uma pressão desproporcional. Dentre as endêmicas ameaçadas, **26,16%** já se encontram na categoria máxima de risco ("Criticamente em Perigo").
- **O Epicentro do Risco (Sudeste):** A região Sudeste é o principal *hotspot* de ameaça, concentrando **322 espécies** endêmicas vulneráveis. Os estados de Minas Gerais, Rio de Janeiro e São Paulo encabeçam a lista de prioridade de conservação.
- **O Peso das Esferas de Proteção:** As Unidades de Conservação (UCs) Estaduais carregam a maior parcela da rede de proteção atual (**44,6%**), seguidas de perto pelas UCs Federais (**41,0%**). As Reservas Particulares do Patrimônio Natural (RPPNs) amparam apenas **15,0%** dessas espécies.

### Recomendações Estratégicas
- **Políticas Públicas Estaduais:** Como os estados são a espinha dorsal da proteção atual, investimentos em infraestrutura e fiscalização das UCs Estaduais no Sudeste e Nordeste trarão o maior retorno de preservação por área.
- **Incentivo à Iniciativa Privada:** O baixo percentual de amparo das RPPNs indica um enorme potencial inexplorado. Campanhas e subsídios para a criação de novas reservas privadas nas regiões de *hotspot* representam a forma mais ágil de expandir a malha de proteção.

## Sobre o Autor
Biólogo com mestrado em transição para Ciência de Dados, aplicando conhecimento científico para resolver problemas com dados.

- **LinkedIn**: [(https://www.linkedin.com/in/felipe-dos-santos-carrasco/)]
- **Email**: [carrascofs@gmail.com]

## Status do Projeto
Finalizado


---

*Este projeto faz parte do meu portfólio de transição de carreira para ciência de dados, demonstrando a aplicação de técnicas analíticas em dados biológicos e ambientais.*