## ``<form>``
- **This tag is used to create the form. The ``action`` attribute specifies where the form data should be sent when it's submitted, and the ``method`` attribute specifies the HTTP method (GET or POST).**

## ``<label>``
- **Defines a label for an ``<input>`` element. The ``for`` attribute should be the same as the ``id`` of the input it's labeling.**

## ``<input>``
- **This tag is a versatile form element. Depending on the ``type`` attribute, it can be a ``text field``, ``password field``, ``radio button``, ``checkbox``, etc. In this example, types used include text, ``email``, ``date``, ``radio``, ``checkbox``, and ``submit``.**

## ``<textarea>``
- **Allows for multi-line text input. It's useful for longer, free-form text like comments or descriptions.**

## ``<input type="submit">``
- **Defines a button for submitting the form.**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Form Tags Example</title>
  </head>
  <body>
    <h2>Registration Form</h2>
    <form action="/submit-form" method="post">
      <label for="fname">First Name:</label><br />
      <input type="text" id="fname" name="fname" /><br />
      <label for="lname">Last Name:</label><br />
      <input type="text" id="lname" name="lname" /><br />
      <label for="email">Email:</label><br />
      <input type="email" id="email" name="email" /><br />
      <label for="birthday">Birthday:</label><br />
      <input type="date" id="birthday" name="birthday" /><br />
      <p>Gender:</p>
      <input type="radio" id="male" name="gender" value="male" />
      <label for="male">Male</label><br />
      <input type="radio" id="female" name="gender" value="female" />
      <label for="female">Female</label><br />
      <input type="radio" id="other" name="gender" value="other" />
      <label for="other">Other</label><br />
      <label for="bio">Biography:</label><br />
      <textarea id="bio" name="bio" rows="4" cols="50"></textarea><br />
      <input
        type="checkbox"
        id="subscribe"
        name="subscribe"
        value="newsletter" />
      <label for="subscribe">Subscribe to newsletter</label><br />
      <input type="submit" value="Submit" />
    </form>
  </body>
</html>
```