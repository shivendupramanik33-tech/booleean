# BOOLEEAN

**The internet's most unnecessary store.**

BOOLEEAN is a joke online store that sells absurd gifts and digital nonsense, priced in Indian rupees.
This repository holds the storefront: one HTML file with the design, code, logo and sample products inside.

## What it does

- Hero with an interactive Emotional Support Rock (follows the cursor, blinks, talks back)
- Six products with artwork: one physical (Emotional Support Rock), five digital
- Product popups with what's included, delivery info and personalisation fields (overthinker name, group chat name, roast certificate text up to 300 characters)
- Cart that remembers items after a refresh, with a flat delivery charge only for the physical rock
- Review form (order ID, clickable 5-star rating, written review), FAQ and Terms sections

## What it does NOT do yet

- **Checkout is not connected.** The button says so and takes no payment. It needs a server endpoint that re-prices the cart and creates a Razorpay order.
- **Reviews are not saved anywhere** until Supabase is configured (`CONFIG` at the top of the script). The three example reviews are labelled demo content.
- No admin dashboard, no digital file delivery, no review photo upload.
- The Terms, Privacy and Refund text is a draft with [bracketed] blanks and has not been checked by a lawyer.

## Run it on your computer

1. Download or clone this repository.
2. Double-click `index.html`. It opens in your browser. No install needed.

## Put it online

GitHub Pages: Settings > Pages > Deploy from a branch > `main` > `/ (root)`.
Keep the `CNAME` file in the repository root if you use a custom domain. Never put secret keys (Razorpay secret, Supabase service-role key) in `index.html`.

## Files

| File | What it is |
|------|------------|
| `index.html` | The whole website (logo is embedded inside) |
| `README.md` | This page |
| `.gitignore` | Tells git which files to never upload |

Sample products and placeholder artwork only. BOOLEEAN is not a registered trademark.
