### Adding Spaces

```sh
Example :

# not better x
export default function Nav() {
    return(
        <nav>
            <ul classname="text-2xl text-gray-100">
                <li className="py-2">Home</li>
                <li className="py-2">About</li>
                <li className="py-2">Pages</li>
            </ul>
        </nav>
    )
}

# Prefer this v / using space-y-12 (other way without flex gap)
export default function Nav() {
    return(
        <nav>
            <ul className="text-2xl text-gray-100 flex flex-col gap-8">
                <li>Home</li>
                <li>About</li>
                <li>Pages</li>
            </ul>
        </nav>
    )
}
```
