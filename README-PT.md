# Relatório Covid-19 em Araraquara - SP
Gera um arquivo .pdf com dados da de casos, óbitos, internações e vacinação na cidade de Araraquara-SP.

<p align="center">
  <img src="https://user-images.githubusercontent.com/65920703/127745697-b2e883fa-7dfe-4282-89d6-bd5b86f8acea.jpg" alt="Page 1" width="300">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/65920703/127745773-92b06572-c3bd-4a3d-8557-c50e199de9b6.jpg" alt="Page 4" width="300">
</p>

## Requisitos
O Jupyter notebook "Covid-19-Araraquara.ipynb" usa as famosas bibiotecas Matplotlib, Seaborn, Numpy, Scipy e Pandas, as quais necessariamente devem estar instaladas a fim de executar o código.

Certifique-se tambem de instalar tambem json, urllib.request e FPDF. Sendo a última necessária para a geração do arquivo .pdf.

## Como usar
Baixe ambos arquivos .ipynb e .xlxs contendo o programa e os dados e execute a rotina. Certifique-se que ambos arquivos se encontram no mesmo diretório.

O Notebook gera e salva neste diretório multiplos plots, os quais serão usados para compor o relatório.

## Dados
Os dados do arquivo .xlxs são coletados manualmente do boletim diário do "Comitê de Contingencia do Coronavirus" da Prefeitura de Araraquara e são adicionado (quase) todos os sábados neste repositório.

![Screen Shot 2021-07-31 at 13 33 36](https://user-images.githubusercontent.com/65920703/127746420-bd0d2c4d-a6af-4cc3-a711-e4fa1edab2b6.png)


## Comentários
Por favor observe que este código não está completamente otimizado e definitivamente existe possibilidade de melhora no tempo de execução e implementação de modo geral.

Sinta-se livre de usar tanto o código quanto os dados da maneira que quiser.

Em caso de dúvidas, mande um E-mail para d195860@dac.unicamp.br.