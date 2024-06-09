# free-react-icons
This library contains free CC0 (Creative Commons Zero) Icons for react that can be used without attribution.

## Current "Collections"
- Jonh - A collection of CC0 Icons sourced from the Free CC0 Icons website (https://cc0-icons.jonh.eu/)

## Usage
Icon components can accept all the props that an SVG element can accept. You can use the icons like this:
```tsx
import { IconName } from 'free-react-icons/jonh';

const MyComponent = () => {
  return (
    <IconName />
  );
}
```

## Contributions
If you want to add more icons, please create a pull request.

Rules:
1. The icons must be CC0 licensed (Some evidence/explanation of source must be provided in the PR)
2. Icon components must follow the same pattern as existing icon components. 
3. Your icons should be either added to a new collection in (Most cases) or an existing collection if appropriate (i.e. a new icon in a set) 
4. Your collection should be added to the index.tsx file in the root of the library.
5. Your collection should be added to the README.md file in the root of the library.