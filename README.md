# Password-Generator
A random password generator application using HTML, CSS, and JavaScript. This application empowers users to create secure and customizable passwords by providing options for password length and character composition. By combining frontend design with dynamic logic


Functionality:

Character Sets: The script defines character sets for uppercase letters, lowercase letters, numbers, and symbols. These sets are used to generate the password.

Password Generation: The generatePassword() function takes user preferences into account, creating a password by selecting characters from the specified sets. The password length is determined by the user's input.

User Input: Users can choose whether their password should contain uppercase letters, lowercase letters, numbers, and symbols. They can also set the desired password length within a specified range.

Display and Truncation: The generated password is displayed in the designated area with appropriate styling. If the generated password exceeds the desired length, the script truncates it to match the specified length, ensuring consistency.

Event Listeners: The "Generate" button triggers the password generation process. It listens for the click event and updates the password display accordingly.
