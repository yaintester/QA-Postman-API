# QA Postman API - Secondhand Project

This repository contains Postman collections and environments for API testing of the **Secondhand** application and website, as well as the HTML reports generated from those tests.


## File Descriptions

### 1. Postman Collections
- **APKSecondhand.postman_collection.json**  
  Contains API requests used in the mobile APK version of the Secondhand app for QA testing.

- **WebsiteSecondhand.postman_collection.json**  
  Contains API requests used in the website version of Secondhand.

### 2. Postman Environments
- **APKSecondhand.postman_environment.json**  
  Defines environment variables used during mobile APK API testing.

- **WebsiteSecondhand.postman_environment.json**  
  Defines environment variables used for website API testing.

### 3. Test Reports
- **hasil-report-apk.html**  
  HTML report generated after executing mobile APK API tests.

- **hasil-report-web.html**  
  HTML report generated after executing website API tests.

## How to Use

### 1. Import into Postman
- Open Postman.
- Click `Import` and select the appropriate collection and environment files:
  - For APK testing:  
    `APKSecondhand.postman_collection.json` and `APKSecondhand.postman_environment.json`
  - For Website testing:  
    `WebsiteSecondhand.postman_collection.json` and `WebsiteSecondhand.postman_environment.json`

### 2. Run the Collections
- Make sure the correct environment is selected.
- Click `Run` on the collection to start testing using the Collection Runner or Newman CLI.

### 3. View Test Reports
- After running the tests, reports can be viewed in:
  - `hasil-report-apk.html` for APK API tests
  - `hasil-report-web.html` for Website API tests

## Tools Used
- [Postman](https://www.postman.com/)
- [Newman](https://www.npmjs.com/package/newman) - CLI tool for running Postman collections
- [Postman HTML Reporter](https://github.com/aatishnn/postman-html-report) - for generating HTML reports


---

📌 *Make sure to configure all required environment variables correctly before running the tests.*
