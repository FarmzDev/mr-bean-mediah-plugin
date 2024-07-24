# Mr. Bean Plugin

The Mr. Bean Plugin is a fun and entertaining plugin that brings the antics of Mr. Bean to your application. This plugin provides a series of Mr. Bean GIFs, quotes, and sound bites to add a touch of humor to your project. 

## Features

- **GIFs**: A collection of hilarious Mr. Bean GIFs to add visual humor.
- **Quotes**: Famous and funny quotes from Mr. Bean.
- **Sound Bites**: Classic Mr. Bean sounds to enhance user interaction.

## Installation

To install the Mr. Bean Plugin, follow these steps:

1. **Download the plugin**:
    ```sh
    git clone https://github.com/yourusername/mr-bean-plugin.git
    ```

2. **Navigate to the plugin directory**:
    ```sh
    cd mr-bean-plugin
    ```

3. **Install the dependencies**:
    ```sh
    npm install
    ```

4. **Add the plugin to your project**:
    ```js
    const mrBeanPlugin = require('path-to-mr-bean-plugin');
    app.use(mrBeanPlugin);
    ```

## Usage

### Display a Random GIF

To display a random Mr. Bean GIF, use the following method:

```js
mrBeanPlugin.getRandomGif()
    .then(gifUrl => {
        console.log(gifUrl);
        // Add code to display the GIF in your application
    })
    .catch(err => {
        console.error(err);
    });
```