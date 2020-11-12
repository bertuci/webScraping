# Web Scraping 
![Screenshot_44](https://user-images.githubusercontent.com/55574172/98995697-79512e80-2510-11eb-864b-86df04961dbc.png)

Web Scraping  simples.

Web Scraping feito para pesquisar vagas de Data Science no site https://br.indeed.com/

para que você consiga utiliza-lo em outros sites é necessários algumas alterações:

deve-se trocar o link do site que você queira fazer o scraping.

![Screenshot_41](https://user-images.githubusercontent.com/55574172/98993096-c8956000-250c-11eb-8d8f-f89fcad09d5b.png)

A próxima alteração é necessário inspecionar o código da página e para fazer isso existe algumas maneiras, e as mais famosas são: botão direito do mouse e em seguida inspecionar, a outro é utilizando a tecla F12. em seguida clique no botão que está aparecendo na imagem abaixo ou pressione CTRL + SHIFT + C e selecione a parte do site que você quer analisar.

![Screenshot_38](https://user-images.githubusercontent.com/55574172/98994087-1068b700-250e-11eb-9ed0-f3d1fc418cbe.png)


Depois de encontra a informação que deseja extrair você deve se atentar ao tipo, a classe, o que você quer retirar dessa classe( seugue exemplo abaixo)

![t](https://user-images.githubusercontent.com/55574172/98994886-4d817900-250f-11eb-906d-0ce1acea54a9.png)


e depois faça isso para cada informação que você queira armazenar.

depois de ter feito o scraping você pode guardar essas informações e para isso existe o comando:
dados.to_csv ( r'C:\Users\mateu\Desktop\Web_Scraping\ teste1.csv ', index = False )
dados é o dataset que você armazenmou as informações, depois usamos a biblioteca pandas para transformar o dataset em um CSV em seguida passamos o camiho que queremos guardar e depois damos um nome ao arquivo csv.

