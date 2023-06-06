# Aplicação: Consulta de CEP
Este projeto consiste em um código Java que permite consultar informações de endereço utilizando um número de CEP como entrada. Ele utiliza a API do ViaCEP para obter os dados do endereço.

## Como usar
Execute o código Java no arquivo Principal.java.

Quando solicitado, digite um número de CEP para consulta.

O código irá se comunicar com a API do ViaCEP para obter os dados do endereço correspondente ao CEP fornecido.

O endereço será exibido no console.

Além disso, o código usará a classe GeradorDeArquivo para salvar os dados do endereço em um arquivo JSON. O arquivo será nomeado com o número de CEP e terá a extensão ".json".

## Requisitos
Certifique-se de ter uma conexão com a Internet para acessar a API do ViaCEP.

## Dependências
O código utiliza as seguintes tecnologias e bibliotecas:

- Biblioteca Gson: Utilizada para serializar os dados do endereço em formato JSON e desserializá-los.
- Biblioteca HttpClient: Utilizada para fazer a requisição HTTP à API do ViaCEP.
- API ViaCEP: Utilizada para obter os dados de endereço com base no número de CEP fornecido.
Certifique-se de ter essas dependências configuradas corretamente em seu projeto.

## Tratamento de erros
O código trata possíveis erros ao consultar o CEP ou ao salvar o arquivo JSON. Se ocorrerem erros, uma mensagem de erro será exibida no console.

## Observações
Certifique-se de que as classes Endereco, GeradorDeArquivo e ConsultaCep estejam definidas corretamente em arquivos separados.

O código faz uso do bloco try-catch para capturar exceções e fornecer mensagens de erro apropriadas.

Ao executar o código, certifique-se de fornecer um número de CEP válido para obter resultados corretos.

Os arquivos JSON gerados serão salvos no diretório de trabalho atual do projeto.
