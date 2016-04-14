# Split Text
Split text is a small JS library that is able to split the contents of HTML tags into lines, words and/or characters.  
## Installation
Download these files and add the file to your HTML page.
`<script type="text/javascript" src="splittext.js"></script>`



## Usage

To split a tag or tags, run `new SplitText("#elementID")`.


The Split Text initialisation function will accept a single or array of any of the following:
 - JS elements
 - jQuery elements
 -  `querySelectorAll` selectors

 `new SplitText("#elementID")` will return a SplitText Object.

The Split text object has properties lines, words and chars which contain arrays of lines, words and chars respectively.

The Split text object also has a method revert() that will undo the changes that were made.



## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
## History
###Version 0.1
Will wrap lines, words and/or chars in separate divs and will set the position to any valid CSS position.  If position is set to null, it won't be set and it is up to your css.

#### TODO: 
Need to set positions and sizes for absolute or fixed positioned divs.

## License
TODO: Write license

