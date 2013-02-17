#Content Editable jQuery Plugin with Placeholder

Set HTML elements to 'contenteditable' with placeholder functionality and manages its content and events quickly and easily.

See demo on http://labs.fellipesoares.com/plugins/contenteditable

##Usage

```
$("#...").contentEditable({
  "placeholder" : "Enter some content",
  "newLineOnEnterKey" : false,
  "onActivate" : function(){
        // DO something here
  },
  "onFocusIn" : function(){
        // DO something here
  },
  "onFocusOut" : function(){
        // DO something here
  },
  "onBlur" : function(element){
        // element.content return the edited content of the element
        // element.settings return the settings object of the element
        
        // Do something with the edited content.
  }
});
```

```
$("#...").contentEditable({
	"placeholder" : "I´m empty",
	"onBlur" : function(element){
		
		// Do something with the edited content (element.content).
	}
});
```
