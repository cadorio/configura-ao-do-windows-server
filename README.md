# configura-ao-do-windows-server
Introdução
No correr deste manual vais constar como podemos instalar passo a passo e configurar um servidor de ficheiros no Windows server 2012





Primeiro Passo:
Instalar o windws server para começar o processo de criaçao de um gestor de ficheiros
![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/8990cdf1-7392-48dc-b109-6e71df0451c4)
 

Segundo passo:
Depois de o Windows server estar instalado temos de configurar o grupo de trabalho do Windows server 
 ![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/b317a243-4d96-4580-8e58-574e5b961d5d)







Terceiro passo:
Vamos começar passo a passo a configurar o gestor de ficheiros e por isso vamos selecionar a opção com o numero 2 que diz Adicionar funções e recursos .
 ![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/a6550b0a-05c1-40c8-94d1-5a98fba836b9)


Quarto passo:
Depois de efetuar o terceiro passo vamos selecionar a opção instalação baseada em função ou recursos.
 ![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/15dde2f9-26d2-4ba8-915a-ccc611609361)










Quinto passo:
Vamos selecionar o servidor de destino onde vamos criar o gestor de ficheiros 
 ![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/49bf68eb-d43d-4905-ba1b-851141a5e9e5)


Sexto passo:
Vamos a funções de servidor e selecionamos os seguintes serviços de Arquivo depois selecionamos também Serviços de Arquivo e ISCSI e depois selecionamos server for nfs
  
![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/f2d24e6b-3faa-4688-88f6-b9d1079146a5)








Sétimo passo :
Vamos confirmar a instalação dos recursos que selecionamos nas etapas anteriores
 ![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/9048f8f3-6e98-49f5-8879-c2423bea1a22)
 


Oitavo passo:
Esperamos ate a instalação dos recursos ficar finalizada


 ![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/bf925b81-255e-4625-a688-41b1cf77df56)








Nono passo:
Vamos criar uma pasta 
 ![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/8b7ed805-102a-4b17-bb5e-2ebc548eedb9)


Decimo passo:
Vamos configurar a partilha da pasta para podemos criar o modo de partilha vamos a propriedades da pasta e selecionamos compartilhamento e depois clicamos na opção compartilhamento 

 ![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/00cfa147-d215-43ec-b252-a32b0e6e6124)








Decimo primeiro passo:
Vamos selecionar os utilizadores e as suas permissões que são destinadas a cada utilizador 

 ![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/579f6bac-d7fb-40c7-9672-dfc6032f6d49)
 

Decimo segundo passo:
Vamos configurar as opções de segurança da pasta relativas aos utilizadores eas suas permissões destinadas a cada utilizador  
 
![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/d291f30e-98a5-401f-b02e-9d9bb2cea6ab)









Decimo terceiro passo:
Temos de inserir o grupo de trabalho igual ao do servidor no Windows local de forma ser possível através do ip localizar o servidor com o ip do servidor no explorador de ficheiros 
 
 
![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/09936972-0cef-49a7-b29a-1925bb7cec01)

![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/6f2df142-dfb0-4f29-b1fb-c1a696be2278)










Decimo quarto passo:
Criar uma quota no gerenciador de recursos 
 ![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/f5e7a0f1-bec7-429d-afd3-d4d313f850b6)
![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/001a778d-c443-4814-9caf-87ad408df00f)

 


Decimo quinto passo:
Criar uma filtragem de ficheiros e suas prioridades da filtragem criada e suas definições bloqueadas 
 ![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/4301994b-4b14-4562-b1c8-9edc22ac2d2d)
![image](https://github.com/cadorio/configura-ao-do-windows-server/assets/35230903/a4648870-7cee-4659-8fd5-0c06c45fc565)

 
