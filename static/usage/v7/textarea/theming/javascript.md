```html
<ion-textarea
  aria-label="Custom textarea"
  placeholder="Type something here"
  class="custom"
  helper-text="Helper text"
  counter="true"
  maxlength="100"
></ion-textarea>

<style>
  ion-textarea.custom {
    --background: #373737;
    --color: #fff;
    --padding-end: 10px;
    --padding-start: 10px;
    --placeholder-color: #ddd;
    --placeholder-opacity: 0.8;
  }
  
  ion-textarea.custom .helper-text,
  ion-textarea.custom .counter {
    color: #373737;
  }
</style>
```
