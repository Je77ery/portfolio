# Data Scientist
Summary: Specializing in predictive analytics, machine learning, and data-driven decision-making. Skilled in analyzing structured and unstructured data to optimize business performance.

Technical Skills : Python, SQL, R, Tableau, Power BI, Scikit-Learn, TensorFlow, PyTorch, NLP

### Education 
Data Science, MSc
Mechanical Engineering, BSc

### Work Experience 
## Data Scientist & Machine Learning Engineer (Independent Research, 2023 – Present)

•	Developed a deep learning model for skin lesion classification, achieving 93% accuracy with CNNs and TensorFlow/PyTorch.

•	Built a predictive model for COVID-19 cases, integrating metadata (age, sex, anatomy) to enhance diagnostic accuracy.

•	Designed an advanced image processing pipeline for medical image analysis, incorporating hair removal and augmentation techniques.

## Data Analyst (Manchester Metropolitan University, 2023)

•	Performed exploratory data analysis (EDA) on large datasets, identifying trends and patterns to drive strategic decision-making.

•	Conducted statistical analysis in R, applying hypothesis testing and regression models to generate actionable insights.

•	Developed interactive Tableau dashboards, visualizing key business insights for stakeholders.

## Data Analytics Consultant (KPMG Virtual Internship, 2023)

•	Assessed data quality and integrity, ensuring consistency across large datasets.


•	Performed customer segmentation analysis, leading to a 15% improvement in targeted marketing effectiveness.

•	Built Tableau dashboards to visualize customer behavior trends, helping executives make data-driven decisions.

## Data Science & Predictive Modelling Intern (British Airways Virtual Internship, 2023)

•	Scraped and analyzed 50,000+ customer reviews using BeautifulSoup and NLP techniques, identifying key drivers of customer satisfaction.

•	Built a machine learning model to predict customer booking behavior, improving booking conversion rates by 15%.

•	Designed interactive Tableau dashboards, enabling executives to visualize sentiment trends and optimize marketing campaigns.

### Projects

## **Deep Learning for Skin Lesion Classification**
#Code Link #PPT

#### **Project Overview** 
This project leverages **deep learning** to classify skin lesions, aiding in **early melanoma detection**. Using **ResNet-50**, the model distinguishes between multiple skin lesion types with **high accuracy**. 

### **Key Highlights:**
- **Dataset:** HAM10000 & BCN20000 (dermoscopic images + metadata).
- **Preprocessing:** Hair removal, contrast adjustment, data augmentation.
- **Model:** Modified **ResNet-50** with metadata integration.
- **Training:** PyTorch, Adam optimizer, batch size = 32, learning rate = 0.001.
- **Evaluation:** Confusion Matrix, ROC-AUC, F1-score.
- **Challenges:** Addressed class imbalance & overfitting with augmentation & dropout.
- **Future Work:** Transfer learning, explainable AI, and multimodal learning.

This project demonstrates the potential of **AI in dermatology**, showcasing **automated skin cancer detection** using CNNs and metadata-driven insights.


## **Car Price Prediction using Machine Learning**
#Code Link #PPT

#### **Project Overview**  
This project focuses on building a **machine learning model** to predict **car prices** based on various features such as **mileage, condition, and specifications**. The dataset was sourced from **Auto Trader**, and an **exploratory data analysis (EDA)** was conducted to uncover insights before model training.

### **Key Highlights**
- **Dataset Source**: Auto Trader
- **EDA & Insights**:
  - Analyzed the relationship between **mileage, price, and car condition**.
  - Identified **outliers and erroneous values**, applying caps on mileage and price.
  - Handled **missing values** using **SimpleImputer**.
- **Feature Engineering & Selection**:
  - Applied **PolynomialFeatures, PCA, and Target Encoding** for transformation.
  - Selected the best predictors using **SelectKBest, RFECV, and SequentialFeatureSelector**.
- **Model Development & Optimization**:
  - Used **train-test split, cross-validation, and hyperparameter tuning**.
  - Achieved **96% model accuracy** using an optimized regression model.
