### What did you accomplish in this phase? What happens if you forget to include event.preventDefault() when handling a form submission in client-side JavaScript, and why is preventing the default behavior necessary when you do not have a backend server endpoint?

In this phase I created a simple event handler that prints what I type in to the console along with a short message. If I were to forget to include prevent default when handleing a form submission the site would try to refresh and try to send the form to a backend server endpoint which I don't have and this would cause errors.
