## Internet of Things - IoT
A Internet das Coisas (IoT) descreve a rede de —“objetos físicos”— incorporados a sensores, software e outras tecnologias com o objetivo de conectar e trocar dados com outros dispositivos e sistemas pela internet. Esses dispositivos variam de objetos domésticos comuns a ferramentas industriais sofisticadas. Com mais de 7 bilhões de dispositivos IoT conectados hoje, os especialistas esperam que esse número cresça para 10 bilhões em 2020 e 22 bilhões em 2025. - Oracle.

<img src="img/conceps-iot.png">

# Desafios da IoT
<ul>Privacidade e Segurança</ul>
<ul>Quantidade exponencial de dospositivos conectadas a rede</ul>
<ul>Ser capaz de processar e armazenar uma enorme quantidade de informações</ul>
<ul>Gerar valor a partir dos dados coletados</ul>

# Arquitetura das IoTs
<p>Atributos a se considerar ao escolher um IoT device:</p>
<li>Baixo consumo de energia;
<li>Rede de dados limitado;
<li>Resilência;
<li>Segurança;
<li>Customização;
<li>Baixo custo.

# Popular platforms:

Arduino:
<p><li>Plataforma de prototipagem;
<li>Com entradas e saídas;
<li>Programável em C/C++;
<li>Interface serial ou USB;
<li>Shields.</p>

Embarcados:

<p>MCUs</p>
<p><li>Microcontrolador de chip único;
<li>Sistema Operacional real time;
<li>Embarcado;
<li>Uso industrial, médico, militar, transporte.</p>

Microcomputadores:

<p>Raspberry PI</p>
<p><li>Computador completo
<li>Hardware integrado em uma única placa
<li>Roda SO Linux ou Windows
<li>Uso doméstico e comercial</p>

# MQTT Protocol - Message Queuing Telemetry Transport

<p>Mais conhecido e mais utilizado de IoT. Ligando um GPS device com Smartphone Android para se comunicar pela nuvem.</p>
<p><li>Base na pilha do TCP/IP
<li>Protocolo de mensagem assíncrona (M2M - Machine to Machine)
<li>Criado pela IBM para conectar sensores de pipelines de petróleo a satélites
<li>Padrão OASIS suportado pelas linguagens de programação mais populares</p>

# Modelo de arquitetura IoT

<p>Modelo Cliente - Servidor:</p><br/>
<p><img src="img/modelo-client-serv.png"><br/>

<p>Modelo Publisher-Subscriber:</p><br/>
<p><img src="img/modelo-ps.png"></p><br/>

<p>O broker é um middleware que vai ser responsável por repassar as informações, no caso de monitoramento de localização em tempo real ele apresenta as determinadas funções:</p><br/>
<p><img src="img/broker.png"></p><br/>

<p> Uma vez lidando com serviço de mensagem através do broker, faz-se necessário adotar algum protocolo que garanta a qualidade na entrega das mensagens, para tal, usa-se o QoS.</p><br/>

<p><b>QoS</b></p>
<p>Quality of Services:</p><br/>

<li> Nível 0:
<ul>Mais barato</ul>
<ul>Menor esforço</ul>
<ul>Sem garantia de entrega</ul>
<ul>Mensagem não é retransmitida</ul>

<li> Nível 1:
<ul>Garante que a mensagem foi entregue no mínimo uma vez ao destinatário</ul>
<ul>Mensagem pode ser retransmitidade se não houver confirmação da entrega</ul>

<p><li> Nível 2:
<ul>Considerado o mais caro</ul>
<ul>Garante que a mensagem foi entregue no mínimo uma vez ao destinatário</ul>
<ul>Mensagem pode ser retransmitidade se não houver confirmação da entrega</ul></p><br/>

# Cloud

<p><li>Número de devices conectadores cada vez maior;
<li>TBs ou PBs de informações;
<li>Potencial de escala global;</p><br/>

<p><b>Líderes em serviço de cloud:</b></p>
<li><a href="https://aws.amazon.com/pt/">Amazon Web Services</a>
<li><a href="https://azure.microsoft.com/pt-br/">Microsoft Azure</a>
<li><a href="https://cloud.google.com/free">Google</a>