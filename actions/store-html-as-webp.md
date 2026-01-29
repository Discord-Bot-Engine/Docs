# Store HTML As WebP

**Description:** Renders provided HTML to a WebP animation and stores as buffer.

**Inputs:**

* HTML text
* Width
* Height
* Duration in seconds
* Store webp buffer in variable

**Outputs:**

* action

**Variable Types:**

* Buffer

**Behaviour:** Uses Puppeteer to render HTML, records the animation for the duration specified, converts the video to WebP, stores the buffer.
