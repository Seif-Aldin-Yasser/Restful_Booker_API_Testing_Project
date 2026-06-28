## 💻 Restful Booker - API Testing Project


## 🔗 Live Demo

<a href="https://restful-booker.herokuapp.com/apidoc/index.html">👉 Click Here to View </a>

---

## 📁 What's Included

- ✅ **Test Plan** – How testing is organized and managed  
- ✅ **Requirements** – API features to be tested  
- ✅ **Test Scenarios** – General test ideas grouped by feature  
- ✅ **Test Cases** – Step-by-step manual test instructions  
- ✅ **Bug Reports** – Issues found during testing  
- ✅ **Postman Collection** – For automated API testing  
- ✅ **Environment File** – Postman environment variables

All manual and automation documents are in Json format and Test-API-Report.html.

---

## ✅ What’s Tested

### Manual Testing

- 🔐 **Auth** – Create token for login  
- 🎫 **Booking** – Create, update, retrieve, and delete bookings
- 🧾 **Data validation** – For booking details
- ❌ **Negative scenarios**

### Automated Testing

- Test cases automated via **Postman** collection  
- Execute using **Newman** via command line
- Create API test scripts using **JavaScript**
- Generate detailed **HTML** API test reports

---

## ⚙️ Run Automation with Newman and Generate HTML Report

### Step 1: Install Newman

Make sure you have Node.js installed, then run:

```cmd
npm install -g newman
```

### Step 2: Install Newman-Reporter-Htmlextra

Make sure you have Newman installed, then run:

```cmd
npm install -g newman-reporter-htmlextra
```

### Step 3: Run Automation Tests

Make sure you have select collections and environment , then run:

```cmd
newman run collections.json -e environment.json
```

### Step 4: Generate HTML Report

Make sure you have select collections, environment and the path that you will export Test API Report.html to it, then run:

```cmd
newman run collections.json -e environment.json -r htmlextra --reporter-htmlextra export ./Test_API_Report/Test_API_Report.html
```
## 🧰 Tools Used
- Postman (API Testing)
- Newman (Command-Line Automation to Run Tests and Generate HTML API Test Reports)
- JavaScript (Programming Language for Create API Test Scripts)
