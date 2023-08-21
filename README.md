# Criação de Instância EC2 e Acesso SSH

## Introdução
Este relatório descreve a criação de uma instância de máquina EC2 na AWS e também descreve a conexão por meio do SSH. O processo foi documentado usando capturas de tela e commits no GitHub.

## Objetivo
O objetivo deste relatório é demonstrar o processo de criação de uma instância EC2 e o acesso bem-sucedido a ela por meio do protocolo SSH.

## Materiais
- Conta na AWS
- Ferramenta de acesso SSH
- Conta no GitHub

## Método
1. Criação da instância EC2 na AWS.
2. Configuração das opções de segurança para permitir o acesso SSH.
3. Acesso à instância EC2 por meio do SSH.
4. Documentação das etapas com capturas de tela.
5. Criação de um repositório no GitHub.
6. Envio das capturas de tela e documentação ao repositório usando commits.

## Resultados
### Etapa 1: Criação da Instância EC2
<img width="1440" alt="Captura de Tela 2023-08-20 às 21 21 47" src="https://github.com/brunomleao/entrega_semana3_prog/assets/99328889/4dc8ef96-4c73-49b9-a435-15936a0335fc">
<img width="1440" alt="Captura de Tela 2023-08-20 às 21 23 05" src="https://github.com/brunomleao/entrega_semana3_prog/assets/99328889/2f88aea5-f0ba-441b-8ec9-ac27d9e8f2f5">
Criei a instância EC2 chamada "entrega_semana3_prog" e registrei tirando um print da tela de "Instâncias". Além disso, durante o processo de criação, configurei uma chave de segunraça .pem, que foi baixada para a pasta downloads.


### Etapa 2: Acesso SSH
<img width="1440" alt="Captura de Tela 2023-08-20 às 21 22 42" src="https://github.com/brunomleao/entrega_semana3_prog/assets/99328889/ee17cd4e-7683-42e9-afcf-134f590b3919">
Nesta etapa, seguindo a recomendação da própria AWS, naveguei até a pasta Downloasd, local onde estava meu arquivo .pem, como foi descrito na etapa anterior e utilizei o comando "chmod 400 entrega_semana3.pem" para garantir que apenas eu possa lê-la, aumentando a segurança da chave privada utilizada para autenticação SSH. Após isso utilizei o comando "ssh -i "entrega_semana3.pem" ec2-user@ec2-35-175-214-206.compute-1.amazonaws.com" para realizar a conexão SSH, que foi bem sucedida.



## Conclusão
Este relatório demonstrou o processo de criação de uma instância EC2 na AWS e o acesso a ela por meio do SSH. As etapas foram documentadas com capturas de tela e os resultados foram armazenados em um repositório no GitHub.
