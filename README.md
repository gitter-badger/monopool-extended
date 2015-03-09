[![Build Status](https://travis-ci.org/JustSomeDood/monopool-extended.svg)](https://travis-ci.org/JustSomeDood/monopool-extended)

## March 8 2015

This is the initial upload, so far what you will get if you were to use this theme is [monopool](https://github.com/coderiot/monopool) with tweaked fonts (now useing noto sans and source code pro{for code snippits}).  I have included highlight.js and added "read more" functionality.

I also minified the sites css files (you can find the unminified files for easy editing in the extras folder)

I added font awesome and social links to the sidebar as well.
___

#### Using highlight and "read more"
- To break the post and use an excerpt add ``<!-- more -->`` wherever you want, anything above that tag will be shown on the front page while the rest will open when the post is opened.
- To highlight code use:


``{% highlight language %}``  
enter code  
``{% endhighlight %}``


and replace language with the language of the code (bash, css, yaml etc.)
