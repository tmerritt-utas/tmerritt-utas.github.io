# tmerritt-utas.github.io

## Auto-Cycling Webpage Display

A webpage that automatically cycles through a list of other webpages. It displays the first page and automatically loads the next page after 5 minutes.

### Features

- **Auto-Cycling**: Automatically switches to the next page after 5 minutes
- **Pause/Resume Control**: Pause button to stop and resume the countdown timer
- **Manual Navigation**: Previous and Next buttons for manual control
- **Visual Feedback**: Live countdown timer and page counter

### Usage

Simply open `index.html` in a web browser. The page will start displaying the first URL from the configured list.

### Customization

To customize the URLs that are cycled through, edit the `pages` array in the `PageCycleManager` class constructor in `index.html`:

```javascript
this.pages = [
    'https://www.example.com',
    'https://www.wikipedia.org',
    'https://www.github.com',
    'https://www.stackoverflow.com'
];
```

You can add or remove URLs as needed. The page will automatically cycle through all URLs in the list.
