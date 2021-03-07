# ufpr-abntex2

==========================

##O modelo criado:
 
 fig.jpg
 tipog.png
 figure.png são figuras e para compilar corretamente devem ser salvas na pasta fig/
 
 TermoA1.pdf
 FichaC1.pdf arquicos pdf do termo de aprovação  e ficha catalográfica. Para que os arquivos sejam inseridos nos 
 locais devidos, deve-se colocá-lo na pasta: metadados/ e retirar o algarismo 1 no final dos nomes dos arquivos.
 
 00-dados.tex 
   Possui os dados necessários para identificar o autor, instituição, trabalho, preambulo, resumo, epígrafe
   lista de siglas e de simbolos,....
 
 00-pacotes.tex 	
   Possui os pacotes customizados para o funcionamento de acordo com as normas da UFPR
   
 00-pretextual.tex 	
   Utilização dos arquivos de entrada de dados e de pacotes para criar os elementos prétextuais

 cap01.tex 	
   Demonstração do uso de comandos criados para a customização
   
 UFPR.sty 	 é o pacote de estilos
	
 main.tex 	 arquivo principal da customização, é o arquivo que deve ser compilado.
 
 referencias.bib exemplo de um arquivo de referências bibliográficas para exemplificar o uso do abntex2cite

 figure.png     arquivo da imagem de exemplo:  https://goo.gl/IpBzr1, deve ser colocada na pasta fig;
 FichaC1.pdf    arquivo da Ficha Catalográfica de exemplo: deve ser colocada na pasta metadados;
 TermoA1.pdf    arquivo do Termo de aprovação de exemplo: deve ser colocada na pasta metadados.

==========================

##Instruções para o uso da customização:

1) Utilize a codificação UTF-8 para trabalhar com a customização;

2) Tenha a disposição um compilador com o pdfLaTeX;

3) Edite as informações solicitadas no arquivo 00.dados.tex

4) Compile o arquivo main.tex 

## Qualquer dúvida ou comentário:  emilio.kavamura@ufpr.br ou eek.edu@outlook.com

Grato.
