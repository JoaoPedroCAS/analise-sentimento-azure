# Análise de Sentimentos com Language Studio no Azure AI

Este repositório documenta um experimento passo a passo utilizando o **Language Studio** no **Azure AI** para realizar análise de sentimentos e extração de opiniões a partir de textos.

## Sobre o Projeto
Este projeto foi desenvolvido como parte do desafio de projeto no **Bootcamp Microsoft Azure AI Fundamentals** da **Dio.me**.

## Recursos Utilizados
- **Microsoft Azure AI**
- **Language Studio**
- **Análise de Sentimentos e Extração de Opiniões**
- **Plano Gratuito (F0)**

### Documentação Oficial
Para mais informações sobre a ferramenta, acesse a documentação oficial: [Microsoft Azure AI Text Analysis](https://aka.ms/ai900-text-analysis).

---

## Passo a Passo: Criando o Recurso no Azure

### 1. Criar um Recurso no Azure
1. Acesse o portal do Azure: [Azure Portal](https://portal.azure.com/#home).
2. Clique em **"Criar um recurso"**.
3. Selecione **"Language Service"**.
4. Clique em **"Continue to create your resource"**.

### 2. Configurar o Recurso
1. Escolha um **Resource Group** (ou crie um novo).
2. Defina um **nome único** para o recurso.
3. No campo **Pricing Tier**, selecione **Free (F0)**.
4. Clique em **"Create"** e aguarde a configuração do recurso.

---

## Passo a Passo: Configurando o Language Studio

### 1. Acessar o Language Studio
1. Acesse o [Language Studio](https://language.cognitive.azure.com/) e faça login.
2. Uma janela modal será exibida com campos para preencher:
   - **Azure Subscription** (seu plano do Azure)
   - **Resource Type** (selecione "Language Service")
   - **Resource Group** (selecione o que você criou anteriormente)
3. Clique em **"Done"** para salvar as configurações.

### 2. Realizar Análise de Sentimentos
1. No **Language Studio**, selecione a aba **"Classify Text"**.
2. Clique no card **"Analyse Sentiment and mine opinions"**.
3. Selecione o idioma do texto (**English**).
4. Copie e cole o seguinte texto de exemplo fornecido pela documentação na caixa de texto:

   ```
   Tired hotel with poor service
   The Royal Hotel, London, United Kingdom
   5/6/2018
   This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk.
   ```

5. Clique em **"Analyze"** e aguarde o processamento dos resultados.
6. O Azure AI exibirá a análise de sentimentos e opiniões extraídas do texto.

---

## Resultados Esperados
Após a análise, você receberá um retorno contendo:
- **Classificação do sentimento geral** (positivo, neutro ou negativo).
- **Extração de opiniões** sobre diferentes aspectos do texto.
- **Pontuação de confiança** associada a cada classificação.

