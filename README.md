# 🍽️ Restaurant Recommendation System

![Python Version](https://img.shields.io/badge/Python-3.7%2B-blue)
![Stars](https://img.shields.io/github/stars/your-username/restaurant-recommender?style=social)

*An intelligent and intuitive restaurant recommendation engine powered by content-based filtering. This project leverages structured data to suggest dining options tailored to user tastes, preferences, and budget. Whether you're in the mood for sushi, steak, or street food, this system ensures your next meal is just the right choice—backed by clean data, thoughtful algorithms, and flexible customization.*

---

## ✨ Features

* **Content-Based Filtering**: Matches restaurants to user preferences (cuisine, price, rating).
* **Customizable Weights**: Tweak importance of price vs. rating vs. cuisine.
* **Modular Design**: Easily swap similarity metrics or extend to collaborative filtering.
* **Quick Start**: Ready-to-run Jupyter Notebook and standalone script.

---

## 🚀 Quick Start

<details>
<summary>Clone & Setup</summary>

```bash
# Clone the repo
git clone https://github.com/your-username/restaurant-recommender.git
cd restaurant-recommender

# Create and activate env
python3 -m venv venv
source venv/bin/activate  # Windows: venv\\Scripts\\activate

# Install dependencies
pip install -r requirements.txt
```

</details>

<details>
<summary>Run in Jupyter</summary>

1. Open `Task2.ipynb` in Jupyter or Colab.
2. Update dataset path if needed.
3. Execute all cells and enjoy recommendations.

</details>

<details>
<summary>Run as Script</summary>

```bash
python recommender.py --input Dataset.csv --top 5
```

</details>

---

## 📂 Project Structure

```plaintext
├── Dataset.csv            # Raw restaurant data (9,551 entries)
├── Task2.ipynb            # Interactive Jupyter walkthrough
└── README.md              # This file
```

---

## 🛠️ Tech Stack & Dependencies

* **Python 3.7+**
* **pandas**: Data manipulation
* **numpy**: Numerical computations
* **scikit-learn**: Similarity metrics & optional extensions

Install with:

```bash
pip install pandas numpy scikit-learn
```

---

## ⚙️ Core Functions

| Function                     | Description                                               |
| ---------------------------- | --------------------------------------------------------- |
| `load_data(file_path)`       | Load CSV and return headers, records, and numeric columns |
| `preprocess_data(data_dict)` | Clean missing values and convert types                    |
| `calculate_similarity(...)`  | Compute similarity score between two restaurant entries   |
| `get_recommendations(...)`   | Fetch top-N restaurants matching user preferences         |
| `display_restaurant(...)`    | Nicely print restaurant details                           |
| `main()`                     | Entry point: orchestrates workflow                        |

---

## 🎨 Example Output

![Sample Output](./assets/sample_recommendations.png)

```plaintext
🍽️ Top 5 Recommendations for You:

1️⃣ La Dolce Vita (Italian, Pizza) – ⭐ 4.7 | 💲 1.5
2️⃣ Sakura Garden (Japanese) – ⭐ 4.5 | 💲 2.0
3️⃣ El Taco Loco (Mexican) – ⭐ 4.6 | 💲 1.2
...
```

---

## 🤝 Contributing

Contributions are 💖! Fork the repo, create a feature branch, and submit a PR.

---

## 📜 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 👤 Author

**Samyuktha Sasikumar** ([your-username](https://github.com/your-username))
✉️ [samyukthasasikumar0061@gmail.com](samyukthasasikumar0061@gmail.com)

*Thank you for checking out the project!*

