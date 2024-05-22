## Use Case 1: Home Page

**Description:** Users should be able to access The Movie Catalog App from its designated URL via the Internet, which should load the Landing page / Home page, appropriate to the user's logged-in status (unregistered/non-logged or registered/logged).

### HP-01
**Prequisites:** 
1. The internet connection is stable.
2. The user's device works properly.
3. User is not logged in.

**Title/Description:** Verify if The Movie Catalog Map is accessible from its designed URL.

**Steps:**
1. Open the application URL.

**Expected result:** The Landing page / Home page is displayed with the navigation menu, on the left-hand side, containing buttons for ABOUT US, OUR SERVICES, LOGIN, REGISTER, and COPYRIGHTS.

**Pass / Fail:** Pass

**Comments:** None

### HP-02
**Prequisites:** 
1. The internet connection is stable.
2. The user's device works properly.
3. The Landing page of the app is loaded.
4. User is not logged in.

**Title/Description:** Verify if the Landing page is scrollable.

**Steps:**
1. Scroll down to the "COPYRIGHTS" section of the Landing Page.
2. Scroll down back to the "ABOUT US" section.
3. Slowly scroll down to each section of the Landing page.

**Expected result:** Users should be able to navigate to different sections by scrolling. The Landing Page smoothly scrolls to the next section, and the relevant content is displayed.

**Pass / Fail:** Pass

**Comments:** None

### HP-03
**Prequisites:** 
1. The internet connection is stable.
2. The user's device works properly.
3. The Landing page of the app is loaded.
4. User is not logged in.

**Title/Description:** Verify if the sidebar (navigation menu) buttons are clickable.

**Steps:**
1. Click on each navigation menu button.

**Expected result:** When clicking on the button, the Landing page / Home page displays the corresponding section.

**Pass / Fail:** Pass

**Comments:** None

### HP-04
**Prequisites:** 
1. The internet connection is stable.
2. The user's device works properly.
3. The Landing page of the app is loaded.
4. User is not logged in.

**Title/Description:** Check the "ABOUT US" section.

**Steps:**
1. Check if the "ABOUT US" section exists.
2. Check if it's the first section in the navigation menu.
3. Click on the "ABOUT US" button.
4. Check if it shows a brief introduction of the Movie Catalog App as per the design, provided in documentation.

**Expected result:** The "ABOUT US" section should be the first section in the navigation menu. It welcomes the user and provides a brief introduction to what users can expect from Movie Catalog, emphasizing the ease of managing a personal movie collection.

**Pass / Fail:** Pass

**Comments:** None

### HP-05
**Prequisites:** 
1. The internet connection is stable.
2. The user's device works properly.
3. The Landing page of the app is loaded.
4. User is not logged in.

**Title/Description:** Check the "OUR SERVICES" section.

**Steps:**
1. Check if the "OUR SERVICES" section exists.
2. Check if it's the second section in the navigation menu.
3. Click on the corresponding button.
4. Check if it presents the main features offered by the website through a combination of icons and descriptive text as per the design provided in the SRS.

**Expected result:** The "OUR SERVICES" is the second section in the navigation menu. It presents the main features offered by the website through a combination of icons and descriptive text as per the design provided in the SRS.

**Pass / Fail:** Pass

**Comments:** None

### HP-06
**Prequisites:** 
1. The internet connection is stable.
2. The user's device works properly.
3. The Landing page of the app is loaded.
4. User is not logged in.

**Title/Description:** Check the "LOGIN" section.

**Steps:**
1. Check if the "LOGIN" section exists.
2. Check if it's the third section in the navigation menu.
3. Click on the "LOGIN" button.
4. Check if it includes a direct link to the login page as per the design provided in SRS.

**Expected result:** The "LOGIN" page is the third section in the Navbar. It welcomes returning users and encourages them to access their personalized movie catalog by logging in. The section includes a direct link to the login page.

**Pass / Fail:** Pass

**Comments:** None

### HP-07
**Prequisites:** 
1. The internet connection is stable.
2. The user's device works properly.
3. The Landing page of the app is loaded.
4. User is not logged in.

**Title/Description:** Check the "REGISTER NOW" section.

