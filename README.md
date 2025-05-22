# Roteador - TP LINK

## Objetivo
Através de um README, descreva como configurar o roteador escolhido de acordo com as instruções passadas pelo professor.

- Link do Emulador MR3420 (V5): https://emulator.tp-link.com/MR3420_V5-2-22/index.htm

## Descrição do Roteador

O roteador escolhido é o modelo *MR3420 (V5)*, versão do firmware: "*171012*"; ele é encontrado dentro do 5G/4G Routers dos emuladores *TP-LINK*:
- Residencial > Modems/ Gateways > Roteadores 5G/4G

## Antes da Configuração

É preciso ter os seguintes materiais em mãos:
- O roteador (*MR3420 (V5)*)
- Um cabo de rede
- Um cabo de internet
- Um computador

Passo a passo:
- Ligue o roteador na tomada;
- Conecte o cabo de rede no computador e na porta amarela (*LAN*) do roteador;
- Conecte o cabo de internet (da operadora) na porta azul (*WAN*) do roteador, ou só conecte via Wi-Fi padrão;

Obs: Se necessitar de usuário e senha, o padrão dos roteadores são:  `admin / admin`

Após esses passos, acesse o site da TP-LINK: http://tplinklogin.net

E siga os passos do Assistente no "Quick Setup", se for da sua preferência configurar rapidamente.

Você pode definir uma senha de administração mais forte dentro do site, acessando: System Tools > Password

## Configuração Avançada

Para um configuração avançada, é preciso conhecer alguns elementos da configuração do roteador...

### Elementos da Configuração

![image](https://github.com/user-attachments/assets/d8b8c27c-3ae5-4a58-ab01-29fe056674e3)

Há diversas opções de configuração, mas somente as mais importantes serão listadas:

### Status

O *Status* é o painel onde conseguimos identificar o provedor da *Internet*, as especificações do *Wireless* e do sistema *LAN*, além dos *Clientes* conectados ao roteador, mostrando diversos detalhes, como: MAC, IP, SubMáscara, Nome da Rede, etc...
O *Status* tem como objetivo nos dar as informações avançadas e essenciais do roteador e suas conexões.

#### Modo de Operação

O *Modo de Operação* define como o seu roteador vai se comportar durante sua ação de provedor.
Nesse modelo, temos 4 opções, conforme a imagem:

![image](https://github.com/user-attachments/assets/eb467ac0-19d1-4873-a444-fdb47cc8f695)

### Rede

Na *Rede* temos 5 módulos:

![image](https://github.com/user-attachments/assets/017a4bea-4728-45aa-9420-93528b3d2835)

Mas os principais, são: ***Internet*** e ***Configurações LAN***

No módulo *Internet*, é possível identificar o *ISP* (Provedor de Serviço de Internet), que é o responsável por fornecer a conexão à Internet do TP-LINK, e configurar um *APN* (Access Point), conectando ou desconectando manualmente do roteador, habilitando a caixinha da imagem:

![image](https://github.com/user-attachments/assets/010f01b9-f712-4525-8324-a35e46f0617b)

No módulo *Configurações de LAN*, nos é apresentado o *Servidor DHCP*, que automotiza as conexões e atribuições de endereços de *IP* (Protocolo de Internet) a dispositivos em uma rede. Nele podemos configurar manualmente os endereços de *IP* dos dispositivos de rede, tanto do *IPv4* (Protocolo de Internet - Versão 4), quanto do *IPv6* (Protocolo de Internet - Versão 6), conforme a imagem a seguir:


**IPv4:**

![image](https://github.com/user-attachments/assets/c54b74cc-43f3-4be8-8692-d95de73f4e4c)


**IPv6:**

![image](https://github.com/user-attachments/assets/e350721d-8887-4b79-a01f-ab0e00c746aa)

### Wireless (*Sem fio*)

No *Wireless* temos mais 5 módulos:

![image](https://github.com/user-attachments/assets/b56b9d62-a7ae-4344-b200-d07a1fefa11d)

Sendo as principais: _**Configurações Wireless**_, _**WPS**_ (_Wi-Fi Protected Setup_) e _**Configurações Avançadas**_

- Configurações Wireless: Dentro dele, podemos definir algumas configurações, como: Ocutar a _SSID_ (Nome da Rede Wireless), tipo de segurança, tipo de criptografia, o modo (versões de Wi-Fi - b/g/n), etc...

![image](https://github.com/user-attachments/assets/df3938aa-da43-44da-87eb-60de1f63d9d0)

- WPS: É como se fosse um atalho para a conexão do Wi-Fi Wireless, só que por meio de um botão

![image](https://github.com/user-attachments/assets/ff671843-c57d-47b9-9290-bd01201c5b2c)

- Configurações Avançadas: Nesse estágio, a configuração começa a ser muito mais complexa e longa, definindo muita coisa que é automática, manualmente.

![image](https://github.com/user-attachments/assets/cdc9f450-2b0c-44e9-9e8e-e596708f72f7)

### Controle de Largura de Banda

Nesta opção de configuração, podemos controlar a velocidade da largura de banda para _uploads_ e _downloads_, sendo manualmente ou impondo regras para a atualização das veloicdades automaticamente; precisando somente habilitar a caixinha _"Habilitar"_.

![image](https://github.com/user-attachments/assets/818fbad9-c4a9-4c3f-a491-7f628db1c614)
![image](https://github.com/user-attachments/assets/1786cc1e-c081-4e6e-90d5-b7540a800bde)

### Ferramentas do Sistema

Dentro das _Ferramentas do Sistema_, temos diversas opções, todas bem intuitivas sobre o que cada uma consegue configurar:

![image](https://github.com/user-attachments/assets/528f5a5d-f2f5-4cff-9ad6-d5aa1965a4b0)

- Configurações de Tempo: Configura o fuso-horário do seu sistema, podendo sincronizar os relógios com outros _IP's_, através do protocolo _NTP_. Além de configurar o fuso com o horário de verão também.
- Diagnóstico: Ele testa a funcionalidade e a velocidade da sua Internet com seu roteador. Ótimo para a configuração e detecção de problemas de instabilidade.
- Atualização de Firmware: É possível observar as informações do roteador e autualizar o firmware como preferir.
- Backup e Restauração: Consegue salvar as configurações do seu roteador ou restaurar configurações de um arquivo da nuvem de um roteador anterior.
- Reínicio: Reinicia seu roteador as configurações de fábrica.
- Administração: Gerencia e testa _IP's_ conectados no roteador, o próprio roteador e habilita o gerenciamento remoto por outras máquinas.
- Monitor de Tráfego: Habilita um monitor para ficar responsável pelo tráfego de _IP's_.
