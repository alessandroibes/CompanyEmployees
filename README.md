<h1>CompanyEmployees</h1>
<p>Projeto desenvolvido durante a leitura do livro Ultimate ASP.NET Core 3 Web API.</p>

<h2>Table of Contents</h2>

<h3>1. PROJECT CONFIGURATION</h3>
<h4>1.1 Creating a New Project</h4>
<h4>1.2 launchSettings.json File Configuration</h4>
<h4>1.3 Program.cs and Startup.cs Explanations</h4>
<h4>1.4 Extension Methods and CORS Configuration</h4>
<h4>1.5 IIS Configuration</h4>
<h4>1.6 Additional Code in the Startup Class</h4>
<h4>1.7 Environment-Based Settings</h4>

<h3>2. CONFIGURING A LOGGING SERVICE</h3>
<h4>2.1 Creating the Required Projects</h4>
<h4>2.2 Creating the ILoggerManager Interface and Installing NLog</h4>
<h4>2.3 Implementing the Interface and Nlog.Config File</h4>
<h4>2.4 Configuring Logger Service for Logging Messages</h4>
<h4>2.5 DI, IoC, and Logger Service Testing</h4>

<h3>3. DATABASE MODEL AND REPOSITORY PATTERN</h3>
<h4>3.1 Creating Models</h4>
<h4>3.2 Context Class and the Database Connection</h4>
<h4>3.3 Migration and Initial Data Seed</h4>
<h4>3.4 Repository Pattern Logic</h4>
<h4>3.5 Repository User Interfaces and Classes</h4>
<h4>3.6 Creating a Repository Manager</h4>

<h3>4. HANDLING GET REQUESTS</h3>
<h4>4.1 Controllers and Routing in WEB API</h4>
<h4>4.2 Naming Our Resources</h4>
<h4>4.3 Getting All Companies From the Database</h4>
<h4>4.4 Testing the Result with Postman</h4>
<h4>4.5 DTO Classes vs. Entity Model Classes</h4>
<h4>4.6 Using AutoMapper in ASP.NET Core</h4>

<h3>5. GLOBAL ERROR HANDLING</h3>
<h4>5.1 Handling Errors Globally with the Built-In Middleware</h4>
<h4>5.2 Startup Class Modification</h4>
<h4>5.3 Testing the Result</h4>

<h3>6. GETTING ADDITIONAL RESOURCES</h3>
<h4>6.1 Getting a Single Resource From the Database</h4>
<h4>6.2 Parent/Child Relationships in Web API</h4>
<h4>6.3 Getting a Single Employee for Company</h4>

<h3>7. CONTENT NEGOTIATION</h3>
<h4>7.1 What Do We Get Out of the Box?</h4>
<h4>7.2 Changing the Default Configuration of Our Project</h4>
<h4>7.3 Testing Content Negotiation</h4>
<h4>7.4 Restricting Media Types</h4>
<h4>7.5 More About Formatters</h4>
<h4>7.6 Implementing a Custom Formatter</h4>

<h3>8. METHOD SAFETY AND METHOD IDEMPOTENCY</h3>

<h3>9. CREATING RESOURCES</h3>
<h4>9.1 Handling POST Requests</h4>
<h4>9.2 Code Explanation</h4>
<h4>9.3 Creating a Child Resource</h4>
<h4>9.4 Creating Children Resources Together with a Parent</h4>
<h4>9.5 Creating a Collection of Resources</h4>
<h4>9.6 Model Binding in API</h4>

<h3>10. WORKING WITH DELETE REQUESTS</h3>
<h4>10.1 Deleting a Parent Resource with its Children</h4>

<h3>11. WORKING WITH PUT REQUESTS</h3>
<h4>11.1 Updating Employee</h4>
<h5>11.1.1 About the Update Method from the RepositoryBase Class</h5>
<h4>11.2 Inserting Resources while Updating One</h4>

<h3>12. WORKING WITH PATCH REQUESTS</h3>
<h4>12.1 Applying PATCH to the Employee Entity</h4>

<h3>13. VALIDATION</h3>
<h4>13.1 Validation while Creating Resource</h4>
<h5>13.1.1 Validating Int Type</h5>
<h4>13.2 Validation for PUT Requests</h4>
<h4>13.3 Validation for PATCH Requests</h4>

<h3>14. ASYNCHRONOUS CODE</h3>
<h4>14.1 What is Asynchronous Programming?</h4>
<h4>14.2 Async, Await Keywords, and Return Types</h4>
<h5>14.2.1 The IRepositoryBase Interface and the RepositoryBase Class Explanation</h5>
<h4>14.3 Modifying the ICompanyRepository Interface and the CompanyRepository Class</h4>
<h4>14.4 IRepositoryManager and RepositoryManager Changes</h4>
<h4>14.5 Controller Modification</h4>

