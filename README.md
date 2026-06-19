# **Mobile App Automation Test**

1. Download app-home-test-mobile.apk from here:
👉 **[Go to Release Page to Download](https://github.com/automationapptest/home-test-mobile/releases/tag/v1.0.0)**

2. ⚠️ **Important Setup Requirement:** You **must** download this APK to your local machine. Configure your Appium capabilities to point to your local file path (e.g., `app: "./app-home-test-mobile.apk"`). Do not point the Appium server directly to the GitHub remote URL.

3. Create in your personal github a public repository (name it for instance home-test-mobile).

4. Code requested exercises, commit and push your code and send the repository link according to the instructions given by the recruiter who contacted you.

5. Forking this repository is forbidden.

### General requisites for submission

 a. **Programming languages**
    - Java
    - Kotlin

 b. **Drivers**
    - Appium

 c. **Platforms**
    - Android.

### General test requisites
- All tests should run successfully either from IDE or command line.
- Instructions to build and run the code and tests submitted must be provided.
- The app login dummy email is johndoe@email.com and the password is 123.
  
### 🎯 Scenario-Based Challenge

You are required to automate the following core business requirements. The architectural design, framework structure, locator strategies, and implementation details are entirely up to your professional judgment. 

#### Scenario 1 - User Authentication (Happy Path)
* **Goal:** Verify successful user login.
* **Business Requirement:** Log into the application using a valid user profile. Assert that the application successfully authenticates the credentials and seamlessly transitions the user to the main Art Gallery catalog view.
* *(Note: You may use these credentials for this scenario,  `johndoe@email.com` / `123`)*

#### Scenario 2 - Input Validation (Error Handling)
* **Goal:** Verify application security and user feedback.
* **Business Requirement:** Attempt to log into the application using missing inputs (empty fields) or invalid credentials. Assert that the application properly blocks access and displays the corresponding error popup or native validation alert to the user.

#### Scenario 3 - Catalog Exploration (Native Interaction)
* **Goal:** Verify feed browsing and content consistency.
* **Business Requirement:** From the main Art Gallery feed, navigate down the scrollable list of items to locate a specific art piece situated deep in the catalog (e.g., "The Starry Night"). Select the item or verify its presence and details on the screen.

---

### 🎁 Bonus Challenge (Optional)

If you wish to showcase advanced framework capabilities or mobile engineering experience, implement the following scenario:

#### Scenario 4 - User Registration Flow
* **Goal:** Verify the account creation path.
* **Business Requirement:** Navigate to the registration screen from the login view. Complete the sign-up form fields—including interacting with the selection components—and verify that the user can successfully reach the registration success screen.



<img width="628" height="1316" alt="image" src="https://github.com/user-attachments/assets/65f972c7-4914-4d7b-b276-b3cf682e9da0" />

      
     
