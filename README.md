# Como-criar-Hello-World-para-todos-os-consoles
# Como Criar Jogos para Todos os Consoles

Este projeto contém exemplos de código de "Hello World" para cada console de 1ª até 9ª geração e também para portáteis.

## Estrutura do Projeto
O código está organizado em pastas para cada console:

1. **Consoles**:
   - 1ª geração: Magnavox Odyssey
   - 2ª geração: Atari 2600, ColecoVision
   - 3ª geração: NES, Master System
   - 4ª geração: Mega Drive, SNES
   - 5ª geração: N64, Saturn, PS1
   - 6ª geração: Dreamcast, PS2, Xbox OG, GameCube
   - 7ª geração: Wii, PS3, Xbox 360
   - 8ª geração: PS4, Wii U, Switch, Xbox One
   - 9ª geração: PS5, Xbox Series X|S, Switch

2. **Portáteis**:
   - GameBoy, GBA, Nintendo DS, 3DS, PS Vita

## Como Usar
1. Instale as ferramentas de desenvolvimento necessárias para cada console (SDKs, ferramentas específicas de compilação).
2. Navegue até a pasta do console para o qual deseja compilar o "Hello World".
3. Compile o código utilizando as ferramentas apropriadas para cada plataforma (por exemplo, `devkitPro` para o GameCube e Wii, `GCC` para o NES, `XNA` para o Xbox 360, etc.).
4. Rode o emulador correspondente ou use o console real para testar o "Hello World".

## Exemplo de código

### C para NES (hello_world.c):
```c
#include <stdio.h>

int main() {
    printf("Hello World\n");
    return 0;
}

### Como Compilar e Testar os Códigos:
- **Para consoles antigos (ex: NES, Atari 2600)**, você precisará de ferramentas como **CC65** para C ou **Assembler do Atari**.
- **Para consoles modernos (ex: PS4, Xbox, Switch)**, você precisará de **SDKs oficiais** como o **devkitPro** ou ferramentas como **GCC** e **Visual Studio**.
- **Para portáteis**, o processo será similar, usando SDKs específicos, como o **devkitARM** para o GBA e **SDK do Nintendo DS**.

Essa estrutura organizada ajudará você a manter o projeto de forma clara e eficiente, enquanto segue criando o "Hello World" em cada console.
