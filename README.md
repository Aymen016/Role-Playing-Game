# 🏰 Advanced Text-Based RPG System

Welcome to the Advanced Text-Based RPG System! ⚔️ This Python-based RPG brings thrilling battles, strategic inventory management, and immersive gameplay right to your terminal. 🎮

## 🚀 Features

✅ **Entity, Player & Monster Classes**: Define characters with health, level, and experience. Players and monsters can attack, take damage, and level up.
✅ **🎲 Randomized Damage**: Attacks deal random damage, making every battle unique and engaging!
✅ **👜 Inventory System**: Collect and use powerful items like potions and weapons.
✅ **📈 Experience & Leveling**: Gain XP by defeating monsters and level up for stronger stats!
✅ **🧪 Item Usage**: Use potions to heal and equip weapons for battle enhancements.
✅ **🕹️ Example Gameplay**: Engage in epic battles and watch your player grow stronger.

## 🔧 Installation

Make sure you have Python installed (version 3.x recommended). Then, simply run:
```bash
python rpg_game.py
```

## 🎮 How It Works

1️⃣ **Create Characters**: Players and monsters are instantiated with health, attack power, and experience.  
2️⃣ **Battle System**: Players and monsters attack each other with random damage values.  
3️⃣ **Inventory Management**: Players can collect and use items like potions and weapons.  
4️⃣ **Level Progression**: Gain experience, level up, and boost your stats!  
5️⃣ **Dynamic Combat**: Every attack and item usage impacts the battle's outcome.  

# 📝 Example Code

### Example Usage
```bash
player = Player("Hero", 100)
monster = Monster("Goblin", 50, 50)
potion = Potion("Healing Potion", 20)
weapon = Weapon("Sword", 15)

player.attack(monster)
monster.attack(player)

player.add_item(potion)
player.use_item(potion, player)

player.add_item(weapon)
player.use_item(weapon, monster)

print(f"{player.name}'s level: {player.level}")
```

### 🏆 Sample Output
```bash
Hero attacks Goblin!
Goblin takes 10 damage!
Goblin attacks Hero!
Hero takes 5 damage!
Hero obtained Healing Potion!
Hero uses Healing Potion!
Hero obtained Sword!
Hero equips Sword!
Hero's level: 1
```

# 💡 Contributing

Want to improve the game? Feel free to fork the repo and submit pull requests! 🤝

# 📜 License

This project is open-source and free to use. 🎉

# 📩 Contact

For any questions or suggestions, reach out to me via GitHub! 🚀

