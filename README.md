

# Learning CSS 

> or also practicing Git

## CSS NOTES:

- CSS is not a programming language
- css is a Styling language
- used for Presentation
- Creativity Focused


#### CSS SYNTAX :
    - selector {
        property1: value;
        property2: value;
    }

    Example1:

        h1{
            color:blue;
        }


 #### CSS SELECTORS :
 - CSS selects the HTML elements you want.
 - CSS has multiple selectors but the main selectors are : Element   Class    ID
 - The universal selectoris represented by a star "*".
 - class selector(starts with a dot)
 - ID selector : it is simailar to class selector;  except it is used to to apply to one specific element in the page as ID is unique
        -the hashtag or pound symbol followed by the id which is test



#### CLASS BOX MODEL :
- In web design , every element is considered a rectangular box.
- Undarstanding this box is the key to create layouts with CSS or align items with other items.
- The CSS model is sor of a standard by which browsers render HTML elements.
- The box model consists of four parts :- MARGINS;
                                        - BORDERS;
                                        - PADDING;
                                        - ACTUAL CONTENT.



#### CASCADE :
- The "C" in CSS stands for cascading.
- Whe the two rules apply that have equal "specificity" , the one that comes last in the CSS is the one that will be used.

#### SPECIFICITY
- Specificity is how the browser decides which rule applies if multple rules have different selectors but apply to the same element.

#### INHERITANCE
- Some CSS property values set on parent elements are inherited by their child elements, and some are not.

#### CSS UNITS :
- ABSOLUTE UNITS , are generally considered to always be the same size.

    - cm (Centimeters)
    - mm (Milimeters)
    - Q (Quarter-milimeters)
    - in (Inches)
    - pc (Picas)
    - pt (Points)
    - px (Pixels) ## mostly used in CSS

- RELATIVE UNITS , relative units on the other hand are relative to something else, perhaps the size of the parent element's font, or the size of the viewport