- **Evaluation Metrics**:
  - **Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score** to assess performance.

### **Conclusion**
This project demonstrates expertise in **data preprocessing, feature engineering, and predictive modeling**. With a **96% accuracy rate**, the model provides **highly reliable car price predictions**, making it a valuable tool for **pricing insights in the automotive industry**.



### **British Airways Customer Review Analysis**  
#Code Link #PPT

#### **Project Overview**  
This project focuses on analyzing customer reviews for British Airways to identify key sentiments and trends. The analysis helps understand customer satisfaction levels and areas for improvement.

#### **Key Highlights**  
- **Dataset Source**: Customer reviews collected from Skytrax platform.  
- **EDA & Insights**:  
  - Analyzed common themes in reviews.  
  - Identified sentiment distribution (positive, neutral, negative).  
  - Explored trends in review scores over time.  
- **Feature Engineering & Selection**:  
  - Applied Natural Language Processing (NLP) techniques to preprocess text.  
  - Used TF-IDF and Word2Vec embeddings for feature extraction.  
  - Selected key predictors using statistical methods.  
- **Model Development & Optimization**:  
  - Used machine learning models such as Logistic Regression, Random Forest, and Support Vector Machines for sentiment classification.  
  - Applied hyperparameter tuning and cross-validation.  
- **Evaluation Metrics**:  
  - Accuracy, Precision, Recall, and F1-score to assess sentiment classification performance.  
#### **Conclusion**
    Provided valuable insights into customer sentiment, while also identifying areas where British Airways can improve service quality.  



### **Sprocket Central Customer Analytics**  
#Code Link #PPT

#### **Project Overview**  
This project focuses on analyzing customer data for Sprocket Central to enhance marketing and sales strategies. The goal is to identify high-value customers and optimize engagement strategies.  

#### **Key Highlights**  

- **Dataset Source**: Internal customer and transaction data.  
- **EDA & Insights**:  
  - Analyzed customer demographics and purchasing behavior.  
  - Identified high-value customer segments based on Recency, Frequency, and Monetary (RFM) analysis.  
  - Detected trends in sales and customer engagement over time.  
- **Feature Engineering & Selection**:  
  - Created new features such as customer lifetime value (CLV) and purchase frequency.  
  - Applied clustering techniques like K-Means and hierarchical clustering for customer segmentation.  
  - Selected key variables using feature importance analysis.  
- **Model Development & Optimization**:  
  - Built predictive models to identify potential high-value customers.  
  - Used classification and regression models such as Decision Trees, Random Forest, and Gradient Boosting.  
  - Performed hyperparameter tuning for optimal performance.  
- **Evaluation Metrics**:  
  - Accuracy, ROC-AUC, and RMSE for model validation.  
#### **Conclusion** 
    Helped Sprocket Central optimize marketing campaigns and improved customer targeting and retention strategies.  


### **Bank Management System (FCMB Mobile App Simulation)**  

####  **Project Overview**  
This project is a simulation of a **banking system** using **Object-Oriented Programming (OOP)** principles in Python. It allows customers to perform basic banking operations such as checking their balance, making withdrawals, deposits, and transferring funds between accounts. The system interacts with external text files to simulate a database for storing **account information** and **transaction history**.  

### **Key Highlights**  

#### **1. System Components**  
- **Customer Class**:  
  - Stores customer details (ID, first name, last name).  
  - Implements encapsulation using the `@property` decorator for customer ID access.  

- **Account Class**:  
  - Manages customer bank accounts with attributes:  
    - Customer information  
    - Account type and number (encapsulated)  
    - Balance and PIN for security  
  - Provides controlled access to account numbers.  

