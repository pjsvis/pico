<style>
@import "../css/pico.docs.min.ex.css";
@import './nw-main.css';
@import './nw-utils.css';
:root{
    --primary:  var(--red-6);
    font-family: var(--font-mono);
}
</style>

# nw-pico.css

We start with pico.css then we add a theme which we style using open-props css variables.

The theme comes from the pico.css documentation and we can use that as examples of our styling.

## Develop an nw-pico theme

## Configure nw-pico theme

- most of the pico docs contain the following

```html
<link rel="stylesheet" href="../css/pico.min.css" />
<link rel="stylesheet" href="css/pico.docs.min.css" />
```

- [X] so lets rename ```pico.docs.min.css``` to ```pico.docs.min.ex.css```
- inside of ```pico.docs.min.css``` we put:

```css
@import './pico.css';
@import './nw-main.css';
@import './nw-utils.css';
```

- [X]  ```nw-main.css``` is our stuff and we have this at the top

```css
@import 'https://unpkg.com/open-props';
```

- [X] and then the contents of ```css/themes/default.css``` 
- [X] now we can preview a docs page and set some ```pico-var``` to an ```open-props``` var in ```nw-main.css``` or ```nw-utils.css```
- [X] and our live-server preview will update
- [] then we go through each of the pico.css docs pages and change stuff in ```main.css``` until we have something that we like
- [] we should also add our grid layout page so that we can test that as well
- [] basically we are revising the default pico.css theme to become our nw-theme
  
