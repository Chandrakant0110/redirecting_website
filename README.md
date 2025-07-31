# AutoDM Redirect Service

A secure, lightweight redirect service that safely redirects users to specified URLs with built-in security protections and a clean user interface.

## Features

- Secure redirects with malicious URL blocking
- Multiple URL formats (query parameters and path-based)
- Clean, responsive UI with loading animations
- Fallback manual redirect button
- Built-in security headers and validation

## How to Use

### Query Parameters
```
https://yoursite.com/?redirect=https://example.com
https://yoursite.com/?url=https://github.com
https://yoursite.com/?to=https://google.com
```

### Path-Based URLs
```
https://yoursite.com/https://example.com
https://yoursite.com/https://github.com/username/repo
```

## Setup

1. **Local**: Open `index.html` in your browser
2. **GitHub Pages**: Enable Pages in repository settings
3. **Web Hosting**: Upload `index.html` to your server
4. **Netlify/Vercel**: Connect repository and deploy

## Security

The service blocks redirects to:
- localhost, 127.0.0.1, private IPs
- Non-HTTP/HTTPS protocols
- Malformed URLs

## Customization

- **Styling**: Modify CSS in `index.html`
- **Timing**: Change redirect delay (default: 1.5s) on line 323
- **Branding**: Update title and "AutoDM" references

## License

MIT License - see [LICENSE](LICENSE) file for details.