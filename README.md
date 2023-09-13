# Data Engineering Code Interview

## 👋 Hi there

Welcome to the Data Engineering code interview! This small data challenge is designed to test out your skills in python, sql, git and basical data visualization.
**Exercise Description:**

**Objective:** The goal of this exercise is to demonstrate your ability to integrate data from multiple sources, perform data processing, and answer specific queries using Python.

**Scenario:** You are provided with two data sources:

1. An inventory dataset in CSV(/data/cars.csv) format containing information about cars available for lease, such as make, model, type, and other relevant attributes.
2. A pricing dataset in JSON(/data/historical_vehicle_pricing.json) format containing pricing information for different car types.

**Task:** Write a Python script that takes these data sources, processes them, and allows a user to query the data to find out what type of car can be leased for a given budget.

**Instructions:**

1. **Data Preprocessing:**
    - Load the inventory data from the CSV file into a Pandas DataFrame.
    - Load the pricing data from the JSON file into a Python dictionary.
2. **Data Integration:**
    - Join the two datasets based on a common attribute (e.g., car type).
3. **User Interaction:**
    - Create a command-line interface or a basic web interface to accept user queries.
4. **Query Processing:**
    - Parse user queries for budget constraints (e.g., "lease for $300").
    - Use Python to filter the integrated dataset to find cars that match the budget constraint.
5. **Response Generation:**
    - Return the results of the query to the user in a user-friendly format.
6. **Testing:**
    - Verify that the script correctly answers the following questions
        - "What type of car can I lease for $300?"
        - “I’m looking to lease a sedan with a monthly between 400 and 550, What would be the cheapest due at signing?
        - What is the most common SUV and how much does it cost on average
        - What are the 10 most affordable make, model, trims for lease and finance respectively
    

**Notes:**

- You can use libraries like Pandas for data processing, argparse for command-line interfaces, or Flask/Django for a web interface.
- das = “Due At Signing”

**Deliverables**

- Create a github project containing instructions to run a cli
- Dockerfiles are preferred since environments could be different
## Post Test Interview process

There will be 2 interviews after the test has been successfully submitted

- 1 Interview will be focused on submitted exercise, code review, and requirements validation
- 1 Interview will be focused on your experience working in —> agile environments, interactions with QA Automation teams, technical collaboration style, and ability to receive and provide honest feedback to team
