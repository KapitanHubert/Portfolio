# Test Plan: Kapusta Application Manual Testing

## 1. Objectives
The main goal of this testing is to verify the core functionalities of the Kapusta application, ensure that all key features work as expected, and identify potential issues or bugs.

---

## 2. Scope of Testing
### Features to Test:
1. **Login and Registration:**
   - User authentication via email and Google account.
   - Validation for email and password inputs.

2. **Main Page (Transactions):**
   - Adding, editing, and deleting transactions.
   - Validation for transaction details (date, description, category, amount).
   - Automatic calculation of account balance.

3. **Reports Page:**
   - Displaying summaries of income and expenses.
   - Navigation between months.
   - Sorting data by category.

4. **Responsive Design:**
   - Ensuring usability on desktop, tablet, and mobile devices.

### Exclusions:
- Backend performance testing.
- Advanced security testing (beyond field validations).

---

## 3. Test Environment
- **URL:** [https://kapusta-qa.netlify.app/](https://kapusta-qa.netlify.app/)
- **Browsers:** 
  - Google Chrome (latest version)
  - Mozilla Firefox (latest version)
  - Opera (latest version)

---

## 5. Test Reporting
- **Test Cases:** Stored in the `Test-Cases/` folder with detailed steps, preconditions, and expected results.
- **Bug Reports:** Stored in the `Bugs/` folder, including reproduction steps, expected vs. actual results, and screenshots.
- **Daily Progress:** Updates and new findings will be committed to the GitHub repository.

---

## 6. Risks and Mitigation
### Risks:
- Limited time may result in untested edge cases.
- Browser compatibility may vary for less commonly used configurations.

### Mitigation:
- Focus testing on the most critical functionalities and most-used browsers.
- Document untested areas for future testing.

---

## 7. Deliverables
- Test cases documented in the `Test-Cases/` folder.
- Bug reports documented in the `Bugs/` folder.
- Summary of findings and recommendations in the `README.md`.

---

## 8. Tools
- **JIRA:** For tracking test cases and bugs.
- **GitHub:** For managing documentation and progress.
- **Browsers:** Chrome, Firefox, and Opera for compatibility testing.


