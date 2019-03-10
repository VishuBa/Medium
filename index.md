
const mediumToMarkdown = require('medium-to-markdown');
 
mediumToMarkdown.convertFromUrl('https://medium.com/@vishubandari/quantum-computer-768d130b132')
.then(function (markdown) {
  console.log(markdown); //=> Markdown content of medium post
});
