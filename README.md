contentEditable jQuery Plugin
===============

Manage events and content from HTML elements with contenteditable attributes and placeholder option.

Usage
=====

$("#...").contentEditable({
  "placeholder" : "Enter some content",
  "newLineOnEnterKey" : false,
  "onActivate" : function(){
        // DO some stuff here
  },
  "onFocusIn" : function(){
        // DO some stuff here
  },
  "onFocusOut" : function(){
        // DO some stuff here
  },
  "onBlur" : function(element){
        // element.content return the edited content of the element
        // element.settings return the settings object of the element
        // like the placeholder text / html
        
        // Do some ajax call to save your edited content
  }
});
