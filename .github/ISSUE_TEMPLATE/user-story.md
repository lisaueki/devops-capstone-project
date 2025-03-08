```markdown
**As a** site administrator  
**I need** to update customer information  
**So that** I can keep customer records up to date  

### **Details and Assumptions**
- Customer information includes "Name," "Address," and "Email."
- Only authenticated administrators can update customer details.

### **Acceptance Criteria**  
```gherkin
Given the user is logged in as an administrator  
When they edit customer details and click "Save"  
Then the updated information is stored in the database  
