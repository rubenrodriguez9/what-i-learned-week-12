# what-i-learned-week-12



## Higher Order Functions

Higher order functions such as map and filter were learned. Higher order functions require helper function to quickly execute what you would like.
The proper way to call a higher function is as follows:

![Higher Order Function](/Users/rubenrodriguez/Documents/code-immersives/term-1/week-12/what-i-learned-week-12/filter.png)

## Document Object Model (DOM)


We're able to change classes, text, id's, append childre to tags. We could basically style HTML solely through DOM manipulation. DOM takes precedence over and CSS for example, if you have
a tag that's supposed to be red:

li {
    background-color: red;
}

Your javascript takes precedence:

li.style.backgroundColor = 'blue';

So your background will be blue, not red;

### Useful tips

change html:

item.innerHTML = 'rando'

document.querySelector(): you can throw tags, selectors, ids, classes inside the parenthesis

document.createElement(): allows you to create tags

appendChild(): allows you to make a child from a created element

item.addEventListener(): creates an event that happens from a type of user interaction


item.classList(): shows what classes are on the selected item
item.