# Gmail Inquiry Sample Page

This is a simple, responsive landing page template that allows users to contact you via email.

### Features

* **Responsive Background**: The background image automatically changes depending on whether the site is viewed on a PC or a mobile device. You can easily replace the `sample_image_pc.png` and `sample_image_phone.png` files.
* **Device-Optimized "Contact Us" Button**: The contact button's behavior adapts to the user's device.
    * **On PC**: It opens a new tab directly to the Gmail compose screen, pre-filled with your email address, a subject line, and body text.
    * **On Mobile**: It launches the user's default email app (e.g., Apple Mail, Gmail app) using a `mailto:` link for a native experience.
* **"Copy Email" Button**: A convenient button allows users to copy your email address to their clipboard with a single click. The button provides feedback by changing its text to "Copy complete!" for two seconds.
* **Easy Configuration**: You can easily customize the contact email address, the default subject line, and the body text by modifying the constants at the top of the `<script>` section.
