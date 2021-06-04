## System Architectures

# Monolito

<img src="img/monolito.png" >
<p>
Pros:
<li>Baixa Complexidade
<li>Monitoramento simplificado

Cons:
<li>Stack única
<li>Compartilhamento de recursos
<li>Acoplamento - sercices
<li>Escalabilidade mais complexa
</p>

# Microservice - 1

<img src="img/microservice1.png" >
<p>
Pros:
<li>Stack dinâmica
<li>Simples escalabilidade

Cons:
<li>Acoplamento
<li>Monitoramento mais complexo 
<li>Provisionamento mais complexo
<br>
</p>

# Microservice - 2

<img src="img/microservice2.png" >
<p>
Pros:
<li>Stack dinâmica
<li>Simples escalabilidade
<li>Desacoplamento

Cons:
<li>Monitoramento mais complexo 
<li>Provisionamento mais complexo
</p>

# Microservice - 3

<img src="img/microservice3.png" >
<p>
Pros:
<li>Stack dinâmica
<li>Simples escalabilidade
<li>Desacoplamento
<li>Menor complexidade

Cons:
<li>Provisionamento mais complexo
<li>Plataforma inteira depende do gerenciador de pipeline
</p>

## Gerenciamento de erros e volume de acesso

<p><li>Onde é mais complexo:
- Processos assíncronos (microservice -2)
- Pipeline

<li>Solução:
-Dead Letter queue
-Filas de re-tentativas </p>