<h3>15. ACTION FILTERS</h3>
<h4>15.1 Action Filters Implementation</h4>
<h4>15.2 The Scope of Action Filters</h4>
<h4>15.3 Order of Invocation</h4>
<h4>15.4 Improving the Code with Action Filters</h4>
<h4>15.5 Validation with Action Filters</h4>
<h4>15.6 Dependency Injection in Action Filters</h4>

<h3>16. PAGING</h3>
<h4>16.1 What is Paging?</h4>
<h4>16.2 Paging Implementation</h4>
<h4>16.3 Concrete Query</h4>
<h4>16.4 Improving the Solution</h4>

<h3>17. FILTERING</h3>
<h4>17.1 What is Filtering?</h4>
<h4>17.2 How is Filtering Different from Searching? </h4>
<h4>17.3 How to Implement Filtering in ASP.NET Core Web API </h4>
<h4>17.4 Sending and Testing a Query</h4>

<h3>18. SEARCHING</h3>
<h4>18.1 What is Searching?</h4>
<h4>18.2 Implementing Searching in Our Application</h4>
<h4>18.3 Testing Our Implementation</h4>

<h3>19. SORTING</h3>
<h4>19.1 What is Sorting?</h4>
<h4>19.2 How to Implement Sorting in ASP.NET Core Web API</h4>
<h4>19.3 Implementation – Step by Step</h4>
<h4>19.4 Testing Our Implementation</h4>
<h4>19.5 Improving the Sorting Functionality</h4>

<h3>20. DATA SHAPING </h3>
<h4>20.1 What is Data Shaping?</h4>
<h4>20.2 How to Implement Data Shaping</h4>
<h4>20.3 Step-by-Step Implementation</h4>
<h4>20.4 Resolving XML Serialization Problems</h4>

<h3>21. SUPPORTING HATEOAS</h3>
<h4>21.1 What is HATEOAS and Why is it so Important?</h4>
<h5>21.1.1 Typical Response with HATEOAS Implemented</h5>
<h5>21.1.2 What is a Link?</h5>
<h5>21.1.3 Pros/Cons of Implementing HATEOAS</h5>
<h4>21.2 Adding Links in the Project</h4>
<h4>21.3 Additional Project Changes</h4>
<h4>21.4 Adding Custom Media Types</h4>
<h5>21.4.1 Registering Custom Media Types</h5>
<h5>21.4.2 Implementing a Media Type Validation Filter </h5>
<h4>21.5 Implementing HATEOAS</h4>

<h3>22. WORKING WITH OPTIONS AND HEAD REQUESTS</h3>
<h4>22.1 OPTIONS HTTP Request</h4>
<h4>22.2 OPTIONS Implementation</h4>
<h4>22.3 Head HTTP Request</h4>
<h4>22.4 HEAD Implementation</h4>

<h3>23. ROOT DOCUMENT</h3>
<h4>23.1 Root Document Implementation</h4>

<h3>24. VERSIONING APIS</h3>
<h4>24.1 Required Package Installation and Configuration</h4>
<h4>24.2 Versioning Examples</h4>
<h5>24.2.1 Using Query String</h5>
<h5>24.2.2 Using URL Versioning</h5>
<h5>24.2.3 HTTP Header Versioning</h5>
<h5>24.2.4 Deprecating Versions</h5>
<h5>24.2.5 Using Conventions</h5>

<h3>25. CACHING</h3>
<h4>25.1 About Caching</h4>
<h5>25.1.1 Cache Types</h5>
<h5>25.1.2 Response Cache Attribute</h5>
<h4>25.2 Adding Cache Headers</h4>
<h4>25.3 Adding Cache-Store</h4>
<h4>25.4 Expiration Model</h4>
<h4>25.5 Validation Model</h4>
<h4>25.6 Supporting Validation</h4>
<h5>25.6.1 Configuration</h5>
<h4>25.7 Using ETag and Validation</h4>

<h3>26. RATE LIMITING AND THROTTLING</h3>
<h4>26.1 Implementing Rate Limiting</h4>

<h3>27. JWT AND IDENTITY</h3>
<h4>27.1 Implementing Identity in ASP.NET Core Project</h4>
<h4>27.2 Creating Tables and Inserting Roles</h4>
<h4>27.3 User Creation</h4>
<h4>27.4 Big Picture</h4>
<h4>27.5 About JWT</h4>
<h4>27.6 JWT Configuration</h4>
<h4>27.7 Protecting Endpoints</h4>
<h4>27.8 Implementing Authentication</h4>
<h4>27.9 Role-Based Authorization</h4>

<h3>28. DOCUMENTING API WITH SWAGGER</h3>
<h4>28.1 About Swagger</h4>
<h4>28.2 Swagger Integration Into Our Project</h4>
<h4>28.3 Adding Authorization Support</h4>
<h4>28.4 Extending Swagger Configuration</h4>

<h3>29. DEPLOYMENT TO IIS</h3>
<h4>29.1 Creating Publish Files</h4>
<h4>29.2 Windows Server Hosting Bundle</h4>
<h4>29.3 Installing IIS</h4>
<h4>29.4 Configuring Environment File</h4>
<h4>29.5 Testing Deployed Application</h4>