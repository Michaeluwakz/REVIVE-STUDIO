# WhatsApp Setup Guide for Nailed By Nadzz Booking Form

## How It Works
When customers fill out the booking form and click "Book Now", it will:
1. Open WhatsApp in a new tab
2. Pre-fill a message with all their booking details
3. They just need to send the message to complete the booking

## Step 1: Get Your WhatsApp Number
1. Open WhatsApp on your phone
2. Go to Settings > Profile
3. Note your phone number (include country code)
4. Example: If your UK number is 07123456789, use "447123456789"

## Step 2: Update Your Website
1. Open `booking.html` in a text editor
2. Find line 665: `const WHATSAPP_NUMBER = "YOUR_WHATSAPP_NUMBER";`
3. Replace `YOUR_WHATSAPP_NUMBER` with your actual WhatsApp number

## Example:
```javascript
const WHATSAPP_NUMBER = "447123456789"; // UK number
// or
const WHATSAPP_NUMBER = "1234567890"; // US number
```

## Step 3: Test Your Setup
1. Save the file
2. Open your website
3. Fill out the booking form
4. Click "Book Now"
5. WhatsApp should open with a pre-filled message
6. Send the message to yourself to test

## What Customers Will See
When they submit the form, they'll get a message like this:

```
🦋 NEW BOOKING REQUEST 🦋

👤 Customer Details:
• Name: Sarah Johnson
• Email: sarah@email.com
• Phone: 07123456789

💅 Service Requested:
• Category: BIAB SETS
• Service: Plain Biab - £35.00

📅 Appointment Details:
• Date: 2025-01-25
• Time: 14:00

📝 Special Requests:
I'd like a natural pink color

---
Booked via Nailed By Nadzz Website
```

## Benefits
✅ **Instant notifications** - You get messages immediately
✅ **No setup required** - Just add your WhatsApp number
✅ **Mobile friendly** - Works on all devices
✅ **Professional format** - Clean, organized messages
✅ **Free forever** - No monthly limits

## Troubleshooting
- Make sure your WhatsApp number includes country code
- Remove any spaces, dashes, or special characters
- Test on both mobile and desktop
- Check that WhatsApp opens correctly

Your booking form will now send all requests directly to your WhatsApp!
