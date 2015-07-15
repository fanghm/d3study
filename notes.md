# D3 Examples

- [How the Drought is Shrinking California’s Reservoirs](http://ww2.kqed.org/lowdown/2014/03/18/into-the-drought-californias-shrinking-reservoirs/)
  (code: https://github.com/vicapow/water-supply)

- Selector method
- selector methods apply to all its containing DOM elements
  + style() -- modify **style** attribute of DOM attributes
  + attr() -- modify attributes of selected DOM elements

  attr('style', "background-color: red;");
  attr('background-color', 'red');
  style('background-color', 'red');

  + selectAll()

> NOTE: a selector object only contains the elements that
matched the selection rule **when the selection was first created**
* selectors are really collections of data/element pairs
* accessor functions are actually getting called for each data/element pair

  CSS rule Meaning
  -----
  .foo select every DOM element that has class foo
  \#foo select every DOM element that has id foo
  div.foo select all the <div> tags that have class foo
  div#foo select all the <div> tags that have id foo
  div .foo select every DOM element that has class foo that’s inside a <div> tag
  div #foo select every DOM element that has id foo that’s inside a <div> tag
  div p .foo select every DOM element that has class foo that’s inside a <p> tag
  that’s inside a <div> tag

Data binding
updating what gets shown based on some piece of information (or data.)

selector data() method takes an array of data and binds each data item in
that array to each DOM element in selector

.enter() returns a new selector of data/element pairs
without elements.
