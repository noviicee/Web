# Problem Description

Create a web page which calculates the discount for the product for the specific season. The seasons with their discount rates are summer (10%), new year (5%) and clearance (15%). The discount is calculated on the price of the product. The web page should look like

![pic-0](//Web/gitignore/ReferenceImages/samplescreen.jpg)

The outcome webpage should look as

![pic-1](//Web/gitignore/ReferenceImages/discountoutput.png)

The client side validation is performed using JavaScript.

Web page Requirements

The web page background color should be #99FFFF. The label “Discount Price” should be a heading tag(h1) and should be italic bolded, centered, and in color code #b03060.

Product name - a text box with the name "name", should not be empty, contain only alphabets and space and mandatory field.
Price - a number box with the name price, mandatory field and the minimum value should be greater than 15000.

Season is a drop down box with tag name “season”. The drop down box will have the following value and display value

|             summer      |           SUMMER SALE   |
|-------------------------|-------------------------|
|         newyear         |           NEW YEAR SALE |
|        clearance        |           CLEARANCE SALE|

The table should be left aligned with 35% and an outer border style of solid 5px and 30% border width. The space between element and the border must be 10px.
A submit button with left aligned with 45% and with a value “GET DISCOUNT PRICE” should be present. Once submit, the web page calculates the discounted price for the product.

The outcome must be displayed in 2 div tags, where the first will have the id named “discount” and is to display the discount % of the product and the second will have the id named “result” and is to display the discounted price of the product. Both the div tags should be center aligned with bold text. The font of the discounted price must be italic, #FF0000 and 40px size and for discount % it is 25px.

Important Note :

1. Make sure all tags and attributes are in lower case
2. After displaying the output, the page should not get redirected.
3. Do not use 'let' or 'const' keywords. Instead, use 'var'.
4. Use getElementById() or getElementsByName() to fetch value out of the HTML components.
