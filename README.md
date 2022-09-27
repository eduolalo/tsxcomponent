# tsxcomponent

[![Powered by Mason](https://img.shields.io/endpoint?url=https%3A%2F%2Ftinyurl.com%2Fmason-badge)](https://github.com/felangel/mason)

Helper for creating React components in TypeScript.

_[mason][1] brick 🧱_

## Getting Started 🚀

This brick hepls you to create a basic NextJS component.

After executing the _make_ command:

```bash
mason make tsxcomponent --name navbar -o ./components
```
 your "components" directory will look like this:
```
└── components
    └── Navbar
        ├── Navbar.module.css
        └── Navbar.tsx

```

Even if you don't have a "components" directory, it will be created.

Your basic component will look like this:

```tsx
/**
 * Component generated with mason-CLI
 */

import styles from './Navbar.module.css';


const Navbar = () => {


    return (
        <>
            <h1>Navbar Component</h1>
            <h2>I'm alive!</h2>
        </>
    );
}

export default Navbar;
```

Then you can start coding your magic.


- [Official Mason Documentation][2]
- [Code generation with Mason Blog][3]
- [Very Good Livestream: Felix Angelov Demos Mason][4]

[1]: https://github.com/felangel/mason
[2]: https://github.com/felangel/mason/tree/master/packages/mason_cli#readme
[3]: https://verygood.ventures/blog/code-generation-with-mason
[4]: https://youtu.be/G4PTjA6tpTU
