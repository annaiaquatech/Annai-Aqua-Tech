# EmailJS Contact Template

Use `docs/emailjs-contact-template.html` as the HTML content for the EmailJS template connected to the contact form.

## Template Settings

- Template name: `Annai Aqua Tech Contact Enquiry`
- Subject: `New {{enquiry_type}} enquiry from {{from_name}}`
- To email: your business inbox, for example `info@annaiaquatech.com`
- From name: `{{from_name}}`
- Reply to: `{{reply_to}}`

## Variables Sent By The App

- `{{from_name}}`
- `{{from_mobile}}`
- `{{from_email}}`
- `{{enquiry_type}}`
- `{{message}}`
- `{{to_name}}`
- `{{reply_to}}`

After creating the template in EmailJS, copy its template ID and replace `YOUR_TEMPLATE_ID` in `src/app/pages/contact/contact.component.ts`.
