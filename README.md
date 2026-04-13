# Web-Project-Milestone-1-
1. Login Page — index.html
Entry point of the app. Users sign in using their Saudi mobile number (+966) and password. New users can register by entering name, phone, city, and password. A demo login is provided for testing: phone 0512345678 / password 123456.
2. Homepage — home.html
Main chef discovery page after login. Contains:
•	Chef photo and full name
 Short bio description including
                     Cuisine specialty and city serving
                     Food tags (e.g. مندي, مشاوي, حلويات)
                     Star rating and years of experience
•	"Book Now" button → opens Booking Modal
3. Booking Modal (inside booking.html)
A 3-step overlay that appears when clicking Book Now on any chef card.
Chef Preview Strip (top of modal — always visible)
•	Chef photo, name, specialty, rating, and price per hour
Food Specialty Gallery
•	Horizontal scroll of food photos showing what the chef specializes in
1 — Event Details
•	Date of event and start time
City and full address
•	Special notes / dietary restrictions
•	Hour selector grid: 2 / 4 / 6 / 8 hours (tap to select)
•	Live price preview updates as hours are selected:
•	Hours × 150 SAR + 30 SAR service fee = Total
 2 — Confirm Booking
•	"Proceed to Payment" button → redirects to payment.html
3. Payment Page — payment.html
Dedicated Mada-only payment page. Contains:
•	Order amount box showing total in SAR
•	Mada logo and badge (only accepted payment method)
•	Card number input with card icon
•	Expiry date and CVV fields (side by side)
•	"Pay Now" button → redirects to success.html
4. Success Page — success.html
Shown after payment is confirmed. Contains:
•	Green checkmark circle
•	"Booking Confirmed!" message
•	Booking reference number (e.g. CL-2026-4821)
•	Chef name and event date summary
•	"Go to My Orders" and "Back to Home" buttons
5. My Orders — orders.html ⚠️ Demo Notice( Might Not Be Included In The Final Project)
•	Shows the user's booking history. 
•	status text (Confirmed / Preparing / Completed)
•	total paid
•	Visual progress bar (stage tracker)
6. About Us — about.html
Presents the ChefLak team with:
•	Team member cards: name, role, short bio
•	Social media links per member (Instagram, X, LinkedIn)
•	Company mission statement
•	Service area note (Khobar, Dammam, Dhahran only)