- **Bank Class**:  
  - Handles core banking operations:  
    **Load and Save Data**:  
      - Loads account data from `accounts.txt`.  
      - Stores transaction history in `transaction.txt`.  
    **Operations**:  
      - **Check Balance**: Displays the account balance.  
      - **Withdraw**: Deducts funds if the balance is sufficient.  
      - **Deposit**: Adds funds to an account.  
      - **Transfer**: Transfers money between two valid accounts.  
    **Transaction Logging**:  
      - Records all actions with timestamps for audit purposes.  

- **FCMBMobileApp Class**:  
  - Provides the user interface (CLI) for banking operations.  
  - Implements PIN authentication with a **3-attempt lockout** for security.  
  - Allows users to navigate through a menu to select options:  
    - Check Balance  
    - Withdraw  
    - Deposit  
    - Transfer  
    - Exit  

### **Features and Functionalities**  

1. **User Authentication**:  
   - PIN verification with limited retries for security.  
2. **Account Management**:  
   - Check account balance.  
   - Deposit and withdraw funds.  
   - Transfer funds between accounts (with same-account validation).  
3. **Transaction Logging**:  
   - Records each transaction with details:  
     - Date and time  
     - Account number  
     - Transaction type (credit, debit, transfer)  
4. **File Handling**:  
   - Data persistence using external files (`accounts.txt` and `transaction.txt`).  

### **Code Design and Principles**  

- **Object-Oriented Programming (OOP)**:  
  - Uses classes for **Customer**, **Account**, and **Bank** with encapsulation via private attributes.  
- **Encapsulation**:  
  - Sensitive data (e.g., `cust_id`, `account_no`, and `PIN`) is accessed via properties.  
- **Error Handling**:  
  - Checks for invalid input (e.g., insufficient balance, wrong PIN, and account existence).  
- **Modularity**:  
  - Each operation is handled in dedicated methods to ensure clarity and reusability.  

### **Conclusion**  
The **FCMB Mobile App Simulation** demonstrates a practical implementation of banking services using **OOP principles** in Python. It provides a comprehensive framework for managing customer data, conducting transactions, and ensuring data security. This project reflects strong skills in **file handling**, **data persistence**, and **modular program design**.  



### **Traffic Light Simulation Using Tkinter**



### **Project Overview**  
This project is a **GUI-based Traffic Light simulation** built using Python's **Tkinter** module. The application visually represents a traffic light system where users can switch between **red, yellow, and green** lights using corresponding radio buttons.


### **Key Highlights**

- **GUI Framework**: Built with **Tkinter**, Python’s standard library for graphical interfaces.
- **Interactive Control**: Users select traffic light colors through **radio buttons**.
- **Dynamic Display**: The interface updates the traffic light display in real-time based on user input.



### **EDA & Insights**

1. **User Interface**:
   - Three **radio buttons** corresponding to the three traffic light states:
     - **Red** for stop
     - **Yellow** for caution
     - **Green** for go
   - **Three canvas areas** display the traffic lights in circular shapes.
   - The default color is **red** on application launch.
   
2. **Event Handling**:
   - **on_RadioChange** method dynamically updates the light display based on the selected radio button.
   - Each light is turned on or off by changing the **fill color** of the respective canvas.



### **Feature Engineering & Selection**

1. **Object-Oriented Design**:
   - **TrafficLights** class encapsulates the entire application, enhancing modularity and maintainability.
   - Methods and attributes are organized for clear separation of logic and GUI components.

2. **Dynamic Light Control**:
   - `StringVar()` tracks the selected color dynamically.
   - **itemconfig()** method updates the canvas display in response to user input.



### **Model Development & Optimization**

1. **Initialization Process**:
   - **Tk()** creates the main window.
   - **Frame()** groups the radio buttons for organized layout.
   - **Canvas()** renders the traffic light display.
   
2. **Radio Button Interaction**:
   - Each button triggers the **on_RadioChange** callback function.
   - Depending on the selected color, the corresponding canvas is updated while others reset to **white**.

3. **User Experience**:
   - Smooth transition between lights.
   - Intuitive interface for traffic light control.



### **Evaluation Metrics**

1. **Functionality**:
   - Correctly toggles between **red, yellow, and green** lights.
   - Default light initializes to **red**.

