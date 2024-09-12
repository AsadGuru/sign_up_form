# sign_up_form
Here's a summary of the form behavior and event handlers you're looking for:

  ->  Email Input:
        -> onChange Function: Checks if the input value has more than 3 characters and contains both "@" and ".".
        -> Validation Feedback: Removes red error messages and displays a green "All good to go" text if the validation is successful.

  ->  Password Input:
        -> onChange Function: Checks if the input value has more than 8 characters.
        -> Validation Feedback: Removes red error messages and displays a green "All good to go" text if the validation is successful.

  ->  Submit Button:
        onClick Function: Shows a confirmation window.
           -> If the user clicks "OK," an alert is displayed saying "Successful signup!"
           -> If the user clicks "Cancel," the form is redirected to the same page, and all input values are cleared.

This ensures user inputs are validated and appropriate feedback is provided, while also managing the form submission process effectively.
