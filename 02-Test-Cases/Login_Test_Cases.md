# Login Page Test Cases

## TC-001

**Title:** Verify login with valid credentials

**Precondition:**
- User is already registered.
- Login page is accessible.

**Test Data:**
- Username: student
- Password: Password123

**Steps:**
1. Open Login page.
2. Enter valid username.
3. Enter valid password.
4. Click Login.

**Expected Result:**
User should be successfully logged in and redirected to Dashboard.

**Priority:** High

---

## TC-002

**Title:** Verify login with invalid password

**Precondition:**
- User account exists.

**Test Data:**
- Username: student
- Password: WrongPassword

**Steps:**
1. Open Login page.
2. Enter valid username.
3. Enter invalid password.
4. Click Login.

**Expected Result:**
Appropriate error message should be displayed and the user should remain on the Login page.

**Priority:** High

---

## TC-003

**Title:** Verify login with empty credentials

**Precondition:**
- Login page is accessible.

**Test Data:**
- Username: Blank
- Password: Blank

**Steps:**
1. Open Login page.
2. Leave both fields empty.
3. Click Login.

**Expected Result:**
Validation messages should indicate that Username and Password are required.

**Priority:** High
