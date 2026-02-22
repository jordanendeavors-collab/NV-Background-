# A3 Smarthome — Background Check Authorization Form

Live e-signature background check consent form for CCC Representatives.

- Nevada FCRA / NRS Chapter 598C compliant
- E-SIGN Act (15 U.S.C. § 7001) + NRS Chapter 719
- Full audit trail: IP, geolocation, device fingerprint, SHA-256 checksum
- Submissions emailed to clifton.jordan@a3smarthome.com

## Stack
- Static HTML — zero dependencies, zero build step
- Formspree for email delivery
- Vercel for hosting

## Setup
1. Clone this repo
2. Go to formspree.io → New Form → set email to clifton.jordan@a3smarthome.com
3. Copy your Form ID, replace `REPLACE_WITH_YOUR_FORMSPREE_ID` in index.html
4. Push to GitHub → auto-deploys on Vercel
