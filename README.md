# -Myntra-Online-Retail-Customer-Segmentation
This project demonstrates the design and implementation of data-driven customer segmentation for Myntra Gifts Ltd., focusing on e-commerce customer analytics using real transaction data. The pipeline includes rigorous data cleaning, exploratory analysis, engineered features, unsupervised clustering, and business interpretation—formulated to empower personalized marketing, targeted promotions, and strategic decision-making.

**1. Data Source and Cleaning**
Dataset: 2 years of transaction logs (Dec 2009–Dec 2011), featuring invoice IDs, products, quantities, prices, customer identifiers, purchase dates, and countries.​

Cleaning: Canceled invoices and outliers removed; missing values handled (especially CustomerID); 'TotalSales', 'MonthYear', and similar features derived for analysis.​

Outlier detection and removal of negative Quantity/UnitPrice help maintain integrity for robust modeling.​

**2. Exploratory Data Analysis & Visualization**
Temporal pattern analysis (monthly trends, seasonal spikes such as Black Friday sales).​

Geographic sales and revenue breakdown (dominant market: UK, top international markets: Germany, France, EIRE, Netherlands).​

Top-selling products and customer distribution visualized using logical, business-impactful charts (15+ charts included) following structured UBM Rule: Univariate, Bivariate, and Multivariate Analysis.​

Insights inform inventory, logistics, and international marketing expansion strategies.​

**3. Feature Engineering**
Conversion of date formats; extraction of cyclic features (DayOfWeek, InvoiceMonth), total invoice spend, frequency per customer, and recency grouping.​

Creation and scaling of custom features for meaningful clustering and trend detection (e.g., purchase frequency groups, average spend by recency/frequency).​​

**4. Clustering and Segmentation Algorithms**
Methodologies: K-Means (chosen for interpretation, efficiency, and silhouette performance), Agglomerative Clustering (for hierarchy detection), and DBSCAN (outlier and dense area segmentation).​​

Metrics used: Silhouette Score (best: 0.34 for K-Means), Davies-Bouldin Index (lower values preferred).​

Business personas defined: high-value frequent buyers, bulk/seasonal shoppers, price-sensitive occasional buyers.​

Segmentation enables targeted marketing, loyalty programs, and personalized recommendations, aligning with leading industry practices in fashion e-commerce analytics.​

**5. Business Impact and Deployment Readiness**
Segment insights drive differential campaigns, inventory allocation, and customer engagement (high-revenue segments prioritized for offers, low-frequency re-engaged via personalization).​​

Codebase is production-ready—modular notebooks, exception handling, documented logic, and no error propagation for seamless deployment.​

Suggestions for future work include dashboard integration, RFM analysis, and predictive modeling for customer lifetime value.​

**6. Technical Highlights**
Pandas, Numpy, Matplotlib, Seaborn for data manipulation and visualization.

Scikit-learn for ML workflow, preprocessing pipelines, and algorithm implementation.

Extensive commenting and error handling throughout notebooks for maintainability and reproducibility.​

**In summary:**
This project is a showcase of applied machine learning and statistical analysis, leveraging clustering to inform critical business decisions in an online retail context. It highlights the synergy between data science and business impact—empowering Myntra’s marketing engine with actionable insights from customer data segmentation.​​​