**Steps:**
1. Check if the "REGISTER NOW" section exists.
2. Check if it's the 4th section in the navigation menu.
3. Click on the "REGISTER" button.
4. Check if it invites new users to join Movie Catalog as per the design provided in the SRS.
5. Check if the section emphasizes the exclusive features available upon registration and provides a quick link to the register process.

**Expected result:** The "REGISTER NOW" is accessible by clicking on the "Register" button on the Navbar. It invites new users to join Movie Catalog. It also emphasizes the exclusive features available upon registration and provides a quick link to the register process.

**Pass / Fail:** Pass

**Comments:** None

### HP-08
**Prequisites:** 
1. The internet connection is stable.
2. The user's device works properly.
3. The Landing page of the app is loaded.
4. User is not logged in.

**Title/Description:** Check the "COPYRIGHTS" section.

**Steps:**
1. Check if the "COPYRIGHTS" section exists.
2. Check if it's the final section in the navigation menu.
3. Click on the "COPYRIGHTS" button.
4. Check if it delineates the legal protections of the content and the terms and conditions for the Movie Catalog.
5. Click on the anchor tag "Terms & Conditions" to check if it redirects to the Terms of Service page.

**Expected result:** The "COPYRIGHTS" section is the final section in the Navbar menu, delineating the legal protections of the content and the terms and conditions for the Movie Catalog.

**Pass / Fail:** Fail

**Comments:** Please check BUG ID - 1

---

## Use Case 2: User Registration

**Description:** Unregistered users should be able to successfully go through the Register process. This involves the utilization of fields such as First Name, Last Name, Username, Email, Password and Repeat Password, all subject to their respective constraints and character type acceptance.

### RF-01
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The "REGISTER NOW" section is loaded.
4. User is not logged in.

**Title/Description:** Check if the "Register now" button redirects to the Register form.

**Steps:**
1. Click on the "Register now" button.
2. Check if it redirects to the Register form.

**Expected result:** When clicking on the "Register now" button, it redirects users to the Register form.

**Pass / Fail:** Pass

**Comments:** None

### RF-02
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The application is loaded.
4. User has already clicked on the "Register now" button in the relevant section and it redirected them to the register form.
5. User is not logged in.

**Title/Description:** Check if the Register form is designed properly as per SRS.

**Steps:**
1. Check if the register form contains all fields as described in the SRS.

**Expected result:** The register form should contain the following fields ordered:
- First Name
- Last Name
- Username
- Email
- Password
- Repeat password

The form also includes a Register button to submit the form. Below the registration form is a quick link for existing members: "Already have an Account? Login here.", that redirects to the login page.

**Pass / Fail:** Fail

**Comments:** BUG ID-02

### RF-03
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The application is loaded.
4. User has already clicked on the "Register now" button in the relevant section and it redirected them to the register form.
5. User is not logged in.

**Title/Description:** Verify if user is able to register with valid credentials.

**Steps:**
1. Enter for First Name: Amy.
2. Enter for Last Name: Doe.
3. Enter for Username: amydoe145.
4. Enter Email: amydoe@example.com.
5. Enter Password: Test12345.
6. Repeat Password: Test12345.
7. Click on the "Register" button.

**Expected result:** Successful registration, user redirected to login screen.

**Pass / Fail:** Pass

**Comments:** As per BUG ID-02, the "Login" button appears instead of "Register", however I have managed to create an account using valid credentials. It seems that the button works, however its name should be changed to "Register".

### RF-04
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The application is loaded.
4. User has already clicked on the "Register now" button in the relevant section and it redirected them to the register form.
5. User is not logged in.

**Title/Description:** Verify if user is able to register with empty credentials.

**Steps:**
1. Leave all fields in the register form empty.
2. Click on the "Register" button.

**Expected result:** The registration should fail.

**Pass / Fail:** Pass

**Comments:** Refer to the comment in RF-03 for more info.

### RF-05
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The application is loaded.
4. User has already clicked on the "Register now" button in the relevant section and it redirected them to the register form.
5. User is not logged in.

**Title/Description:** Verify if user is able to register with invalid (shorter) username.

**Steps:**
1. Input:
   - First Name: Sarah
   - Last Name: Brown
   - Username: abc
   - Email: sarah@example.com
   - Password: Test1234
   - Repeat Password: Test1234

