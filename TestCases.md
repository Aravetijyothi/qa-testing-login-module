# Test Cases

## TC01 - Valid Login
| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Enter valid username | Accepted |
| 2 | Enter valid password | Accepted |
| 3 | Click login | Login successful |

---

## TC02 - Invalid Password
| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Enter valid username | Accepted |
| 2 | Enter wrong password | Error |
| 3 | Click login | Error message |

---

## TC03 - Empty Fields
| Step | Action | Expected Result |
|------|--------|----------------|
| 1 | Leave fields empty | Not allowed |
| 2 | Click login | Validation message |
