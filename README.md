# Configuração de rede MPLS com roteadores CISCO 7200

## Observações
- :question: [Ambiente de simulação](#Ambiente-de-simulação)
- :file_folder: [Organização dos arquivos](#Organização-dos-arquivos)
- :sparkles: [Demonstrações](#Demonstrações)
  
## Ambiente de simulação
  Para a simulação dessa rede foi utilizado o [GNS3](https://www.gns3.com/). As imagens utilizadas nos roteadores podem ser obtidas através do GOOGLE (:wink:).
  
## Organização dos arquivos
  Há duas redes foram implementadas. Cada rede está contida em um arquivo nomeado como /redeX, onde X é o número da rede. Em cada arquivo há um relatório explicando os detalhes da implementação, bem como a configuração de cada roteador específico. A configuração de um roteador é marcada com o nome do roteador entre colchetes: "\[NomeDoRoteador\]".
  
## Demonstrações

#### Exercício 2 (Roteadores utilizando protocolo de roteamento interno OSPF)
![Exerc2](https://github.com/DarkMCT/host_images/blob/master/Topologia.png)

#### Exercício 2 parte C (Adicionar um roteador que não esteja na mesma MPLS que os demais)
![Exerc2C](https://github.com/DarkMCT/host_images/blob/master/Topologia%20(C).png)

#### Exercício 3 (Configuração de uma rede MPLS com duas VRF's distintas)
![Exerc3 Original](https://github.com/DarkMCT/host_images/blob/master/Topologia%20original.png)

#### Exercício 3 Modificações (Movendo roteadores e adicionando novos roteadores à rede implementada no exercício 3)
![Exerc3 Modificado](https://github.com/DarkMCT/host_images/blob/master/Modifica%C3%A7%C3%B5es%20na%20topologia%20original.png)
