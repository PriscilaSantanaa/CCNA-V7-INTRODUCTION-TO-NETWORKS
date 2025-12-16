## Lista de controle de acesso (ACL) ✨

### O que é uma ACL?
"Uma ACL é uma série de comandos IOS usados ​​para filtrar pacotes com base nas informações encontradas no cabeçalho do pacote. Por padrão, um roteador não tem nenhuma ACL configurada. No entanto, quando uma ACL é aplicada a uma interface, o roteador executa a tarefa adicional de avaliar todos os pacotes de rede à medida que passam pela interface para determinar se o pacote pode ser encaminhado." (Fonte: https://ccna.network/objetivo-acls/)
<br></br>
Podemos utilizar as ACL's inclusive para melhorar o roteamento da rede e economizar processamento dos ativos e largura de banda. Além disso, conseguimos criar tarefas como: limitar o tráfego de rede, triagem de hosts na rede, dar prioridade para determinadas classes de tráfego, etc.
<br></br>
Os roteadores Cisco oferecem suporte a dois tipos de ACL:
- ACLs padrão: Filtram apenas na camada 3 usando apenas o endereço IPv4 de origem
- ACLs estendidas: Filtram na camada 3 usando o endereço IPv4 de origem e/ou destino. Essas ACLs também podem filtrar na camada 4 usando portas TCP, UDP, serviços, etc.
<br></br>
### Cenário:
<img src="https://github.com/PriscilaSantanaa/CCNA-V7-INTRODUCTION-TO-NETWORKS/blob/main/ACL/Captura%20de%20tela%20de%202025-12-16%2020-18-28.png" width="880px"/>
