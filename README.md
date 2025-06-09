# Modern CSS Reset

A modern CSS reset that uses CSS layers for better cascade control and maintainability. This reset provides a clean slate for your styles while maintaining good defaults and accessibility.

## Features

- Uses CSS layers for better cascade control
- Modern browser support
- Maintains accessibility
- Lightweight and performant
- Easy to customize

## Installation

```bash
npm install modern-css-reset
```

## Usage

```html
<link rel="stylesheet" href="node_modules/modern-css-reset/dist/reset.css">
```

Or import in your CSS:

```css
@import 'modern-css-reset/dist/reset.css';
```

## CSS Layers

The reset uses the following layers:

1. `@layer reset` - Base reset styles
2. `@layer defaults` - Sensible defaults
3. `@layer accessibility` - Accessibility-focused styles

## Browser Support

- Chrome 99+
- Firefox 97+
- Safari 15.4+
- Edge 99+

## License

MIT