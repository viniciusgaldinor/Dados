2ª parte do Curso:

## INTRODUÇÃO A LINGUAGEM DE PROGRAMAÇÃO (SCANIA):

- ![[Fluxograma_tipos_simbolos.png]] --> Fluxograma
- MOD 2 =0 :se o resto da divisão por 2 for igual a zero, faça....
- 9 DIV 4 = 2: o resultado inteiro da divisão

- Variáveis indexadas: cada vez do loop a variável se torna um valor--> vetor v=(1,2,3,4,...) v= v+1

- Laço/loop encadeado: loop dentro de outro


- Processamento predefinido:
	- TROCAR (A,B)= o valor B recebe o valor A

![[CertificadoDeConclusao_Introducao a Ciencia de Dados Conceitos Basicos.pdf]]
![[Introducao a logica de programacao.pdf]]

## SCANIA - ETL na Prática - Como Trabalhar com Dados

CRISP-DM: Cross industry standard process for data mining

PRÉ PROCESSAMENTO:
1)entendimento do negócio - Objetivo, necessidade, métricas
2)entendimento sobre os dados - quais dados? onde estão armazenados? fontes? 			   atualização?
3)preparaçao dos dados - problemas?,ajustes, preparação para a fase final,         adequação

MODELAGEM
4)modelagem - construção da solução, machine learning, aplicar técnicas para       solução do problema
5)avaliação - métricas, medidas, entendendo os dados novamente, novas análises e   ajustes

IMPLANTAÇÃO
6)implantação - colocar em produção a melhor produção encontrada!


## ETL: Extract-> Transform-> Load
![[Processos_ETL.png]]-->resultando em um dado em um #Data_Warehouse
- dado estruturado: relacionais que podem ser usados a linguagem sql cara consulta
- não estruturados: dados em forma de áudio, vídeo, imagens e documentos
- semi-estruturado: XML, ele tem uma estrutura, porém, flexível


# Python
- Usa-se o Jupiter (interface web) como interface de desenvolvimento


Ler um arquivo do computador

 - Funções:
	 -	File = Open("caminho do arquivo","w ou r ou a ")
	 -	modo correto:
	 -	File = open("C:/Users/VGADR5/Desktop/Data Squad/ETL/sobrepython.txt","r")
		 -	File é a variável de leitura
		 -	w é write: escrever, porém ele sobreescreve 
		 -	r é read: ler
		 -	a é append: adiciona conteúdo sem apagar 
	agora coloco:
	- File.read(): ele aparece o que tem dentro no arquivo
	- File = open("C:/Users/VGADR5/Desktop/Data Squad/ETL/sobrepython.txt","r",encoding="utf-8")  --> coloco o formato de acento visivel normalmente na palavra, sem dar erros
	
	- File.seek(0) -->joga o cursor para o inicio do texto do arquivo
	
	- import pandas as pd : importo a biblioteca do pandas dou apelido de "pd"
- notas = pd.Series([10,8,7,9]): uso a biblioteca do pandas (pd) e atribuio isso a variavel notas
- notas.mean(): significa calcular a media das notas 

- pallet = pd.read_csv("C:/Users/VGADR5/Desktop/Data Squad/ETL/packing_data.csv",sep=";") :le o arquivo de uma forma correta, ele está separado por ponto e virgula

- pallet.head(10) : le as primeiras 10 linhas
- pallet.tail(8) : le as ultimas 8 linhas

- Dados sobre transformação, ver link:
	- http://localhost:8888/notebooks/Tranforma%C3%A7%C3%A3o.ipynb

