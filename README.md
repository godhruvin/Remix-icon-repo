# Remix Icon Repository

This is a GitHub repository for the **Remix Icons** library, which provides a set of icons. It contains the CDN link to import Remix Icons into your codebase.

## Installation

### Using npm (Optional)
If you'd like to install Remix Icons via npm:

```bash
npm install remixicon --save

### Usage ###
import 'remixicon/fonts/remixicon.css';

### import this to your main.js file. ###

### CDN ###

<link
    href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css"
    rel="stylesheet"
/>



### React ###
### Installation  ###

npm install @remixicon/react
# or
yarn add @remixicon/react
# or
pnpm install @remixicon/react
Usage
import { RiHeartFill } from "@remixicon/react";

const MyComponent = () => {
    return (
        <RiHeartFill
            size={36} // set custom `width` and `height`
            color="red" // set `fill` color
            className="my-icon" // add custom class name
        />
    );
};
