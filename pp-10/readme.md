# Production Problem 10: A/B Testing on the Cheap

## The Problem

Locate an interface component on a website that you use frequently that you think could be improved. The improvement should be minor.

Take a screenshot of the interface on both a mobile and desktop device. Then, sketch or illustrate your alternate/"b" test. Finally, describe modification and the HTML, CSS, and JavaScript that you would need to write in order to conduct the test.

## Deliverables

* Screenshots of the interface component on mobile and desktop, placed in this directory (`pp-10/`)

* Sketch or illustrate (e.g., in Photoshop) your alternate/"b" test, placed in this directory (`pp-10/`)

* A text description of the modification, and a description of the HTML, CSS, and JavaScript that you would need to write for the test (you do *not* have to write the actual HTML, CSS, and JavaScript, however)

##### Text description of the modification:
I wanted to redesign the login form of BankofAmerica.com. I wanted to declutter that landing page by removing that component out of immediate sight. I then decided to add a login button instead on the upper right corner of the landing page of BankofAmerica.com. When that login button is clicked on, a dialog window for login purposes appears in the middle of the screen prompting the user for their username and password.

#### Changes:

* In HTML: I would remove the login form from the landing page and I would add a login button to the same page.
* In CSS: I would normalize and style the login form that would appear inside the dialog window.
* In JS: I would add a JS function that triggers a dialog window, when the login button is clicked on. The dialog window would then contain the login form's html. I could also add additional functions to handle the login information for authentication purposes.
