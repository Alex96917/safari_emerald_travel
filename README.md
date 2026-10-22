# Safari & Beyond — Tours & Travel Website Starter

A responsive multi-page travel website starter built with HTML, CSS and vanilla JavaScript.

## Pages
- `index.html` — homepage
- `tours.html` — searchable/filterable tour catalogue
- `tour-details.html?id=mara` — reusable tour details template
- `destinations.html` — destination guide
- `about.html` — about page
- `contact.html` — contact enquiry form (demo only)
- `booking.html` — booking enquiry form (demo only)

## Run locally
1. Extract the ZIP.
2. Open the folder in VS Code.
3. Install/use the VS Code Live Server extension, then right-click `index.html` and choose **Open with Live Server**.
4. You can also open `index.html` directly, but Live Server is better for testing navigation.

## Before publishing
- Replace the demo company name, telephone number, email, tour prices, itinerary and all placeholder claims with accurate business information.
- Images currently load from Unsplash URLs and therefore need an internet connection. For production, download licensed images into `assets/images/` and update image paths.
- Forms validate in the browser only. They do NOT send emails, save enquiries or create confirmed bookings. Connect a backend or form service before accepting real enquiries.
- This is a starter design, not yet a pixel-perfect recreation of the reference. Send screenshots of the reference from top to bottom so the layout can be adjusted to match it more closely.


## Latest enhancements
- Nine tour cards in a responsive, searchable and sortable catalogue.
- Destination guide page: `destination-details.html?id=safari`, `?id=coast`, or `?id=highlands`.
- Booking enquiry now supports a selected tour, travel date, traveller count and a live indicative subtotal.
- Forms remain front-end demos: they do not send email or save bookings until connected to a backend.
- All displayed prices are illustrative sample prices and must be confirmed before taking real bookings.
