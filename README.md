# JavaScript Form Event

When a user interacts with the drop-down select box, the change event will trigger the packageHint() function. This shows messages below the select box that reflect the choice.

![111](https://cloud.githubusercontent.com/assets/18538482/16814788/58c0a650-4905-11e6-97db-e2ff5de829fa.png)

When the form is submitted, the checkTerms() function is called. This tests to see if the user has checked the box that includes they agree to the terms and conditions.

![111](https://cloud.githubusercontent.com/assets/18538482/16814898/d156e480-4905-11e6-9636-588ec051df14.png)

If not, the script will prevent the default behavior of the form element and stop it from submitting the form data to the server. It will show an error message to the user.

## How to run the app locally?

* In your own terminal type:
```
git clone https://github.com/bostonhuman/javascript-form-event
```
* Open `form.html` to run the app.
