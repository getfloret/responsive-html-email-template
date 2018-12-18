
## Sending emails directly from your codebase or using a developer service?

For an API service (like Mailgun) **you need to inline the CSS before sending**. See `email-inlined.html` for an example.

https://templates.mailchimp.com/resources/inline-css/

You can use CSS inliner tools like [Responsive CSS Inliner](https://htmlemail.io/inline/) or [Juice](https://github.com/Automattic/juice) to do this automatically.

* Copy all of email.html
* Paste the HTML as the source into the inliner
* Copy the HTML output and use this as the email template you send

## Sending emails using a marketing service like Mailchimp?

Use the template `email.html` as is. They'll put the CSS inline for you when you put together your campaign.
