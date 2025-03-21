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
    <title>Advanced HTML5 Elements Practice</title>
</head>
<body>
    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>

   <main>
        <section>
            <h2>Roman Numeral List</h2>
            <ol type="I">
                <li>First Priority</li>
                <li>Second Task</li>
                <li>Third Item</li>
                <li>Fourth Element</li>
                <li>Fifth Component</li>
            </ol>
        </section>

   <section>
            <h2>Sample Image</h2>
            <img src="https://images.pexels.com/photos/674010/pexels-photo-674010.jpeg" 
                 alt="Sample Image from Pexels" 
                 width="600"
                 style="border-radius: 8px;">
        </section>
        <section>
            <h2>Contact List</h2>
            <table border="1" cellpadding="8">
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
                        <td>John Smith</td>
                        <td>123 Oak Street</td>
                        <td>(555) 123-4567</td>
                        <td>john.smith@email.com</td>
                    </tr>
                    <tr>
                        <td>Sarah Johnson</td>
                        <td>456 Maple Ave</td>
                        <td>(555) 234-5678</td>
                        <td>sarahj@work.com</td>
                    </tr>
                    <tr>
                        <td>Mike Chen</td>
                        <td>789 Pine Road</td>
                        <td>(555) 345-6789</td>
                        <td>mike.chen@mail.net</td>
                    </tr>
                    <tr>
                        <td>Emma Wilson</td>
                        <td>321 Elm Blvd</td>
                        <td>(555) 456-7890</td>
                        <td>ewilson@company.org</td>
                    </tr>
                    <tr>
                        <td>David Brown</td>
                        <td>654 Birch Lane</td>
                        <td>(555) 567-8901</td>
                        <td>dbrown@example.com</td>
                    </tr>
                </tbody>
            </table>
        </section>
        <section>
            <h2>Registration Form</h2>
            <form id="registrationForm">
               
   <fieldset>
                    <legend>Personal Details</legend>
                    <p>
                        <label for="fullName">Full Name:</label>
                        <input type="text" id="fullName" name="fullName" 
                               placeholder="John Doe" required minlength="3">
                    </p>
                    <p>
                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email"
                               placeholder="john@example.com" required>
                    </p>
                    <p>
                        <label for="password">Password:</label>
                        <input type="password" id="password" name="password"
                               placeholder="Minimum 8 characters" 
                               required minlength="8">
                    </p>
                    <p>
                        <label for="birthdate">Birth Date:</label>
                        <input type="date" id="birthdate" name="birthdate" required>
                    </p>
                </fieldset>

  <fieldset>
                    <legend>Additional Info</legend>
                    <p>
                        <label for="country">Country:</label>
                        <select id="country" name="country" required>
                            <option value="">-- Select Country --</option>
                            <option value="us">United States</option>
                            <option value="ca">Canada</option>
                            <option value="uk">United Kingdom</option>
                            <option value="au">Australia</option>
                        </select>
                    </p>
                       <p>
                        <span>Subscription Plan:</span>
                        <label>
                            <input type="radio" name="plan" value="basic" required>
                            Basic
                        </label>
                        <label>
                            <input type="radio" name="plan" value="premium">
                            Premium
                        </label>
                        <label>
                            <input type="radio" name="plan" value="pro">
                            Professional
                        </label>
                    </p>
   <p>
                        <label>
                            <input type="checkbox" name="newsletter" required>
                            Subscribe to newsletter
                        </label>
                        <label>
                            <input type="checkbox" name="terms" required>
                            I agree to terms and conditions
                        </label>
                    </p>
                </fieldset>

   <button type="submit">Register Now</button>
            </form>
        </section>

     
   <section>
            <h2>Multimedia Content</h2>
            <video controls width="600" poster="https://picsum.photos/600/340">
                <source src="https://sample-videos.com/video123/mp4/720/big_buck_bunny_720p_1mb.mp4" 
                        type="video/mp4">
                Your browser does not support the video tag.
            </video>

  <audio controls style="margin-top: 20px;">
                <source src="https://sample-videos.com/audio/mp3/wave.mp3" 
                        type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </section>
    </main>
</body>
</html>
