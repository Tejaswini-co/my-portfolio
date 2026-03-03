# Contact Form Email Setup Guide

Your contact form is now configured to send emails using **Formspree**. Follow these steps to activate it:

## 📧 Setup Steps (Takes 2 minutes):

### 1. Create Free Formspree Account
- Go to: **https://formspree.io/**
- Click "Get Started" or "Sign Up"
- Sign up with your email (231210044@nitdelhi.ac.in) or GitHub

### 2. Create a New Form
- After logging in, click **"+ New Form"**
- Name it: "Portfolio Contact Form"
- Click "Create Form"

### 3. Get Your Form Endpoint
- You'll see a form ID like: `https://formspree.io/f/xyzabc123`
- Copy the **entire URL** (including the random code at the end)

### 4. Update Your Portfolio
- Open `index.html`
- Find this line (around line 319):
  ```html
  <form class="contact-form" id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  ```
- Replace `YOUR_FORM_ID` with your actual form ID
- Example:
  ```html
  <form class="contact-form" id="contactForm" action="https://formspree.io/f/xyzabc123" method="POST">
  ```

### 5. Save and Test
- Save the `index.html` file
- Open your portfolio in browser
- Fill out the contact form and click "Send Message"
- Check your email (231210044@nitdelhi.ac.in) for the message!

## ✨ Features Now Available:

✅ **Email notifications** - Messages sent to your email
✅ **Loading spinner** - Shows while sending
✅ **Success/Error messages** - User feedback
✅ **Email validation** - Prevents spam
✅ **Mobile responsive** - Works on all devices

## 🎯 Formspree Free Tier:

- ✅ **50 submissions/month** (perfect for portfolio)
- ✅ Spam filtering
- ✅ Email notifications
- ✅ No credit card required

## 🔄 Alternative Option (No Setup Required):

If you prefer a simpler solution without signing up, I can change the form to use a direct "mailto" link instead. Just let me know!

---

**Need help?** Let me know if you have any questions during setup!
