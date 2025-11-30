# Habesha Kitchen Website

A functional restaurant website with user authentication and reservation system.

## Features

### ✅ User Authentication
- **Register Page** (`register.html`): Create a new account
- **Login Page** (`login.html`): Sign in to your account
- **Profile Page** (`web/profile.html`): View your account and reservations
- All user data is stored in browser's localStorage

### ✅ Reservation System
- Make reservations directly from the homepage
- View all your reservations in your profile
- Reservations are saved and linked to your account
- Form validation and date checking

### ✅ Pages Included
1. **Homepage** (`web/index.html`) - Main restaurant website
2. **Login** (`login.html`) - User login
3. **Register** (`register.html`) - New user registration
4. **Profile** (`web/profile.html`) - User dashboard

## How to Use

### For Customers:
1. **Register**: Go to `register.html` and create an account
2. **Login**: Use `login.html` to sign in
3. **Make Reservations**: 
   - Go to the homepage
   - Scroll to "Reservations" section
   - Fill out the form and submit
4. **View Reservations**: 
   - Click "My Profile" in the navigation (when logged in)
   - See all your reservations with details

### For Developers:
- All data is stored in **localStorage** (browser storage)
- No backend server required - works completely offline
- Easy to customize and extend

## File Structure

```
├── web/
│   ├── index.html          # Main homepage
│   ├── profile.html        # User profile page
│   ├── styles.css          # All styling
│   └── images/             # Image assets
├── login.html              # Login page
├── register.html           # Registration page
└── README.md               # This file
```

## Data Storage

The website uses **localStorage** to store:
- **Users**: All registered user accounts
- **Current User**: Currently logged-in user session
- **Reservations**: All reservation bookings

### To Clear All Data:
Open browser console and run:
```javascript
localStorage.clear();
```

## Customization

### Change Colors:
Edit CSS variables in `web/styles.css`:
```css
:root {
  --color-accent: #ffb200;  /* Main accent color */
  --color-bg: #050608;      /* Background color */
  /* ... more variables */
}
```

### Add More Menu Items:
Edit the menu section in `web/index.html`

### Modify User Fields:
Edit the registration form in `register.html` and update the profile display in `web/profile.html`

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge
- Firefox
- Safari
- Opera

## Notes

- This is a **frontend-only** solution using localStorage
- For production use, you'd want a real backend server
- Passwords are stored in plain text (not secure for real apps!)
- All data is stored locally in the browser

## Future Improvements

- [ ] Add password hashing
- [ ] Connect to a real backend API
- [ ] Add email notifications
- [ ] Add reservation cancellation
- [ ] Add admin panel for managing reservations
- [ ] Add payment integration

---

**Made with ❤️ for Habesha Kitchen**

