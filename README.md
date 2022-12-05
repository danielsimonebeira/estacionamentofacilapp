# estacionamentofacilapp

Aplicativo mobile para estacionamento

## Pré-requisito para usar este projeto

Para usar o projeto é necessário:
* [Dart versão: 2.18.2](https://dart.dev/get-dart)
* [Flutter versão: 3.0.2](https://docs.flutter.dev/get-started/install/linux)
* [Android Studio versão: API 32](https://developer.android.com/studio)

## Checklist do que foi desenvolvido e o que falta a desenvolver

* [OK] - Tela de Login
* [OK] - Tela de criar nova conta
* [OK] - Tela inicial do app
* [OK] - Menu lateral tela inicial
* [  ] - Tela  editar de usuario
* [OK] - Tela listagem de veiculos
* [OK] - Tela  cadastro de veiculos
* [  ] - Tela  editar de veiculo
* [  ] - Modal de Reservar vaga
* [  ] - Modal de vaga liberada
* [  ] - Modal de mensagem 
* [  ] - Criar comunicação com a API de estacionamento

## Fluxo do aplicativo


### Fluxo tela de login:
![login](https://user-images.githubusercontent.com/44556635/205749158-591f98b4-2a07-4d79-8e55-e15ff4ab601c.png)

### Home do app:
![home](https://user-images.githubusercontent.com/44556635/205751218-36752153-534b-4de4-9700-2ad28404a6f4.png)

### Menu lateral:

![menu_lateral](https://user-images.githubusercontent.com/44556635/205751282-1a3d0728-6ed2-4faa-9116-64578c636014.png)

### Fluxo para consultar placa e reservar a vaga:

Neste exemplo foi selecionada uma vaga disponível, informado uma placa existente e efetuada a reserva com sucesso, conforme imagens exibidas na sequência:
![reserva_vaga](https://user-images.githubusercontent.com/44556635/205751348-bfe77381-50d0-41a1-9e03-75794c8fb8b9.png)
![reserva_vaga_2](https://user-images.githubusercontent.com/44556635/205751372-330abc2d-917a-461c-b92a-8d239bdbffc0.png)

### Fluxo para consultar placa inexistente e cadastrar o veículo:

Neste exemplo foi selecionada uma vaga disponível, informado uma placa inexistente e efetuado o cadastro de um veículo com sucesso, conforme imagens exibidas na sequência:

![reserva_vaga_veiculo_nao_encontrado png](https://user-images.githubusercontent.com/44556635/205751516-ac2c428f-ba33-4e21-af23-ec9cf15f7792.png)


#### Mensagem exibida para vaga em manutenção: 

Ao clicar em uma vaga em manutenção a mensagem abaixo será exibida.
![mensagem_vaga_manutencao](https://user-images.githubusercontent.com/44556635/205751610-46918146-dd56-4bda-96b4-7e4e6d77d9ab.png)


### Mensagem exibida para vaga ocupada:

Ao clicar em uma vaga ocupada a mensagem abaixo será exibida.

![mensagem_vaga_ocupada](https://user-images.githubusercontent.com/44556635/205751648-6a15f8c3-db0e-40d9-98ea-57628645d305.png)


### Mensagem exibida para liberação de vaga ocupada: 

Ao clicar em uma vaga ocupada e confirmar a liberação será exibida a mensagem abaixo.

![mensagem_vaga_liberada](https://user-images.githubusercontent.com/44556635/205751692-e4a89b9d-af63-45d3-8ace-d3e3d6de7413.png)


### Lista de veículos cadastrados:

Ao acessar através do menu lateral a opção ‘Cadastrar veículos’ será exibida uma lista contendo os veículos cadastrados no app. Sendo possível realizar a consulta de um veículo, edição, exclusão lógica e cadastrar um novo veículo.

![lista_veiculos](https://user-images.githubusercontent.com/44556635/205751720-414b33d5-095c-4e09-82ea-9ef4d177f8e3.png)


### Telas de edição e cadastro de veículo:

Poderá ser cadastrado um novo veículo através da opção ‘+’ na tela de cadastro de veículos Menu Lateral / Cadastrar veículos.

![editar_veiculo](https://user-images.githubusercontent.com/44556635/205751950-d0036346-455e-411f-a7c1-2c5295e59909.png)


### Cadastro de usuário:

Através do botão <Criar Conta> da tela inicial do aplicativo é possível realizar o cadastro de um usuário. Ao clicar no botão será exibida a tela abaixo:

![cadastrar_usuario](https://user-images.githubusercontent.com/44556635/205751764-485f2825-c5d4-4406-98f1-e0d55c051920.png)

  
### Editar cadastro de usuário:

Ao acessar através do menu lateral a opção ‘Editar perfil de usuário’’ será exibida a tela abaixo, onde o usuário poderá alterar seus dados de acesso.

![editar_usuario](https://user-images.githubusercontent.com/44556635/205751788-f0e5ad1e-7b34-48a8-af6b-414d4865fb9f.png)

