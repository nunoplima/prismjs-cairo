# `prismjs-cairo`

Cairo syntax highlighting for [react-syntax-highlighter](https://github.com/react-syntax-highlighter/react-syntax-highlighter#readme) and [refractor](https://github.com/wooorm/refractor#readme).

## Installation

```bash
npm install prismjs-cairo
```

## Usage

```javascript
import { PrismLight } from 'react-syntax-highlighter';
import cairo from 'prismjs-cairo';

PrismLight.registerLanguage('cairo', cairo);
```
or
```javascript
import { refractor } from 'refractor'
import cairo from 'prismjs-cairo'

refractor.register(cairo)
```


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome. Please check the issues to see how you can help.
