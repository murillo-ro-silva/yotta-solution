# yotta-solution

This repository demonstrates a simple PySpark solution to read, transform, and flatten nested JSON data. Below you will find a link to the main notebook and a brief explanation of what it does.

## Contents
- [spark_solution.ipynb](spark_solution.ipynb)  
  - A Jupyter Notebook showing the step-by-step PySpark code and transformations.
- [simple_draw_solution.jpeg](simple_draw_solution.jpeg)  
  - An image illustrating the macro architecture/design of the solution.
- [README.md](README.md)  
  - This file, providing an overview of the repository.

## Overview
In the [spark_solution.ipynb](spark_solution.ipynb) notebook, you will see how to:
1. Initialize a Spark Session.
2. Read a JSON file (with multiline support).
3. Explode the nested `products` array so each product becomes a separate row.
4. Select relevant columns (`customer_id`, `order_id`, `product_name`, `product_price`) in a flattened DataFrame.

## How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/murillo-ro-silva/yotta-solution.git
   cd yotta-solution
   ```
2. Open the site https://www.sparkplayground.com/pyspark-online-compiler

3. Launch the spark_solution.ipynb and run the cells to see the code in action.
