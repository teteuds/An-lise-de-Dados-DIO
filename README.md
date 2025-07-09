# Fundamentos de IA e Análise de Sentimentos com Azure AI

## Introdução

Este repositório contém o material desenvolvido durante as aulas da **DIO** sobre **Fundamentos da IA Generativa**, **Conceitos de IA**, **Aprendizado de Máquina (Machine Learning)**, **Processamento de Linguagem Natural (PLN)** e **Análise de Sentimentos com Language Studio no Azure AI**. O objetivo deste projeto é aplicar os conceitos aprendidos para implementar soluções de inteligência artificial, focadas em PLN e análise de sentimentos, utilizando o **Azure AI**.

## Tecnologias Utilizadas
- **Azure AI**
- **Language Studio** (Azure)
- **GitHub** para versionamento e documentação

## Tópicos Abordados

### 1. **Fundamentos da IA Generativa**
   A IA Generativa refere-se a modelos de aprendizado de máquina que são capazes de criar novos dados, como imagens, textos ou músicas, com base em exemplos anteriores. Este tipo de IA está se tornando cada vez mais popular devido à sua capacidade de produzir conteúdo original em diversas áreas.

   - **Exemplo**: Utilização de modelos de IA generativa para criar respostas automatizadas ou gerar descrições de imagens.
   - **Aplicação no projeto**: Implementação de uma solução para gerar textos automatizados com base em temas definidos pelo usuário.

### 2. **Conceitos Fundamentais de IA**
   A **Inteligência Artificial (IA)** envolve a criação de sistemas que podem realizar tarefas que normalmente exigiriam inteligência humana, como reconhecimento de padrões, tomada de decisões e previsão de resultados. 
   
   - **Áreas da IA**:
     - **Aprendizado supervisionado e não supervisionado**: Métodos de treinamento de modelos com dados rotulados ou não rotulados.
     - **Redes neurais artificiais**: Modelos inspirados no cérebro humano, usados para resolver problemas complexos.
   - **Aplicação no projeto**: Implementação de um modelo básico de IA para classificar dados textuais ou realizar previsões com base em dados históricos.

### 3. **Fundamentos do Aprendizado de Máquina (Machine Learning)**
   O **Aprendizado de Máquina** é uma subárea da IA que permite que os computadores aprendam com os dados, sem serem explicitamente programados para realizar uma tarefa específica.
   
   - **Tipos de aprendizado**:
     - **Supervisionado**: O modelo é treinado com exemplos rotulados.
     - **Não supervisionado**: O modelo tenta encontrar padrões sem rótulos explícitos.
     - **Aprendizado por reforço**: O modelo aprende por tentativa e erro, com feedback em tempo real.
   - **Aplicação no projeto**: Utilização do aprendizado supervisionado para classificar sentimentos em textos utilizando o Azure Language Studio.

### 4. **Conceitos de Processamento de Linguagem Natural (PLN)**
   O **Processamento de Linguagem Natural (PLN)** envolve técnicas que permitem que os computadores entendam, interpretem e gerem linguagem humana de maneira útil.
   
   - **Técnicas importantes**:
     - **Tokenização**: Divisão de textos em unidades menores, como palavras ou frases.
     - **Análise de sentimentos**: Identificação da emoção por trás de um texto (ex: positivo, negativo ou neutro).
     - **Extração de entidades**: Identificação de nomes, lugares, datas e outros itens relevantes no texto.
   - **Aplicação no projeto**: Implementação de técnicas de PLN para analisar o sentimento de textos inseridos pelo usuário no **Azure Language Studio**.

### 5. **Análise de Sentimentos com Language Studio no Azure AI**
   O **Azure Language Studio** é uma ferramenta poderosa da Microsoft que permite realizar análises de sentimentos, identificar entidades e classificar textos em categorias específicas. A análise de sentimentos tem como objetivo identificar se o texto expressa uma opinião positiva, negativa ou neutra.
   
   - **Como funciona**: Utilizando o **Azure Language Studio**, é possível importar textos e aplicar modelos prontos para analisar o sentimento do conteúdo.
   - **Passos realizados**:
     1. Criação de um projeto no **Azure Language Studio**.
     2. Análise de sentimentos com diferentes exemplos de texto.
     3. Ajustes nos parâmetros para melhorar a precisão da análise.
   - **Resultado esperado**: Classificação dos textos conforme seu tom emocional (positivo, negativo ou neutro).

---

## Passos Realizados

### 1. **Configuração do Ambiente**
   - Criação de uma conta no **Azure** e acesso ao **Azure Language Studio**.
   - Familiarização com as ferramentas de análise de texto e de sentimentos.
   
### 2. **Treinamento de Modelos no Language Studio**
   - Carreguei dados de exemplo para treinar os modelos de análise de sentimentos.
   - Experimentei com diferentes configurações de parâmetros e testei a precisão do modelo.

### 3. **Desenvolvimento da Solução de Análise de Sentimentos**
   - Apliquei um modelo pré-existente do **Azure Language Studio** para realizar a análise de sentimentos em textos inseridos.
   - Os resultados mostraram uma boa precisão na identificação de sentimentos em diferentes contextos de texto.

---

## Desafios Encontrados
- Durante a configuração do Azure, houve dificuldades em conectar corretamente a API de análise de sentimentos ao projeto.
- A precisão da análise de sentimentos não foi ideal em textos muito curtos ou ambíguos. Para resolver isso, ajustes finos nos dados de treinamento foram realizados.

## Conclusão
Ao final deste desafio, fui capaz de compreender e aplicar os conceitos de **Inteligência Artificial**, **Aprendizado de Máquina** e **Processamento de Linguagem Natural** com o Azure. A análise de sentimentos utilizando o **Azure Language Studio** foi uma aplicação prática e interessante dos conceitos aprendidos nas aulas da DIO.


