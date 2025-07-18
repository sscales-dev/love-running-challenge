# Love Running: Challenge 1

The expected solution to this first challenge should look similar to the image below (a bit simplistic for now, but we'll spruce it up with some CSS in the next challenge).

![image.png](attachment:596080ee-03d0-4874-983f-8f3c2a85fc94:image.png)

**Form outer structure**

- Add a form element inside the section provided. (Don't forget to add all closing tags where needed).
- Add form method. The value is: **POST**
- Set the form action The value is: **https://formdump.codeinstitute.net/**
- Inside the form add an h2 heading providing a motivational message for the user. The value is: **Let's get you signed up!**

**Form personal detail text input fields**

Personal details (fully styled):

![image.png](attachment:b5c69e56-6d7e-43ee-9df0-bec382f0f71d:image.png)

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

![image.png](attachment:42fd5da2-0647-45f2-99a4-a2b20e6ee3f2:image.png)

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

![image.png](attachment:6ee5ae98-8061-4187-96d1-b0c718f77bbc:image.png)

Submission button (fully styled):

- Below the radio buttons, add submit input field
- Set the form submission input **type**. The value is: **submit**
- Set the **value** for the submit button to let the user know the purpose of the form. The value is: **Let's Run!**

**What to do next:**

1. Run your code to test the form submission
2. Submit your challenge for assessment
3. Once you have successfully submitted this challenge, copy your code and paste it into the same section provided on the second challenge. You'll then style the HTML created in this challenge