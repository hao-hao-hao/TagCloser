#TagCloser


This is a simple package that can help to close all unclosed html tags.
Normally your website layout will look strange if the html tags are not closed in the excerpt.

It is very easy to use:
```
import tagcloser
sample_html = '<div>This is a unclosed tag html'
closed_html = tagcloser.close_tags(sample_html)```
  
It will return ```<div> This is a unclosed tag html </div>```
