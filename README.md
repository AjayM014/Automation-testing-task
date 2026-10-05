# Selenium Automation Tests

Three Selenium test scripts in Python, each printing TEST PASSED or TEST FAILED.

## Tests

| File | What it tests |
|------|---------------|
| flipkart_otp_test.py | Flipkart mobile number login with OTP verification |
| login_test.py | Username and password login with success check |
| search_surya.py | Searching for the actor Surya and verifying results |

## Tech stack
- Python 3
- Selenium WebDriver
- Chrome
- ADB (optional, to read OTP SMS from an Android phone)

## Setup
    python -m pip install -r requirements.txt

## Run
    py flipkart_otp_test.py
    py login_test.py
    py search_surya.py

## Flipkart OTP test
- Number is entered automatically
- OTP is read from a USB-connected Android phone via ADB, or typed in the terminal if no phone is connected

## Limitations
- Flipkart may show a CAPTCHA or block automated browsers
- Locators may need updating when sites change
