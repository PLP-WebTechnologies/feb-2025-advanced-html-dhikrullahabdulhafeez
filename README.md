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
    <title>FUK Library</title>
</head>
<body>
    <header>
        <h1>Library website practice</h1>
    </header>

    <section>
        <h2>List of services</h2>
        <ol>
            <li>reference services</li>
            <li>serial control</li>
            <li>aquisition</li>
            <li>interlibrary loan</li>
            <li>lending</li>
        </ol>
    </section>

    <section>
        <h2>Recommended Logo</h2>
        <img src="istockphoto-2152690052-1024x1024.jpg" alt="A man scrolling his phone" height="200" width="250"
    </section>    

    <section>
        <h2>Administrators contact</h2>
        <table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>emaiL</th>
                    <th>mobile</th>
                    <th>address</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>Abdulhafeez</td><td>abd@gail.com</td><td>07045411501</td><td>n0.3 sabo junction</td></tr>
                <tr><td>Abdulhafeez</td><td>abd@gail.com</td><td>07045411501</td><td>n0.3 sabo junction</td></tr>
                <tr><td>Abdulhafeez</td><td>abd@gail.com</td><td>07045411501</td><td>n0.3 sabo junction</td></tr>
                <tr><td>Abdulhafeez</td><td>abd@gail.com</td><td>07045411501</td><td>n0.3 sabo junction</td></tr>

            </tbody>
        </table>
    </section>

    
        <h2>Registration form</h2>
        <form>
            <input type="text" id="name" name="name" placeholder="Username" required />
            <label for="name">Name</label><br><br>
            
            <input type="emaiL"id="emaiL"name="emaiL"placeholder="input your email" required/>
            <label for="emaiL">Email</label><br><br>

            <input type="password"id="password"name="password"placeholder="imput your password" min-lenght="6" required/>
            <label for="password">password</label><br><br>

            <input type="date"id="dob"value="dob" required/>
            <label for="dob">date of birth</label><br><br>

            <label for="country">country</label>
            <select id="country"name="country" required>
                <option value="">--select option--</option>
                <option value="us">United States</option>
                <option value="nig">Nigeria</option>
                <option value="ca">Canada</option><br><br>


            <label>hobbies</label><br>    
            <label for="reading">reading</label>
            <input type="checkbox"id="reading"name="hobbies"value="reading"/>

            <label for="memorizing">memorizing</label>
            <input type="checkbox"id="memorizing"name="hobbies"value="memorizing"/>
            
            <label for="learning">learning</label>
            <input type="checkbox"id="learning"name="hobbies"value="learning"/><br><br>


            <label>Gender</label><br>
            <label for="male">male</label>
            <input type="radio"id="male"name="gender"value="male"/>

            <label for="female">female</label>
            <input type="radio"id="female"name="gender"value="female"/>
            
            <label for="other">other</label>
            <input type="radio"id="other"name="gender"value="other"/>
            
            <input type="submit" value="register"/>
        </form>
        

        <h2>Multimedia</h2>

        <h3>Audio</h3>
        <audio controls>
            <source src=""
        </audio>

        <h3>Video</h3>

        <video width="500" controls>
            <source src="https://cdn.pixabay.com/video/2025/03/16/265271_tiny.mp4" type="video/mp4" alt="your browser does not support this format"
        </video>

        <p>&copy;website design</p>       
    
</body>
</html>
