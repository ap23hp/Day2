# Day2
## 5 differences between Browser JS(console) v Nodejs
Node js:
Node doesn’t have a predefined “window” object cause it doesn’t have a window to draw anything.
“location” object is related to a particular url; that means it is for page specific. So, node doesn’t require that.
Ofcourse Node doesn’t have “document” object also, cause it never have to render anything in a page.
Node has “global”, which is a predefined global object. It contains several functions that are not available in browsers, cause they are needed for server side works only.
“require” object is predefined in Node which is used to include modules in the app.
In Node everything is a module. You must keep your code inside a module.
Browser js(Console) :
“window” is a predefined global object which has functions and attributes, that have to deal with window that has been drawn.
“location” is another predefined object in browsers, that has all the information about the url we have loaded.
“document”, which is also another predefined global variable in browsers, has the html which is rendered.
Browsers may have an object named “global”, but it will be the exact one as “window”.
Browsers don’t have “require” predefined. You may include it in your app for asynchronous file loading.
Moduling is not mandatory in client side JavaScript, i.e. in browsers.


typeof(1)
typeof(1.1)
typeof('1.1')
typeof(true)
typeof(null)
typeof(undefined)
typeof([])
typeof({})
typeof(NaN)
# Output:
number
number
string
boolean
object
undefined
object
object
number
