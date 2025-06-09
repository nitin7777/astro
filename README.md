# Astrology App

This is a React-based astrology application. In addition to the basic western zodiac sign it now includes:

- **Numerology**: calculates a simple Life Path number using your birth year, month and day.
- **Vedic Moon Astrology**: approximates your Vedic (moon) sign by shifting the western zodiac one sign back.
- **Palmistry**: open your webcam and capture a picture of your palm for a basic reading using simple line detection.

## Running

Start a small Node server and open the app in your browser:

```bash
node server.js
```

Then navigate to <http://localhost:3000>.

The page now supports signing up with your Google account. Create a Google OAuth client and replace `YOUR_GOOGLE_CLIENT_ID` in `index.html` with your client ID. After signing in you can view your personal astrology profile. If you prefer not to sign in, click **Continue as Guest** when prompted.

Enter your birth month, day and year and click **Calculate** to see your western sign, Vedic sign and Life Path number.

To try palmistry, click **Open Camera**, position your hand in view and capture a photo. The app will analyze the lines in the image and display a short palm reading.
