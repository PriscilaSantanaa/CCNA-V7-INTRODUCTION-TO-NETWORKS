## Roteamento Estático ✨

**roteamento:** comunicação entre gateways, selecionando o melhor caminho para os pacotes viajarem da origem ao destino. Essa escolha do melhor caminho é feita pelos roteadores, utilizando a tabela de roteamento.
<br></br>
<img width="650" height="349" alt="image" src="https://www.learncisco.net/wp-content/themes/learncisco/assets/images/icnd1/91-static-route-example.jpg" />
<br></br>
**tabela de roteamento estático** é um tipo de tabela onde as rotas são configuradas manualmente pelo administrador da rede. Para montar essa tabela, o administrador deve saber as rotas que o roteador não conhece e o próximo salto, ou seja, interface do roteador vizinho.

**principais características**<br>
configuração é feita manualmente pelo administrador da rede<br>
a atualização não é automatica, logo, caso ocorra qualquer alteração na rede, essas alterações devem ser configuradas manualmente<br>
é uma forma mais segura mas possui uma alta dificuldade na manutenção, principalmente em redes grandes e complexas<br>
é o oposto do roteamento dinâmico, aquele que usamos protocolos como OSPF, RIP ou BGP que descobrem a melhor rota de maneira automática.<br>

#### Cenário:
<img width="1426" height="595" alt="image" src="/home/priscilasantana/Documentos/CCNA-V7-INTRODUCTION-TO-NETWORKS/Roteamento Estático/Captura de tela de 2025-10-04 14-39-48.png" />
<br>
**script com configuração dos equipamentos dentro do diretório em .txt
