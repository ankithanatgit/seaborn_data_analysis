This project performs exploratory data analysis (EDA) and visualizations using Python, Pandas, Seaborn, and Matplotlib.
It includes barplots using hue, lineplots with custom colors, and lineplots using Viridis colormap.

🚀 Features

Data cleaning & preprocessing

Barplot with hue for grouped comparison

Lineplots with custom colors

Lineplots with Viridis colormap

Category-wise and time-series analysis

Easy-to-follow visualization code

📁 Project Structure
project/
│── data/               # dataset files
│── analysis.ipynb      # Jupyter Notebook with EDA & charts
│── analysis.py         # Optional Python script version
└── README.md           # Documentation

🔧 Setup & Installation
Install required libraries:
pip install pandas seaborn matplotlib

📊 Example Visualizations
Barplot with Hue
sns.barplot(
    data=df,
    x="category",
    y="value",
    hue="segment",
    palette="viridis"
)
plt.show()

Lineplot with Custom Color
sns.lineplot(
    data=df,
    x="date",
    y="sales",
    color="purple"
)
plt.show()

Lineplot with Viridis Colormap
sns.lineplot(
    data=df,
    x="date",
    y="sales",
    hue="product",
    palette="viridis"
)
plt.show()

📝 Notes

You can replace the column names based on your dataset.

Modify palette values to switch between color themes.

Works with any CSV or Excel dataset.

🤝 Contributing

Pull requests and suggestions are welcome.
