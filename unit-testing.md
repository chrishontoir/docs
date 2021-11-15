# **Unit Testing**

## **Principles**
- **100% code coverage**
                    
  This ensures that all code has been tested. Anything less potentially means that code being run hasn't been tested.

  It encourages writing better functions. If a function is difficult to unit test, then the function has probably been written badly.
  
- **Mocking**

  Unit testing should only test one specific function. If any other functions are called within that function, they should be mocked.

  *The exception to this is other functions written within the same file.*