# Cadmus
Introdução a solução e seu funcionamento.
<p>Visando a tarefa realizada para gerar o relatorio analitico das vagas em aberto,foi realizado um mapeamento para documentação e desenvolvida a automação para extração dos dados,criação do arquivo em excel e o disparo do email.</p>
<p>Deixo anexado no repositorio o arquivo do .ipynb do Jupiter, o qual acredito ser mais organizado, como tambem, o arquivo .py do Python.</p>
<p>O pacote Python ultilizado para a raspagem de pagina foi o BeautifulSoup.</p>
<p>1º Passo:</p>
  <p>Importação das bibliotecas,entre elas,o propio BeatifulSoup como também o Pandas,Request,Win32 e Date.</p>
<p>2º Passo:</p>  
  <p>Realizar um request de validação ao site.</p>
<p>3º Passo:</p> 
  <p>Tranformar o conteudo da pagina em String.</p>
<p>4º Passo:</p>
  <p>Parser HTML no conteudo da Pagina.</p>
<p>5º Passo:</p>
   <p>Realizar a raspagem da pagina, aonde primeiro extrai as vagas em aberto e por localidade,logo após, realizei um append como e extrair somente os textos .</p>
<p>6º Passo:</p>
   <p>Criação do Dataframe no pandas , onde defini as colunas e os dados</p>
<p>7º Passo:</p> 
    <p>Definição de mais duas variaveis aonde,uma contem o nosso Dataframe criado no passo anterior convertido em .HTML e outro em .XLSX .</p>
<p>8º Passo:</p> 
    <p>Definição das variaveis com, dados para o corpo do email,data atual e a quantidade de setores com vagas abertas.</p>
<p>9º Passo:</p> 
    <p>Realizar as configurações do Email e anexar o arquivo em .XLSX .</p>
<p>10º Passo:</p> 
    <p>Criação do corpo do email, com as variaveis de data, quantidade de vagas e a planilha em HTML</p>
<p>11º Pasos:</p> 
    <p> Enviar email.</p>

32
