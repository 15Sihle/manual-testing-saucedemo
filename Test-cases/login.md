# Login Test Cases – SauceDemo

## Test Data
| Username | Password |
|--------|----------|
| standard_user | secret_sauce |
| locked_out_user | secret_sauce |
| invalid_user | wrong_password |

---

## Login Test Cases

| Test Case ID | Test Scenario | Test Steps | Expected Result | Status |
|-------------|--------------|------------|-----------------|--------|
| TC_LOGIN_01 | Valid login | 1. Open SauceDemo<br>2. Enter valid username<br>3. Enter valid password<br>4. Click Login | User is logged in and redirected to Products page | Pass |
| TC_LOGIN_02 | Invalid password | 1. Open SauceDemo<br>2. Enter valid username<br>3. Enter invalid password<br>4. Click Login | Error message is displayed | Pass |
| TC_LOGIN_03 | Invalid username | 1. Open SauceDemo<br>2. Enter invalid username<br>3. Enter valid password<br>4. Click Login | Error message is displayed | Pass |
| TC_LOGIN_04 | Empty username and password | 1. Open SauceDemo<br>2. Leave username and password empty<br>3. Click Login | Error message is displayed | Pass |
| TC_LOGIN_05 | Locked out user | 1. Open SauceDemo<br>2. Enter locked out user credentials<br>3. Click Login | User is not allowed to log in and error message is shown | Pass |


