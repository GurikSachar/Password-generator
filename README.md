# Password-generator

This is a simple random password generator which has been developed using React hooks + tailwind css framework for styling.

## Hooks Used

1. useState - to track the state of the inputs used in the project, that is the length of the password, the number and special character checkboxes.

2. useCallback - to run the function which generates a new password and store the same function call and password in cache only when one of the input fields change, i.e, either length or any of the checkboxes. This prevents unnecessary running of the function and re-rendering of the output box on the browser, saving time and resources.

3. useEffect - to run the password generating function when one of the dependencies change, i.e, either length or any of the checkboxes.