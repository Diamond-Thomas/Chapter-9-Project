### What did you accomplish in this phase? What happens if you forget to include event.preventDefault() when handling a form submission in client-side JavaScript, and why is preventing the default behavior necessary when you do not have a backend server endpoint?

In this phase I created a simple event handler that prints what I type in to the console along with a short message. If I were to forget to include prevent default when handleing a form submission the site would try to refresh and try to send the form to a backend server endpoint which I don't have and this would cause errors.

### What validation approach did you take to collect and display errors? Did you display errors all at once or one at a time, and what are the user experience pros and cons of your chosen approach?

I used multiple if statements to check for invalid input tgeb stored them in an array. I then printed the array and stopped my console log with the messages being printed out instead. one pro is that because it displays all at once it is nore efficient but with my current method as it is the errors don't erase after their done so you won't be able to tell what part is fixed just through the messages.

### PROBLEMS WITH PHASE THREE
for some reason the it's saving to the appication but it's not console logging out anything? 