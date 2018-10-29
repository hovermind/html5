## `data-*`
Very often we need to store information associated with different DOM elements. This information might not be essential for readers, 
but having easy access to it would make life a lot easier for us developers.

HTML5 has introduced custom data attributes. All attributes on an element whose name starts with data- are data attributes.
```
<li data-x="414354" data-y="85160" data-z="31940">
  Co-ordinate
</li>
```

**Notes:**
* data stored in these attributes should be of type string.
* data attributes should only be used when there are no other appropriate HTML elements or attributes.

**See:** [jQuery `data()`](https://api.jquery.com/data/)
