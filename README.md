# flipgrid code challenge
 given a mockup, my task is to create a sign up form where a user can register for a service. The form contains user first name, email addrress and password fields.

 - The page should dynamically adapt to screen size.(media queries)

 ## View 1 - Sign Up page ##
this page includes; 

1. a header, 
2. help text, 
3. a form with 3 fields; First Name, Email Address and Password, and 
4. a Submit button.

OnSubmit, the fields are *required* to submit the form.

# View 2 - Confirmation page #
Upon the user filling out all the fields of the form and clicking 'Submit' button, they are brought to this confirmation page.

Confirmation contains information with their first name and email address.

There is a 'Sign In' button on this page (does not require functionality now).

# Task 3: Project description #
I used HTML, CSS and JS for this project. 
for the first task, i created a HTML file, using form element providing fields for input - First Name, Email Address and Password.
the user has to input their first name and email, password being optional (in this particular case).

This form has a sign up button, that has some animation/transition. Onclick, the button returns the confirmation view, returning the user first name and email.

I created the second form, the confirmation form view, reusing form comonent.
this view dispalys what the user entered as their first name and their email address.

The sign in button for as an example in this page takes the user back to the index.html page(view 1; sign up form).

I created CSS file to style the html pages, I used the B.E.M (Block Element Modifier) naming convention/methodology to achieve reusability of components.

I used localStorage Javasript property to dispay the user input from the sign up page (view 1) in the view 2, the confirmation view.

I implemented media query and other css properties to ensure the html pages dynamically adapt to screen size.

I used basic css attributes to implement form input validation.