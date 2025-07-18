# Love Running: Challenge 1

The expected solution to this first challenge should look similar to the image below (a bit simplistic for now, but we'll spruce it up with some CSS in the next challenge).

![image.png](/assets/images/lrc1.png)

**Form outer structure**

- Add a form element inside the section provided. (Don't forget to add all closing tags where needed).
- Add form method. The value is: **POST**
- Set the form action The value is: **https://formdump.codeinstitute.net/**
- Inside the form add an h2 heading providing a motivational message for the user. The value is: **Let's get you signed up!**

**Form personal detail text input fields**

Personal details (fully styled):

![image.png](/assets/images/lrc2.png)

**First Name**

- Create a label identifying the user's first name. The label text is: **First Name**
- Below the label, add an associated text input field to let the user add their first name.
- Add matching label "**for**" and text input "**id**" attribute values to create a clickable relationship between the first name label and it's associated first name text input field. The value is: **fname**
- Set the first name input **type**. The value is: **text**
- Set the first name input name for reading by the server. The value is: **first_name**
- To avoid an empty first name input being submitted to the server, set its **required** attribute.

**Last Name**

- Create a label identifying the user's last name. The label text is: **Last Name**
- Below the label, add an associated text input field to let the user add their last name.
- Add matching label "**for**" and text input "**id**" attribute values to create a clickable relationship between the last name label and it's associated last name text input field. The value is: **lname**
    - Set the last name input **type**. The value is: **text**
- Set the last name submission input **name** for reading by the server. The value is: **last_name**
- To avoid an empty last name input being submitted to the server, set its **required** attribute.

**Email Address**

- Create a label identifying the user's email address. The label text value is: **Email Address**
- Below the label, add an associated email input field to input the user's email address
- Add matching label "**for**" and email input "**id**" attributes to create a clickable relationship between the email label and it's associated email input field. The value is: **email**
- Set the email input **type**. The value is: **email**
- Set the email submission input **name** for reading by the server. The value is: **email_address**
- To avoid an empty email address input being submitted to the server, set its **required** attribute.

**Form running preference radio input fields:**

Running preferences:

![image.png](/assets/images/lrc3.png)

**Road**

- Create a label identifying the first running preference. The label text value is: **Road**
- Below the label, add an associated radio input field to input the road running preference
- Add matching label "**for**" and radio input "**id**" attribute values to create a clickable relationship between a label and it's associated radio button. The value is: **road**
- Set the radio input **type**. The value is: **radio**
- Group the radio buttons to make exclusive selections. To do this, set the input name attribute. The value is: **running_preference**
- Set the **value** for the radio button for reading by the server. The value is: **road**
- To avoid an unselected running preference being submitted to the server, set its **required** attribute. Note we only need to set this for **one** radio button in the group

**Trail**

- Create a label identifying the second running preference. The label text value is: **Trail**
- Below the label, add an associated radio input field to input the trail running preference
- Add matching label "**for**" and radio input "**id**" attribute values to create a clickable relationship between a label and it's associated radio button. The value is: **trail**
- Set the radio input **type**. The value is: **radio**
- Group the radio buttons to make exclusive selections. To do this, set the input name attribute. The value is: **running_preference**
- Set the value for the radio button for reading by the server. The value is: **trail**

**Both**

- Create a label identifying the second running preference. The label text value is: **Both**
- Below the label, add an associated radio input field to input the trail and road running preference
- Add matching label "**for**" and radio input "**id**" attribute values to create a clickable relationship between a label and it's associated radio button. The value is: **both**
- Set the radio input **type**. The value is: **radio**
- Group the radio buttons to make exclusive selections. To do this, set the input name attribute. The value is: **running_preference**
- Set the **value** for the radio button for reading by the server. The value is: **both**

**Form submission button:**

![image.png](/assets/images/lrc4.png)

Submission button (fully styled):

- Below the radio buttons, add submit input field
- Set the form submission input **type**. The value is: **submit**
- Set the **value** for the submit button to let the user know the purpose of the form. The value is: **Let's Run!**

**What to do next:**

1. Run your code to test the form submission
2. Submit your challenge for assessment
3. Once you have successfully submitted this challenge, copy your code and paste it into the same section provided on the second challenge. You'll then style the HTML created in this challenge

# Love Running: Challenge 2

The finished form should look like this:

![Love Running Signup Form](/assets/images/lrc5.png)

Copy the finished code from **Challenge 1**  and paste it into the **section** created within **signup.html**

**Styling the form:**

- Add a class attribute to your **form** element. The value is: **signup-form**
- In **index.css** add a corresponding class rule below the **.form-section**. The rule name is **.signup-form**

**Add properties to the rule**

- Add a top margin to push the form down towards the center of the page. The value is: **150 pixels**
- Set the form text color. The value is: **#fff**
- To contrast, the form with the page background image set the form background-color. The value is **rgba(60, 60, 60, 0.6)**
- Set the maximum width for the form. The value is: **400 pixels**
- To ensure that the form maintains it's structural integrity and positioning across device sizes set its position. The value is: **absolute**
- Continue the positioning by setting the form at a responsive position from the left edge of the screen. The value is: **10 per cent**
- Provide all-round padding for the form elements within the form. The value is: **30 pixels**

**Styling the form header:**

- Below the **.signup-form** rule add style rule that targets the form's child header

**Add properties to the rule**

- Make the header text color more visible to the user. The value is: **#fafafa**
- Set the bottom margin to create some space between the header text and the input fields below. The value is: **20 pixels**

**Styling the text/email input fields**

- Add a class attribute to each of the personal details input elements (i.e. fname, lname, and email). The class name is: **text-input**
- In style.css add a corresponding class rule. The rule name is **.text-input**

**Add properties to the rule**

- Ensure the form background color is visible inside the input fields by setting the input background color. Use the background property (not background-color). The value is: **transparent**
- Ensure the input text color can be seen against the form background. The value is: **#fafafa**
- Set the width for the input fields. The value is: **100%**
- Set the height of the input fields. The value is: **25 pixels**
- Set the margins. Use the shorthand syntax. The values are: **Top = 5 pixels , Bottom = 20 pixels**
- Set the input field border. Use the shorthand syntax. The values are: **Border width = 1 pixel, Border style = solid, Border color = #fafafa**
- Set the border radius. The value is: **2 pixels**

**Styling the input hover event**

- Reuse the **.text-input** rule and add a **hover** pseudo-class.

**Add properties to the rule**

- Set the border color when a user hovers over the personal details input fields. The value is: **#f16c6b**

**Styling the submit button**

- Add a class attribute to your submit input. The value is: **join-button**
- In style.css add a corresponding class rule. The rule name is **.join-button**

**Add properties to the rule**

- Create some space between the submit button and the radio buttons above. Set the top margin. The value is: **20 pixels**
- Set the border radius for the button. The value is: **2 pixels**
- Set the padding for the button text. Use the shorthand syntax. The values are: **Top = 15 pixels, Right = 32 pixels, Bottom = 15 pixels, Left = 32 pixels**
- Align the button text. The value is: **center**
- Set the font size. The value is: **100 percent**
- Set the background color that is in line with color that appears on the main page The value is: **#f16c6b**
- Ensure the text can be seen against the background color. Set the text color. The value is: **#fafafa**
- Position the button below the radio buttons. Let's change the display. The value is: **block**

**Styling the submit hover event**

- Reuse the **.join-button** rule and add a hover pseudo-class.

**Add properties to the rule**

- Set a contrasting background color when a user hovers over the button. The value is: **#fafafa**
- Set a contrasting text color when a user hovers over the button. The value is: **#f16c6b**

**Adding the Font Awesome Icon**

- Inside **signup.html** add a Font Awesome icon to the form header. The class values are: **fas fa-heartbeat**

**What to do next:**

1. Run your code to test the form submission
2. Submit your challenge for assessment
3. Once you have successfully completed this challenge, congratulate yourself on making deep inroads into pure HTML/CSS software development. You are now ready to take your development and design skills to an advanced level.
4. Explore good design and development ideas using the following sites:https://www.awwwards.com/https://dribbble.com/https://alistapart.com/