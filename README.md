# Automatic addition input
> The script is used to extract data from the database and add it to a site, checking if an account (email / username and password) exists.

Programming language used: ``PYTHON``
 
## Careful:
* python must be installed on your computer.
* must have python mysql, selenium and webdriver_manager installed

## Use:
* at line 15 the host, user, passwrd, database parameters must be modified with your database connection data.
* line 20 and 49 must be modified in the site url where you want to check the connection data.
* The variables ~ btn_button ~, ~ password_textbox ~, ~ username_textbox ~ must be adjusted to the name of the site button / input id.

## Important: 
 * in the case of the site ~ facebook ~ the id of the button to accept cookies changes every time the page is opened. In this case, use the name displayed on the button
