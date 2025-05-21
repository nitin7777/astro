# Astrology App

This is a React-based astrology application. In addition to the basic western zodiac sign it now includes:

- **Numerology**: calculates a simple Life Path number using your birth year, month and day.
- **Vedic Moon Astrology**: approximates your Vedic (moon) sign by shifting the western zodiac one sign back.

## Running

Start a small Node server and open the app in your browser:

```bash
node server.js
```

Then navigate to <http://localhost:3000>.

The page now supports signing up with your Google account. Create a Google OAuth client and replace `YOUR_GOOGLE_CLIENT_ID` in `index.html` with your client ID. After signing in you can view your personal astrology profile.

Enter your birth month, day and year and click **Calculate** to see your western sign, Vedic sign and Life Path number.
