# github-notification-markups 🎉
Set of notification pseudo-markups created for GitHub upon the request @McFoggy in [GitHub markdown issue](https://github.com/github/markup/issues/887). I used svg based rendered containers using the foreignObject trick. There are four of the notifications markup. I can add up upon request.

<img src="./markups/info-markup.svg">
<img src="./markups/success-markup.svg">
<img src="./markups/warning-markup.svg">
<img src="./markups/error-markup.svg">

## How to use?

The only thing you have to do is to include them in your markdown file. An example below:
``` md
<img src="./markups/info-markup.svg">
```

The text inside them is predifined but you can change it easily just changing the ```span.message``` element in svg files. An example file is created in **_./markdown_** folder.
It is like below: 

<img src="./markups/random-markup.svg">