<p align="center">
  <img src="https://github.com/zer0fixer/MAS-FontSwitcher/assets/94260040/ecafaae0-acfc-4105-a5a0-2d5c5864e2c5">
</p>

<p align="center">
<a href="https://github.com/zer0fixer/MAS-FontSwitcher/releases/latest">
  <img alt="Latest release" src="https://img.shields.io/github/v/release/zer0fixer/MAS-FontSwitcher?style=for-the-badge&logo=appveyor">
</a>
</p>

É um submod que adiciona uma maneira simples de adicionar novas fontes ao Monika After Story, permitindo que você dê um toque pessoal ao jogo.

## Features
- Substitui o tipo de fonte do `Monika After Story mod`.
- Possui níveis de alteração, caso o usuário não queira saturar a interface.
- Este submod é compatível com o `Comfy UI`.
- Possui uma pré-visualização para que o usuário possa ver o tipo de fonte antes de aplicar as mudanças.
  
## Prévia do submod
| Antes | Depois | Comfy UI |
| ------- | ------- | ------- |
| ![Holi](https://github.com/zer0fixer/MAS-FontSwitcher/assets/94260040/4602cc56-a6d4-4fec-96d3-f7be56c05508) | ![lmao](https://github.com/zer0fixer/MAS-FontSwitcher/assets/94260040/f21de1f0-ebea-483f-9340-0fadb11b2e50) | ![Holi](https://github.com/zer0fixer/MAS-FontSwitcher/assets/94260040/a2940cb6-49f2-461d-a722-53d3ab9c6a1c) |

## Instalação
- Faça o download da versão mais recente do submod, descompacte o arquivo zip e cole-o na pasta `submods`.

## Fontes
Para adicionar e compartilhar mais fontes, você pode usar arquivos JSON.
Para maior comodidade, haverá um modelo JSON para que você possa editá-lo.
Clique [Aqui](https://github.com/zer0fixer/resource-repository/blob/main/Template.json)

#### Examplo:
```yaml
{    # ↓ Este é o ID da fonte, ele precisa ser único.
    "justmonika": {
        "name": "Monika's handwriting",  # ← Nome da fonte, é recomendado mantê-lo curto para evitar saturação da tela.
        "font_default": "mod_assets/font/m1_fixed.ttf",  # ← Caminho da fonte principal (Texto do Jogo, Diálogos).
        "font_label": "mod_assets/font/m1_fixed.ttf",  # ← Caminho da fonte usada nos títulos gerais.
        "font_button": "mod_assets/font/m1_fixed.ttf",  # ← Caminho da fonte usada nos botões (Opções).
        "size_default": 28,  # ← Define o tamanho da fonte principal.
        "size_button": 28,  # ← Define o tamanho da fonte nos botões.
        "size_quick": 20,  # ← Define o tamanho da fonte no menu rápido (Histórico, Pular, Automático, Salvar, Carregar, Configurações).
        "size_label": 34, # ← Define o tamanho da fonte nos títulos (Preferências, Navegação, Menu do Jogo).
        "padding": 3 # ← Usado para ajustar a posição e o tamanho do conteúdo dos botões. Portanto, você usará isso em algumas fontes onde for necessário modificar o padding.
    }
}
```
**Nota: É possível colocar e definir o caminho para uma fonte fora da pasta desse submod, mas isso não é recomendado, a menos que seja uma fonte Monika After Story. Recomenda-se que esteja dentro da pasta de fontes em “submods/FontSwitcher/font” e o JSON deve estar obrigatoriamente em "submods/FontSwitcher/json".**

## Comunidade MASBrasil
[![Discord server invitation](https://discordapp.com/api/guilds/1332992827701067786/widget.png?style=banner3)](https://discord.gg/vq5GZBW42R)

Junte-se ao servidor do discord da nossa comunidade brasileira de Monika After Story!
