# 🔍 Power BI Pokédex Dashboard  
*A beginner-friendly data storytelling project built in Power BI using the world of Pokémon.*

---

## 🎯 Project Overview

What happens when you're handed a dataset from a world you've never explored? You learn fast.

This project began as a way to improve my Power BI skills by working with a structured but unfamiliar dataset — the Pokédex. As someone new to Pokémon, this was a rewarding opportunity to practice asking the right questions, interpreting unknown data, and designing a dashboard that communicates clearly to others who are just starting out.

---

## 👥 Who This Is For

- 🧑‍🎓 **Beginners learning Power BI or data visualisation**  
- 🧪 **Students or analysts working with new datasets**  
- 🎮 **Pokémon fans exploring patterns behind their favourite characters**  
- 💼 **Consultants handling unfamiliar client data sets or business domains**

---

## ❓ Key Questions Explored

- How can users **search and select Pokémon visually** to learn about them interactively?
- What patterns emerge across **core stats**: HP, Attack, Defence, Special Attack, Special Defence, Speed?
- How do Pokémon differ in **Height, Weight, Total Base Points**, and **Generation**?
- What insights can we gain from **Pokédex Number**, **Typing**, and **descriptive attributes**?
- How can a dashboard guide beginners to **explore data effectively**, even without prior domain knowledge?

---

## 📁 Dataset Overview

| Column               | Description                                  |
|----------------------|----------------------------------------------|
| `Pokedex Number`     | National Pokédex ID                          |
| `PokemonName`        | Pokémon's name                               |
| `Height (m)`         | Height in metres                             |
| `Weight (kg)`        | Weight in kilograms                          |
| `Number of Abilities`| Count of known abilities                     |
| `Total Base Stats`   | Sum of all individual stats                  |
| `HP` to `Speed`      | Base stat breakdown                          |
| `Catch Rate`         | Likelihood of capture                        |
| `Base Friendship`    | Default friendship value                     |
| `Base Experience`    | EXP awarded when defeated                    |
| `Pokémon Image`      | Scraped image for display                    |

📦 *Note: Images were obtained via web scraping for non-commercial, educational purposes only.*

---

## 🧹 Data Cleaning & Processing

- Removed duplicate entries
- Standardised column formats and names
- Handled null values in stat columns
- Scaled numerical fields for consistency
- Linked images using Pokémon names for dynamic visualisation

---

## 🧩 Interactive Dashboard Features

This dashboard is designed to be **playful, intuitive, and beginner-friendly**, with a retro-inspired Pokédex UI:

### 🎮 Visual Slicers & Filters
- **Image-based slicer** to select Pokémon by icon  
- Additional filters for:
  - Generation (e.g., Gen 1–9)
  - Type (Water, Rock, Fire, etc.)
  - Base Stat Range (via slider)
  - Speed/Attack filters

### 🖼️ Pokémon Profile Display
- Dynamic image updates based on slicer selection
- Helps new users connect names with visuals

### 📈 Radar Chart: Stat Comparison
- Spider chart showing:
  - HP
  - Attack
  - Defence
  - Special Attack
  - Special Defence
  - Speed  
- Enables side-by-side Pokémon stat comparisons

### 📦 Attribute Summary Cards
- Pokédex Number  
- Generation  
- Height & Weight  
- Total Base Stats  
- Typing (e.g., Water/Rock)

### 📘 Text Description Panel
- Example: *“Corsola is a Water/Rock Pokémon introduced in Generation 2. It is known as the Coral Pokémon.”*  
- Adds narrative and learning context for each Pokémon

---

## 🖼️ Example: Corsola (No. 222)
<img width="3829" height="1766" alt="poke" src="https://github.com/user-attachments/assets/baedef7e-e0e1-412f-bf6f-00f857f22227" />

- **Generation**: 2  
- **Type**: Water / Rock  
- **Height**: 0.60 m  
- **Weight**: 5.00 kg  
- **Base Stat Total**: 410  
- Displayed with image, radar chart, and full stat breakdown

---

## 📊 Dashboard Highlights

- **Stat Comparison View**  
- **Top Stat Leaderboard by Type or Attribute**  
- **Visual Filtering for Exploration**  
- **Card-based Pokémon Profiles**

📌 *[Optional: Add screenshots or a link to Power BI Service if published]*

---

## 🛠 Tools & Skills Used

| Tool / Method         | Purpose                                     |
|-----------------------|---------------------------------------------|
| Power BI              | Dashboard creation, DAX, interactivity      |
| Excel                 | Data cleaning and shaping                   |
| Web Scraping          | Image collection for Pokémon visuals        |
| Design Thinking       | User experience and accessibility           |
| Data Storytelling     | Turning raw data into insight and clarity   |

---

## 💡 Key Takeaways

- You don’t need subject expertise — just **curiosity** and a willingness to explore.
- Understanding your **audience** is more important than knowing every datapoint.
- Power BI is a powerful tool for bringing new datasets to life — even when you're a beginner.

---

## 📘 How to Use This Project

1. Clone or download this repository  
2. Open the `.pbix` file in Power BI Desktop  
3. Explore filters, select different Pokémon, and uncover insights  
4. Add your own datasets or create new visuals to extend the project!

---

## 🤝 Contributions & Feedback

Have an idea? Want to expand the dashboard?  
Fork the repo, open a pull request, or raise an issue.

---

**Made with data and curiosity by Anansha Kc**  
*Learning Power BI — one Pokémon at a time.*

🌐 [LinkedIn](https://linkedin.com/in/anansha-kc) | 💼 Project Advisory Group | ⚙️ Data6 Studio
