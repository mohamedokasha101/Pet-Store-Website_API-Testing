# 🐾 Petstore Website API Testing Project

This repository contains a complete API testing project for the **Swagger Petstore** sample API using **Postman**.

It includes automated tests, manual test cases, bug reports, and a well-structured test suite focusing on the **Pet module**.

---

## 🚀 Project Overview

- ✅ Built using **Postman** and **JavaScript test scripts**
- ✅ Covers **6 core Pet endpoints**
- ✅ Includes **functional**, **negative**, and **UX** test cases
- ✅ Full test documentation in Excel
- ✅ Bug report with screenshots and classifications

---

## 📁 Folder Structure

| Folder            | Description                                    |
|-------------------|------------------------------------------------|
| `postman/`         | Postman collection and environment file       |
| `test-docs/`       | Test case sheet, bug report, and screenshots  |
| `sample-files/`    | Test data files ( for upload endpoint)   |

---

## 🧪 Tested Endpoints

| Method | Endpoint                             | Description                        |
|--------|--------------------------------------|------------------------------------|
| POST   | `/pet`                               | Add a new pet                      |
| GET    | `/pet/{petId}`                       | Retrieve pet by ID                 |
| PUT    | `/pet`                               | Update an existing pet             |
| DELETE | `/pet/{petId}`                       | Delete pet by ID                   |
| GET    | `/pet/findByStatus`                  | Find pets by status                |
| POST   | `/pet/{petId}` (form-data update)    | Update pet using form data         |
| POST   | `/pet/{petId}/uploadImage`           | Upload image for a pet             |

---

## 📊 Test Coverage

- 🔹 **90 Manual Test Cases**
- 🔹 **35 Bugs Reported**
- 🔹 Automated assertions using Postman’s `pm` test framework
- 🔹 Covers positive, negative, and edge scenarios

---

## 🐞 Sample Bugs Reported

| Bug ID        | Description                            | Severity  |
|---------------|----------------------------------------|-----------|
| BUG-PUT-001   | Allows update without `id`             | Major     |
| BUG-PUT-002   | Accepts invalid `status` value         | Medium    |
| BUG-DEL-001   | Accepts non-numeric pet ID             | Medium    |
| BUG-GET-001   | Status param is case-sensitive         | UX Issue  |

> Full details in `/test-docs/PetModule_BugReport.xlsx`

---

## 🛠️ How to Use

### ▶️ Import into Postman
1. Open Postman
2. Import `postman/Swagger Petstore - Pet Module.postman_collection.json`
3. Import `postman/Petstore_Environment.postman_environment.json`
4. Run tests from each request tab or via Collection Runner

### 📂 Open Test Documentation
- `PetModule_TestCases.xlsx` – all manual test cases with detailed steps
- `PetModule_BugReport.xlsx` – tracked issues from actual API behavior

---

## 📌 Tech Stack

- 🧪 Postman
- 📄 Excel
- 🐞 Manual + Automated Testing
- 🔍 Swagger Petstore API

---

## 📣 Author

**Muhammad Okasha**  
🧪 Manual & Automation Tester  
📧 okasha.mohamed101@gmail.com

---

## ⭐ Bonus Ideas (For Portfolio Polish)

- ✅ Add badges (Postman, Testing, API Testing,Java Scripts)
- ✅ Include GIF or video of collection runner in action
- ✅ Add test execution summary (pass/fail chart)



