# St. Luke Knights of Columbus Website
## Council #14895 - Indianapolis

A modern, multi-page website for St. Luke Knights of Columbus with warm, community-focused design.

---

## 📁 File Structure

```
kofc-site/
├── index.html          # Home page with hero and overview
├── about.html          # Council history and charitable causes
├── events.html         # Meeting schedule and event calendar
├── volunteer.html      # Volunteer opportunities
├── join.html           # Membership information
├── contact.html        # Contact info and donations
├── styles.css          # Shared stylesheet for all pages
└── README.md           # This file
```

---

## 🎨 Design Features

- **Warm Color Palette**: Earth tones (brown, gold, cream) for a welcoming feel
- **Classic Fonts**: Crimson Pro and Lora serif fonts for traditional look
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Consistent Navigation**: Easy movement between all pages
- **Professional Layout**: Clean, organized content presentation

---

## 📄 Page Contents

### **index.html** (Home Page)
- Hero section with council name
- Four core principles (Charity, Unity, Fraternity, Patriotism)
- Quick overview of activities
- Call-to-action buttons

### **about.html** (About Us)
- Knights of Columbus history
- Council 14895 background
- Primary causes (Special Olympics, Gibault)
- Full list of charitable organizations supported
- How funds are raised

### **events.html** (Events & Meetings)
- Regular meeting schedule
- Complete 2026 calendar
- Annual recurring events
- Event descriptions and dates

### **volunteer.html** (Volunteer)
- 12 different volunteer opportunities
- Detailed descriptions
- Sign-up links via email
- Impact statistics

### **join.html** (Join Us)
- Membership requirements
- Benefits of joining
- Step-by-step joining process
- What to expect as a member
- FAQs

### **contact.html** (Contact)
- Email and location information
- Meeting times
- Donation section with preset amounts
- Links to related organizations

---

## ✏️ Customization Guide

### **Update Content:**

1. **Replace Placeholder Images**
   - Look for sections with gradient backgrounds and text like "Add your photo here"
   - Replace with actual images using: `<img src="your-image.jpg" alt="Description">`

2. **Add Officer Information**
   - Currently in `about.html` or can be added to `contact.html`
   - Add officer cards with names, roles, and contact info

3. **Update Events**
   - Edit `events.html` to add/remove events
   - Keep the 2026 calendar current

4. **Customize Colors** (in `styles.css`)
   ```css
   :root {
       --primary: #8B4513;    /* Main brown */
       --secondary: #D4AF37;  /* Gold accent */
       --accent: #C85A3C;     /* Red-brown */
   }
   ```

5. **Add Your Logo**
   - Replace the ✠ symbol in hero sections
   - Use: `<img src="logo.png" alt="Council Logo">`

---

## 🚀 Deployment Options

### **Option 1: GitHub Pages (FREE)**
1. Create GitHub account at github.com
2. Create new repository named `kofc-website`
3. Upload all files from `kofc-site/` folder
4. Go to Settings → Pages
5. Select "main" branch and Save
6. Your site will be live at: `https://[username].github.io/kofc-website`

### **Option 2: Web Hosting Service**
Upload files via FTP to any web host:
- **Bluehost** (~$3-10/month)
- **HostGator** (~$3-10/month)
- **SiteGround** (~$4-15/month)

### **Option 3: Church/Parish Server**
Ask your parish IT if they can host the site on the St. Luke domain.

---

## 📧 Email Links

All volunteer and contact forms use `mailto:` links to council14895@gmail.com.

To change the email address:
1. Search for `council14895@gmail.com` in all HTML files
2. Replace with your preferred email address

---

## 💳 Donation Integration

The donation button currently shows an alert. To accept real payments:

1. **PayPal Button**
   - Create button at PayPal.com
   - Replace the `processDonation()` function with PayPal code

2. **Stripe**
   - Sign up at Stripe.com
   - Use Stripe Checkout integration

3. **Square**
   - Create Square account
   - Use Square Payment Forms

4. **Diocesan Giving Platform**
   - Many dioceses have approved platforms
   - Link directly to their donation page

---

## 🗺️ Add Google Maps

In `contact.html`, replace the map placeholder with:

```html
<iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3057.123456789!2d-86.123456!3d39.987654!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zM0KCsDU5JzAzLjYiTiA4NsKwMDcnMjQuNCJX!5e0!3m2!1sen!2sus!4v1234567890123!5m2!1sen!2sus"
    width="100%" 
    height="400" 
    style="border:0; border-radius: 12px;" 
    allowfullscreen="" 
    loading="lazy">
</iframe>
```

Get your embed code from Google Maps:
1. Search for St. Luke Catholic Church
2. Click "Share"
3. Click "Embed a map"
4. Copy the HTML code

---

## 📱 Testing on Mobile

Before going live, test on:
- iPhone/Android phone
- iPad/tablet
- Desktop browser

Make sure:
- Text is readable
- Buttons work
- Navigation functions
- Images load properly

---

## 🔧 Troubleshooting

**Problem**: Pages look unstyled
**Solution**: Make sure `styles.css` is in the same folder as HTML files

**Problem**: Navigation links don't work
**Solution**: Ensure all file names match exactly (case-sensitive on some servers)

**Problem**: Emails don't work
**Solution**: Check that email client is set up on the computer/device

---

## 📞 Need Help?

- **For technical questions about the website**: Email the developer who created this
- **For Knights of Columbus questions**: council14895@gmail.com
- **For web hosting help**: Contact your chosen hosting provider's support

---

## 📝 Future Enhancements

Consider adding:
- Photo gallery with actual event photos
- Online RSVP forms for events
- Newsletter signup
- Member login area (requires backend)
- Blog/news section for announcements
- Social media integration

---

**Built with care for Council #14895**
*May your charitable work continue to bless the Indianapolis community!*
