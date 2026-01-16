Automação de Testes de API - JSONPlaceholder

Repositório destinado ao estudo de testes automatizados de API utilizando a ferramenta Postman. O foco deste projeto é validar a integridade dos dados e a performance da API pública JSONPlaceholder.

## Tecnologias Utilizadas
* **Postman**: Ferramenta para desenvolvimento e testes de APIs.
* **JavaScript**: Linguagem utilizada para a escrita dos scripts de validação.
* **JSONPlaceholder API**: API REST fake para testes e prototipagem.

---

## Explicação dos Testes Realizados

Os testes foram escritos na aba **Scripts (Post-response)** do Postman e garantem os seguintes critérios de aceitação:

1.  **Status Code 200**: Valida se a requisição foi processada com sucesso pelo servidor.
2.  **Tempo de Resposta**: Verifica se a API responde em menos de 200ms, garantindo a performance da aplicação.
3.  **Integridade do Corpo (String)**: Busca por palavras-chave obrigatórias no corpo da resposta para garantir que o conteúdo não está vazio ou corrompido.
4.  **Validação de ID (Contrato)**: Compara o ID retornado no JSON com o ID solicitado na URL, garantindo que o sistema está entregando o dado correto.
5.  **Tratamento de Erros (Negative Testing)**: Validação de retornos 404 para recursos inexistentes.

---

##  Como Executar este Projeto

Para rodar estes testes na sua máquina, siga os passos abaixo:

### 1. Pré-requisitos
Você precisará ter o **Postman** instalado (Desktop ou Web).

### 2. Importando a Collection
1.  Faça o download do arquivo JSON da collection neste repositório (caso disponível) ou copie o link da API.
2.  No Postman, clique no botão **Import** no canto superior esquerdo.
3.  Arraste o arquivo baixado ou cole o link da collection.

### 3. Rodando os Testes
1.  Selecione a requisição dentro da pasta **Estudos API - JSONPlaceholder**.
2.  Clique no botão azul **Send**.
3.  Clique na aba **Test Results** na parte inferior para visualizar os resultados (Pass/Fail).

---
 *Projeto desenvolvido por João Pedro Brito para fins de estudo em Qualidade de Software (QA).*
