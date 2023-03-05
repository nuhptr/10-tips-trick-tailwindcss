### @Apply nay or yay

```sh
Example : using this way if your class in html too long

export default function Nav() {
    return(
        <nav>
            <ul className="nav-items">
                <li>Home</li>
                <li>About</li>
                <li>Pages</li>
            </ul>
        </nav>
    )
}


# in global.css / main.css
.nav-items {
    @apply text-2xl text-gray-100 flex flex-col gap-8;
}
```
