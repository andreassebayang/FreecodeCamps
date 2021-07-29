# Basic-HTML-and-HTML5

### Comment in HTML
Digunakan agar barisan code html tidak dibaca sebagai barisan code yang harus dieksekusi atau memberi keterangan pada barisan code html.
```
<!-- This is a comment -->
```

### Heading 
Heading terdiri dari **h1, h2, h3, h4, h5, h6** 
```
<h1> Hello World </h1>
<h2> Hello World </h2>
<h3> Hello World </h3>
<h4> Hello World </h4>
<h5> Hello World </h5>
<h6> Hello World </h6>
```

### Paragraph
Tag ini digunakan untuk membuat barisan baru
```
<p> This is a new paragraph </p>
```

## HTML5
HTML5 introduces more descriptive HTML **tags. These include main, header, footer, nav, video, article, section and others.**
```
<main> 
  <h1>Hello World</h1>
  <p>Hello Paragraph</p>
</main>
```

### Declare the Doctype of an HTML Document
The challenges so far have covered specific HTML elements and their uses. However, there are a few elements that give overall structure to your page, and should be included in every HTML document. At the top of your document, you need to tell the browser which version of HTML your page is using. HTML is an evolving language, and is updated regularly. Most major browsers support the latest specification, which is HTML5. However, older web pages may use previous versions of the language.
You tell the browser this information by adding the <!DOCTYPE ...> tag on the first line, where the ... part is the version of HTML. For HTML5, you use <!DOCTYPE html>.
The ! and uppercase DOCTYPE is important, especially for older browsers. The html is not case sensitive. Next, the rest of your HTML code needs to be wrapped in html tags. The opening <html> goes directly below the <!DOCTYPE html> line, and the closing </html> goes at the end of the page.
Here's an example of the page structure. Your HTML code would go in the space between the two html tags.
```
<!DOCTYPE html>
<html>

</html>
```


### Define the Head and Body of an HTML Document
You can add another level of organization in your HTML document within the html tags with the head and body elements. Any markup with information about your page would go into the head tag. Then any markup with the content of the page (what displays for a user) would go into the body tag.

Metadata elements, such as link, meta, title, and style, typically go inside the head element.
```
<!DOCTYPE html>
<html>
  <head>
    <meta />
  </head>
  <body>
    <div>
    </div>
  </body>
</html>
```

### Add Images
You can add images to your website by using the img element, and point to a specific image's URL using the src attribute.
```
<img src="https://www.freecatphotoapp.com/your-image.jpg">
```

### Link to external Pages with Anchor
You can use a (anchor) elements to link to content outside of your web page.
```
<a href="https://www.freecodecamp.org"> this links to freecodecamp.org </a>
```

### Link to internal Pages with Anchor
a (anchor) elements can also be used to create internal links to jump to different sections within a webpage.
```
<a href="#contacts-header">Contacts</a>
.....
<h2 id="contacts-header">Contacts</h2>

```
Untuk menghubungkan antar elemen dalam satu page, harus mempunyai id yang untuk menjadi wadah penampung inisialisasi. Seperti contoh diatas tag a akan dihubungkan ke h2, maka di h2 harus dibuat sebuah id dengan nama contacts-header lalu didaftarkan ke tag a dengan menambahkan **#**.

### Nest an Anchor Element within a Paragraph
You can nest links within other text elements.
```
<p> View more cat photos <a href="https://www.freecatphotoapp.com" target="_blank">cat photos </a> </p>
```

### Make Dead Links Using the Hash Symbol
Sometimes you want to add a elements to your website before you know where they will link. This is also handy when you're changing the behavior of a link using JavaScript, which we'll learn about later.
```
href="#"
```

### Create Unordered List
```
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
```

### Create Ordered List
```
<ol>
  <li>Garfield</li>
  <li>Sylvester</li>
</ol>
```

### Create a Text Field
input elements are a convenient way to get input from your user.
```
<input type="text">
```

### Add Placeholder Text to a Text Field
Placeholder text is what is displayed in your input element before your user has inputted anything.
```
<input type="text" placeholder="input yout text here">
```

