# Product Management API Assignment
**Subject:** Product Management API Assignment 

---

## Dear Students,

I hope you are doing well. This document provides all the details related to the **Product Management API Assignment**, including the assignment overview, objectives, marking scheme, and important submission deadlines. Please read it carefully and make sure to submit your work on time to avoid any issues.

---

## 1. Overview

In this assignment, you will develop a **RESTful API** for managing products using **Spring Boot** and **MongoDB**. The goal is to create a fully functional **CRUD (Create, Read, Update, Delete)** application that allows users to add, view, update, and remove products from the database. You will also demonstrate your API using **Postman** and verify data storage in **MongoDB**.

---

## 2. Objectives

1. **API Development**  
   - Implement a RESTful API with endpoints to perform CRUD operations on a product collection.

2. **Database Integration**  
   - Utilize MongoDB for persistent data storage and leverage Spring Data for seamless integration.

3. **Data Modeling**  
   - Design a product model that includes essential attributes such as product ID, name, description, price, quantity, etc.

4. **Testing & Demonstration**  
   - Validate the API functionality using Postman and display the stored data in MongoDB.

5. **Documentation**  
   - Prepare comprehensive documentation detailing your code structure, API endpoints, and demonstration instructions.

---

## 3. Product Data Model

Your product model should include (but is not limited to) the following attributes:

- **Product ID:** A unique identifier (automatically generated or user-defined).  
- **Name:** The name of the product.  
- **Description:** A brief overview of the product.  
- **Price:** The cost of the product.  
- **Quantity:** The available quantity in stock.  
- **Category (Optional):** The category to which the product belongs.

> **Note:** You may add other fields as required or beneficial for your application.

---

## 4. API Endpoints

You must implement the following endpoints:

1. **Create Product**  
   - **Endpoint:** `POST /api/products`  
   - **Function:** Create a new product.  
   - **Request Body Example:**
     ```json
     {
       "name": "Wireless Mouse",
       "description": "Ergonomic wireless mouse with USB receiver",
       "price": 29.99,
       "quantity": 100,
       "category": "Electronics"
     }
     ```
   - **Response:** The created product with a unique Product ID.

2. **Read All Products**  
   - **Endpoint:** `GET /api/products`  
   - **Function:** Retrieve a list of all products.  
   - **Response:** A JSON array of product objects.

3. **Read Product by ID**  
   - **Endpoint:** `GET /api/products/{id}`  
   - **Function:** Retrieve a single product by its unique identifier.  
   - **Response:** A JSON object representing the product.

4. **Update Product**  
   - **Endpoint:** `PUT /api/products/{id}`  
   - **Function:** Update an existing product's details.  
   - **Request Body Example (Only the fields to be updated):**
     ```json
     {
       "price": 24.99,
       "quantity": 150
     }
     ```
   - **Response:** The updated product details.

5. **Delete Product**  
   - **Endpoint:** `DELETE /api/products/{id}`  
   - **Function:** Remove a product from the database.  
   - **Response:** A confirmation message indicating successful deletion.

---

## 5. Implementation Guidelines

1. **Project Setup**  
   - Use the latest version of Spring Boot.  
   - Configure the project using Maven or Gradle.  
   - Ensure MongoDB is installed and properly configured on your machine or accessible via a cloud service.  
   - Follow standard coding practices and project structure conventions.

2. **Exception Handling & Validation**  
   - Implement proper exception handling to capture scenarios such as missing products or invalid data.  
   - Validate input data for creating and updating products.

3. **Testing**  
   - Write unit tests for the service and controller layers.  
   - Include integration tests to ensure the end-to-end functionality of your API.

---

## 6. Demonstration Requirements

1. **Postman API Testing**  
   - Prepare a Postman collection that includes requests for all the endpoints.  
   - Demonstrate:
     - Creating a new product.  
     - Retrieving all products.  
     - Fetching a product by its ID.  
     - Updating product details.  
     - Deleting a product.  
   - Include screenshots or a video demo in your project report to showcase your API in action.

