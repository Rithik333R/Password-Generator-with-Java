**Password Generator**  

A **Java Console Application** that generates secure passwords and evaluates their strength based on predefined criteria.  

## Overview  

This project was developed during my **Winter Break of the second year** after completing the *Object-Oriented Effective Java Programming* course. My goal was to apply my Java skills by building a practical application.  

The idea stemmed from a conversation with my father about online security and the importance of using strong passwords for social media accounts. Inspired by this discussion, I created a **Random Password Generator**. Later, I enhanced the project by incorporating a **Password Strength Checker** to evaluate the robustness of user-defined passwords.  

## Features  

### Password Generation  
- Users can specify preferences for the generated password, including:  
  - Uppercase letters  
  - Lowercase letters  
  - Numbers  
  - Special characters  
- The user defines the **desired password length**.  
- A custom character set is created based on user preferences.  
- A random password is generated and displayed in the console.  

### Password Strength Evaluation  
The strength checker analyzes passwords based on the following factors:  
- Inclusion of **uppercase letters**  
- Inclusion of **lowercase letters**  
- Presence of **numbers**  
- Presence of **special characters**  
- Minimum length of **8 characters** (baseline security)  
- Minimum length of **16 characters** (recommended for strong security)  

Each factor contributes to a **score**, categorizing the password as:  
- Weak  
- Moderate  
- Strong  
- Very Strong  

### Security Best Practices  
- The program provides guidance on improving password security.  
- Tips include:  
  - Avoiding **reusing** passwords.  
  - Preventing **predictable patterns** (e.g., "123456" or "qwerty").  
  - Using **randomized** and **unique** passwords for different accounts.  

## Future Enhancements  
- Develop a **Graphical User Interface (GUI)** for better usability.  
- Implement **password storage & encryption** for secure management.  
- Add an **API integration** for generating passwords dynamically.  

## Conclusion  
The **Password Generator** serves as a practical tool for enhancing online security by creating strong passwords and assessing their effectiveness. This project strengthened my Java development skills and inspired future improvements, such as a GUI version available in the *Password-Services* repository.  

## License  
This project is licensed under the **MIT License**.  


