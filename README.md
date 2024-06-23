# ppxa/ui
Welcome to my custom styled component library built with shadcn/ui and TailwindCSS. This library provides a collection of reusable UI components that are styled with TailwindCSS to ensure a consistent and modern design. Developed using Vite, this library is optimized for rapid development and efficient bundling. Components can be easily previewed and tested with Storybook.

## Prerequisites
Before you start, ensure you have the following installed:
- Node.js (v18.18.0 or higher)
- npm (v10.0.0 or higher)

## Installation
To use the component library in your project, you need to install it via npm or yarn:
```bash
npm install @ppxa/ui
# or
yarn add @ppxa/ui
# or
pnpm add @ppxa/ui
```

## Usage
After installation, you can import and use the components in your React projects like this:
```jsx
import { Button } from '@ppxa/ui'
function App() {

  return (
    <>
      <Button variant='primary'>Click me</Button>
      <Button variant='dangerous'>Warning!</Button>
    </>
  )
}

export default App
```
## Development
1. To set up the development environment, follow these steps:
```bash
git clone git@github.com:xichen1/ppxa-ui.git
cd ppxa-ui
```
2. Install the dependencies:
```bash
pnpm install
```
3. Start the storybook server:
```bash
pnpm run storybook
```

## Building the library
To build the library, run the following command:
```bash
pnpm run build
```

## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
