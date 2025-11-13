# E-commerce-Cosmetic-Prediction

E-commerce Cosmetic Product Analysis
📋 Project Overview
This project analyzes an e-commerce cosmetic products dataset containing over 12,000 products from multiple platforms. The analysis includes data preprocessing, exploratory data analysis, and visualization to understand product distributions, pricing patterns, and customer ratings.

🎯 Objectives
Perform comprehensive data cleaning and preprocessing

Handle missing values in key columns like price, ingredients, ratings, etc.

Analyze product distribution across different websites and categories

Explore pricing patterns and customer rating distributions

Visualize insights to understand the cosmetic product landscape

📊 Dataset Information
The dataset contains 12,615 cosmetic products with the following features:

Key Columns:
product_name: Name of the cosmetic product

website: E-commerce platform (Flipkart, Amazon, Ulta, Sephora)

country: Country of sale (India, USA)

category: Main product category (body, face, eyes, etc.)

subcategory: Specific product type (perfume, foundation, blush, etc.)

price: Product price

brand: Manufacturer brand

ingredients: Product composition

form: Physical form (aerosol, cream, powder, etc.)

type: Skin/hair type suitability

color: Product color/shade

size: Product size/quantity

rating: Customer rating (1-5)

noofratings: Number of customer ratings

🛠️ Technologies Used
Python 3

Pandas - Data manipulation and analysis

NumPy - Numerical computations

Scikit-learn - Data preprocessing

Matplotlib - Data visualization

Seaborn - Statistical data visualization

📈 Data Preprocessing Steps
1. Data Loading & Initial Exploration
Loaded dataset with Latin-1 encoding

Examined data structure and basic statistics

Identified missing values across columns

2. Missing Value Treatment
Price: Filled with median value

Ingredients: Replaced NaN with "Not Specified"

Type: Filled with mode (most frequent value)

Color: Filled with mode value

Size: Filled with mode value

Rating: Converted to numeric, clipped to 1-5 range, filled with mean

noofratings: Converted to numeric, filled with median

3. Data Type Conversion
Ensured proper data types for numerical and categorical columns

Handled special characters and formatting issues

🔍 Key Insights
Website Distribution
Products distributed across multiple e-commerce platforms

Flipkart and Amazon being major contributors in Indian market

Ulta and Sephora representing international brands

Product Categories
Body care: Perfumes, lotions, etc.

Face products: Foundation, concealer, blush

Eye products: Makeup and care products

Multiple subcategories within each main category

Pricing Patterns
Wide price range from budget to premium products

Different pricing strategies across platforms and countries

📊 Visualizations
Bar charts showing website distribution

Category-wise product analysis

Price distribution across different segments

Rating patterns and customer feedback trends

🚀 Getting Started
Prerequisites & Installation
bash
# Clone the repository
git clone https://github.com/rehanmalik-1590/E-commerce-Cosmetic-Prediction.git

# Navigate to project directory
cd E-commerce-Cosmetic-Prediction

# Create virtual environment (optional but recommended)
python -m venv cosmetic_env
source cosmetic_env/bin/activate  # On Windows: cosmetic_env\Scripts\activate

# Install required dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Launch Jupyter notebook
jupyter notebook E_commerce_Cosmatic.ipynb

# Alternative: Run as Python script (if converted)
python e_commerce_analysis.py

# To deactivate virtual environment
deactivate
Additional Useful Commands:
bash
# Install specific versions (if needed)
pip install pandas==1.5.3 numpy==1.24.3 matplotlib==3.7.1 seaborn==0.12.2 scikit-learn==1.2.2

# Generate requirements.txt
pip freeze > requirements.txt

# Install from requirements.txt
pip install -r requirements.txt

# Check dataset info
head -5 e_commerce_cosmetic.csv

Add sentiment analysis on product reviews

Develop recommendation system

Create interactive dashboards

Expand analysis to include seasonal trends

🤝 Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues for suggestions.

📄 License
This project is licensed under the MIT License.

👨‍💻 Author
Rehan Malik

GitHub: rehanmalik-1590

Project Repository: E-commerce-Cosmetic-Prediction
