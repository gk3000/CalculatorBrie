Open button.html in the browser. 

The code for opening a pop-up with defined window size is this:

```html
<a href="#" onClick="window.open('calc.html','calculator','resizable,height=520,width=290'); return false;"><button>Calculator</button></a>
```

So, basically `href="#" onClick="window.open('calc.html','calculator','resizable,height=520,width=290'); return false;">` then botton or simply text for the label of the link (what user will see and click) and you close it with `</a>`

Try it and tell me if it's what you needed. 

Cheers! 