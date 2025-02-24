<h1>
    <a href="https://www.dio.me/" style="color:8542DB">
     <img align="center" alt="Dio Logo" width="66px" src="https://ac-landing-pages-user-uploads-production.s3.amazonaws.com/0000051657/a6176d56-6fab-496b-93a9-b95c0f49b56b.png">
    <span>Atividade Laboratorial de IA - DIO</span></a>
</h1>

<main>
<img align="right" alt="Platform" height="350" src="https://cdn.prod.website-files.com/66460d4ab476aafd53ffb355/66460d4cb476aafd530082e8_speech.microsoft.com-portal.jpeg">
<p align="justify"><h1> Laboratório da trilha de IA DIO.</h1>
<br/>
O intuito deste laboratório é apresentar um pouco sobre Speech e Language Studio, visando testar os conhecimentos adquiridos durante as videoaulas.
Infelizmente, não possuo uma assinatura Azure, então realizei um percurso simulado da utilização das ferramentas com base nos estudos adquiridos, seguindo os processos e métodos recomendados para a análise e conversão de texto em áudio e análise de sentimento.
</p>
</main>

<article>
<h1>Percurso</h1>

<h2>
    <img align="center" alt="Copilot Logo" width="45px" src="https://brandlogos.net/wp-content/uploads/2023/09/microsoft_copilot-logo_brandlogos.net_zaqzr.png"> Análise de Sentimentos e Geração de Áudio com IA
</h2>

+ **Speech Studio**: Utilizando o Microsoft Speech para converter sentenças textuais em áudio, criando uma experiência de voz sintética para textos.

+ **Azure Cognitive**: Azure Cognitive Services para análise de sentimento de cada sentença inserida, determinando se o sentimento é positivo, negativo ou neutro.

<h3>Passos Realizados:</h3>

1. Criação do Documento de Entrada
+ A pasta inputs/ contém alguns textos iniciais, que foram utilizados tanto para a conversão em áudio quanto para a análise de sentimentos.

2. Utilização do Microsoft Speech
+ Para gerar o áudio, foi implementada a conversão de texto em fala através da criação do recurso utilizando o serviço de Microsoft Speech. 
+ O arquivo de texto foi anexado no recurso, que converteu o conteúdo em áudio.

3. Análise de Sentimento com Azure Cognitive Services
+ Para análise de sentimentos, foi feita a implementação da ferramenta de linguagem através do portal Azure. 
+ Foi realizado a criação do recurso **Análise de sentimento e opniões** na Classificação de texto.
+ O arquivo de texto foi anexado no recurso, as sentenças do arquivo foram analisadas através do serviço, que retornou o sentimento geral do texto. Isso permitiu observar como diferentes frases geram diferentes sentimentos.

</article>


<div align="center">Made by <a href="https://github.com/kurokagami/">Kuro Kagami</a>.</div>