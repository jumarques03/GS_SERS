# Análise de Eficiência em Estações de Carregamento de EVs e o Futuro do Trabalho

Este repositório contém a análise de dados para a Global Solution sobre Energias Renováveis e Sustentabilidade. O projeto foca em identificar desperdícios em estações de carregamento de EVs e propor uma solução que conecta a eficiência energética ao futuro do trabalho.

**Aluna:** Júlia Souza Marques
**RM:** 565010

---

## Resumo do Trabalho

Este projeto analisa um dataset público sobre o uso de estações de carregamento de veículos elétricos (EVs) para identificar padrões de desperdício. O objetivo é:
1.  Entender como a infraestrutura é usada e propor uma solução para otimizar o consumo de energia e a rotatividade das vagas.
2.  Demonstrar como essa otimização técnica é promove a criação de novos empregos do futuro.

A análise identificou dois problemas centrais:
* **Pico de Demanda de Energia:** Um forte aumento no consumo de energia ocorre durante o horário comercial (8h-18h), sobrecarregando a rede elétrica.
* **Uso Ineficiente da Infraestrutura:** Os veículos permanecem nas vagas por um tempo significativamente maior do que o necessário para o carregamento, especialmente à noite (22h-2h).

---

## Solução Proposta (Resumo)

Para solucionar os desperdícios identificados, propõe-se um **Sistema de Carregamento Inteligente**.

### A Solução Técnica
* **Notificações ao Usuário:** Enviar alertas via aplicativo quando o carregamento for concluído.
* **Aplicação de Taxas:** Implementar um sistema de taxas para veículos que permanecerem na vaga por tempo excessivo, incentivando a rotatividade.
* **Incentivo de Horário:** Enviar notificações para usuários carregarem seus carros em horários de menor demanda.

### A Conexão com o Futuro do Trabalho
A implementação e operação desse sistema cria novas funções que exigem habilidades analíticas e de gestão sustentável. A solução propõe a criação de cargos como:

* **Analista de Demanda de Eletromobilidade:** 
* **Técnico Especializado em Carregadores Inteligentes:**
* **Gerente de Demanda Energética em Estações de Carregamento**

---

## Fonte de Dados

O dataset utilizado nesta análise é público e pode ser encontrado no Kaggle:

* **Link:** [EV Charging Station Usage of California City](https://www.kaggle.com/datasets/venkatsairo4899/ev-charging-station-usage-of-california-city)

---

## Orientações de Execução

Para executar este projeto e visualizar a análise completa:

1.  **Clone o Repositório**
    ```bash
    git clone https://github.com/jumarques03/GS_SERS
    ```

2.  **Instale as Dependências**
    O notebook utiliza as seguintes bibliotecas Python. Certifique-se de que elas estejam instaladas:
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```
    
3.  **Execute o Notebook**
    Abra e execute o arquivo `GS_SERS.ipynb` em um ambiente compatível, como Jupyter Notebook, Jupyter Lab ou Google Colab.
