Experimenting with formatting lists, numbering lists, etc.    


References: 
- https://docs.github.com/en/free-pro-team@latest/github/writing-on-github
  + https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax
    * https://github.github.com/gfm/#example-265
  * https://gist.github.com/joshbode/491ad0e678d456ea8ddc
  * https://gist.github.com/patik/89ee6092c72a9e39950445c01598517a


# World
## Country
### State
#### City
##### Suburb
###### Street

<style type="text/css">
  body {
    margin: auto;
    max-width: 44em;
    font-family: Calibri, sans-serif;
    font-size: 18pt;
  }

h1 { counter-reset: h2counter; }
h2 { counter-reset: h3counter; }
h3 { counter-reset: h4counter; }
h4 { counter-reset: h5counter; }
h5 { counter-reset: h6counter; }
h6 {}

h2:before {
    counter-increment: h2counter;
    content: counter(h2counter) ".\0000a0\0000a0";
}

h3:before {
    counter-increment: h3counter;
    content: counter(h2counter) "." counter(h3counter) ".\0000a0\0000a0";
}

h4:before {
    counter-increment: h4counter;
    content: counter(h2counter) "." counter(h3counter) "." counter(h4counter) ".\0000a0\0000a0";
}

h5:before {
    counter-increment: h5counter;
    content: counter(h2counter) "." counter(h3counter) "." counter(h4counter) "." counter(h5counter) ".\0000a0\0000a0";
}

h6:before {
    counter-increment: h6counter;
    content: counter(h2counter) "." counter(h3counter) "." counter(h4counter) "." counter(h5counter) "." counter(h6counter) ".\0000a0\0000a0";
}
</style>
