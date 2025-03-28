HomesbyEnglish-404
Homes by English - Custom Error Page
Overview
This repository contains the custom error page that is displayed when the Homes by English website is offline. The page is designed to inform visitors that the site is temporarily unavailable while maintaining a professional appearance.
Purpose
At Homes by English, we occasionally need to perform maintenance on our website to improve our services. During these maintenance periods, our main website may be temporarily offline. Rather than showing a generic error message, this custom page provides a more professional and informative experience for our visitors.
Implementation
This page is served through Cloudflare Workers when our main site is unavailable. The Worker detects when our origin server is unreachable and automatically redirects visitors to this custom error page.
Files

index.html - The main error page
/css - Stylesheet directory
/js - JavaScript directory
/images - Image assets
/fonts - Custom fonts

Maintenance
To update the error page, simply modify the files in this repository and commit the changes. The changes will be automatically reflected when the page is displayed.
Contact
For any questions or concerns regarding this repository, please contact: info@homesbyenglish.com
