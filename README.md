
# First Challenge for Boot camp 

In this project we are taking existing code and modifying the functionality without changing the style or display of the webpage. We were giving a webpage that was nearly complete but was missing some functionality throughout the page. We focus on condensing code so that we wouldn't repeat ourselves when assigning the same values to elements from the same class. 

I made some alteration to the css code that was provided by condensing certain calls into one call for all instances of the same class. I noticed that this was being done multiple times throughout the code and figured out a way to all the same functionality without the repetition. 

I ahve included some examples of code that i used in the css that helped me eliminate repeated code. 
## Authors

- [@marshallrizzuto](https://github.com/Zoot83)


## Features

- Display block
- Class properties
- Margin and Border
- Text-align
- Scout Rule
- Detailed Comments


## Usage/Examples

 Condencing code:

 I noticed that there was repeated code that was all doing the same thing for 3 elements from the same class.
Rather then having those extra lines of code in this i condenced it and tarrgeted the h3 in all the elements so they would all share the same margin and alignment.

.benefits h3
{
    margin-bottom: 10px;
    text-align: center;
}


Here is another section of code that I condenced to allow all instances of the benefits class to receive. This will keep everything consistent.


.benefits img
{
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```

