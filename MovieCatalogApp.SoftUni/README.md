
# Movie Catalog Application Testing

This repository contains a testing project, developed as part of the regular exam task for "QA Fundamentals and Manual Testing" course in SoftUni.

## Overview
- [Software Requirements Specification (SRS)](#software-requirements-specification-srs)
- [Test Cases](#test-cases)
  - [Use Case 1: Home Page](#use-case-1-home-page)
  - [Use Case 2: User Registration](#use-case-2-user-registration)
  - [Use Case 3: User Login](#use-case-3-user-login)
  - [Use Case 4: Profile Management](#use-case-4-profile-management)
  - [Use Case 5: Adding Movies](#use-case-5-adding-movies)
  - [Use Case 6: Movies Management](#use-case-6-movies-management)
- [Bug Report](#bug-report)
- [Postman HTTP Requests File](#postman-http-requests-file)

## Software Requirements Specification (SRS) 

The SRS document for the Movie Catalog application is included in "Regular-Exam-MovieCatalog.docx" file, providing detailed information about the application's requirements and design. It also contains a detailed description of the regular exam's tasks.

## Test Cases

This section provides an overview of the test cases, organized by use cases and designed to ensure the main functionality and reliability of the Movie Catalog application.

### Use Case 1: Home Page

**Objective:** To verify the accessibility and functionality of the Home Page and its navigation elements.

**Test Cases:**
1. **HP-01:** Verify if The Movie Catalog Map is accessible from its designed URL.
2. **HP-02:** Verify if the Landing page is scrollable.
3. **HP-03:** Verify if the sidebar (navigation menu) buttons are clickable.
4. **HP-04:** Check the "ABOUT US" section.
5. **HP-05:** Check the "OUR SERVICES" section.
6. **HP-06:** Check the "LOGIN" section.
7. **HP-07:** Check the "REGISTER NOW" section.
8. **HP-08:** Check the "COPYRIGHTS" section.

**Summary:** These tests ensure that all sections of the home page are accessible and functional, providing a seamless navigation experience for users.

### Use Case 2: User Registration

**Objective:** To validate the user registration process, ensuring users can create accounts with valid information and receive appropriate feedback for invalid inputs.

**Test Cases:**
1. **RF-01:** Check if the "Register now" button redirects to the Register form.
2. **RF-02:** Check if the Register form is designed properly as per SRS.
3. **RF-03:** Verify if the user is able to register with valid credentials.
4. **RF-04:** Verify if the user is able to register with empty credentials.
5. **RF-05:** Verify if the user is able to register with an invalid (shorter) username.
6. **RF-06:** Verify if the user is able to register with an invalid (shorter) password.

**Summary:** These tests ensure that the registration form functions correctly, handling both valid and invalid inputs as expected.

### Use Case 3: User Login

**Objective:** To validate the login process, ensuring users can access their accounts and navigate to relevant pages.

**Test Cases:**
1. **LF-01:** Check if the "Login here" button redirects to the login page.
2. **LF-02:** Check if the Login form is designed properly as per SRS.
3. **LF-03:** Check if the "Forgot password" link redirects to the restore page.
4. **LF-04:** Check if the "Terms of Use" link redirects to the relevant page.
5. **LF-05:** Check if the "Register here" link redirects to the relevant page.

**Summary:** These tests verify the functionality of the login page and related links, ensuring users can access necessary features for account management.

### Use Case 4: Profile Management

**Objective:** To ensure users can view and edit their profile information effectively.

**Test Cases:**
1. **PM-01:** Check if the profile info page is accessible.
2. **PM-02:** Check if the "Edit" button redirects to the Edit profile page.
3. **PM-03:** Check if changes are saved by clicking the Edit button.
4. **PM-04:** Check if the profile image can be added via its URL.

**Summary:** These tests ensure users can access and update their profile information, including profile images, ensuring personalized user experiences.

### Use Case 5: Adding Movies

**Objective:** To verify the functionality of adding new movies to the user's catalog.

**Test Cases:**
1. **AM-01:** Check if the "Add movie" section works.
2. **AM-02:** Check if the app does not allow adding a movie without a title.
3. **AM-03:** Check if the add movie function works with title and description entered.

**Summary:** These tests ensure the add movie functionality works correctly, requiring necessary fields and redirecting users appropriately.

### Use Case 6: Movies Management

**Objective:** To verify the management of movies within the user's catalog.

**Test Cases:**
1. **MM-01:** Check if the list of movies is displayed when clicking on the "All movies" section.
2. **MM-02:** Check if each movie has all options described in the SRS.
3. **MM-03:** Check if the "View details" button works.

**Summary:** These tests ensure users can manage their movie catalog effectively, with options to view, edit, and delete movies.

## Bug Report

The project also contains a bug report document. The following bugs were identified during the testing process:

1. **BUG ID - 1:** The "COPYRIGHTS" section is not functioning as expected on the home page.
2. **BUG ID - 2:** The Register form is missing fields as described in the SRS.
3. **BUG ID - 3:** The "Forgot password" link does not redirect to the restore page.
4. **BUG ID - 4:** The "View details" button on the movie list does not work as expected.
5. **BUG ID - 5:** The "Terms of Use" link does not redirect to the relevant page.
6. **BUG ID - 6:** The "Register here" link does not redirect to the register form.

## Postman HTTP Requests File

The repository includes a Postman collection with HTTP requests for testing general endpoints of the application.

## Conclusion

The test cases cover a broad range of the application's functionality, ensuring a reliable and user-friendly experience.

They include both positive and negative scenarios to validate expected behavior and effectively handle invalid inputs.

Given the time constraints, it's important to note that this project mainly focuses on practicing functional testing methods. The key areas for enhancement can be the following:

- Adding more edge cases and negative test scenarios to elevate robustness of the software application.
- Including various UI/UX testing approaches (e.g., feedback messages, loading indicators) to ensure a good user experience.
- Enhancing security measures by validating secure login and ensuring data privacy.
