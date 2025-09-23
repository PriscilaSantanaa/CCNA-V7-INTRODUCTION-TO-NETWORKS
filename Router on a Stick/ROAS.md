## ROAS (Router on a Stick) ✨

**roteamento:** comunicação entre gateways
<br></br>
<img width="650" height="349" alt="image" src="https://github.com/user-attachments/assets/35f3c247-631e-4f68-b3b5-e43c6cfee75c" />
<br></br>
**router-on-a-stick (roas):** é uma técnica para conectar um roteador com uma única interface a um switch e realizar o roteamento IP entre VLAN’s.
> utilizamos um switch L2 e um roteador.<br>
> para fazer comunicação entre switch’s não podemos usar uma porta de acesso, usamos uma porta tronco.

**qual a diferença entre portas de acesso e portas tronco?**<br>
**portas de acesso** → conectam dispositivos finais (computadores, impressoras, telefones IP, etc) a uma rede, atribuindo-os a uma única vlan
**portas tronco** → interligam switches, roteadores e outros dispositivos intermediários de rede, permitindo o transporte simultâneo de tráfego de várias vlans<br>
ou seja, podemos passar vlan na porta de acesso mas somente uma. na porta tronco podemos pasar várias vlans na mesma porta.

#### Cenário:
<img width="1426" height="595" alt="image" src="https://github.com/user-attachments/assets/617a6a77-aa0d-46be-a5fe-9f5ad52fbf93" />
<br>
**script com configuração dos equipamentos dentro do diretório em .txt
