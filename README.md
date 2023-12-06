# anti-phishing-opener
A web page to prevent phishing by informing the user about the destination URL

A user ordinarily needs to inspect a URL by hovering over it. The text of the URL would then be displayed in a small font in their email or browser. This open source project will intercept the click and display available information about the URL, including:

- Using a larger font
- The contents of any TLS certificate
- A lookup of the URL against suspected malicious hosts
- A preview of the URL
- Breaking up the URL into segments in order to prevent attacks that confuse by:
  - substituting trusted-domain.untrusted-domain.tld for trusted-domain.tld.
  - substituting untrusted-domain.tld/trusted-domain for trusted-domain.tld/
- Calling attention to non-TLS http URLs (rather than TLS+HTTPS)
- Being actively maintained and iteratively improved

For privacy:
- The site will have a strong no-cookie no-telemetry policy
- All features of the site will be open source and available by hosting an independent clone

## Requirements

Accepts as input:
* A URL

Output:
* User clicks through to the destination link
* User reports suspected phishing

## Status

For now this is a placeholder. By making it public before I fill in the features I am putting myself on the spot to get the work done.

Help wanted:
- UX wireframes
- UI visual design
- Web back end code
- Web front end code
- Dockerization
- DevOps for build, deployment, and hosting

Support wanted:
- Funding
- Web hosting

