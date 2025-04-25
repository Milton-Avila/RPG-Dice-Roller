# 🎲 Dice Roller Parser
(Documentação em português abaixo)

A lightweight and extensible Python library to parse and roll RPG-style dice (e.g., `2d6+1d4-2`). Perfect for games, Discord bots, tabletop systems, and more!

![MIT License](https://img.shields.io/badge/license-MIT-green)
![Made with 💻](https://img.shields.io/badge/made%20with-python-blue)
![PyPI](https://img.shields.io/pypi/v/RPG-Dice-Roller)

## ✨ Features

- Parses dice expressions like `2d6+1d4-2`
- Supports multiple dice, bonuses, and penalties
- Provides min and max value ranges
- Automatically validates input

## 🧙‍♂️ Usage examples

```python
python
CopiarEditar
from RPG_Dice_Roller import roll_dice, get_dice_range, get_dice_rolled

print(roll_dice("2d6+1d4-2"))      # Example: 10
print(get_dice_range("2d6+1d4-2"))  # Example: {'min': 3, 'max': 17}
print(get_dice_rolled())            # Total number of rolls performed

```

## 📦 Installation

Install from PyPI:

```bash
bash
CopiarEditar
pip install RPG-Dice-Roller

```

Or clone manually:

```bash
bash
CopiarEditar
git clone https://github.com/Milton-Avila/Rpg-Dice-Roller.git
cd dice-roller
pip install .

```

## 🛠 Project Structure

```bash
bash
CopiarEditar
RPG_Dice_Roller/
├── __init__.py
├── src/
│   ├── models/
│   │   ├── dice_input.py
│   │   ├── dice_controller.py
│   │   └── errors.py
│   └── functions/
│       ├── dice_roll.py
│       └── statistics.py

```

## 📜 License

MIT — feel free to use it, modify it, distribute it... and if you make some money with it, invite me to roll some dice 😄

## 💌 Contributing

Feel free to open issues, submit PRs, or suggest improvements. Feedback, bug reports, and new ideas are always welcome!

## 🎲 May the dice be ever in your favor.

# 🎲 Dice Roller Parser

Uma biblioteca Python leve e extensível para interpretar e rolar dados no estilo RPG (ex: `2d6+1d4-2`). Ideal para jogos, bots de Discord, sistemas de mesa e mais.

![MIT License](https://img.shields.io/badge/license-MIT-green)
![Made with 💻](https://img.shields.io/badge/made%20with-python-blue)
![PyPI](https://img.shields.io/pypi/v/RPG-Dice-Roller)

## ✨ Funcionalidades

- Interpreta expressões de dados como `2d6+1d4-2`
- Suporta múltiplos dados e bônus/penalidades
- Fornece range de valores mínimos e máximos
- Valida entradas automaticamente

## 🧙‍♂️ Exemplos de uso

```python
from RPG_Dice_Roller import roll_dice, get_dice_range, get_dice_rolled

print(roll_dice("2d6+1d4-2"))      # Ex: 10
print(get_dice_range("2d6+1d4-2"))  # Ex: {'min': 3, 'max': 17}
print(get_dice_rolled())          # Total de rolagens realizadas
```

## 📦 Instalação
Utilize o comando pypi:

```bash
pip install RPG-Dice-Roller
```

Ou clone manualmente:

```bash
git clone https://github.com/Milton-Avila/Rpg-Dice-Roller.git
cd dice-roller
pip install .
```

## 🛠 Estrutura do projeto

```bash
RPG_Dice_Roller/
├── __init__.py
├── src/
│   ├── models/
│   │   ├── dice_input.py
│   │   ├── dice_controller.py
│   │   └── errors.py
│   └── functions/
│       ├── dice_roll.py
│       └── statistics.py
```

## 📜 Licença

MIT — faça bom uso, modifique, distribua, e se for monetizar... me chama pra rolar uns dados 😄

## 💌 Contribuindo

Sinta-se livre pra abrir issues, enviar PRs ou melhorar qualquer parte do projeto. Feedbacks, bugs e novas ideias são sempre bem-vindos!

## 🎲 Que os dados estejam a seu favor.