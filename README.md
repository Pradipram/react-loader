# React-loader

react-loader is a lightweight and customizable React component designed to display an infinity symbol as a loading spinner. It enhances the user experience by providing a visually appealing indicator during asynchronous operations, such as data fetching or processing tasks. With simple integration and flexible styling options, react-loader seamlessly fits into any React project, making it an essential tool for developers who prioritize both functionality and aesthetics.

## Features

-   **Easy Integration**: Seamlessly add the sign-in page component to your existing React projects.
-   **Customization**: Style the sign-in page according to your application's theme using custom CSS.
-   **Lightweight**: Minimal dependencies ensure that your application remains fast and efficient.
-   **Infinity Symbol Animation**: Displays an elegant infinity symbol as the loading spinner, providing a modern and visually appealing loading indicator.
-   **Accessible**: Built with accessibility in mind to ensure it is usable by all users, including those relying on assistive technologies.

## Installation

Install the package using npm:

```bash
npm i @p__radip/react-loader
        OR
yarn add @p__radip/react-loader
```

## Screenshots

[![Infinity Loader Demo](https://github.com/Pradipram/react-loader/assets/101059602/391cdae9-01fe-407a-8529-9bb739bf9de8)](https://github.com/Pradipram/react-loader/assets/101059602/7d9228c2-52ed-493c-a6f0-b97c0a12b22c)

[Watch the demo video](https://github.com/Pradipram/react-loader/assets/101059602/7d9228c2-52ed-493c-a6f0-b97c0a12b22c)

## Usage

```javascript
import React from "react";
import Loader from "@p__radip/react-loader";

function App() {
    return <Loader />;
}

export default App;
```

## Example

```javascript
import React, { useState } from "react";
import Loader from "@p__radip/react-loader";

const YourComponent = () => {
    const [loading, setLoading] = useState(false);

    return (
        <div>
        {
            loading ?
            <Loader/>
            :
            <div>{Other Compoent}</div>
        }
        </div>
    );
};

export default YourComponent;
```

## Contributing

Contributions are always welcome ! If you have any suggestions or improvements, please submit a pull request or open an issue on GitHub.

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

## Feedback

If you have any feedback, please reach out to us at pradipramjnv@gmail.com