2. **Usability**:
   - Simple and intuitive UI with clear labeling.
   - Immediate visual feedback when selecting a color.

3. **Efficiency**:
   - Lightweight application using efficient **Tkinter** methods.
   - Clear separation of logic between the display and the control.



### **Conclusion**

This **Traffic Light Simulation** is a practical demonstration of **Object-Oriented Programming** and **GUI development** in Python. It effectively models real-world traffic signals with dynamic user control. The project showcases skills in:

- **Tkinter GUI development**  
- **Event-driven programming**  
- **Object-oriented design**  

The design is extensible and can be enhanced with **timing mechanisms** for automated light transitions or additional traffic system simulations.

### **Vending Machine Management System**  


### **Project Overview**  
This project is a **Python-based Vending Machine System** using the **Pandas** library for data manipulation and **input/output interactions** for user interface. It supports both **admin** and **customer functionalities**, including managing stock and purchasing products.


### **Key Highlights**

- **Data Handling**: Uses **Pandas** to manage and manipulate vending machine inventory.
- **User Authentication**: Implements a basic **admin login** system for secure access.
- **Stock Management**: Allows **admins** to add products to vending machine slots.
- **Purchase System**: Customers can buy items, and the system calculates the **total cost and change**.
- **Error Handling**: Provides feedback for invalid inputs and manages exceptions gracefully.


### **EDA & Insights**

1. **Dataset Usage**:
   - **vm.csv**: Contains product information from the vending machine (e.g., snack name, machine code, price).
   - **stock.csv**: Holds the current stock levels of each product.

2. **Data Cleaning & Standardization**:
   - **standardise_product_name** function:
     - Cleans and formats product names for consistency.
     - Handles cases where products may have hyphens or inconsistent capitalization.
   - DataFrames are merged using **pd.merge()** on the `snack` column.
   - Sets the vending machine slot (`machine_code`) as the **index**.



### **Feature Engineering & Selection**

1. **Admin Authentication**:
   - Users enter a **username** and **numeric password**.
   - Allows three failed attempts before locking access.

2. **Add Product (Admin Only)**:
   - Admins can select a slot and add a specified quantity of products.
   - Enforces a **maximum stock** of 8 per slot.
   - Handles invalid inputs like negative quantities or non-existent slots.

3. **Purchase Product**:
   - Users can choose a product and specify the **quantity** to purchase.
   - System calculates the **total cost** and verifies payment.
   - Updates stock and provides **change** if the payment exceeds the cost.
   - Handles errors for insufficient payment, invalid slots, and out-of-stock items.



### **Model Development & Optimization**

1. **Functions and Modular Design**:
   - **auth()**: Handles admin login and authentication.
   - **add_product()**: Allows the admin to increase product quantities.
   - **buy_product()**: Manages customer purchases and processes payments.
   - **menu()**: Displays available operations.
   - **vending_machine()**: Main control flow for the vending machine system.

2. **Data Handling**:
   - Uses **Pandas DataFrames** to store and manipulate product and stock information.
   - Implements **input validation** and exception handling to prevent crashes.



### **Evaluation Metrics**

1. **Functionality**:
   - Correctly adds products and enforces stock limits.
   - Ensures accurate payment processing and inventory updates.

2. **Usability**:
   - User-friendly menu-driven interface.
   - Clear messages for errors and successful operations.

3. **Security**:
   - Password-based admin access.
   - Limits the number of failed login attempts.

4. **Efficiency**:
   - Efficient use of **Pandas** for data manipulation.
   - Reduces redundancy through well-structured functions.



### **Conclusion**

This **Vending Machine System** demonstrates effective **data handling**, **user authentication**, and **inventory management** using Python. The program is:

- **Modular**: Each function handles a specific task, ensuring code clarity.
- **Robust**: Manages errors (e.g., invalid inputs, insufficient funds).
- **Scalable**: Can be expanded to handle more advanced inventory tracking or user roles.
