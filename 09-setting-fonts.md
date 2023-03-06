### Setting Fonts

```sh
Example:

# in NextJs
const montserrat = Montserrat({
    weight: ["400"],
    subsets: ["latin"],
    variable: "--font-montserrat"
})

# in tailwind.config.js
theme: {
    extend: {
        ....,
        font-family: {
            montserrat: ["var(--font-montserrat)"]
        }
    }
}
```
