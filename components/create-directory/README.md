[![Build status](https://travis-ci.org/dcache-elements/create-directory.svg?branch=master)](https://travis-ci.org/dcache-elements/create-directory)


# \<create-directory\>

_[Demo and API docs](http://dcache-elements.github.io/create-directory/)_

A dialog box content for creating a directory. This element can  
be attached to an element that implement 
`Polymer.PaperDialogBehavior` and `paper-dialog-shared-styles.html`.

For example, if `\<x-dialog-impl\>` implements this behavior:

```html
<x-dialog-impl>
    <create-directory dir-full-path="/abc/def"></create-directory>
</x-dialog-impl>
```