# PDF Viewer

A simple and efficient PDF viewer web component built with Kit and PDF.js. This component allows you to display and navigate through PDF documents within your application seamlessly.

**Warning: This component is still in development and may not work as expected.**

## Features

- **Easy Integration**: Quickly integrate the PDF viewer into your application.
- **Responsive Design**: Adapts to different screen sizes.
- **Navigation**: Supports page navigation (next, previous, specific page).
- **Zoom**: Ability to zoom in and out of pages.
- **Performance**: Optimized for performance with large PDF files.

## Installation

To install the PDF Viewer Web Component, run:

```bash
npm install nex-pdf-viewer
```

## Usage

Here's how to use the PDF Viewer Web Component in your application:

### Import the Component

First, import the PDF Viewer Web Component into your application:

```javascript
import PDFViewer from 'next-pdf-viewer';
```

### Use the Component

Then, use the component in your render method:

```javascript
function App() {
  return (
    <div className="App">
      <next-pdf-viewer url="/path/to/your/pdf/document.pdf" />
    </div>
  );
}

export default App;
```

### Props

| Prop          | Type     | Description                              |
|---------------|----------|------------------------------------------|
| `url`         | String   | The URL of the PDF document to display.  |
| `scale`       | Number   | The initial zoom level (default: 1).     |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to PDF.js for providing a powerful PDF rendering library.
- Thanks to the Kit framework for providing an excellent foundation.
- Inspiration and code snippets were taken from various open-source projects.
