
# Projeto de Redes e Serviços Internet
## O que foi feito?
Foi criada no Packet Tracer uma rede de acordo com a imagem. 

### Infraestruturas
O Laboratório Final é composto pelas infraestruturas seguintes conforme indicado na rede descrita na imagem.
- gigapix — Ponto de Troca de Tráfego (Internet Exchange Point) português. Este assegura a
qualidade das interligações das redes em Portugal e evita recorrer a recursos internacionais para
trânsito de pacotes IP com origem e destino em Portugal. Está representado na rede pelos nós
de Lisboa e do Porto (gigapix-lisboa e gigapix-porto) conectados com fibra óptica gigabit e que
também asseguram a interligação internacional.
- isp-x — ISP (Internet Service Provider) com três nós em Lisboa, Porto e Braga contratado pela
empresa abc para disponibilizar acesso à rede.
- isp-y — ISP (Internet Service Provider) apenas com um nó em Lisboa disponibiliza serviços de
acesso para clientes residenciais. Aqui representados por casa/pc1-casa.
- rossiya/isp-z — Ponto de acesso nacional russo e ISP (Internet Service Provider) através dos nós
rossiya e isp-z disponibiliza acesso para clientes locais representados por dom-x/kompyuter-x.
- abc — Empresa abc que utiliza os serviços de rede disponibilizados pelo ISP isp-x tem escritórios
em Braga e Lisboa.
- google — Serviços Google de email, DNS e de pesquisa disponíveis.
- INTERNET — Representa a Internet na topologia de modo a interligar as várias infraestruturas e
serviços em frame-relay.

<img width="1682" height="595" alt="image" src="https://github.com/user-attachments/assets/cad77a32-7722-48e1-97ee-3eec7de4d4b2" />

### Tarefas
- Adicionar todos os equipamentos.
- Ligar todos os equipamentos entre si.
- Configurar os endereços de forma eficiente e seguindo as indicações dadas, apresentando os
respetivos mapas de endereços.
- Configurar os endereços IP fixos em todos os servidores.
- Configurar as rotas OSPF entre os routers GigaPix.
- Configurar os circuitos Frame-Relay na Internet Cloud.
- Configurar as VLANs nos vários switches.
- Configurar os servidores de DNS para funcionarem de forma hierárquica com duas camadas
(sendo a de topo constituída pelo servidor DNS 8.8.8.8).
- Configurar os servidores Web para HTTP, cada um dos servidores com uma página index.html
distinta.
- Configurar o servidor de Web www.abc.pt para responder também a HTTPS.
- Definir Gateway of Last Resort no router gigapix-porto.
- Configurar os servidores de email.
- Configurar contas de correio em pelo menos um pc de cada rede.
- Nos locais com um Access Point e um equipamento portátil com acesso Wi-Fi, configurar uma
senha WEP para permitir acesso através da rede Wi-Fi.
- Configurar a ligação por Cabo de Consola para gerir o router isp-x-lisboa.
- Configurar as passwords de login e de acesso aos routers no gigapix-porto e gigapix-lisboa como
“gpix” e “xipg”.
- Configurar a partilha de rotas entre RIP e OSPF.
- Extra: Implementar listas de acesso (ACL) no isp-x que impeçam o acesso ao servidor www.kompaniya.ru
a partir dos computadores da empresa abc.
- Escrever um pequeno relatório no formato PDF, a submeter com o ficheiro do Packet Tracer, incluindo
as configurações efetuadas via CLI em cada router e nos switches, bem como as tabelas
de endereços.

## Quem participou?
Este projeto foi realizado por mim no 1º ano da Lincenciatura de Informática Web, Móvel e na Nuvem.

## Que tecnologias foram utilizadas?
- Packet Tracer

## Como inicializar o projeto?
Com o auxilio do Packet Tracer, abrir o documento "Trabalho.ptk"

