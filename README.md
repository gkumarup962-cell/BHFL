# Prime Home Loan Desk 🏠

A premium, single-page fintech platform designed for the **Bajaj Housing Finance Prime Home Loan Vertical (₹35 Lakh+)**. It seamlessly connects direct customers and channel partners (DSAs, Aggregators, Connectors) with a real-time eligibility calculator and instant enquiry routing.

## ✨ Key Features

- **Real-Time Calculator:** Instantly calculates EMI, FOIR (Fixed Obligation to Income Ratio), and LTV (Loan to Value) based on BHFL Prime guidelines.
- **Dual Workflows:** Dedicated sections for Customer Enquiries and Partner/DSA Registrations.
- **Instant Email Routing:** All form submissions are instantly routed to authorized emails via Formspree.
- **Premium UI/UX:** Gorgeous mixed Claymorphism and Minimalist design with smooth animations and full mobile responsiveness.
- **Zero Dependencies:** Built with pure HTML, CSS, and Vanilla JavaScript. No build tools or heavy frameworks required.

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Custom Properties, Claymorphism), Vanilla JavaScript
- **Backend/Form Handling:** Formspree API
- **Fonts:** Plus Jakarta Sans (Google Fonts)

## 🚀 How to Run & Deploy

### Local Development
1. Clone or download the repository.
2. Open the `index.html` file directly in any modern web browser.

### Deployment (Vercel / Netlify / GitHub Pages)
1. Upload the `index.html` file to your repository.
2. Connect the repository to Vercel or Netlify.
3. The site will deploy instantly as a static site.

## ️ Configuration

The platform is pre-configured to route all enquiries to the following:

- **Formspree Endpoint:** `https://formspree.io/f/xdeokqja`
- **Routing Emails:** 
  - `saurabh.kumar@bajajhousing.biz`
  - `dekhog1234@gmail.com`

*(Note: If you change the Formspree endpoint, ensure you update the `action` attributes in the HTML forms and the `fetch` URLs in the JavaScript section.)*

##  Calculator Logic (BHFL Prime Guidelines)

- **FOIR Limits:** 
  - DA/Builder Purchase: 75% (Preferential)
  - Resale / Balance Transfer: 60%
  - LAP: 60% (Strict, no deviation for Salaried)
- **LTV Limits:** 
  - Home Loans: Up to 80%
  - LAP: 65% – 75%

##  Disclaimer

This is a proposed independent platform concept. It is not an official portal of Bajaj Housing Finance Limited and is not affiliated unless authorized in writing. Rates, eligibility, and payouts are indicative and subject to lender policy and credit approval.

---

**Connect with Saurabh | SM | Made by Saurabh ❤️**
