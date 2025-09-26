QA Machine Test Instructions
App Under Test: Seekmachines

1. Test Scenarios / Test Cases (Excel or Word)
Objective:
To evaluate your ability to write clear and structured test cases for real-world web applications.
Instructions:
    1. Explore seekmachines app and identify at least 3–4 main modules 
        ◦ Homepage
        ◦ Search
        ◦ Ads Listing 
        ◦ Reach the Seller
        ◦ Create Ads 
        ◦ Login & Register
    2. Prepare a Test Case document in Excel or Word with the following columns:
        ◦ Test Case ID
        ◦ Module / Feature
        ◦ Test Scenario
        ◦ Test Steps
        ◦ Test Data
        ◦ Expected Result
        ◦ Actual Result (leave blank, only fill if you execute)
        ◦ Status (Pass/Fail)
        ◦ Remarks
    3. Cover positive, negative, and edge cases (example: empty input, invalid data, long text).
    4. Write at least 10 test cases.

2. Bug Report (Excel or PDF)
Objective:
To assess your ability to identify and document defects in a structured way.
Instructions:
    1. While testing seekmachines app, if you find any bugs/defects, log them in a Bug Report.
    2. Prepare the Bug Report in Excel or PDF with the following fields:
        ◦ Bug ID
        ◦ Module / Feature
        ◦ Bug Title / Summary
        ◦ Steps to Reproduce
        ◦ Expected Result
        ◦ Actual Result
        ◦ Severity (Critical / Major / Minor)
        ◦ Priority (High / Medium / Low)
        ◦ Status (New/Open/Closed)
        ◦ Screenshot or Reference Link (if possible)
    3. Report minimum 3 valid bugs (if found).

3. API Testing – Postman Collection (If API Available)
Objective:
To test your basic skills in API validation using Postman.
Instructions:
    1. Please see available API endpoints on seekmachines app
        ◦ https://bigleap.tech/seek-api/api
    2. Create a Postman Collection with at least:
        ◦ One GET request (e.g., product listing / search).
                • Product listing 
          https://bigleap.tech/seek-api/api/home/get-machines
          Parameters:
            ▪ page → integer (for pagination)
                • Search
              https://bigleap.tech/seek-api/api/home/get-machines
              Parameters:
              page → integer (for pagination)
              keyword → string (search keyword for machines)
              
        ◦ One POST request (e.g., Login / Service form).
            ▪ Login
              https://bigleap.tech/seek-api/api/login
              Parameters : {"email": email, "password": password}
            ▪ Service 
              https://bigleap.tech/seek-api/api/home/post-requirement
              Parameters : {
  "category_id": 1,
  "company": "",
  "contact_name": "",
  "email": "",
  "product": "",
  "description": ".",
  "phone": "",
  "location": ""
}
        ◦ Add Assertions in Postman (e.g., check status code = 200, response contains a specific field).
    3. Export the Postman Collection (.json file).
    4. Submit it along with your test cases and bug report.

Final Deliverables to Submit
    1. Test Cases → Excel or Word file.
    2. Bug Report → Excel or PDF file.
    3. Postman Collection → .json file (if APIs available).

Time Limit: 2–3 hours
Submission Format: ZIP folder containing all required files.
