WEXIO EMAIL SIGNATURES (hosted-image version for Gmail)
=======================================================

Gmail rejects signatures with embedded images because they exceed its size
limit. This version keeps the images as separate files and links to them, so
the signature itself is tiny and Gmail accepts it.

STEP 1 - Upload the images
  Upload every file in the "images" folder to a PUBLIC location on your web
  host or CDN (they must load without a login). For example:
     https://wexio.io/assets/email-signature/wexio-wordmark.png
     https://wexio.io/assets/email-signature/icon-linkedin.png   ...etc
  Keep the file names exactly as they are.

STEP 2 - Point the HTML at your images
  Open john.html and vasyl.html in a text editor. Find every instance of
     https://REPLACE-WITH-YOUR-IMAGE-FOLDER-URL
  and replace it with the folder URL where you uploaded the images
  (NO trailing slash), e.g.  https://wexio.io/assets/email-signature
  A single find-and-replace does all of them.

STEP 3 - Add to Gmail (do this on a computer, not the phone app)
  - Open the edited john.html in a browser.
  - Select the whole dark card (from its top-left corner down past the
    tagline) and copy.
  - Gmail > gear icon > See all settings > General > Signature.
  - Create/select a signature, paste, then Save Changes at the bottom.
  Repeat with vasyl.html in Vasyl's Gmail account.

Both the calendar and "BOOK A DEMO" link to each person's cal.com page;
wexio.io and the social icons are linked too. Confirm cal.com/wexio/john
exists before shipping.

Tip: prefer a real transactional/asset host over Google Drive links - Drive
"share" links are not direct image URLs and won't render in email.
