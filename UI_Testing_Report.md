# User Interface Testing – Detailed Report

This document contains a page-by-page analysis of UI and usability problems found in the **Bad UI Website** used in the Udemy "Manual Testing for Complete Beginners" course.

Each section includes:
- Screenshot placeholder 
- List of identified problems.
- Why it’s bad.
- Suggested fixes.

---

## **01 – Home Page**
![Homepage](images/01_Home_Page.png)

**Problems:**
- Green “No” button misleads users — green usually signals proceed, not cancel.
- “Click here” is underlined but not clickable.
- “here” is clickable but not styled like a link.
- Clicking “No” does not behave as expected for moving forward.

**Why it’s bad:**
- Breaks user expectations.
- Confusing for first-time visitors.
- Inconsistent design patterns.

**Fix suggestions:**
- Use red for negative actions.
- Ensure clickable links are styled consistently.
- Label buttons clearly according to their function.

---

## **02 – Cookies**
![Cookies](images/02_Cookies.png)

**Problems:**
- Question phrased negatively: “Is that a problem for you?” with “No” as the correct answer.

**Why it’s bad:**
- Users can misread and choose the wrong option.
- Adds unnecessary cognitive load.

**Fix suggestions:**
- Use direct, positive phrasing (e.g., “Do you accept cookies?”).
- Provide clear “Accept” and “Decline” buttons.

---

## **03 – Abnormal Box**
![Abnormal Box](images/03_Abnormal_Box.png)

**Problems:**
- Arrow points up but moves content up endlessly.
- Box moves out of reach with no restore option.
- “Send to bottom” button label is misleading.

**Why it’s bad:**
- Misleads users and traps them in broken navigation.
- Poor label wording confuses functionality.

**Fix suggestions:**
- Correct arrow direction.
- Keep controls accessible after moving content.
- Rename button to reflect actual action.

---

## **04 – Time Box**
![Time Box](images/04_Time_Box.png)

**Problems:**
- Pop-up covers screen unnecessarily.
- “Close” button disguised with stylized “C” and no pointer cursor.

**Why it’s bad:**
- Reduces discoverability of important actions.
- Wastes user time searching for close option.

**Fix suggestions:**
- Make close buttons clearly visible with standard icon or text.
- Use pointer cursor for clickable actions.

---

## **05 – Login Box**
![Login Box](images/05_Login_Box.png)

**Problems:**
- Placeholders remain in fields when typing.
- Overly complex password rules.
- Error messages appear in green, success in red.
- Confusing phrases like “Your password is not unsafe.”
- Terms scroll is too slow.
- Cancel button highlighted instead of Next.

**Why it’s bad:**
- Inconsistent color semantics.
- Adds friction to basic login.
- Breaks standard form conventions.

**Fix suggestions:**
- Clear placeholder on input.
- Simplify password requirements.
- Use green for success, red for errors.
- Highlight the primary action button.

---

## **06 – User Profile I**
![User Profile I](images/06_User_Profile_I.png)

**Problems:**
- “Upload photo” downloads an image instead.
- Uploaded image keeps loading.
- All interests pre-selected.
- “Select All” / “Unselect All” placed between items.

**Why it’s bad:**
- Breaks user expectations.
- Forces unnecessary actions.

**Fix suggestions:**
- Ensure upload buttons actually upload.
- Stop loading once upload is done.
- Place bulk selection controls in a separate location.

---

## **07 – User Profile II**
![User Profile II](images/07_User_Profile_II.png)

**Problems:**
- Placeholders don’t disappear when typing.
- Street number format restrictive.
- Age slider hard to use.
- Country selection only by flag.
- Clicking outside country selector doesn’t close it.

**Why it’s bad:**
- Poor form usability.
- Inefficient country search.

**Fix suggestions:**
- Use proper form inputs.
- Add text search for countries.
- Enable closing selectors by clicking outside.

---

## **08 – Personal Details**
![Personal Details](images/08_Personal_Details.png)

**Problems:**
- Date picker shows limited days, requires scrolling.
- Months not ordered properly.
- Years ordered ascending from 1900.
- Age and birth date both required (redundant).
- Gender and title mismatch logic reversed.
- Cancel button highlighted instead of Next.

**Why it’s bad:**
- Inconvenient date selection.
- Unnecessary duplication of inputs.
- Logic errors cause incorrect validation.

**Fix suggestions:**
- Use a proper date picker.
- Require only one of age or birth date.
- Fix validation logic.

---

## **09 – Country Selection**
![Country Selection](images/09_Country_Selection.png)

**Problems:**
- Flags only, no country names.
- Flags not highlighted on hover.
- No search option.
- List order not obvious.
- Picker stays open when clicking outside.

**Why it’s bad:**
- Slows down selection.
- Not accessible for users unfamiliar with flags.

**Fix suggestions:**
- Show country names alongside flags.
- Add search box.
- Close picker when clicking outside.

---

## **10 – Check If You Are Human**
![Check If You Are Human](images/10_Check_If_You_Are_Human.png)

**Problems:**
- Unclear checkbox alignment with images.
- Not all checkboxes visible without scrolling.
- Infinite loop when making incorrect selections.

**Why it’s bad:**
- Causes user frustration.
- Poor visual association between controls and content.

**Fix suggestions:**
- Align checkboxes clearly with related images.
- Ensure all options are visible at once.
- Provide clear feedback after selection.

---
