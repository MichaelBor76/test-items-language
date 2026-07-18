# test-items-language
Запуск автотестов для разных языков интерфейса

    1. Create a GitHub repository that will contain the files conftest.py and test_items.py.
    2. Add a handler to the conftest.py file that reads the language parameter from the command line.
    3. Implement the logic in the conftest.py file to launch a browser with the specified user language. The browser must be declared in the `browser` fixture and passed to the test as a parameter.
    4. In the test_items.py file, write a test that verifies that the product page on the website contains an “Add to Cart” button. For example, you can check for products available at http://selenium1py.pythonanywhere.com/catalogue/coders-at-work_207/.
    5. The test must be run with the “language” parameter using the following command:

    pytest --language=es test_items.py

    and pass successfully. It’s enough for the code to work only in the Chrome browser.
    6. Please submit a link to this repository as your answer to this assignment.
    7. Submit your solution for review by other students. Please note that you can only submit your solution for review once.
    8. Check the solutions of at least three other students to earn points for this assignment.
