# About
this is just a simple stylesheet providing a class for hover effect
# Preview
![preview](https://github.com/ihaswn/css-animated-hover-underline/assets/20137018/d78c67eb-a9ab-49d3-9e4b-77a8f219d01a)

# How to use
You just need to assign a HTML element the `hover-underline` class:
```html
<h1 class="hover-underline">Lorem ipsum dolor sit amet consectetur</h1>
```

# Settings
* There is a few settings that you can assign to elements as css variables:
  * --ahu-transition-interval (default: 350ms)
  * --ahu-thickness (default: 3px)
  * --ahu-color (default: white)

usage example:

```html
<h1 class="hover-underline" style="--ahu-thickness: 5px; --ahu-thickness: 5px; --ahu-transition-interval: 0.5s; --ahu-color: red;">Lorem ipsum dolor sit amet consectetur</h1>
```
