
# 📋 Test Report — Sprint 1 — Urban Routes

**Execution Date:** [Insert execution date]  
**Version:** [Insert tested version]  
**Tester:** [Your Name]  

---

## ✅ Test Execution Summary

| Total Test Cases | Passed | Failed | Success Rate |
|------------------|--------|--------|--------------|
| 24               | 13     | 11     | 54%          |

---

## 🧪 Test Case Results

| Test Case ID | Test Name | Status | Bug ID |
|--------------|-----------|--------|--------|
| CASE-1       | Map scrolling | Passed | - |
| CASE-2       | Map zoom in/out | Passed | - |
| CASE-3       | Area titles on map are not clickable | Passed | - |
| CASE-4       | City titles on map are not clickable | Passed | - |
| CASE-5       | "From" field can be selected | Failed | BR11 |
| CASE-6       | It is possible to search objects in "To" field | Failed | BR1 |
| CASE-7       | Address pin appears after filling "From" field | Failed | BR2 |
| CASE-8       | Address pin appears after filling "To" field | Failed | BR3 |
| CASE-9       | Address is removed after clearing "From" field | Failed | BR4 |
| CASE-10      | Address is removed after clearing "To" field | Failed | BR5 |
| CASE-11      | 3D objects are displayed | Failed | BR6 |
| CASE-12      | Fullscreen mode activation | Failed | BR7 |
| CASE-13      | Fullscreen mode deactivation | Passed | - |
| CASE-14      | Relief mode activation | Passed | - |
| CASE-15      | Satellite mode activation | Passed | - |
| CASE-16      | Building display on zoom-in | Passed | - |
| CASE-17      | Subway stations shown on zoom-in | Failed | BR8 |
| CASE-18      | Landmarks shown on zoom-in | Passed | - |
| CASE-19      | Parks displayed on zoom-in | Failed | BR9 |
| CASE-20      | Object information is displayed | Passed | - |
| CASE-21      | Object info is hidden when clicking the close button | Passed | - |
| CASE-22      | Street View mode activation | Passed | - |
| CASE-23      | Street View mode deactivation | Passed | - |
| CASE-24      | Clicking on app logo shows app information | Failed | BR10 |

---

## 🐞 Bug Report Summary

| Bug ID | Title | Priority | Status |
|--------|-------|----------|--------|
| BR1    | "subway" search in "To" field triggers 'Enter departure address' message | High | Open |
| BR2    | Map does not display location after filling "From" field | High | Open |
| BR3    | Map does not update when entering address in "To" field | High | Open |
| BR4    | Map pin remains after clearing "From" field | Medium | Open |
| BR5    | Map pin remains after clearing "To" field | Medium | Open |
| BR6    | LAX Airport does not show 3D view when zoomed in | Medium | Open |
| BR7    | "From" and "To" fields are not displayed in fullscreen mode | High | Open |
| BR8    | Subway station icon is not displayed on the map | Medium | Open |
| BR9    | Park icon not displayed — only name is shown | Medium | Open |
| BR10   | Clicking app logo does not show application information | High | Open |
| BR11   | "From" field appears pre-filled unexpectedly | Medium | Open |

---

## 💡 Final Analysis

During the functional tests for **Urban Routes Sprint 1**, 11 defects were identified, categorized as:

- 5 **High Priority**
- 6 **Medium Priority**

The system demonstrated good stability in basic navigation and layer switching (Relief, Satellite, Street View). However, recurring failures in the "From" and "To" fields, combined with missing map object icons, could severely impact user experience.

**Recommendation:** Address all high-priority issues before the next release to ensure a stable and reliable application for end users.
