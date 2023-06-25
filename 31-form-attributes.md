# Form Attributes

## SpellCheck
Used to enable/disable spell checking for a form field.
```
<textarea name="message" spellcheck="true"> </textarea>
```

<br>



## Auto Complete
Used to enable/disable the browser's autocomplete feature for a form field.

```
<input type="text" name="username autocomplete="off">
```

<br>

## Accept
Describe which input file types are allowed.

```
<input type="file" accept=".jpg, .png">
```

<br>

## Input Mode
Hints at the type of data that might be entered by the user while editing the element or its contents. This allows a browser to display an appropriate virtual keyboard.
```
<input type="text" inputmode="url" />
<input type="text" inputmode="email" />
<input type="text" inputmode="numeric" />
```

<br>

## Capture
Hints the browser that for a file input, allow user to provide image/audio directly from the camera/microphone.
```
<input type="file" capture="user" accept="image/*" />
```