**Expected result:** Registration fails, error message indicates username is too short.

**Pass / Fail:** Pass

**Comments:** None

### RF-06
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The application is loaded.
4. User has already clicked on the "Register now" button in the relevant section and it redirected them to the register form.
5. User is not logged in.

**Title/Description:** Verify if user is able to register with invalid (shorter) password.

**Steps:**
1. Enter for First Name: Amy.
2. Enter for Last Name: Doe.
3. Enter for Username: amydoe145.
4. Enter Email: amydoe@example.com.
5. Enter Password: T.
6. Repeat Password: T.
7. Click on the "Register" button.

**Expected result:** Registration fails, error message indicates password is too short.

**Pass / Fail:** Pass

**Comments:** None

---

## Use Case 3: User Login

**Description:** Registered users should be able to successfully go through the Login process. They should be able to log in using  Email and Password. Users also should be able to recover their password via Forgot Password functionality.

### LF-01
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The "LOGIN" section of the app is loaded.
4. User is not logged in.

**Title/Description:** Check if the "Login here" button redirects to the login page.

**Steps:**
1. Click on the "Login here" button.
2. Check if it redirects to the login page.

**Expected result:** When clicking on the "Login here" button, it redirects users to the Login page.

**Pass / Fail:** Pass

**Comments:** None

### LF-02
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The "LOGIN" section of the application is loaded.
4. User is not logged in.

**Title/Description:** Check if the Login form is designed properly as per SRS.

**Steps:**
1. Click "Login here" button.
2. Check if the login form contains all fields as described in the SRS.

**Expected result:** The login form contains the following items:
- Email address
- Password
- "Forgot password" section that leads to the restore page.
- Link to the Register page with anchor text "Register here".
- Link to the 'Terms of use' and 'Privacy policy'.

**Pass / Fail:** Pass

**Comments:** None

### LF-03
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The login page of the application is loaded.
4. User is not logged in.

**Title/Description:** Check if the "Forgot password" link redirects to the restore page.

**Steps:**
1. Click on the "Forgot password?" anchor tag.

**Expected result:** The "Forgot password?" anchor tag redirects to the restore page.

**Pass / Fail:** Fail

**Comments:** BUG ID - 3

### LF-04
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The login page of the application is loaded.
4. User is not logged in.

**Title/Description:** Check if the "Terms of Use" link redirects to the relevant page.

**Steps:**
1. Click on the "Terms of Use" anchor

### LF-04
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The login page of the application is loaded.
4. User is not logged in.

**Title/Description:** Check if the "Terms of Use" link redirects to the relevant page.

**Steps:**
1. Click on the "Terms of Use" anchor text.

**Expected result:** The "Terms of Use" link redirects to the relevant page, showing Terms & Conditions.

**Pass / Fail:** Fail

**Comments:** BUG ID - 5

### LF-05
**Prequisites:**
1. The internet connection is stable.
2. The user's device works properly.
3. The login page of the application is loaded.
4. User is not logged in.

**Title/Description:** Check if the "Register here" link redirects to the relevant page.

**Steps:**
1. Click on the "Register here" link.

**Expected result:** The "Register here" link redirects to the register form.

**Pass / Fail:** Fail

**Comments:** BUG ID - 6

---

## Use Case 4: Profile Management

**Description:** Upon successful Login, logged users should be able to navigate to their Profile Info page, edit their profile details, and view their Movies count. This involves the changing of profile picture inserted via URL, and editing of user data fields including First Name, Last Name, Email and Username sections.

### PM-01
**Prequisites:**
1. The application is open.
2. User is logged in to the application.

**Title/Description:** Check if the profile info page is accessible.

**Steps:**
1. Click on the profile icon/picture on the Sidebar.

**Expected result:** The Profile Info page is accessible for logged users by clicking on the profile icon/picture on the Sidebar.

**Pass / Fail:** Pass

**Comments:** None

### PM-02
**Prequisites:**
1. The application is open.
2. User is logged in to the application.

**Title/Description:** Check if the "Edit" button redirects to the Edit profile page.

**Steps:**
1. Click on the profile icon/picture on the Sidebar.
2. Click on the "Edit" button.

