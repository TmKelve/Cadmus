# Cadmus
<h2>Introdução as soluções desenvolvidas e seu funcionamento.</h2>

<p><b> Primeira Solução </b></p>
<p>Visando a tarefa realizada para gerar o relatório analítico das vagas em aberto, foi realizado um mapeamento para documentação e desenvolvida a automação para extração dos dados, criação do arquivo em Excel e o disparo do e-mail.</p>
<p>Deixo anexado no repositório o arquivo do .ipynb do Jupiter, o qual acredito ser mais organizado, como também, o arquivo .py do Python.</p>
<p>O pacote Python utilizado para a raspagem de página foi o BeautifulSoup.</p>
<p><b>1º Passo:</b></p>
  <p>Importação das bibliotecas, entre elas, o próprio BeatifulSoup como também o Pandas, Request, Win32 e Date. </p>
<p><b>2º Passo:</b></p>  
  <p>Realizar um request de validação ao site. </p>
<p><b>3º Passo:</b></p> 
  <p>Transformar o conteúdo da página em String.</p>
<p><b>4º Passo:</b></p>
  <p>Realizar um Parser para torna a estrutura dos dados aninhada.</p>
<p><b>5º Passo:</b></p>
   <p>Realizar a raspagem da página, extraindo as vagas em abertas e suas localidades, realizei um append e extrair somente os textos .</p>
<p><b>6º Passo:</b></p>
   <p>Criação do Dataframe no pandas, onde defini as colunas e os dados</p>
<p><b>7º Passo:</b></p> 
    <p>Definição de mais duas variáveis aonde, uma contém o nosso Dataframe criado no passo anterior convertido em .HTML e outro em .XLSX .</p>
<p><b>8º Passo:</b></p> 
    <p>Definição das variáveis com dados para o corpo do e-mail, data atual e a quantidade de setores com vagas abertas. </p>
<p><b>9º Passo:</b></p> 
    <p>Realizar as configurações do E-mail e anexar o arquivo em .XLSX. </p>
<p><b>10º Passo:</b></p> 
    <p>Criação do corpo do e-mail, com as variáveis de data, quantidade de vagas e a planilha em HTML</p>
<p><b>11º Passos:</b></p> 
    <p> Enviar E-mail. </p>


<p><b> Segunda Solução </b></p>
  <p> Como o desafio proposto foi obter uma solução do caso, acredito que a variedade de opções seja fundamental para o cliente, pensando nisso,
desenvolvi uma solução diferente da proposta, um relatório em Power BI o qual realiza a extração dos dados no site da empresa, calcula quantas
vagas em aberto e a variação dessas vagas, gerei uma matriz detalhado e criei um botão com integração ao Power Automate, o qual, ao ser
pressionado dispara um e-mail com o relatório de Vagas e Local no corpo do e-mail em HTML. </P
<p><b> 1º Passo: </b></p>
    <p> Obter os dados direto do site pelo Power BI </p>
<p><b> 2º Passo: </b></p>
    <p> Tratar os dados </p>
<p><b> 3º Passo: </b></p>
     <p> Criação das visualizações: </p>
        <p>Foi desenvolvido as visualizações em pontos de impacto para facilitar o entendimento e as tomadas de decisões. </p>
<p><b> 4º Passo: </b></p>
         <p>Desenvolvimento de fluxo no Power Automate, com gatilho manual o qual dispara um e-mail com o relatório no corpo em Tabela HTML. </p>
