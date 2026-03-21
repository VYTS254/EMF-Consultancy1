# Email Push Notifications Setup Guide

## Overview
Your contact form now sends submissions to your email: **vitaliswafula211@gmail.com**

To receive instant notifications on your phone, follow these steps:

## Setup Steps

### ✅ Form Configuration (Already Done)
- Web3Forms access key: Configured
- Notification email: vitaliswafula211@gmail.com
- Subject line: 🔔 New Client Message - EMF Consultants

### 📱 Enable Push Notifications on Your Phone

#### For Android (Gmail App):
1. Open the **Gmail app** on your phone
2. Tap the **menu icon** (☰) in the top-left
3. Scroll down and tap **Settings**
4. Select your account: **vitaliswafula211@gmail.com**
5. Tap **Notifications**
6. Enable **Notifications** toggle
7. Set **Notification sound** to something distinct
8. Enable **Vibrate** for immediate alerts
9. Set **Importance** to "High" or "Urgent"
10. Enable **Lock screen** notifications

#### For iPhone (Gmail App):
1. Open **Settings** on your iPhone
2. Scroll down and tap **Gmail**
3. Tap **Notifications**
4. Enable **Allow Notifications**
5. Set **Alert Style** to "Banners" or "Alerts"
6. Enable **Sounds**
7. Enable **Badges**
8. Enable **Show on Lock Screen**
9. Open Gmail app and ensure you're signed in

#### Alternative: Use Default Mail App
If you prefer the default phone mail app:

**Android:**
1. Open **Email/Mail** app
2. Add your Gmail account if not already added
3. Go to **Settings** → **Notifications**
4. Enable notifications with sound

**iPhone:**
1. Go to **Settings** → **Mail** → **Accounts**
2. Add Gmail account if not already added
3. Go to **Settings** → **Notifications** → **Mail**
4. Enable all notification options
5. Set **Fetch New Data** to "Push" in Settings → Mail → Accounts → Fetch New Data

## 🔔 Recommended Settings for Instant Alerts

1. **Enable Priority Inbox** in Gmail to ensure form submissions appear at the top
2. **Create a Gmail Filter** to:
   - Star messages from "EMF Consultants Website"
   - Apply a label like "🔴 URGENT - New Client"
   - Never send to spam
   
### How to Create Gmail Filter:
1. Go to Gmail on desktop
2. Click the search box dropdown (▼)
3. In "From" field, enter: `noreply@web3forms.com`
4. In "Subject" field, enter: `New Client Message`
5. Click "Create filter"
6. Check: ✓ Star it, ✓ Apply label (create "New Clients"), ✓ Never send to Spam
7. Click "Create filter"

## 📧 What You'll Receive

When someone submits the form, you'll get an email like:

```
From: EMF Consultants Website
Subject: 🔔 New Client Message - EMF Consultants

Name: John Doe
Client Email: john@example.com
Phone: +254712345678
Service: Airbnb Tax Advisory
Message: I need help with my Airbnb tax compliance.
```

## ✅ Test Your Setup

1. Open your website
2. Fill out the contact form with test data
3. Submit it
4. Check your phone within 1-2 minutes for the notification
5. If no notification, check:
   - Gmail app notification settings
   - Phone's "Do Not Disturb" mode
   - Gmail spam folder
   - Internet connection

## 🚀 Pro Tips for Better Notifications

1. **Use a distinct notification sound** for Gmail so you recognize client messages immediately
2. **Enable vibration** for when your phone is on silent
3. **Set Gmail as high priority** in your phone's notification settings
4. **Keep Gmail app updated** for best performance
5. **Ensure background data** is enabled for Gmail app

## Troubleshooting

**Not receiving notifications?**
- Check if Gmail app has battery optimization disabled (Android Settings → Apps → Gmail → Battery → Unrestricted)
- Verify notification permissions are granted
- Check if "Do Not Disturb" is blocking notifications
- Ensure Gmail sync is enabled

**Delayed notifications?**
- Disable battery optimization for Gmail
- Set Gmail to sync more frequently
- Check your internet connection

**Messages going to spam?**
- Create the Gmail filter mentioned above
- Mark Web3Forms emails as "Not Spam"

## Alternative: SMS Forwarding (Optional)

If you want actual SMS, you can use:
1. **IFTTT** (If This Then That) - Free
   - Create applet: "If new email from Web3Forms, then send SMS"
2. **Africa's Talking** - Kenya-based SMS service (paid)
3. **Twilio** - International SMS service (paid)

Your form is ready to use! Just make sure push notifications are enabled on your phone.
