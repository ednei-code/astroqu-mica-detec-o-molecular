# astroqu-mica-detec-o-molecular
Análise exploratória de dados e clusterização de moléculas interestelares com foco na complexidade molecular e na detectabilidade espectroscópica.

# Análise da Detectabilidade Espectroscópica de Moléculas Interestelares

Este projeto investiga a relação entre **complexidade molecular**, **composição química** e **detectabilidade espectroscópica** de moléculas interestelares, utilizando dados derivados de catálogos espectroscópicos amplamente empregados em estudos de astroquímica observacional.

A análise combina **exploração estatística de dados** e **técnicas de aprendizado não supervisionado** para identificar padrões físico-químicos e regimes moleculares associados a diferentes níveis de riqueza espectral, medida pelo número de linhas espectrais catalogadas (`n_lines`).

---

## 🎯 Objetivos

- Analisar a distribuição da complexidade estrutural e da diversidade química no catálogo
- Investigar a relação entre propriedades moleculares e a detectabilidade espectroscópica
- Identificar grupos naturais de moléculas com características físico-químicas semelhantes por meio de clusterização
- Caracterizar um regime molecular associado a alta eficiência espectroscópica

---

## 🧪 Metodologia

- Auditoria e preparação dos dados
- Análise Exploratória de Dados (EDA)
  - Estatísticas descritivas
  - Correlações não paramétricas (Spearman)
  - Visualizações em escala logarítmica
- Redução de dimensionalidade (PCA)
- Clusterização (KMeans)
- Interpretação científica dos clusters

---

## 📊 Dados

Os dados utilizados neste projeto são derivados de catálogos espectroscópicos de referência na astroquímica observacional:

- **CDMS — Cologne Database for Molecular Spectroscopy**  
  https://cdms.astro.uni-koeln.de/

- **JPL Molecular Spectroscopy Catalog (NASA)**  
  https://spec.jpl.nasa.gov/


Os arquivos analisados representam versões consolidadas e estruturadas desses catálogos, utilizadas exclusivamente para fins **educacionais e científicos**, respeitando as diretrizes de citação e atribuição das fontes originais.

---

## 📁 Estrutura do Repositório

- `astroquimica_detectabilidade_clusterizacao.ipynb` — Notebook principal com toda a análise e interpretação dos resultados
- `README.md` — Descrição geral do projeto

---

## 👤 Autor

**Ednei Cunha Vicente**  
Cientista de Dados  
Entusiasta de Astrofísica e Astroquímica  

---

## 📌 Observações

Este projeto tem caráter exploratório e não visa estabelecer relações causais diretas, mas identificar **padrões estatísticos e físico-químicos** que auxiliem na interpretação de observações espectroscópicas em ambientes astrofísicos.
