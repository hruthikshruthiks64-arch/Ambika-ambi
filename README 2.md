# Ambika Kitchen’s – Food Ordering Chatbot Demo

A simple, responsive food ordering website for a college project. It runs entirely in the browser and does not need an API key, server, database, or paid AI service.

## Features
- Food menu with category filters
- Add/remove items and update quantities in the cart
- Cart saved in the browser using localStorage
- Rule-based demo chatbot with menu recommendations and ordering guidance
- Checkout form and simulated order confirmation with a demo order ID
- Responsive layout for mobile and desktop

## Run locally
1. Extract the ZIP file.
2. Open the `ambika-kitchens` folder.
3. Double-click `index.html` to open it in a browser.

No installation is required. An internet connection is only needed for the externally hosted food photos and Google Fonts.

## Publish on Vercel
1. Extract the ZIP file.
2. Open https://vercel.com and sign in.
3. Choose **Add New → Project** and import the project from a Git repository, or use Vercel CLI from this folder.
4. For this static project, leave the framework preset as **Other** and leave the build command and output directory blank.
5. Deploy.

## Important demo note
The chatbot is a scripted/rule-based assistant, not a live generative AI model. Checkout creates a sample confirmation only. It does not send an order to a restaurant, collect payment, or store customer details on a server. Menu items and prices are sample data and can be edited in `app.js`.
