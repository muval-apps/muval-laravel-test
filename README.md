# **Codebase Review Task Instructions**

## **Overview**
This task is designed to assess your ability to:
1. Identify issues in a Laravel codebase.
2. Provide detailed feedback on the problems.
3. Fix the issues and improve the codebase by following Laravel best practices.
4. Extend the functionality to support new requirements.

You are provided with a Laravel project that contains intentional flaws. Your objective is to review the code, document your findings, and implement fixes and new requirements.

## **What You Need to Do**

### **1. Identify Issues**
- Review the codebase thoroughly.
- Document any issues you find, including:
    - What is wrong.
    - Why it’s a problem.
    - How you would fix it.

### **2. Fix the Issues**
- Implement fixes for as many issues as possible within the allotted time.
- Refactor the codebase to follow Laravel best practices.
- Ensure your fixes address both functionality and maintainability.

### **3. Create API Endpoints**
- Turn the codebase into a set of API endpoints to manage tasks with Sanctum authentication.
- Add unit or feature tests for key functionality.

### **4. Test Your Changes**
- Test your fixes to ensure the application works as expected.
- Add unit or feature tests for key functionality.

### **5. Provide Deliverables**
Prepare the following deliverables:
1. **Issue Report (`report.md`)**  
   A detailed report of the issues you identified, why they are problematic, and how you fixed or would fix them. A breakdown of the changes you have made to meet the new API requirements.
2. **Refactored Codebase**  
   A Zip file containing your updated codebase.
3. **Tests**  
   Include unit or feature tests for code coverage in the Zip file.
3. **Upload**  
   Upload your Zip file to the TestDome question.

## **What to Look For**

### **Key Areas to Review**
1. **Security**
    - Are there any security vulnerabilities (e.g., SQL injection, missing CSRF protection)?
2. **Code Quality**
    - Is the code well-structured, reusable, and maintainable?
3. **Performance**
    - Are there performance bottlenecks (e.g., N+1 query issues)?
4. **Best Practices**
    - Does the code follow Laravel conventions and best practices?
5. **Testing**
    - Are there tests? If not, consider where they might be useful.
      
## **Technical Requirements**

### **Environment Setup**
1. Download the project.
2. Use the .env.example file to configure your .env file.

### **Project Features**
The application is a basic task management system with the following:
- **Task Management**: Create, view, and edit tasks.
- **User Assignment**: Each task is associated with a user.
- **API Endpoints**: Implement a set of API endpoints to manage tasks with Sanctum authentication.

## **Evaluation Criteria**
You will be evaluated on:

1. **Depth of Analysis**
    - Did you identify the key issues in the codebase?
    - Were your observations accurate and well-explained?
2. **Quality of Fixes**
    - Are the fixes aligned with Laravel best practices?
    - Did you refactor the codebase to follow Laravel best practices?
    - Is the code more secure, maintainable, and performant after your changes?
3. **API Implementation**
    - Did you implement the API endpoints correctly?
    - Are the endpoints secure and follow best practices?
    - Are the endpoints well-documented?
    - Is Sanctum properly configured for authentication?
4. **Code Readability**
   - Is the refactored code clean and easy to understand?
5. **Testing**
    - Did you add meaningful tests for key features or fixes?
    - Do the tests cover the codebase adequately?

## **Time Limit**
This task is estimated to take 4–5 hours.

--- 
If you have any questions or encounter issues during the task, feel free to reach out to nicole@muval.com.au. Good luck!