### Create a Form Element
You can build web forms that actually submit data to a server using nothing more than pure HTML. You can do this by specifying an action attribute on your form element.
```
<form action="https://www.freecatphotoapp.com/submit-cat-photo">
    <input type="text" placeholder="cat photo URL">
</form>
```

### Add a Submit Button to a Form
Let's add a submit button to your form. Clicking this button will send the data from your form to the URL you specified with your form's action attribute.
```
<button type="submit">this button submits the form</button>
```
or combination
```
<form action="https://www.freecatphotoapp.com/submit-cat-photo">
   <input type="text" placeholder="cat photo URL">
   <button type="submit>"> Submit Here </button>
</form>
```

### Use HTML5 to Require a Field
You can require specific form fields so that your user will not be able to submit your form until he or she has filled them out.

For example, if you wanted to make a text input field required, you can just add the attribute required within your input element, like this: 
```
<input type="text" required>
```
or combination
```
<form action="https://www.freecatphotoapp.com/submit-cat-photo">
   <input type="text" placeholder="cat photo URL" required>
   <button type="submit>"> Submit Here </button>
</form>
```

### Create a Set of Radio Buttons
You can use radio buttons for questions where you want the user to only give you one answer out of multiple options, Radio buttons are a type of input.
```
<label> 
  <input type="radio" name="indoor-outdoor">Indoor 
</label>
```
It is considered best practice to set a for attribute on the label element, with a value that matches the value of the id attribute of the input element. This allows assistive technologies to create a linked relationship between the label and the related input element. For example:
```
<label for="indoor"> 
  <input id="indoor" type="radio" name="indoor-outdoor">Indoor 
</label>
```
We can also nest the input element within the label tags:
```
<label for="indoor"> 
  <input id="indoor" type="radio" name="indoor-outdoor">Indoor 
</label>
```
example make 2 radio button:
```
<form action="https://www.freecatphotoapp.com/submit-cat-photo">
  <input type="text" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>
   <label> <input type="radio" name="indoor-outdoor"> indoor </label>
   <label> <input type="radio" name="indoor-outdoor"> outdoor </label>
</form>
```

### Create a Set of Checkboxes
Forms commonly use checkboxes for questions that may have more than one answer, Checkboxes are a type of input.
Each of your checkboxes can be nested within its own label element. By wrapping an input element inside of a label element it will automatically associate the checkbox input with the label element surrounding it. All related checkbox inputs should have the same name attribute.
It is considered best practice to explicitly define the relationship between a checkbox input and its corresponding label by setting the for attribute on the label element to match the id attribute of the associated input element.
```
<label for="loving"><input id="loving" type="checkbox" name="personality"> Loving</label>
```
or
```
  <label> <input type="checkbox" name="personality">1 </label>
  <label> <input type="checkbox" name="personality">2 </label>
  <label> <input type="checkbox" name="personality">3 </label>
```

### Use the value attribute with Radio Buttons and Checkboxes
When a form gets submitted, the data is sent to the server and includes entries for the options selected. Inputs of type radio and checkbox report their values from the value attribute.
```
<label for="indoor">
  <input id="indoor" value="indoor" type="radio" name="indoor-outdoor">Indoor
</label>

<label for="outdoor">
  <input id="outdoor" value="outdoor" type="radio" name="indoor-outdoor">Outdoor
</label>
```
Here, you have two radio inputs. When the user submits the form with the indoor option selected, the form data will include the line: indoor-outdoor=indoor. This is from the name and value attributes of the "indoor" input.

If you omit the value attribute, the submitted form data uses the default value, which is on. In this scenario, if the user clicked the "indoor" option and submitted the form, the resulting form data would be indoor-outdoor=on, which is not useful. So the value attribute needs to be set to something to identify the option.

### Check Radio Buttons and Checkboxes by DefaultPassed
You can set a checkbox or radio button to be checked by default using the checked attribute.
```
<input type="radio" name="test-name" checked>
```
Just add **checked** 

### Nest Many Elements within a Single div Element
The div element, also known as a division element, is a general purpose container for other elements.

The div element is probably the most commonly used HTML element of all.

Just like any other non-self-closing element, you can open a div element with <div> and close it on another line with </div>.
```
<div>
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
</div>
```
