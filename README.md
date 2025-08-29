# 📊 Análise de Vendas com Excel

Este projeto tem como objetivo demonstrar minhas habilidades em análise de dados com **Excel** como ferramenta principal, desde a importação e limpeza de dados até a criação de dashboards interativos.  
Os dados utilizados são reais e foram obtidos no [Kaggle](https://www.kaggle.com/).

---
## Projeto em andamento! Atuamente na etapa 3, análise exploratória
---

## Apresentação Geral do Dataset:

Este conjunto de dados contém uma lista de +16.000 linhas de videogames com vendas superiores a 100.000 cópias. Foi gerado a partir de uma busca no vgchartz.com e disponibilizado no kaggle.com

---

## Insight em Destaque
Distribuíção de Lançamentos por Ano
  
![Gráfico de linha mostrando o número de games por ano](Análise%20exploratória/Indentificação%20de%20Padrões%20Gerais/Número%20de%20jogos%20por%20ano/Numero%20de%20Jogos%20por%20Ano.png)

O gráfico mostra um crescimento quase constante de lançamentos até 2008, seguido de uma forte queda.

Esse comportamento não reflete a realidade da indústria de games, que segue em expansão, por esse motivo me questionei sobre oque gerou essa estranha queda,
primeiro criei uma hipótese: será que isso se deve ao fato do dataset só considerar jogos que atingiram ao menos 100 mil cópias vendidas? Sendo assim jogos 
lançados após 2015 tiveram pouco tempo para alcançar esse marco, o que causa a queda aparente... Para testar essa hipótese decidi medir a correlação entre
a idade de cada jogo (maior ano considerado no dataset que é 2020 menos a data de lançamento do game) e o número de vendas de cada jogo, mas para minha supresa
a correlação, apesar de positiva, foi extremamente fraca (0,05).

Resposta encontrada: Ao buscar contexto, informações do mercado de games descobri que o mercado de jogos continuou crescendo, mas o modo de consumo mudou. 
Antes (anos 80–2000s) o desempenho era medido por unidades físicas vendidas, em 2008 começaram a entrar em cena downloads digitais 
massivos, jogos free-to-play com microtransações (jogos grátis que faturam com vendas dentro do game) e jogos mobile, mais assinaturas, como gamepass — tudo isto gera receita 
e atenções, mas não aparece num contador de “cópias vendidas”.

## Jogos mobile, serviços de assinatura e jogos gratuitos que faturam através de microtransações começaram a dominar o mercado
---

## 🛠️ Ferramentas Utilizadas
- **Excel** → Limpeza, análise e dashboards  
- **VS Code** → Organização e edição de arquivos do repositório  
- **GitHub Desktop** → Controle de versão e envio dos arquivos para o GitHub 
- **PowerBI** → Criação de dashboard 

---

## 📂 Estrutura do Repositório

analise_de_vendas_excel/

 -Dados/ 
 <blockquote>
  
   games_dataset_bruto.csv # dados originais
     
   games_dataset_limpo.xlsx # dados tratados
   
 </blockquote>
-Análise exploratória
 
 <blockquote>
Uso de **tabelas dinâmicas** e funções estatísticas para extrair informações
 
 
 </blockquote>
 -Limpeza e organização/
 <blockquote>
 
 #processo de limpeza com prints 
 e textos explicando o processo
 
 </blockquote>
 
 -Documentacao/
 
 
 -README.md

---

## 🚀 Etapas do Projeto

### 1. Importação dos Dados
Carregamos o dataset original no Excel.  

---

### 2. Limpeza e Tratamento
Foram removidos dados duplicados, valores inconsistentes e padronizadas as colunas.  

---

### 3. Análises Exploratórias
Uso de **tabelas dinâmicas** e funções estatísticas para explorar o dataset.  

---

### 4. Criação do Dashboard
Gráficos e indicadores principais para melhor visualização das vendas.  

---

### 5. Resultados e Conclusões
Resumo dos principais insights encontrados.  

---

## 📸 Prints Detalhados
Você pode conferir prints de todas as etapas durante o processo
  

---

## 👤 Autor
Feito por **Caio** – Estudante de Ciência de Dados e entusiasta de análise de informações.  

