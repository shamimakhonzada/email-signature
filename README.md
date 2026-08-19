# Email Signature Template

A clean and professional HTML email signature template designed for personal branding and business communication. This project provides a lightweight signature layout with a logo, name, role title, and quick links to a portfolio, GitHub, LinkedIn, and WhatsApp.

## Project Overview

This template is built as a single HTML file and is optimized for easy use in email clients such as Gmail and Outlook. It is intentionally simple, lightweight, and visually polished so it can be pasted directly into a signature editor without requiring a complex setup process.

The current design includes:

- A compact profile block with a logo
- A professional name and job title
- Contact and portfolio links
- A modern, minimal color palette
- Mobile-friendly, email-safe HTML structure

The signature file is located in:

- `email_signature.html`

---

## Installation & Setup Guide

Follow these steps to use the signature in your email client.

### 1. Open the HTML File in a Web Browser

1. Locate the `email_signature.html` file in the project folder.
2. Double-click the file, or right-click it and choose Open with Browser.
3. The browser will render the signature as a clean HTML design so you can preview it.

You can also open it directly from your browser by using:

- File > Open
- Select `email_signature.html`

This preview is useful before copying the signature into your email app.

### 2. Copy the Rendered Signature

Once the file loads in the browser:

1. Select the signature area with your mouse.
2. Press `Ctrl + C` on Windows or `Command + C` on macOS.
3. Alternatively, use the browser’s copy feature if needed.

This will copy the formatted signature content so it can be pasted into your email client.

> Tip: If the browser does not preserve styling perfectly when pasted, paste it into a plain-text editor first or use the browser’s “copy as HTML” option if available.

### 3. Add the Signature in Gmail

1. Open Gmail in your browser.
2. Click the gear icon in the top-right corner and select See all settings.
3. Scroll down to the Signature section.
4. Click the signature text area.
5. Paste the copied HTML content into the signature box.
6. Save the changes at the bottom of the page.
7. Make sure the signature is selected as your default signature for new messages and replies if desired.

#### Gmail Notes

- Gmail may sometimes strip some styling when pasting HTML directly.
- If needed, use a browser-based signature editor or paste the content into an email draft and then copy the styled version into the signature section.
- It is best to keep the signature concise, readable, and consistent with your professional brand.

### 4. Add the Signature in Outlook

#### Outlook on the Web

1. Open Outlook in your browser.
2. Go to Settings.
3. Select Mail > Compose and reply.
4. Find the Email signature section.
5. Paste the copied signature content into the signature editor.
6. Save your changes.

#### Outlook Desktop

1. Open Microsoft Outlook.
2. Go to File > Options > Mail.
3. Click Signatures.
4. Create a new signature or edit an existing one.
5. Paste the copied content into the signature editor.
6. Set it as the default for new messages and replies.
7. Click OK to save.

### 5. Paste Correctly for Best Results

When placing the signature into your email client:

- Paste it into the signature editor, not in the regular message body.
- Do not paste it into a plain text field if the client offers an HTML-rich editor.
- Confirm the design appears correctly after saving.
- Test it by composing a new email and checking spacing, alignment, and link colors.

---

## Customization Tips

This template is easy to personalize for your own branding. You can modify the HTML directly using any text editor such as VS Code, Sublime Text, or Notepad.

### Update Personal Information

Look for the following content in the HTML file:

- `Muhammad Shamim Shoaib` → Replace with your name
- `Full Stack Developer` → Replace with your role or title
- Portfolio, GitHub, LinkedIn, and WhatsApp links → Replace with your own URLs

### Update the Logo or Image

The logo currently uses:

```html
<img src="https://sshoaib.vercel.app/light-logo.png" alt="Muhammad Shamim Shoaib" width="58" height="58" />
```

To change the image:

1. Replace the `src` value with your own image URL.
2. Update the `alt` text to match your name or brand.
3. Adjust the `width` and `height` attributes if needed.

### Customize Links

Each link is defined in the HTML file using anchor tags such as:

```html
<a href="https://github.com/shamimakhonzada" target="_blank">GitHub</a>
```

Change the URL inside `href` to your own social profiles or portfolio links.

### Adjust Styling

The signature includes inline CSS for color, spacing, and layout. Common edits include:

- Changing text colors
- Updating fonts and sizes
- Tweaking border spacing and padding
- Modifying the logo size
- Changing the link color to match your brand

For example, to change the link color:

```html
style="color: #1a73e8; text-decoration: none;"
```

Replace `#1a73e8` with any hex color that fits your brand style.

### Suggested Personal Branding Improvements

- Add your company name
- Include a phone number
- Include a location or office address
- Replace the placeholder logo with your own brand logo
- Add a website or contact form link

---

## Best Practices

- Keep the signature clean and readable.
- Use a consistent brand color scheme.
- Avoid excessive links or long text blocks.
- Make sure links are valid and working.
- Test the signature in different email clients before sending.

---

## Call to Action

If you find this template helpful, please consider starring the repository on GitHub to show your support.

A star helps encourage future improvements, new templates, and more professional design updates.

Thank you for using this email signature template.

---

## License

This project is provided as a simple HTML template for personal and professional use. If you are sharing or modifying it publicly, feel free to credit the original work.

---

## Summary

This project is a practical, polished, and easy-to-customize email signature template suitable for developers, freelancers, and professionals seeking a minimal but effective online identity in their email communications.
