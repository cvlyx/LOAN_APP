# CrediTrack Authentication Pages

This directory contains separate, standalone authentication pages for the CrediTrack loan management system. Each file is a complete, self-contained HTML page with all necessary CSS (Tailwind CSS) and JavaScript (Alpine.js) embedded within it.

## Files Included:

- `login.html`: User login page with secure authentication form
- `signup.html`: User registration page with comprehensive signup form

## Key Features:

### 🎨 **Design Consistency**
- **Unified Branding**: Updated from "IRM Creditors" to "CrediTrack" to match the dashboard ecosystem
- **Color Scheme**: Uses the same primary (#4361ee), secondary (#3f37c9), and accent colors as the dashboards
- **Typography**: Inter font family for consistency across all pages
- **Glass Effects**: Modern glass-morphism design with backdrop blur effects

### 🌙 **Dark Mode Support**
- **Toggle Functionality**: Dark mode toggle button in the header
- **Persistent Settings**: Dark mode preference is saved to localStorage
- **Consistent Theming**: All elements properly adapt to dark/light themes
- **Smooth Transitions**: Color transitions match dashboard behavior

### 📱 **Responsive Design**
- **Mobile-First**: Optimized for various screen sizes
- **Adaptive Layout**: Split-screen design on desktop, stacked on mobile
- **Touch-Friendly**: Proper touch targets and mobile navigation

### 🔐 **Authentication Features**

#### Login Page (`login.html`):
- Email and password input fields
- Password visibility toggle
- "Remember me" checkbox
- "Forgot password" link
- Form validation
- Redirects to dashboard on successful login

#### Signup Page (`signup.html`):
- Full name, email, and phone number fields
- Password and confirm password with strength validation
- Real-time password matching validation
- Terms and conditions checkbox
- Form validation and error handling
- Redirects to login page after successful registration

### 🔗 **Inter-Functionality**
- **Seamless Navigation**: Links between login and signup pages work perfectly
- **Consistent State**: Dark mode preference persists across page navigation
- **Form Validation**: Client-side validation with user-friendly error messages
- **Dashboard Integration**: Login form redirects to the loan dashboard

### 🛡️ **Security Features**
- **Password Visibility Toggle**: Users can show/hide passwords
- **Form Validation**: Client-side validation for all required fields
- **Secure Styling**: Visual indicators for form states and validation

## Usage:

1. **Open in Browser**: Simply open either `login.html` or `signup.html` directly in your web browser
2. **No Dependencies**: All CSS and JavaScript are embedded - no external files needed
3. **Navigation**: Use the "Sign up" and "Sign in" links to navigate between pages
4. **Testing**: Forms include basic validation and redirect functionality

## Integration:

These authentication pages are designed to work seamlessly with:
- **User Dashboard**: `../standalone_loan_dashboard/dashboard.html`
- **Admin Dashboard**: `../standalone_admin_dashboard/dashboard.html`
- **Landing Page**: `../redesigned_landing_page.html`

## Customization:

You can easily customize these pages by:
- Modifying the Tailwind CSS configuration in the `<script>` tag
- Updating the Alpine.js data and methods
- Changing the form validation rules
- Updating the redirect URLs in the JavaScript

The pages maintain full functionality while being completely self-contained and easy to deploy.

