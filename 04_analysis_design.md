# Test Analysis and Design

## 4.3. White-Box Test Techniques
* Statement testing
  * 100% - all executable statements in the code have been exercised at least once
  * 100% coverage != 100% branch coverage
* Branch testing/Branch coverage
  * 100% all branches in the code, unconditional and conditional, are exercised by test cases
  * 100% branch coverage -> 100% statement coverage

### 4.3.3. The Value of White-box Testing
* entire software implementation is taken into account during testing
* defect detection even for vague requirements
* Can be used in static testing
  * dry runs of code
  * code review
* Weaknesses
  * May not detect defect in non implemented requirements

## 4.4 Experience-based Test Techniques
* Error guessing
  * How the application has worked in the past
  * Defects from common dev mistakes
  * Failures in other, similar applications
* Exploratory Testing
* Checklist based testing
