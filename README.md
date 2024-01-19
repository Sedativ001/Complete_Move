# Player Controller 3D - Unity

Este é um script em C# para Unity que controla o movimento 3D de um jogador, incluindo movimento, rotação, pulo e agachamento.

## Configuração

1. Certifique-se de ter a Unity instalada.
2. Abra o projeto Unity.
3. Adicione um objeto de jogador à sua cena.
4. Adicione um componente Rigidbody ao objeto do jogador.
5. Configure as entradas no Unity para "Horizontal", "Vertical", "Rotation", "Jump" e "Crouch".
6. Crie uma camada chamada "Ground" e aplique a essa camada ao objeto do solo na sua cena.

## Parâmetros

- `speed`: Velocidade de movimento do jogador.
- `rotationSpeed`: Velocidade de rotação do jogador.
- `jumpForce`: Força do pulo do jogador.
- `groundLayer`: Camada do solo para detecção de colisão.

## Controles

- Movimento: Teclas de seta ou teclas W, A, S, D.
- Rotação: Teclas Q e E.
- Pulo: Barra de espaço.
- Agachamento: Tecla de controle.

## Notas

- Certifique-se de ajustar os valores dos parâmetros conforme necessário para o seu projeto.
- Este é um exemplo básico e pode ser expandido com animações, detecção de colisões avançada, etc.
