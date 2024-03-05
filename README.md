# Desafio de projeto

## Reconhecimento Facial e transformação de imagens em Dados no Azure ML

Projeto desenvolvido no Bootcamp Microsoft Azure AI Fundamentals - oferecido pela **[Digital Innovation One](https://www.dio.me/)**.

Para a prática deste laboratório é necessário ter uma conta na Microsoft e acessar o portal [Azure](https://portal.azure.com/).

## Passos

1. Realizar o login no portal [Azure](https://portal.azure.com/).

2. Clicar em **Create Resource**

   ![image](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/f8e55bf3-a8b9-4f45-aaf5-a0dbf81d4363)
   
4. Clicar em **AI + Machine Learning**, localizar **Azure AI Services** e clicar em **Create**

   ![image](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/542e8937-c22e-4074-9ca0-110f1b5cb19b)

5. Nas configurações básicas é necessário:
   - Criar ou inserir o nome de um Resource Group
   - Dar um nome para a instância
   - Selecionar no Princing Tier: Standard S0
   - Selecionar que leu os termos de uso.
  
  ![image](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/e60c9acd-e71b-4c3b-a667-7d186e1b072a)

6. Clicar em **Create** para que seja criado.

   ![image](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/5cac65d8-277c-46a8-a6e0-b7295d3d00d8)

   Aguardar e assim que o Deploy for concluído, basta clicar em **Go to Resource** como na imagem abaixo ou acessar diretamente o link do [Vision Studio] (https://portal.vision.cognitive.azure.com/)

   ![image](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/3f3e6f25-fad7-449c-9012-543138a90f0e)

7. Dentro do portal [Vision Studio](https://portal.vision.cognitive.azure.com/), clicar em **View all Resources**

   ![image](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/e2d22797-ea96-405c-8aa1-b3dd7e2f88ee)

8. Selecionar o Resource que vai utilizar e clicar em **Select as default resource**, no meu caso eu já tinha feito testes e por isso aparecem outros resources.
   Caso o resource que foi criado não apareça automaticamente, basta clicar em Refresh para a página ser atualizada e já deverá aparecer o novo resource que foi criado.

   ![image](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/4e683763-5a0b-4b8a-a31c-3af16b56fe7f)

   Assim que for selecionado, em Current resource já vai aparecer o nome atualizado. Então basta clicar no X para fechar essa tela.

   ![image](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/8fab4526-2d8c-4b0a-9f28-42a16bedbbc5)

10. Na tela inicial, selecionar **Optical character recognition** e em seguida **Extract text from images**

    ![image](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/8022cec9-5c9f-4a05-ac83-31586cdce405)

    Então é necessário selecionar a box de que será utilizado o determinado resource.
    Logo em seguida já é possível realizar um teste com as imagens disponíveis ou selecionar um arquivo ou ainda tirar uma foto.

    ![image](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/383e07b0-d823-4ab7-af54-3e8157f1ddf0)

    Neste exemplo, utilizei uma imagem do próprio portal e assim que o processamento for feito, os textos aparecerão no canto direto da tela em **Detected attributes**

_____________________________________________________________________________________________________________________________________________________

## Projeto pessoal

Para concluir este lab decidi realizar o teste de leitura de texto em imagens em livros e discos.

Na pasta *Inputs* é possível verificar as imagens originais.

Na pasta *Outputs* é possível verificar os screenshots com a identificação dos textos nas imagens.

# Exemplo:

Input 1
![input1](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/d75e1039-47a9-4d97-b351-6b90528a4283)

Output 1

![output1](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/05acc385-ec5e-4a07-ab56-43b54cf3e45b)


## Principais insights 💡

- Acessibilidade que condiz em facilitar a leitura de textos em imagens para pessoas que possuem baixa visão;
- Catalogação de arquivos pessoais de textos em imagens como em livros físicos, discos, CDS e outras mídias;
- Catalogação de documentos históricos para pesquisas;
  
