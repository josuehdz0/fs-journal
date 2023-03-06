# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
One way data binding with colon syntax. Two way data binding with v-model.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
SPA stands for Single Page Application. 
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Easier maintanance, faster page loads, and better performance.  
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
The onMounted method is a lifecycle hook thats called when the component is mounted on the DOM. Any functions within the onMounted are called when that said component is mounted on the DOM.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
The v-model attribute is used for two-way data binding between form inputs and components. It is useful when creating forms to update user input.

```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
It can be used to call a function when a button is selected. Example: @click="logout"
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
You can use v-if, v-show, or v-for. 
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key is helps vue identify each element in a list so that it can be effeciently updated to the DOM. Without the key, vue would rerender the entire list after any updates. But with a key, vue can update the specific changes in an element without updating the entire list. This is how using 'key' can help update the DOM more effeciently.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
The '<slot>' element is a component in Vue that lets you define content placeholders in a components template. 

The '<slot>' element can be used to make a component reusable. For example, you can use the same Modal component, and use a slot to insert several other components within. If you wanted that same modal to be used for signing in and filling in a seperate form. 
```