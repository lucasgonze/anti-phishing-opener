# anti-phishing-opener
A web page to prevent phishing by informing the user about the destination URL

A user ordinarily needs to inspect a URL by hovering over it. The text of the URL would then be displayed in a small font in their email or browser. This open source project will intercept the click and display available information about the URL.

Readability will be enhanced. Rather than a tiny text prompt in the bottom left of the browser or mail agent, the text of a URL will be in full view, centered, sized to the browser default.

If the URL uses HTTPS, the certificate contents will be displayed. Data in the certificate will be shown inline. If there is cross-referenced information about the organization owning the certificate, it will be made available inline.

If the URL uses HTTP, with no certificate, this information will be prominently displayed. 

The URL will be broken up for comprehensibility by non-technical users. 
  - Prevent confusion between trusted-domain.untrusted-domain.tld and trusted-domain.tld.
  - Prevent confusion between untrusted-domain.tld/trusted-domain for trusted-domain.tld/

A preview image of the destination URL will be shown. 

The reputation of the remote host will be looked up and displayed. 

As new phishing attacks are created, the site will keep pace by fielding new defenses. 

Privacy issues in the destination site will be shown before the user arrives. 

The country of hosting will be shown.

All features of the site will be open source and available to third-party hosts. 

Attacks using character sets, such as by subtituting zero for capital letter "O", will be defended by displaying the URL in multiple character sets.

If a user suspects phishing, they will be able to report it. 

## Requirements

Accepts as input:
* A URL

Output:
* User clicks through to the destination link
* User reports suspected phishing
* User returns to calling URL

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

