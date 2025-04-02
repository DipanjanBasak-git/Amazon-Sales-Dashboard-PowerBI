## Amazon Sales Dashboard in Power BI  

### 📌 Project Overview  
This project involves creating a **Power BI dashboard** to analyze Amazon sales data for the year **2022**. The dataset includes various attributes like **product details, pricing, ratings, stock availability, seller information**, and more. The dashboard provides **key insights** into sales trends, customer preferences, and product performance.  

## 📊 Key Features of the Dashboard  
- **Total Sales & Revenue Analysis**  
- **Top-Selling Products & Categories**  
- **Customer Ratings & Reviews Distribution**  
- **Stock Availability & Inventory Insights**  
- **Discount Analysis & Pricing Trends**  

## 🗂️ Dataset Details  
### **Dataset Used: Amazon Sales 2022**  
- <a href ="https://github.com/DipanjanBasak-git/Amazon-Sales-Dashboard-PowerBI/blob/main/Amazon%20Sale%20Report%20-%20YT.xlsx">Amazon-Sale-Report-Dataset</a>
- <a href ="https://github.com/DipanjanBasak-git/Amazon-Sales-Dashboard-PowerBI/blob/main/compressed_data.csv.gz">Amazon-Sales-Cleaned-Dataset</a>

### The dataset consists of **28,731 records** with key attributes such as:  

```
- amazon_prime__y_or_n: Whether the product is Amazon Prime eligible (Y/N)
- asin: Amazon Standard Identification Number
- best_seller_tag__y_or_n: Bestseller status (Y/N)
- brand: Product brand name
- colour: Product color
- discount_percentage: Discount percentage offered
- rating: Customer rating (out of 5)
- sales_price: Price of the product
- no_of_reviews: Total number of customer reviews
- Category: Product category (e.g., Men's T-Shirts, Women's Kurtas)
- seller_name: Seller's name
```

## 📈 Data Visualizations  
### 🔹 **Page 1: Overview**  
```
- Total Sales: $89.08 million (Card Visualization)
- Total Units Sold: 120.30K (Card Visualization)
- Best-Selling Products (Bar Chart)
- Top Categories by Revenue (Pie Chart)
- Overall Rating Distribution (Gauge Chart)
```

### 🔹 **Page 2: Product**  
```
- Average Customer Rating by Category (Column Chart)
- Distribution of Customer Reviews (Histogram)
- Amazon Prime vs. Non-Prime Sales (Stacked Bar Chart)
- Top-Selling Brands & Their Market Share (Tree Map)
```

### 🔹 **Page 3: Product View**  
```
- Stock Availability Trends (Line Chart)
- Discount Percentage Impact on Sales (Scatter Plot)
- Price Ranges for Different Categories (Box Plot)
- Customer Sentiment Analysis Based on Ratings (Bubble Chart)
```

## 🖼️ Sample Dashboard Screenshots  
📌 **Page 1: Overview**  
(<a href="https://github.com/DipanjanBasak-git/Amazon-Sales-Dashboard-PowerBI/blob/main/Screenshot%202025-04-02%20154427.png">Overview Sales</a>) 
![Screenshot 2025-04-02 154427](https://github.com/user-attachments/assets/3bc8bca0-aa0e-4d33-af38-e248f173b20a)

(<a href="https://github.com/DipanjanBasak-git/Amazon-Sales-Dashboard-PowerBI/blob/main/Screenshot%202025-04-02%20165938.png">Overview Units</a>)
![image](https://github.com/user-attachments/assets/58b4697a-03a0-4d37-a17a-cb1b73c44c16)


📌 **Page 2: Product**  
(<a href="https://github.com/DipanjanBasak-git/Amazon-Sales-Dashboard-PowerBI/blob/main/Screenshot%202025-04-02%20154502.png">All Product Sales Display</a>)
![Screenshot 2025-04-02 154502](https://github.com/user-attachments/assets/4697f0b0-b883-4773-8b67-5a4ae0417b38)

(<a href="https://github.com/DipanjanBasak-git/Amazon-Sales-Dashboard-PowerBI/blob/main/Screenshot%202025-04-02%20154004.png">Check Product Sales</a>) 
![Screenshot 2025-04-02 154004](https://github.com/user-attachments/assets/c746f229-7cc6-460d-960e-ca680826ee7d)


📌 **Page 3: Product View**  
(<a href="https://github.com/DipanjanBasak-git/Amazon-Sales-Dashboard-PowerBI/blob/main/Screenshot%202025-04-02%20154529.png">All Product-view Sales</a>) 
![Screenshot 2025-04-02 154529](https://github.com/user-attachments/assets/06e12001-7475-4e35-b6b4-64e6bcd0ecb8)

(<a href="https://github.com/DipanjanBasak-git/Amazon-Sales-Dashboard-PowerBI/blob/main/Screenshot%202025-04-02%20154021.png">Specific Product-view Sales</a>) 
![Screenshot 2025-04-02 154021](https://github.com/user-attachments/assets/a7c74f13-23e4-42fb-b601-f52d7d345f51)


## ⚙️ Data Cleaning & Processing  
```
1. Handling Missing Values (Filled missing stock availability using median values)
2. Standardizing Column Formats (Converted discount_percentage to numerical values)
3. Removing Duplicates (Filtered out duplicate product listings)
4. Feature Engineering (Created new fields like Discounted Price, Revenue Impact)
5. Grouping & Aggregations (Summarized sales data by category, brand, and price range)
```

## 🔍 Insights Derived  
```
- Total Sales: $89.08 million 💰
- Total Units Sold: 120.30K 📦
- Products with higher discounts tend to have more sales but lower ratings.
- Amazon Prime products sell faster than non-Prime products.
- Men's T-Shirts & Women's Kurtas are the top-selling categories.
- Best-selling brands maintain a 4.2+ rating, showing a correlation between quality and sales.
- Products priced between $20-$50 have the highest purchase volume.
```

## ❓ Questions Answered by This Dashboard  
| Question                                      | Answer |
|----------------------------------------------|--------|
| What is the total revenue generated?        | **$89.08 Million** |
| How many total units were sold?             | **120.30K** |
| Which products are the best-selling?        | **Men's T-Shirts, Women's Kurtas** |
| What is the impact of discounts on sales?   | **Higher discounts = More sales, but lower ratings** |
| Do Prime products sell more than non-Prime? | **Yes, Prime products have higher sales** |
| Which price range sees the most purchases?  | **$20-$50** |
| How do customer ratings impact sales?       | **Higher-rated products sell more** |
| Which brands dominate the market?          | **Top 5 brands cover 60%+ sales** |

## 📥 How to Use This Dashboard  
```
1. Download the Power BI `.pbix` file from this repository.
2. Open it in Power BI Desktop.
3. Interact with the visuals to analyze Amazon sales trends!
```

## 🤝 Connect with Me  
If you found this project useful, feel free to connect with me on **LinkedIn**! 🚀  
<a href="https://www.linkedin.com/in/dipanjan-basak-49bb59280/">Linkedin Account Link!</a>
---  
