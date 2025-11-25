# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Fase 4 - Da Terra ao Código: Automatizando a Classificação de Grãos com Machine Learning

## Grupo 16

## 👨‍🎓 Integrantes:

- <a href="https://www.linkedin.com/in/amanda-damasceno-martins/">566598 - Amanda Damasceno Martins</a>
- <a href="https://www.linkedin.com/in/cauasantoslt">566599 - Cauã Santos</a>
- <a href="https://www.linkedin.com/in/fabio-baldo-7959a22a/">567851 - Fabio Baldo</a>
- <a href="https://www.linkedin.com/in/giovanna-gomes-82b993372/">567169 - Giovanna Gomes Oliveira</a>
- <a href="https://www.linkedin.com/in/roberto-alvares-785059215/">568265 - Roberto Almeida Alvares</a>

## 👩‍🏫 Professores:

### Tutor(a)

- <a href="https://www.linkedin.com/in/sabrina-otoni-22525519b/">Sabrina Otoni</a>

### Coordenador(a)

- <a href="https://www.linkedin.com/in/andregodoichiovato/">André Godoi</a>

---

## 📜 Descrição
Este projeto tem como objetivo aplicar a metodologia **CRISP-DM** para automatizar o processo de classificação de grãos de trigo em cooperativas agrícolas. Atualmente, esse processo é manual, demorado e sujeito a erros humanos. Utilizando Machine Learning, buscamos aumentar a eficiência e a precisão dessa triagem.

O modelo foi treinado com o **"Seeds Dataset"** (disponível no UCI Machine Learning Repository) para distinguir três variedades de trigo: **Kama**, **Rosa** e **Canadian**, com base em características geométricas (como área, perímetro e compacidade).

**Principais etapas desenvolvidas:**
* **Análise e Pré-processamento:** Limpeza de dados, tratamento de outliers e padronização de escalas com `StandardScaler`.
* **Modelagem:** Implementação e comparação de três algoritmos:
    * K-Nearest Neighbors (KNN)
    * Random Forest
    * Naive Bayes (GaussianNB)
* **Otimização:** Ajuste de hiperparâmetros (Fine-tuning) utilizando `GridSearchCV` no modelo Random Forest.
* **Resultados:** O modelo **KNN** apresentou o melhor desempenho, alcançando acurácia próxima a **100%**, provando ser a solução ideal para o problema de negócio proposto.

---

## 📁 Estrutura de pastas

```sh
├── CauãSantos_RM566599_Fase4_Cap3.iypnb
├── Interpretação dos Resultados e Insights.pdf
├── seeds_dataset.txt
└── README.md
```

## 🗃 Histórico de lançamentos

* 0.0.1 - 25/11/2025
    * Implementação do notebook com análise exploratória e pré-processamento.
    * Treinamento e validação dos modelos (KNN, Random Forest e Naive Bayes).
    * Otimização de hiperparâmetros com Grid Search.
    * Geração do relatório final de insights.

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
