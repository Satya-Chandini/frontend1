# frontend1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <form  class="contact-form">
            <h2>Contact Us</h2>
            <div class="form-group">
                  <label for="Name">Name:</label>
                  <input type="text" id="name" name="Name"/>

            </div>
            <div class="form-group" >
                 <label for ="email">Email:</label>
                 <input type="email" id="email" name="email"/>
            </div>
            <div class="form-group">
                <label for ="subject">Subject:</label>
                <input type="subject" id="subject" name="Subject"/>

            </div>
            <div>

                 <label for ="message">Message:</label>
                 <textarea id="message" name="message" rows="5"></textarea>
            </div>
            <button type="submit">Submit</button>

        </form>
</body> 
</html>
