# SpiceJet_POM_Project
Automated MakeMyTrip flight search using Java, Selenium, Page Object Model (POM). Prints SpiceJet flight details.
# MakeMyTrip-SpiceJet Flight Automation

Automated test script for searching and extracting **SpiceJet flight details** from [MakeMyTrip](https://www.makemytrip.com/) using **Java**, **Selenium WebDriver**, **Page Object Model (POM)**

------------------------------------------------------------------------------------------------------------------------------------------------------

## 🚀 **Project Goal**
Automate the following workflow:
1. Launch MakeMyTrip website
2. Select **Round Trip**
3. Enter **From** and **To** destinations
4. Choose **Departure** and **Return** dates
5. Enter **Passenger Details** and click **Search**
6. Extract and **Print SpiceJet flight details** from search results

------------------------------------------------------------------------------------------------------------------------------------------------------

## ⚡️ **Technologies Used**
- **Java 11**
- **Selenium WebDriver**
- **Page Object Model (POM)**
- **Page Factory**

## 🗂️ **Project Structure**
makemytrip-spicejet/
├─ src/main/java/com/makemytrip/pages/
│ └─ HomePage.java
│ └─ FlightSearchPage.java
├─ src/test/java/com/makemytrip/tests/
│ └─ SpiceJetFlightTest.java
├─ src/test/resources/testdata/
│ └─ flight_data.xlsx
├─ pom.xml
├─ .gitignore
├─ README.md


------------------------------------------------------------------------------------------------------------------------------------------------------

## ✅ **Key Features**
- Implements **POM** and **PageFactory** patterns
- Extracts and **prints SpiceJet flight details** from results
- Easily extensible for other airlines and platforms

------------------------------------------------------------------------------------------------------------------------------------------------------

## ⚙️ **How to Run the Project**
### 1️⃣ Clone the repository:
```bash
git clone https://github.com/<your-username>/makemytrip-spicejet.git
2️⃣ Install Dependencies
Make sure you have:
Java 11 or later
Maven 3.6+
Chrome browser
ChromeDriver (or use WebDriverManager)

3️⃣ Run Tests
bash
Copy
Edit
mvn clean test

4️⃣ View Results
The test will print SpiceJet flight details in the console.


