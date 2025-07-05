# 📱 Urban Lunch – Sprint 5: Mobile App Types

## ✅ Short Description

This project contains the **test cases and results** for the mobile app **Urban Lunch**, as part of **Sprint 5** in the TripleTen QA Bootcamp. It covers visual layout verification, ordering flow, user interaction, and error validation, with structured reporting for both **positive** and **negative** paths.

---

## 🧪 Test Checklist Summary

### 📍 Pickup Point Selection

| #   | Description                                        | Status | Bug Report                                                |
| --- | -------------------------------------------------- | ------ | --------------------------------------------------------- |
| 1.1 | The map displays all pickup points                 | ✅      | –                                                         |
| 1.2 | The map shows the pickup order                     | ❌      | [TRIP-31](https://gibranlog.atlassian.net/browse/TRIP-31) |
| 2   | No pickup point is selected by default             | ✅      | –                                                         |
| 3   | Tapping a point selects it                         | ✅      | –                                                         |
| 4   | Tapping the same point again cancels the selection | ✅      | –                                                         |
| 5   | Tapping another point changes the selection        | ✅      | –                                                         |
| 6   | Pickup point name appears in the footer            | ✅      | –                                                         |
| 7   | Dropdown shows available restaurants               | ✅      | –                                                         |
| 8   | Selecting a restaurant highlights it on the map    | ✅      | –                                                         |
| 9   | "Next" button is disabled without a pickup point   | ✅      | –                                                         |
| 10  | "Next" button enabled when a point is selected     | ✅      | –                                                         |
| 11  | "Next" navigates to dish selection screen          | ✅      | –                                                         |

### 🍽️ Dish Selection & Info

| #  | Description                                          | Status | Bug Report |
| -- | ---------------------------------------------------- | ------ | ---------- |
| 12 | Dish list shows name, price, +/- buttons             | ✅      | –          |
| 13 | Tapping outside the + opens dish detail page         | ✅      | –          |
| 14 | Tapping + adds item to the order                     | ✅      | –          |
| 15 | "Next" disabled when no dish is selected             | ✅      | –          |
| 16 | Progress updated to step 2                           | ✅      | –          |
| 17 | "Next" navigates to order confirmation               | ✅      | –          |
| 18 | Dish info page shows image, description, ingredients | ✅      | –          |
| 19 | Back arrow returns to dish list                      | ✅      | –          |
| 20 | Tapping restaurant name increases quantity by 1      | ✅      | –          |

### ✅ Order Confirmation

| #  | Description                          | Status | Bug Report                                                |
| -- | ------------------------------------ | ------ | --------------------------------------------------------- |
| 21 | Confirmation shows pickup name       | ✅      | –                                                         |
| 22 | Dish list with names and quantities  | ✅      | –                                                         |
| 23 | Screen scrolls with long dish list   | ✅      | –                                                         |
| 24 | Smooth scroll test                   | ❌      | [TRIP-36](https://gibranlog.atlassian.net/browse/TRIP-36) |
| 25 | "Order" button enabled if dish added | ✅      | –                                                         |
| 26 | "Order" proceeds to tracking         | ✅      | –                                                         |

### 🗺️ Order Tracking – Pickup Phase

| #  | Description                                | Status | Bug Report                                                |
| -- | ------------------------------------------ | ------ | --------------------------------------------------------- |
| 27 | Map shows pickup location                  | ❌      | [TRIP-32](https://gibranlog.atlassian.net/browse/TRIP-32) |
| 28 | Dish list with restaurants                 | ✅      | –                                                         |
| 29 | ETA and delivery time correct as per Figma | ❌      | [TRIP-34](https://gibranlog.atlassian.net/browse/TRIP-34) |
| 30 | Scrollable with long list                  | ❌      | [TRIP-35](https://gibranlog.atlassian.net/browse/TRIP-35) |
| 31 | Auto-transition when timer ends            | ✅      | –                                                         |

### 🏁 Order Delivered

| #    | Description                                  | Status | Bug Report                                                |
| ---- | -------------------------------------------- | ------ | --------------------------------------------------------- |
| 32   | "Order delivered" message shown              | ✅      | –                                                         |
| 33   | Pickup address displayed correctly           | ✅      | –                                                         |
| 34   | "Got it" button finalizes and shows feedback | ✅      | –                                                         |
| 35.1 | After clicking “Got it”, returns to start    | ❌      | [TRIP-29](https://gibranlog.atlassian.net/browse/TRIP-29) |
| 35.2 | Feedback icon triggers return to start       | ✅      | –                                                         |

### ⚠️ Error Handling & Edge Cases

| #  | Description                                   | Status | Bug Report                                                |
| -- | --------------------------------------------- | ------ | --------------------------------------------------------- |
| 36 | Error shown when location access is denied    | ✅      | –                                                         |
| 37 | Error shown when trying to order with no dish | ✅      | –                                                         |
| 38 | Cost calculated correctly                     | ❌      | [TRIP-33](https://gibranlog.atlassian.net/browse/TRIP-33) |
| 39 | Prices match official pricing table           | ❌      | [TRIP-26](https://gibranlog.atlassian.net/browse/TRIP-26) |
| 40 | Network switch (Wi-Fi ↔ Mobile) handled       | ❌      | [TRIP-27](https://gibranlog.atlassian.net/browse/TRIP-27) |
| 41 | Works in airplane mode                        | ✅      | –                                                         |
| 42 | Call interruption test                        | ✅      | –                                                         |
| 43 | Lock screen and resume test                   | ✅      | –                                                         |
| 44 | Low battery behavior                          | ✅      | –                                                         |
| 45 | App fails gracefully offline                  | ✅      | –                                                         |
| 46 | Permission handling after update              | ✅      | –                                                         |
| 47 | App update preserves data                     | ❌      | [TRIP-28](https://gibranlog.atlassian.net/browse/TRIP-28) |
| 48 | Screen rotation mid-order                     | ❌      | [TRIP-30](https://gibranlog.atlassian.net/browse/TRIP-30) |
| 49 | Restaurant name overflow issue                | ❌      | [TRIP-37](https://gibranlog.atlassian.net/browse/TRIP-37) |

---

## 📌 Documentation

* 💾 **Test Plan Spreadsheet**
  [Google Sheets – Urban Lunch Mobile Tests](https://docs.google.com/spreadsheets/d/1fOeHuOKkFWUSN_iipfXhLZn42mJNhS26uZzp6MRwR4Q/edit?usp=sharing)

* 🐞 **Bug Reports in Jira**
  [https://gibranlog.atlassian.net](https://gibranlog.atlassian.net)
