# Plugin Barra Oficial do Governo

## 🎯 Problema Identificado

Durante o desenvolvimento do tema "IBRAM 2025" para os sites oficiais dos museus, surgiu a necessidade de integrar a **Barra Oficial do Governo Federal** de forma fixa no cabeçalho (*header*) de todos os sites.

Na prática, inserir o código da barra diretamente no tema se mostrou inviável, pois qualquer atualização do WordPress ou do próprio tema resultaria na sua remoção. 

## 🛠️ Solução Desenvolvida

Diante disso, me desafiei a criar um plugin exclusivo para resolver esse problema. A implementação consiste em dois scripts PHP:

* O primeiro gera o HTML da barra, incluindo uma `div` e a `tag <script>` que carrega o conteúdo oficial via CDN.
* O segundo aplica as regras de CSS necessárias para fixar a barra no topo do site, sem afetar a estrutura visual do tema principal.

Com este plugin, toda a lógica de exibição da barra foi centralizada de forma prática e organizada. Basta ativá-lo para que a barra apareça automaticamente no site, sem a necessidade de modificar manualmente o código do tema.

## ✅ Benefícios

* Resistente a atualizações do WordPress ou do tema
* Gestão centralizada e padronizada
* Zero dependência de inserção manual
* Manutenção simples e segura

![Preview da barra](assets/screenshot.png)
