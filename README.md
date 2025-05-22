<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Finals Lab Task 5</title>
  <style>
    /* Glowing Blue Background */
    body {
      background: linear-gradient(135deg, #00bfff, #1e90ff);
      background-size: 400% 400%;
      animation: gradientShift 10s ease infinite;
      color: #fff;
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Button Styling */
    .btn {
      display: inline-block;
      padding: 12px 30px;
      background-color: #1e90ff;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      font-size: 1.2em;
      font-weight: bold;
      box-shadow: 0 0 15px rgba(30, 144, 255, 0.6);
      transition: all 0.3s ease;
    }

    /* Button Hover Effect */
    .btn:hover {
      background-color: #00bfff;
      box-shadow: 0 0 25px rgba(30, 144, 255, 0.8);
      transform: scale(1.05);
    }

    /* Glowing Gradient Animation */
    @keyframes gradientShift {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }

    /* Content Styling */
    .content {
      text-align: center;
      padding: 50px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.2em;
      margin-bottom: 40px;
    }
  </style>
</head>
<body>

  <div class="content">
    <h1>Finals Lab Task 5</h1>
    <p>Views, Stored Procedures, and Functions in MySQL</p>

### 1 **Setup MySQL Workbench:**
- Open XAMPP and start the MySQL server.
- Connect MySQL Workbench to the server.
- Execute practice queries using the democodes.sql file.
### **2 Use Inventory Database:**
- Open the inventory.sql file to begin the tasks.
### **3 reate Views:**
- View to display vendor info and products with in-date from 2002 onward.
- View for products priced between 100–150.
- View to compute total price for products sold by specific vendors.
### **4 Create Stored Procedure:**
- Procedure to update vendor name from 'Bryson, Inc.' to 'Bryson and Co'.
### **5 Create Function:**
- Function that takes vendor code and state to display product details.
### **6 Execute and Document:**
- Run the SQL and capture screenshots of commands and results.
### Sample output
![Image](https://github.com/user-attachments/assets/46f1d0db-abfd-486b-88f8-c0e8dd3ec15d)
![Image](https://github.com/user-attachments/assets/f549dbe1-afe5-498a-8edc-f016529cc559)

    <a href="https://chan-edm.github.io/README/" class="btn">Back to Portfolio</a>
    <a href="https://chan-edm.github.io/Final-Lab-Task-6/" class="btn">Continue to Learn</a>
  </div>

</body>
</html>
