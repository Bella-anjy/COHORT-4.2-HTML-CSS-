### Media Query
--------------------
- This is use to apply styles conditionally based on screen size, orientation or platform.

### How to write Media Query
------------------------------

```css
@media (screen size in px,rem or em){

}
```

### Illustration
-------------------

```css
@media (max-width: 768px){
  .container{
    display: none;
  }
}
@media (min-width: 768px){
    .container{
        display: block
    }
}