2. **MongoDB Verification**  
   - Use MongoDB Compass or the MongoDB shell to display the product collection.  
   - Show how data is being stored, updated, and deleted in the database.  
   - Include screenshots in your documentation to verify that your API interacts with MongoDB as expected.

---

## 7. Project Documentation(Do this documentation in Readme File in github)

Your final submission should include:

1. **Source Code**  
   - All code files and a README with setup instructions.

2. **Postman Collection**  
   - Exported Postman collection or a detailed list of API requests.

3. **Demo Screenshots/Video**  
   - Evidence of API testing in Postman and MongoDB data verification.

4. **Project Report**  
   - A document detailing:
     - Project overview and objectives.  
     - Explanation of the product data model and API endpoints.  
     - Implementation details and any additional features.  
     - Testing strategy and demo instructions.  
     - Challenges faced and how you addressed them.
 

---

## 8. Marking Scheme

Your submission will be evaluated out of **100 marks** based on the following criteria:

| **Criteria**                     | **Marks** |
|----------------------------------|----------:|
| **Code or GitHub**               |       35  |
| **Video without access**         |        5  |
| **Video with access**            |        5  |
| **Video with output**            |       10  |
| **Video with audio**             |        5  |
| **Design**                       |       10  |
| **Explanation of code & output** |       20  |
| **Overall rating**               |       10  |
| **Total**                        | **100**   |

1. **Code or GitHub (35 Marks)**  
   - Well-structured code with proper naming conventions.  
   - Clear project structure, following Spring Boot best practices.  
   - Proper use of Git or GitHub for version control.

2. **Video Demonstrations (25 Marks Total)**  
   - **Video without access (5 Marks)**  
   - **Video with access (5 Marks)**  
   - **Video with output (10 Marks)**  
   - **Video with audio (5 Marks)**
   > Demonstrate how to run the application, show the Postman requests, and confirm that data is correctly stored in MongoDB.

3. **Design (10 Marks)**  
   - Clarity of design, including consistent naming of endpoints, model attributes, and code readability.

4. **Explanation of Code & Output (20 Marks)**  
   - Clear and concise explanation of how the code works.  
   - Ability to interpret and explain the output from the API endpoints.

5. **Overall Rating (10 Marks)**  
   - Overall quality, completeness, and professionalism of your submission.

---

## 9. Submission Deadlines & Phases

Please note the **start dates**, **end dates**, and **marks** for each phase. Submit your work within the specified phase to secure the corresponding marks:

1. **Phase 1 – 100 Marks**  
   - **Opens:** Sunday, March 09, 2025, 9:00 AM  
   - **Closes:** Wednesday, March 12, 2025, 12:00 AM  

2. **Phase 2 – 90 Marks**  
   - **Opens:** Wednesday, March 12, 2025, 9:00 AM  
   - **Closes:** Thursday, March 13, 2025, 12:00 AM  

3. **Phase 3 – 70 Marks**  
   - **Opens:** Friday, March 14, 2025, 9:00 AM  
   - **Closes:** Saturday, March 15, 2025, 12:00 AM  

4. **Phase 4 – 50 Marks**  
   - **Opens:** Saturday, March 15, 2025, 4:00 PM  
   - **Closes:** Sunday, March 16, 2025, 11:59 PM  

> **Important:** Submissions made after the final deadline will not be accepted unless you have prior approval.

---

## 10. Final Notes

- Ensure your application runs smoothly and consistently before submission.  
- Provide clear documentation to help the evaluator set up and test your project.  
- If you have any questions or face any issues, feel free to reach out before the deadline.

---

**Good luck, and happy coding!**

**Best Regards,**  
*(Paindla Narendar Reddy)*  
*(MERN STACK)*

---

github [github](https://www.youtube.com/watch?v=zXudHfNGwzg)

[Springboot+MongoDb Configuration Video](https://www.youtube.com/watch?v=pmi_YCmCToU)
[project overview](https://latestnewreactfoodapp.bytexl.live/)


