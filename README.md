# dio-azure-advanced
Contém os Exercícios do Bootcamp Dio Azure Advanced

# Resumo do Laboratório Tradutor de Artigos Técnicos com AzureAI

No laboratório o professor mostrou como utilizar a plataforma da Azure para realizar traduções de duas formas, utilizando o serviço de tradução do Azure e o serviço de tradução da OpenAI. Em ambos os casos ele utilizou python, colab, requests e bs4 nos seus exemplos.

O professor mostrou e exemplificou os valores do serviço no Azure por meio de cálculos de caracteres ou tokens e exemplificou de forma prática traduzindo um documento e gerando uma versão traduzida em outro docx. 

Além disso, o professor traduziu um artigo por meio do fornecimento de uma url utilizando a OpenAI e langchain.

Foi possível aprender com o laboratório a utilizar as ferramentas de tradução do Azure em ambientes reais de desenvolvimento.

Escrito por __Jefferson Yuri__

# Resumo do Laboratório Análise de Documentos Anti-fraude com AzureAI

O professor utilizou um Storage Account e o serviço Document Intelligence para fazer um projeto que analisava documentos. No caso em questão ele estava analisando cartões de crédito.

O professor demonstrou de maneira prática como criar um analisador de documentos com ambos os serviços. No caso em teste ele fez com Streamlit um analisador de cartões de crédito e utilizou um modelo pré-built do Document Intelligence para analisar se a imagem repassada era de um cartão de crédito ou de outra coisa.

O laboratório foi de muito aprendizado para sabermos como utilizar o serviço de Document Intelligence.

# Resumo do Laboratório Trabalhando Aplicações Serveless no Azure

O professor realizou nesse laboratório um projeto utilizando Azure Functions e Logic Apps para criar um ToDo onde ao inserir uma nova tarefa era criado uma mensagem e inserida em uma fila. A arquitetura do projeto possuía duas Azure Functions uma que era disparada sempre que uma nova mensagem caía na fila. Essa function fazia a leitura da fila e enviava a mensagem para que outra function persistisse no banco de dados. Ao ser realizada a persistência a mensagem era excluída da fila.

O professor explicou muito bem com esse exercício como podemos utilizar Azure Functions em nossos projetos. As soluções serveless possuem diversas aplicações possuindo como principais vantagens o escalonamento facilmente a depender da demanda, facilidade em criar e configurar as funções, e facilidade de implantar, inclusive facilitando a continuous integration e a entrega contínua.

Este projeto também mostrou como esse tipo de aplicação é segura e como a Azure possue soluções robustas para lidar com Funções serveless.
