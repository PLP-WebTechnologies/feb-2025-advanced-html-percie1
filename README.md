# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements and Forms</title>
</head>
<body>
    <!-- Main content container -->
    <header>
        <h1>Welcome to the Registration Page</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List (Roman Numerals)</h2>
        <ol type="I">
            <li>Introduction to HTML5</li>
            <li>Learning HTML Elements</li>
            <li>Implementing Forms</li>
            <li>Multimedia Elements</li>
            <li>Advanced HTML5 Techniques</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Image from Pexels</h2>
        <img src="https://images.pexels.com/photos/1116355/pexels-photo-1116355.jpeg" alt="A beautiful sunset over the ocean" width="600" />
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Contact Information</h2>
        <table border="1" cellpadding="10">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>ijilusi precious</td>
                    <td>12 percie St.</td>
                    <td>08072885802</td>
                    <td>ijilusiprecious1@gmail.com</td>
                </tr>
                <tr>
                    <td>Jane marvelous</td>
                    <td>5 Oak Rd.</td>
                    <td>(234) 987-6543</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>Robert precious</td>
                    <td>91 Maple lane.</td>
                    <td>(234) 555-5555</td>
                    <td>robert@example.com</td>
                </tr>
                <tr>
                    <td>john prince</td>
                    <td>13 parker street.</td>
                    <td>(234) 777-7777</td>
                    <td>prince@example.com</td>
                </tr>
                <tr>
                    <td>Michael Brown</td>
                    <td>1 Cedar Lane.</td>
                    <td>(234) 333-3333</td>
                    <td>michael@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST" novalidate>
            <!-- Name Field -->
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="John Doe" required />

            <!-- Email Field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="example@example.com" required />

            <!-- Password Field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required />

            <!-- Date Field -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required />

            <!-- Dropdown (Select) -->
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="" disabled selected>Select your country</option>
                <option value="usa">United States</option>
                <option value="canada">Canada</option>
                <option value="uk">United Kingdom</option>
            </select>

            <!-- Radio Buttons -->
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required />
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female" required />
            <label for="female">Female</label>

            <!-- Checkboxes -->
            <label for="subscribe">Subscribe to newsletter:</label>
            <input type="checkbox" id="subscribe" name="subscribe" value="yes" />

            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>

    <footer>
        <p>© 2025 HTML5 Elements and Forms</p>
    </footer>
</body>
</html>
<!-- End of HTML Document -->




