### Extending Styles

```sh
# tailwind.config.js
theme: {
    extend: {
        colors: {
            primary: 'var(--color-primary)',
        }
    }
}

# global.css / main.css which include tailwind utilities class
# @tailwind base;
# @tailwind components;
# @tailwind utilities;

:root {
    ...,
    --color-primary: #000000;
}
```
