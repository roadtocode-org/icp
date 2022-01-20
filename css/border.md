# CSS Borders

## You may style, width, and colour the border of an element using CSS border attributes.
### This is a shorthand for the CSS properties listed below:
- border-style
- border-width
- border-color

## border-style
### The border-style attribute determines the type of border that will be displayed.
### Following are the values of border-style:
- ```dotted``` : A dotted border is defined by this property.
- ```dashed``` : A dashed border is defined by this property.
- ```solid```  : A solid border is defined by this property.
- ```double``` : A double border is defined by this property.
- ```groove``` : Defines a three-dimensional grooved border. The outcome is determined on the border-color value.
- ```ridge```  : Defines a three-dimensional ridged border. The outcome is determined on the border-color value.
- ```inset```  : Defines a three-dimensional inset border. The outcome is determined on the border-color value.
- ```outset``` : Defines a three-dimensional outset border. The outcome is determined on the border-color value.
- ```none```   : No border is defined by this property.
- ```hidden``` : Defines hidden border.

## Syntax :
### One to four values can be assigned to the border-style property (for the top border, right border, bottom border, and the left border).
```
p.dotted {border-style: dotted;}
p.dashed {border-style: dashed;}
p.solid {border-style: solid;}
p.double {border-style: double;}
p.groove {border-style: groove;}
p.ridge {border-style: ridge;}
p.inset {border-style: inset;}
p.outset {border-style: outset;}
p.none {border-style: none;}
p.hidden {border-style: hidden;}
p.mix {border-style: dotted dashed solid double;}
```
### Outcome :

![Screenshot (209)](https://user-images.githubusercontent.com/90567283/149627362-09697d7a-47da-446f-9cb0-19f8378705c0.png)

## border-width
### You can control the width of an element's borders with the border-width property.
### This property's value can be a length in pixels, points, or centimetres, or it can be set to thin, medium, or thick.
### The following properties can be used to adjust the width of an element's bottom, top, left, and right borders independently.

- ```border-bottom-width``` changes the width of bottom border.
- ```border-top-width``` changes the width of top border.
- ```border-left-width``` changes the width of left border.
- ```border-right-width``` changes the width of right border.

### Examples :
```
p.one {
  border-style: solid;
  border-width: 5px;
}

p.two {
  border-style: solid;
  border-width: medium;
}

p.three {
  border-style: dotted;
  border-width: 2px;
}

p.four {
  border-style: dotted;
  border-width: thick;
}
```

### Outcome :
![Screenshot (210)](https://user-images.githubusercontent.com/90567283/150331665-53f73a59-e282-404d-a6dc-57e74953b59e.png)

