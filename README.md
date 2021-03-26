# Tweeter Project

Tweeter is a simple, single-page Twitter clone.
Primarily a client-side Single Page App (SPA).

## Project Stack
- HTML, CSS, JS, jQuery and AJAX on the client-side
- Node and Express on the server-side

## Project Features
- most recent tweet is displayed on top of a list of tweets
- character counter and tweet length validation
- error message if 140 characters limit is exceeded or  tweet-box blank
- responsive design for an optimized user experience across devices
- animated toggle button to show/hide tweet-box
- fading toggle button appearing when scrolling down to bring the user back up to the top of the page

## Final Product
Desktop view with both toggle buttons shown and tweet-box hidden
!["desktop-view"](https://github.com/leightonchien/tweeter/blob/6c14aac7c038f64b981106fe638833dd7f5416e5/docs/desktop-view.png)

Error message when tweet length exceeded
!["error-message"](https://github.com/leightonchien/tweeter/blob/6c14aac7c038f64b981106fe638833dd7f5416e5/docs/error-msg.png)

Mobile view/responsive design
!["mobile-view"](https://github.com/leightonchien/tweeter/blob/6c14aac7c038f64b981106fe638833dd7f5416e5/docs/mobile-view.png)

## Getting Started

1. Fork this repository, then clone your fork of this repository.
2. Install dependencies using the `npm install` command.
3. Start the web server using the `npm run local` command. The app will be served at <http://localhost:8080/>.
4. Go to <http://localhost:8080/> in your browser.

## Dependencies

- Express
- Node 5.10.x or above
- Body-parser
- Chance
- Moment