**Expected result:** "Edit" button redirects to the Edit profile page as per the SRS.

**Pass / Fail:** Pass

**Comments:** None

### PM-03
**Prequisites:**
1. The application is open.
2. User is logged in to the application.

**Title/Description:** Check if changes are saved by clicking the Edit button.

**Steps:**
1. Click on the profile icon/picture on the Sidebar.
2. Click on the "Edit" button.
3. Edit information in the relevant field.
4. Click "Edit".

**Expected result:** Changes are saved by clicking the Edit button. "Profile is edited successfully!" notification appears.

**Pass / Fail:** Pass

**Comments:** None

### PM-04
**Prequisites:**
1. The application is open.
2. User is logged in to the application.

**Title/Description:** Check if the profile image can be added via its URL.

**Steps:**
1. Click on the profile icon/picture on the Sidebar.
2. Click on the "Edit" button.
3. Enter the valid URL of the image to the "Profile image" field.
4. Click "Edit".

**Expected result:** User is able to add Profile image (picture is not uploaded, but must be a valid URL of a picture, for example http://......jpg).

**Pass / Fail:** Pass

**Comments:** None

---

## Use Case 5: Adding Movies

**Description:** Logged users should be able to navigate to the Add Movie page, where they can add a new Movie with a Title, Description, Picture (URL), and an youtube link (URL). After the Movie is added, users should be redirected to All Movies page, where the newly added Movie should be present.

### AM-01
**Prequisites:**
1. The application is open.
2. User is logged in to the application.

**Title/Description:** Check if the "Add movie" section works.

**Steps:**
1. Click on the "Add movie" section in the sidebar of Movie Catalog.

**Expected result:** When users click on the Add Movie option, they're directed to a form where they can enter details about a new movie to add to their catalog.

**Pass / Fail:** Pass

**Comments:** None

### AM-02
**Prequisites:**
1. The application is open.
2. User is logged in to the application.

**Title/Description:** Check if the app does not allow adding a movie without a title.

**Steps:**
1. Click on the "Add movie" section in the sidebar of Movie Catalog.
2. Leave the title field empty.
3. Click "Add" button.

**Expected result:** The title and the description are required as per SRS. The user should not be able to add movies with an empty title.

**Pass / Fail:** Pass

**Comments:** None

### AM-03
**Prequisites:**
1. The application is open.
2. User is logged in to the application.

**Title/Description:** Check if the add movie function works with the title and description entered.

**Steps:**
1. Click on the "Add movie" section in the sidebar of Movie Catalog.
2. Enter a title.
3. Enter a description.
4. Click "Add" button.

**Expected result:** After the required Movie info is added, users should be redirected to the All Movies page, where the newly added Movie should be present.

**Pass / Fail:** Pass

**Comments:** None

---

## Use Case 6: Movies Management

**Description:** On All Movies Page, logged users should see all their Movies listed. Each Movie should have options for View Details, Edit, Delete, and an option to mark the movie as watched or unwatched depending on its current status. Watched Movies and Unwatched Movies pages should operate in a similar manner with the same options.

### MM-01
**Prequisites:**
1. The application is open.
2. User is logged in to the application.

**Description:** Check if the list of movies is displayed when clicking on the "All movies" section.

**Steps:**
1. Click on the "All movies" section.

**Expected result:** On the All Movies Page, logged users should see all their Movies listed.

**Pass / Fail:** Pass

**Comments:** None

### MM-02
**Prequisites:**
1. The application is open.
2. User is logged in to the application.

**Description:** Check if each movie has all options described in the SRS.

**Steps:**
1. Click on the "All movies" section.
2. Check the movie list.

**Expected result:** Each movie should have the following options:
- View details button
- Edit button
- Delete button
- Option to mark the movie as watched or unwatched depending on its current status

**Pass / Fail:** Pass

**Comments:** None

### MM-03
**Prequisites:**
1. The application is open.
2. User is logged in to the application.

**Description:** Check if the "View details" button works.

**Steps:**
1. Click on the "All movies" section.
2. Check the movie list.
3. Click the "View details" option.

**Expected result:** The "View details" option shows details of the current movie.

**Pass / Fail:** Fail

**Comments:** BUG ID - 04