# Rule Engine Application

## Overview

This application is a rule engine that determines user eligibility based on attributes such as age, department, salary, and experience. It uses an Abstract Syntax Tree (AST) to represent and manage conditional rules, allowing for dynamic rule creation, combination, and evaluation.

![Rule Engine Overview](https://github.com/user-attachments/assets/78f6bdca-68aa-4818-a56f-5a50c2023b7f)

## Features

# Rule Engine with AST

## Create Rule Screenshots

![Create Rule 1](./main/Images/CreateRule.png)
![Create Rule 2](./main/Images/CombineRule.png)
![Create Rule 3](./main/Images/EvaluateRule.png)


- **Create Rules:** Define rules using a string format that gets converted into an AST.
  
  ![Create Rule](./images/CreateRule.png)


- **Combine Rules:** Combine multiple rules into a single AST for more complex evaluations.
  
  ![Combine Rules](https://github.com/user-attachments/assets/63145818-6936-4763-8fbe-db65f264e4ff)

- **Evaluate Rules:** Check if the given data meets the criteria defined by the AST.
  
  ![Evaluate Rules](https://github.com/user-attachments/assets/041e664f-1711-4bbb-b107-50d5fb7909f4)

- **Tree Visualization:** Visual representation of rules in tree format.

## Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Installation

1. **Clone the Repository**
   ```bash
   git clone "https://github.com/Neeraj-rajauriya/Rule-Engine-with-AST.git"
   cd Rule-Engine-with-AST
