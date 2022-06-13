# Seoltab Colors

A quick guide on using Seoltab Colors

### styled-components

```ts
import {
  amber,
  amberA,
  blue,
  blueA,
  amberDark,
  blueDark,
} from "@seoltab/colors";

import styled from "styled-components";

const Button = styled.button`
  background-color: ${blue.blue4};
  color: ${blue.blue11};
  border-color: ${blue.blue7};
  &:hover {
    background-color: ${blue.blue5};
    border-color: ${blue.blue8};
  }
`;

export default function App() {
  return <Button> seoltab </Button>;
}
```

## Installation

`yarn add @seoltab/colors`
