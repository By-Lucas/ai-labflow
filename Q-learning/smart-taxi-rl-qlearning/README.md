
# Simulação de Táxi Inteligente com Aprendizado por Reforço

Este projeto demonstra, de forma prática, como aplicar **Q-Learning**, uma técnica de Aprendizagem por Reforço, para treinar um agente capaz de atuar como um táxi inteligente. O agente aprende a buscar passageiros em um ponto de origem e levá-los ao destino, dentro de um ambiente simulado.

## 🚀 Sobre o Projeto

- O ambiente do táxi é composto por um mapa com quatro pontos fixos (locais de embarque e desembarque).
- O objetivo do agente é pegar o passageiro no ponto de origem (representado como ponto azul) e deixá-lo no destino (ponto rosa).
- O Q-Learning é utilizado para que o agente aprenda, através de episódios repetidos, as melhores ações em cada estado do ambiente.
- Ao longo do treinamento, o agente ajusta a sua **tabela Q**, que representa a política ótima de decisão para maximizar as recompensas.

## 📌 Aplicações Possíveis

✅ Otimização de rotas para serviços de transporte sob demanda  
✅ Logística de entregas autônomas  
✅ Mobilidade urbana inteligente (cidades inteligentes)  
✅ Robótica de navegação autônoma  

## 🧩 Tecnologias e Ferramentas

- Python
- OpenAI Gym (ambiente `Taxi-v3`)
- Numpy
- Algoritmo Q-Learning

## 🏗️ Estrutura do Código

- **Definição do ambiente**  
  Criação do ambiente `Taxi-v3` do Gym para simular os pontos de embarque/desembarque.

- **Inicialização da Tabela Q**  
  Matriz de estados × ações, inicializada com zeros.

- **Treinamento com Q-Learning**  
  Atualização da política de ação usando a equação de Q-Learning, ajustando os valores para maximizar as recompensas.

- **Simulação**  
  Execução de episódios de teste para demonstrar como o táxi aprendeu a buscar e levar passageiros de forma eficiente.

## 📈 Resultados Esperados

Após treinamento, o agente consegue realizar a rota do passageiro de forma otimizada, com menos movimentos e menor penalidade, simulando um comportamento semelhante ao de um táxi autônomo.

## 📎 Como Executar

1. Clone o repositório  
   ```bash
   git clone git@github.com:By-Lucas/machine-learning-deep-learning.git
   ```
2. Instale as dependências  se quiser usar local em .py ou somente execute o script .ipynb
   ```bash
   pip install -r requirements.txt
   ```
3. Rode o notebook Jupyter  
   ```bash
   jupyter notebook smart-taxi.ipynb
   ```

## 🤝 Contribuição

Contribuições são muito bem-vindas! Você pode abrir um pull request ou reportar issues diretamente aqui.

---

