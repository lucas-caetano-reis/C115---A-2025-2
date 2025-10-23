# Trabalho Mininet - C115 A
# Lucas Caetano Reis - 1953 - GEC
# Criação da Topologia
<img width="662" height="419" alt="topologia" src="https://github.com/user-attachments/assets/682d78c8-4147-416f-ac51-29d0c9f0ebb5" />

Topologia linear com 6 switchs, 6 portas e um controlador. O endereço MAC foi padronizado e a largura da banda bw foi definida em 25 Mbps.

# Interface da Topologia
<img width="661" height="298" alt="nodes e nets" src="https://github.com/user-attachments/assets/d7da6397-6e1f-4b0c-ace5-70a79fca84e6" />

Inspeção dos hosts e switchs da topologia.

<img width="658" height="235" alt="dump" src="https://github.com/user-attachments/assets/3db6f9e8-203c-4088-8410-2fd628956902" />

Ligações entre os diferentes nós da topologia.

# Configuração dos Hosts
<img width="542" height="564" alt="dados h1 e h2" src="https://github.com/user-attachments/assets/f06ca930-1b30-442a-8db8-be67ed12cbdd" />

Inspeção dos endereços MAC e IP das portas H1 e H2.

# Configuração dos Switchs
<img width="620" height="1013" alt="s1 parte 1" src="https://github.com/user-attachments/assets/15c681cd-9e0b-4dff-827a-8dc7355c0319" />

<img width="599" height="1013" alt="s1 parte 2" src="https://github.com/user-attachments/assets/77b41c8d-16d9-4f48-a3cd-c0c1038ee2c7" />

<img width="535" height="926" alt="s1 parte 3" src="https://github.com/user-attachments/assets/f927f833-e502-439e-8eaa-a3dade1289d9" />

# Testes de Conectivade
<img width="542" height="229" alt="h1 ping h2" src="https://github.com/user-attachments/assets/d4f63ef9-56e5-4e81-8367-8299809e0ac8" />

Teste de conectividade entre o host 1 e o host 2, sem limite de pacotes.

<img width="506" height="196" alt="h2 ping h3" src="https://github.com/user-attachments/assets/654606b4-322d-42f3-8774-703502ffed59" />

Teste de conectivade entre o host 2 e o host 3, com limite de 5 pacotes.

<img width="334" height="163" alt="pingall" src="https://github.com/user-attachments/assets/44dd4f01-272f-4b7f-8796-61374bd7e896" />

Teste de conectivade geral.

# Interface de Desempenho (iperf)
<img width="971" height="348" alt="iperf h1 h2" src="https://github.com/user-attachments/assets/4bc7deef-fdfb-44cc-818b-44510d3ab26d" />

O host h2 foi configurado como sendo um servidor TCP com porta 5555, capaz de executar 1 teste iperf a cada 15 segundos. Por sua vez, o host h1 foi configurado como sendo o cliente, também com porta 5555.
