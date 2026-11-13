# SQA TRAINEESHIP – DAY 06

## Testing Approaches

**Organization:** Alif Algorithm  
**Program:** SQA Traineeship  
**Day:** 06  
**Date:** 10 November 2026  
**Mode:** Remote  

## Topics Covered

- Static Testing
- Dynamic Testing
- Black-box Testing
- White-box Testing
- Grey-box Testing
- Scripted Testing
- Exploratory Testing
- Test Charters
- Requirement Review

## Part A – Requirement Review

Reviewed the registration requirement and identified unclear, missing, and untestable points.

### Main Problems Identified

- Strong password rules are not defined.
- Registration time is not measurable.
- Required user details are not specified.
- Confirmation method is unclear.
- Wrong information is not defined.
- Proper error message is not defined.
- Minimum age is not specified.
- System speed is not measurable.
- Supported devices are not specified.

Questions were prepared for the team to clarify these requirements.

## Part B – Test Charters

### Charter 01 – Cart and Checkout

**User:** `problem_user`

Explored the cart and checkout process to find functional, validation, and calculation issues.

### Charter 02 – Product Sorting and Product Pages

**User:** `visual_user`

Explored product sorting and product pages to find display, image, layout, and sorting issues.

## Part C – Exploratory Testing Sessions

### Session 01

**Charter:** CH-01  
**User:** problem_user  
**Duration:** 45 minutes

Tested:

- Products
- Cart
- Checkout
- Checkout information
- Order summary

### Session 02

**Charter:** CH-02  
**User:** visual_user  
**Duration:** 45 minutes

Tested:

- Product list
- Product images
- Product prices
- Sorting
- Product details
- Navigation

Screenshots were captured during the testing sessions.

## Part D – Testing Classification

| Testing Activity | Type | Approach |
|---|---|---|
| Requirement Review | Static | Black-box |
| Feature Inventory | Dynamic | Black-box |
| Mobile Testing | Dynamic | Black-box |
| Login Testing | Dynamic | Black-box |
| Exploratory Testing | Dynamic | Black-box |

## Tools Used

- SauceDemo
- Microsoft Excel
- Browser
- Screenshots
- GitHub

## Key Learnings

- Difference between static and dynamic testing
- Difference between black-box and white-box testing
- Requirement review
- Exploratory testing
- Test charters
- Time-boxed testing sessions

## Folder Structure

```text
day-06/
├── README.md
├── SQA_Day_06_Task.xlsx
└── screenshots/
    ├── Session-01/
    └── Session-02/
```

## Conclusion

Day 06 helped me understand different testing approaches and practice requirement review and exploratory testing using structured test charters.
