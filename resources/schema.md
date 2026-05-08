src/
├── engine/
│   ├── map.py        # room graph, navigation
│   ├── player.py     # stats, inventory, level
│   ├── combat.py     # decision-based encounter system
│   └── events.py     # random encounter generator
├── content/
│   ├── scenarios/    # JSON fajlovi — scenariji odvojeni od koda
│   ├── enemies.py    # regulator, journalist, board...
│   └── items.py      # policy docs, evidence, budget
├── ui/
│   └── terminal.py   # colorama / rich output
└── main.py