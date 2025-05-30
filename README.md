<picture>
  <source srcset="https://avatars.githubusercontent.com/u/123291668?v=4">
  <img 
    alt="My Profile Photo" 
    src="https://avatars.githubusercontent.com/u/123291668?v=4">
</picture>


## About me

Hi, I'm Debasish and in this project I will be Building End to End Prices Predictor System - Top 1% Way, it is referenced from <b>FreeCodeCamp.org</b> and this will be an <b>Production Grade Project</b>. 

This Project is focused on building an end-to-end machine learning pipeline for a house price prediction system. <br>
The pipeline is developed using ZenML, a MLOps framework that helps managing machine learning workflows and MLflow, which is used for experiment tracking and model deployement.

The primary goal is to predict house prices based on various features of the properties, such as the size, location. and condition.

## But everyone is doing house prediction system. How it will differentiate you ?!

### What most people are doing ??
1. Limited Exploration.<br>
   a. Most practitoners start with basic exploratory data analysis (EDA) using standard frameworks.<br>
   b. They quickly move on to calling .fit on a model without thoroughly understanding the data.<br>
## What we will do ? <br>
<b>1. Basic Model Training.<br>
   a. Implement findings from EDA in the preprocessing satge, ensuring the data is clean and feature-engineered to maximize model performance.<br>
   b. Continuously validate and correct assumptions during model training and fixing any violations through iterative improvement.<br>
2. Beyond Core ML.<br>
   a. We don't just train na model : we will ensure it meets all necessary assumptions and refine it iteratively.<br>
   b. We focus on building a robust pipeline that can be easily reproduced and deployed.<br>
3. MLOps and Production Readiness.<br>
   a. Differentiate our project by integrating MLOps practices using ZenML and MLflow.<br>
   b. Implement CI/CD pipelines to automate testing, deployement of the model in production.<br>
   c. Ensure the model is not only accurate but also maintainable, scalable, and ready for real-world use.<br>
   </b>
## First Step is always to load the data:
  We will ingest data first: here's how we will do it little differently:
  - Use Design patterns to handle other sets of data accordingly.
  - Make it readable, and reproducible in that sense.
###  I will make use of Factory Design Pattern but before we go, here's small explaination of Factory design pattern:
## Factory Design Pattern:
Imagine you run a coffee shop. Customers can order different type of coffee, but the process of making coffee follows a similar pattern. You have a general coffee making machine (the factory) that can be use dot make different types of coffee(products) like Espresso, Latte, or Cappuccino.
   - CoffeeMachine(Factory): Has the method to make coffee.
   - Espresso, Latte, Cappuccino(ConcreteProducts): Different types of coffee that can be made by the machine.
   - Example code in python - explainations/factory_design_pattern.py
