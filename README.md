# FormIO
To integrate and use formIO read this Manual document. [FORMIO.docx](https://github.com/MuhammadSaadBukhtiar97/FormIO/files/11981610/FORMIO.docx)

Steps to Create a Form using FormIO.

Step - 1:
Click on the ‘Create a new Form’ on the top right corner of home page (Super Admin). You’ll be taken to the Form builder screen.

Creating new E-forms:
To add form elements, simply drag them from the left-hand panel and drop them onto the canvas. You can choose from a variety of form elements, including text fields, checkboxes, radio buttons, and more.
For this example, we'll create a simple form with three fields: "Name", "Email", and "Message". To do this, drag a "Text Field" element onto the canvas and enter "Name" as the label. Repeat this process for the "Email" and "Message" fields.

Example screenshots: 

<img width="451" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/d55dde6e-7e2b-4dd8-b4ef-f85071815fe8">

<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/afe7c682-3b91-4c16-ac27-d6dab3695c71">

<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/8e0c4cfe-57e0-41ff-8336-ebd47b07bc19">

Customize Form Elements:
Once you've added your form elements, you can customize them to suit your needs. For example, you can change the label text, add placeholder text, or set validation rules.
To customize a form element, simply click on it to select it, and then use the options panel on the right-hand side of the screen to make changes. For example, you might want to set the "Email" field to require a valid email address by selecting the "Validation" tab and checking the "Email" checkbox.

Example screenshots:
<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/cc34d3d8-5827-4ece-8cf6-654945b73faf">

Basic components:
Text field:
A Text Field can be used for short and general text input. There are options to define input masks and validations.

Text Area:
A Text Area is a multi-line input field that allows for longer text.
Number:
Use a Number field whenever a field should be limited to a number value type. There are options to set thousands of separators, decimal places, and decimal requirements.
Password:
The password field has the same options as a text field component. It differs from a text field in that its HTML <input> type will be password instead of text. This will cause the field to display hidden input symbols instead of the entered value.

Checkbox:
A check box can be used for Boolean value input field. It can either be checked (true) or unchecked (false). 
Select Box:
This multi-valued component allows users to select one or more options in checkbox style format. Set your values within the Data tab of the settings. Apply unique settings such as value shortcuts and min/max value validation.

Select: 
The Select component displays a list of values in a dropdown list where users can select one of the values. This component has flexibility on where the data source originates from. There is also a large offering of settings providing different ways of filtering, querying, and loading data values. 

Radio: 
The radio component is a field that allows users to select a single option from a list of options displayed in radio-style format.

Button:
Buttons can be added to perform various actions within the form. The most obvious function of the Button component is the Submission action. However, you can also utilize the Button component to trigger events associated with workflow logic, reset field data, authenticate to an OAuth provider, and more. 

Advanced Component:
Email:
The Email component is a string field that carries special input validation ensuring the entered data is in a valid email format. A valid email address consists of an email prefix and an email domain, both in acceptable formats. 

Phone Number:
The Phone Number field carries an input mask to force the user to enter the field data in Phone Number format.

Date & Time:
The Date/Time component is a powerful and flexible component that offers many options for validation and date ranges.

Day:
The Day component is used to enter values for the Day, Month, and Year using a number or select type of field.

Time:
A stand-alone time field for manual input or a time selector widget. 



Currency:
Use the Currency component when a field should display currency amounts on the field. This component holds a numeric input mask that allows two decimal values and automatically adds commas as a user inputs a currency amount. The type of currency can also be selected which will change the prefix currency symbol.

Signature:
This is used to draw signature on signature canvas and will be saved as Image.

Layout Components:

HTML Element:
An HTML Element component may be added to a form to display a single HTML Element. This is useful if you wish to quickly insert and configure some HTML in your form.

Content:
Its just like rich text editor where you can add text/paragraph and style it.

Columns:
This component can be used for grouping other components, like Text Field, Text Area, Checkbox etc., into configurable columns. Use Columns if you want to display more than one component in one line or to save vertical space on your form. 

Field Set:
A Field Set can be used to create a title for an area of the form or grouping of components. This is useful to put inside Layout components or in between lots of related components. 

Panel:
A Panel is used to wrap groups of fields with a title and styling. Use the Panel to organize your components and create a more appealing UI.

Table:
Create a Table with columns and rows that allow adding additional components within it.

Data:
Container:
A Container is a wrapper around a set of fields, similar to a Field Set. What makes the Container unique is the way the data is stored. The fields inside the Container are put into an object with the container key. This is useful for creating more complex objects and data sets within your form.

Data Grid:
Data Grids allow users to add a grouping of components on a line item grid. Users can then add multiple rows of the component grouping inside the Data Grid. Additionally, any number of grids can be added within a form, which is especially useful when needing the ability to add or duplicate multiple fieldsets.

Examples:
1-	In Below image, I’m creating a container which can hold/group different field
<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/51c96877-66d2-4716-be80-389e66b9963a">

2-	Text Field:
You can customize label by adding Label title, position and placeholder text, you can also disable or hide the component, There’s an option “Is Enable for Admin”, If its checked then only admin can edit this field.
There’re also many validations which include the min/max length, make the field required or optional, Show label title when there’s some error. 
<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/f70ae86f-0a28-413d-a0bc-4e445e0f9e47">

3- You can add the default values of fields. Field text case can also be selected.
e.g. Selecting upper case will convert the value in uppercase
<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/7f1e13a1-a04f-4bce-a90c-c99eeeacf751">

4-	You can Preview the form by selecting Preview option on bottom right corner
<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/5e28f4c9-0a3f-4715-97b3-cd94c8cb7a29">

5-	This is the output of preview.

<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/58880df9-587a-4a4c-a5d1-94cbdc647b7f">

6-	You can add Select/Dropdown menu and its values can be added in advanced tab as shown below.

<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/ee203322-71d5-49ef-91e8-17273fca37aa">

<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/5663011c-8a8e-4686-ada1-0c60a7bebf5f">

7-	Custom CSS classes can also be added to containers like shown in below example.

<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/bcc6e036-ee59-4b72-9eac-627014095507">

8-	Here I’m doing custom calculations to evaluate the results of fields.

<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/4184793e-bfc5-4d77-84a6-104cefde646a">

9-	Custom validations can also be added. Here I’ve added a regular expression to validate email.

<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/02baeb58-8969-4c49-93d0-fd11689415bb">

10-	Using data grid we can add fields dynamically on the run as shown in below image.

<img width="452" alt="image" src="https://github.com/MuhammadSaadBukhtiar97/FormIO/assets/57248503/72ee8f54-bcce-4f68-96cb-32b96523fdd9">


Conclusion: 

Using Form.Io’s drag-and-drop form builder, you can quickly and easily create custom forms without any coding.














  

 
