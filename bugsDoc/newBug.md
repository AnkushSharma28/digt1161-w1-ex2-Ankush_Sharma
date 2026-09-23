# Bug Report: Login Page Authentication Error

## 1. Description
Users receive an "Unhandled Server Error (500)" message when attempting to log in with valid credentials on the main portal.

## 2. Steps to Reproduce
1. Navigate to the login page (`/login`).
2. Enter valid user credentials (email and password).
3. Click the **Submit** button.
4. Observe the page error response.

## 3. Expected Behavior
The user should be authenticated successfully and redirected to their account dashboard.

## 4. Actual Behavior
The page hangs for 5 seconds and displays a `500 Internal Server Error` banner.

## 5. Environment & System Details
- **Browser:** Google Chrome (v122)
- **OS:** Windows 11 / macOS Sonoma
- **Severity:** High (Blocks user login)