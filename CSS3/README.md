# CSS3 Tutorial



```css



/*CSS3*/

/*Start*/
div{
    /*Background Colors*/
    background-color: red;
    background-color: rgb(0, 200, 0);
    background-color: rgba(200,0, 0, 0.5);
    background-color: #FFFFFF;


    /*Background Imegas*/
    background-image: url("./assets/tree-736885__480.jpg");
    background-repeat: no-repeat;
    background-attachment: fixed;


    /*background-position: direction direction;*/
    background-position: left top;
    background-position: 200px 100px;
    background-position: 20% 50%;
    background-position-x: 100px;
    background-position-y: 200px;


    /* background-size: width height;*/
    background-size: auto;
    background-size: contain;
    background-size: cover;
    background-size: 200px 100px;
    background-size: 10% 20%;


    /*Background Shortcut*/
    background: fixed red repeat left Top;


    /*Padding (Top Right Bottom Left*/
    padding: 10px;
    padding: 10px 20px;
    padding: 10px 20px 10px;
    padding: 10px 20px 10px 20px;
    padding-top: 10px;
    padding-right: 20px;
    padding-bottom: 10px;
    padding-left: 20px;

    /*Margin*/
    /*Margin can take negative value while padding can't*/
    margin: auto; /*make item at center by adjust the margin at left and right to be equal*/
    margin: 20px;
    margin: 20px 30px;
    margin: 20px 30px 10px;
    margin: 10px 20px 30px 40px;
    margin-top: 10px;
    margin-right: 20px;
    margin-bottom: 30px;
    margin-left: 40px;


    /*Border*/
    /*Border Width*/
    border-width: 10px;
    border-width: 10px 20px;
    border-width: 10px 20px 10px;
    border-width: 10px 20px 10px 20px;
    border-top-width: 10px;
    border-right-width: 10px;
    border-bottom-width: 10px;
    border-left-width: 10px;
    /*Border Color*/
    border-color: black;
    border-color: black red;
    border-color: black red green;
    border-color: black green yellow blue;
    border-top-color: red;
    border-right-color: green;
    border-bottom-color: blue;
    border-left-color: wheat;
    /*Border Style*/
    border-style: solid;
    border-style: solid dashed;
    border-style: solid dashed dotted ;
    border-style: solid dashed dotted double;
    border-top-style: solid;
    border-right-style: dashed;
    border-left-style: dotted;
    border-bottom-style: double;
    border-radius: 10px;
    /*Border Shortcut*/
    border: 10px solid red;


    /*Outline*/
    /*the same like border but it's size don't add to div width */
    /*in outline you can't select side like outline-top*/
    outline: 10px solid red;
    
    
    
    /*Display*/
    
    /* Ctrl+h to replace any thin in all shhet*/
    /* Alt and select to move more than one cursor*/

    /*
    Block

    - Take Full Width If No Width
    - Add Line Break
    - Respect Padding, Margin, Width, Height

    Inline

    - Don't Add Line Break
    - Don't Respect Width, Height
    - Respect Padding, Margin [Just left + right]
    - Allow Elements Before And After It

    Inline-Block

    - Allow Elements Before And After It
    - Respect Padding, Margin, Width, Height

      different between display:none; Visibility: hidden
      display: none;  remove element and second element take place
      visibility: hidden; remove element and keep it's place
    */

    display: block;
    display: inline;
    display: inline-block;
    display: none;
    visibility: hidden;
    
    /*Width and Hight*/
    width: 400px;
    min-width: 400px;
    max-width: 400px;
    width: fit-content;
    height: 600px;
    min-height: 600px;
    max-height: 1200px;
    
    
    /*Overflow*/
    overflow: auto;
    overflow: visible;
    overflow: hidden;
    overflow: scroll;
    overflow-x: hidden;
    overflow-y: auto;
    
    
    /*Text Shadow*/
    /*Syntax => text-shadow: H-shadow V-Shadow Blur Color*/
    text-shadow:0 0 0 red ;
    
    
    /*Text align*/
    text-align: center;
    text-align: left;
    text-align: right;
    direction: ltr;
    direction: rtl;
    vertical-align: top;
    
} 
/*End*/
    


    
    /*Grouping Multiple Selectors*/
    .one,
    .two,
    .three
    {
        padding: 10px;
        margin: 10px 0;
        background-color: #EEE;
    }

    .one{
        border-bottom: 2px solid red;
        color: red;
    }

    .two{
        border-bottom: 2px solid green;
        color: green;
    }

    .three{
        border-bottom: 2px solid blue;
        color: blue;
    }


    /*Nesting*/
    /*Nesting => Access Element by tag name through his parent*/
    div p{

    }
    /*Nesting => Access Element by class through his parent*/
    div .one{

    }
    /*Nesting => Access Element by id through his parent*/
    div #one{

    }

```
