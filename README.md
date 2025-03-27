# Projeto: Calculadora de Rotas com Algoritmo Guloso

## Descrição
Este projeto é uma aplicação web para calcular o melhor caminho entre duas cidades usando um algoritmo guloso. Ele utiliza FastAPI para o backend e React para a interface do usuário. O banco de dados Firestore é usado para armazenar as informações das cidades e suas conexões.

## Tecnologias Utilizadas
- **Backend:** FastAPI, Firebase Firestore, Python
- **Frontend:** React, Bootstrap, Axios
- **Banco de Dados:** Firebase Firestore

---

## Estrutura do Projeto

### Backend (FastAPI)
- O backend fornece um endpoint /caminho para calcular a rota entre duas cidades.
- Utiliza Firebase Firestore para armazenar e recuperar os dados das cidades.
- Implementa um algoritmo guloso para encontrar o melhor caminho.
- Utiliza cache global para otimizar o acesso aos dados das cidades.
- Oferece suporte a CORS para permitir requisições do frontend.

#### Instalação e Execução
1. Execute o start.bat para iniciar automaticamente o backend e o frontend. (pode ser necessario executar varias vezes para a funcionar)

---

## Como Usar
1. Acesse a interface web e insira as cidades de origem e destino.
2. Clique em "Calcular Rota" para encontrar o melhor caminho.
3. O resultado exibirá a rota calculada e a distância total.
4. Se não houver caminho disponível, uma mensagem de erro será exibida.
