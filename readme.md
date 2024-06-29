Build a WordPress plugin that:

lets a visitor sign up to a contact list
lets the admin see a signed up user's contact information and display it as a contact card
The plugin will have
a front end page
a block (for the block editor)
an admin page
The frontend page:
Show this page when the user navigates to the /sign-up route. The page will have a sign-up form. Do not use any frontend framework for this form - use plain JS only. Make the form as complete as possible:
check for errors
prevent form submission on error
sanitize inputs
properly style the form
secure the form
The form should have 5 fields:
Name
Address
Phone number
Email
Hobbies
On form submission, save the user to DB.
The hobbies field must be a custom taglist component. Taglist reference: https://formkit.com/inputs/taglist. Suggested hobbies: fishing, running, coding, photography, singing, gardening, travelling. User should be able to add their own custom text. Allow a maximum of 3 hobbies.

The block:
Inserting the block in editor will show the user a list of all the people who have signed up. The user will be able to select a person from the list which will render a contact card of the selected person. Add dynamic rendering using php.

The admin page:
Create an admin menu item for the plugin. In the plugin admin page, render a react app that shows in a simple table all the people in the DB and their information.

Tips:
You are encouraged to submit the project even if it's incomplete
Implement functionality first, then add styling, finally add security
Build the form first, then the block, finally build the admin page
If you cannot build a WordPress plugin, you may use a different backend technology
Building the WordPress plugin is still preferred
Laravel, Ruby on rails, and node.js is prohibited
php or golang is preferred
