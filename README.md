
# Zomato Data Analysis Project Using Python

This project involves an in-depth analysis of Zomato's restaurant data using Python, aimed at uncovering valuable insights into customer preferences, restaurant performance, and trends in online and offline food orders. The analysis is structured around key business questions and provides actionable insights for improving customer experience and business strategy.

---

## **Project Overview**
The primary goal of this project is to analyze Zomato's restaurant dataset and answer key questions related to customer preferences, restaurant ratings, online vs. offline order trends, and spending behavior. By leveraging Python's powerful data analysis libraries, we aim to derive meaningful insights to support data-driven decisions.

---

## **Questions Addressed**
This project is structured around the following questions:
1. **What type of restaurant do the majority of customers order from?**  
   - We identify the most popular restaurant categories based on customer preferences and votes.

2. **How many votes has each type of restaurant received from customers?**  
   - This analysis gives a detailed breakdown of customer engagement by restaurant type.

3. **What are the ratings that the majority of restaurants have received?**  
   - By analyzing the ratings, we uncover the common rating distribution across restaurants.

4. **What is the average spending on each order for couples who order most of their food online?**  
   - This analysis focuses on the spending behavior of couples who prefer online food orders.

5. **Which mode (online or offline) has received the maximum rating?**  
   - We compare ratings for online and offline orders to understand customer satisfaction levels.

6. **Which type of restaurant received more offline orders?**  
   - This analysis identifies the restaurant types with higher offline orders to help target potential offers.

---

## **Key Insights**
- **Popular Restaurant Types:** Identify which restaurant types attract the most customers and votes.  
- **Customer Ratings:** Understand the rating patterns and determine which rating is most common among restaurants.  
- **Spending Behavior:** Analyze spending habits of online customers, especially couples, to derive potential marketing strategies.  
- **Online vs. Offline:** Compare the performance and ratings of restaurants based on the mode of order.  
- **Offline Favorites:** Find out which restaurant types perform better offline for creating tailored offline offers.

---

## **Tools and Libraries Used**
- **Python:** Primary language for data analysis.
- **Libraries:**
  - `Pandas` for data manipulation and cleaning.
  - `NumPy` for numerical computations.
  - `Matplotlib` and `Seaborn` for data visualization.
  - `Jupyter Notebook` for interactive coding and presenting results.

---

## **Dataset**
The dataset used in this project includes detailed information about restaurants, including:  
- Restaurant types (e.g., Café, Quick Bites, Fine Dining)  
- Ratings, votes, and online/offline order options  
- Approximate cost for two people  
- Location and cuisine information  

### **Dataset Columns:**
- `name`: Name of the restaurant.  
- `online_order`: Whether the restaurant accepts online orders (`Yes` or `No`).  
- `book_table`: Whether the restaurant allows table booking (`Yes` or `No`).  
- `rate`: Restaurant rating out of 5.  
- `votes`: Number of votes the restaurant has received.  
- `location`: Location of the restaurant.  
- `listed_in(type)`: Type of restaurant (e.g., Café, Casual Dining, etc.).  
- `approx_cost(for two people)`: Estimated cost for two people.

---

## **Project Workflow**
### 1. **Data Cleaning**
- Handle missing values, outliers, and inconsistencies in the dataset.
- Clean the `rate` and `approx_cost` columns for numerical analysis.

### 2. **Exploratory Data Analysis (EDA)**
- Visualize data distributions and relationships.
- Group data by restaurant types, ratings, and order modes.

### 3. **Answering Key Questions**
- Apply data aggregation, filtering, and statistical methods to answer the project questions.

### 4. **Insights and Recommendations**
- Present actionable insights in the form of charts and reports.

---

## **How to Run This Project**
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/vivek09-bit/Zomato-Data-Analysis-Pandas.git
   ```
2. **Install Dependencies**  
   Ensure you have Python installed along with the required libraries. You can install the dependencies using:  
   ```bash
   pip install -r requirements.txt
   ```
3. **Open the Jupyter Notebook**  
   ```bash
   jupyter notebook Zomato_data_analysis.ipynb
   ```
4. **Run the Analysis**  
   Follow the notebook cells to reproduce the results and insights.

---

## **File Structure**
- **`Zomato_data_analysis.ipynb`**: Jupyter Notebook containing the code and analysis.
- **`README.md`**: Detailed project documentation.
- **`requirements.txt`**: List of Python dependencies for the project.

---

## **Sample Visualizations**
1. **Top Restaurant Types by Customer Votes**  
   ![Restaurants Votes](https://github.com/user-attachments/assets/ef0d7649-cbe0-47ae-8a9a-d4f6c4ba8b78)


2. **Rating Distribution Across Restaurants**  
   ![Rating Distribution](https://github.com/user-attachments/assets/02a72dee-3441-4334-ba49-2618019a515d)


3. **Comparison of Online vs. Offline Ratings**  
   ![Online And Offline Rating](https://github.com/user-attachments/assets/7c43ed76-f903-4c07-adaf-1c9fb7ca586a)


---

## **Future Scope**
- Incorporate advanced machine learning models to predict customer ratings and spending behavior.
- Add geospatial analysis to identify the best locations for opening new restaurants.
- Explore time-series data for seasonal trends in customer preferences.

---

## **Contact**
For questions or feedback, feel free to reach out:  
- **Email:** [vkg127@gmail.com](mailto:vkg1257@gmail.com)  
- **GitHub:** [My GitHub ](https://github.com/vivek09-bit)


**Let’s analyze and uncover insights together!**
