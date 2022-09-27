# tsxcomponent

[![Powered by Mason](https://img.shields.io/endpoint?url=https%3A%2F%2Ftinyurl.com%2Fmason-badge)](https://github.com/felangel/mason)

Helper for creating React components in TypeScript.

_[mason][1] brick 🧱_

## Getting Started 🚀

This brick hepls you to create a basic NextJS component.

### Installation

```bash
mason add -g tsxcomponent --git-url https://github.com/kalmecak/tsxcomponent
```

### Usage

```bash
mason make tsxcomponent -o ./components          
```
Mason will ask for the name of the component, after that it will create a folder with the component name and a `.css` file inside:

```bash
? What the new componets name? (component) button
✓ Made brick tsxcomponent (48ms)
✓ Generated 2 file(s):
  ./components/Button/Button.module.css (new)
  ./components/Button/Button.tsx (new)
```

After executing the _make_ command your "components" directory will look like this:
```
└── components
    └── Button
        ├── Button.module.css
        └── Button.tsx

```

Even if you don't have a "components" directory, it will be created.

Your basic component will look like this:

```tsx
/**
 * Component generated with mason-CLI
 */

import styles from './Navbar.module.css';


const Button = () => {


    return (
        <>
            <h1>Button Component</h1>
            <h2>I'm alive!</h2>
        </>
    );
}

export default Button;
```

Then you can start coding your magic!!

For more information about mason, please visit the [Official Mason Documentation][1]

[1]: https://github.com/felangel/mason/tree/master/packages/mason_cli#readme