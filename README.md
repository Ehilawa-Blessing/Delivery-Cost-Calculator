🚚 Delivery Cost Calculator System

A Python-based delivery cost calculation and reporting system designed to process delivery records, calculate accurate delivery costs, apply customer discounts, and generate useful business insights.

📌 Project Overview

The Delivery Cost Calculator System processes multiple delivery records and calculates the final cost of each delivery based on distance, package weight, delivery type, location, and customer type.

The system also applies discounts to Premium customers and generates analytical reports that answer key business questions around revenue, delivery patterns, pricing, and customer segmentation.

This project was developed as part of the Python Study Group – Team H Case Study, bringing together key Python concepts from the second semester, including:

- String slicing and manipulation
- Variables and data types
- Lists and dictionaries
- Conditional statements
- "for" and "while" loops
- Functions
- Parameters and return values
- Logical operators
- Variable scope
- Input validation

---

⚙️ Core Functionality

Cost Calculation Components

Component| Description
Base Cost| Fixed starting cost of ₦1,000 for every delivery
Distance Charge| Additional cost based on distance travelled
Weight Charge| Additional cost based on package weight
Delivery Type Charge| Additional charge for Express or Same-Day delivery
Location Charge| Additional charge for Regional or Inter-State delivery
Premium Discount| 10% discount applied to Premium customers

Delivery Factors Considered

The system calculates delivery costs using five major factors:

1. Distance Travelled – Longer distances increase delivery costs.
2. Package Weight – Heavier packages attract higher charges.
3. Delivery Type – Standard, Express, or Same-Day.
4. Location Category – Local, Regional, or Inter-State.
5. Customer Type – Premium or Regular.

---

📊 Business Questions Answered

The system generates insights that answer 15 key business questions:

#| Business Question| Business Value
1| Which delivery has the highest final cost?| Identifies cost outliers
2| Which delivery has the lowest final cost?| Identifies cost optimization opportunities
3| What is the total delivery revenue?| Measures overall revenue
4| What is the average delivery cost?| Establishes pricing benchmarks
5| How much was spent on Premium discounts?| Evaluates discount costs
6| How many customers used Standard delivery?| Measures service adoption
7| How many customers used Express delivery?| Measures premium service demand
8| How many customers used Same-Day delivery?| Measures urgent delivery demand
9| How many deliveries were Local?| Tracks local activity
10| How many deliveries were Regional?| Tracks regional activity
11| How many deliveries were Inter-State?| Tracks cross-state activity
12| Which delivery had the highest package weight?| Identifies weight outliers
13| Which delivery had the longest distance?| Identifies distance outliers
14| Which customer received the highest discount?| Identifies highest discount recipient
15| How many Premium customers are in the dataset?| Measures customer segmentation

---

🧾 Sample Delivery Records

The system processes multiple delivery records, including:

- D1
- D2
- D3
- D4
- D5
- D6
- D7

Each record contains relevant delivery information used to calculate the final delivery cost and generate individual reports.

---

💻 Technical Implementation

Python Concepts Applied

Concept| Application
Variables & Data Types| Storing delivery records, costs, and customer information
String Operations| Processing delivery IDs and customer names
String Slicing| Extracting specific parts of delivery codes
Data Structures| Organizing records using lists and dictionaries
Arithmetic Operations| Calculating charges, totals, discounts, and averages
Logical Operators| Evaluating multiple conditions
Conditional Statements| Determining charges based on delivery factors
For Loops| Processing multiple delivery records
While Loops| Validating input and controlling program flow
Nested While Loops| Building structured input validation
"while True"| Creating controlled program exit
Functions| Modularizing cost calculation logic
Parameters & Arguments| Passing delivery information into functions
Return Values| Returning calculated charges and results
Variable Scope| Working with global and local variables

---

🎯 Key Achievements

- Successfully processed multiple delivery records.
- Calculated delivery costs using five major factors.
- Implemented a 10% Premium customer discount.
- Generated individual delivery cost reports.
- Produced summary analytics answering 15 business questions.
- Implemented input validation using controlled loops.
- Built modular functions with parameters and return values.
- Applied global and local variable scope appropriately.
- Transformed raw delivery data into meaningful business insights.

---

💼 Business Value

Area| Value Provided
Operations| Standardized delivery cost calculations
Finance| Revenue, average cost, and discount tracking
Strategy| Service demand and pricing insights
Customer Management| Premium customer pricing benefits
Decision-Making| Data-driven logistics insights

---

🚀 What This Project Demonstrates

This project demonstrates how fundamental Python programming concepts can be combined to develop a practical business solution.

It shows that Python can be used to:

- Automate repetitive calculations
- Process and analyze structured data
- Apply business rules and decision logic
- Generate useful reports
- Support operational and financial decision-making

---

🔮 Future Improvements

The system can be further enhanced by:

- Adding more delivery types and pricing structures
- Integrating CSV/Excel files for batch processing
- Connecting the system to a database
- Building a graphical user interface (GUI)
- Adding data visualization for trend analysis
- Supporting larger delivery datasets
- Automating report generation

---

🏁 Conclusion

The Delivery Cost Calculator System strengthened my understanding of how Python fundamentals can be applied to solve real-world logistics and business problems.

By combining conditional statements, loops, functions, data structures, and variable scope, the project demonstrates how programming can transform raw delivery information into actionable insights.

Key Areas Supported

Decision-Making: Data-driven logistics insights
Financial Analysis: Revenue tracking and cost optimization
Operational Efficiency: Standardized pricing and reporting
Customer Management: Segmented pricing and service tracking

Built with Python — delivering insights, one delivery at a time.
