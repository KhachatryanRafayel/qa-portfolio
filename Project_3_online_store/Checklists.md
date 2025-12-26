## Registration/Login
Positive scenarios
- Login with a valid phone number
- Login with a valid email address
Negative scenarios
-  Empty phone number field
-  Empty email address field
-  Invalid phone number format (e.g. symbols, letters)
-  Invalid email format (e.g., missing @, domain)
-  Too long phone number (more than 15 digits)
-  Too long email address (>255 characters)
-  Incorrect verification code (user cannot log in)
UI/UX
- Placeholder text in input fields is displayed correctly
-  Buttons ("Sign in") are active/inactive correctly depending on field state
-  Error messages are clear and visible
-  Loader/spinner is displayed while waiting for verification code
## Search and Filtering
Positive scenarios
- Search
	- Search for existing products (e.g. “SSD”, “T-shirt”, “shampoo”) → results should show only relevant products.
	- Check that pagination works correctly (after N products, page navigation to the next page appears).
	- Check that search suggestions (if available) appear after entering a few letters.
	- Check that search results show correct product names and images.
- Filtering
	- Search for products (e.g. “Skechers”, “shampoo”, “iPhone 15 Pro Max case”).
	- Then\`
		- Apply Price filter — only products within the selected price range should appear.
		- Apply Color filter — results should contain only products of the chosen color.
		- Combine several filters (e.g., Price + Color) — results must match both criteria.
		- Remove filters — full product list should be restored.
Negative scenarios
- Search
	- Search for a non-existent product (e.g. “qwerty123”, "bbbaaauuuiii" etc) — system should show “No results found”.
	- Search with special characters (e.g. “@#$%”, "\$%&^*" etc) — system should handle it without errors or crashes.
	- Search with an extremely long query (e.g. 300+ characters) — system should show “No results” or cut input safely.
- Filtering
	- Search for products (e.g. “Skechers”, “shampoo”, “iPhone 15 Pro Max case”).
	- Then\`
		- Try to set the minimum price higher than the maximum — system should handle it correctly․
		- Toggle multiple filters — ensure the system doesn’t freeze or break.
UI/UX
- Search bar is clearly visible and accessible on all pages.
- Search results are displayed in a grid with consistent spacing.
- Filters section is easy to access
- Loading spinner appears while applying filters.
## Favorites
Positive scenarios
- In any product list (e.g "Recommended", or "Search Results")
	- Clicking the “Add to Favorites (heart)” button adds the product to the Favorites list.
	- After adding a product, the counter near the heart icon appears (or increases by 1 if products are already added).
	- Clicking the heart icon again removes the product from the Favorites list.
	-  After removing the product, the counter decreases by 1 (or disappears if no products remain).
	- When reloading the page, previously added products remain in Favorites (data is saved).
Negative scenarios
- In any product list (e.g "Recommended, or Search result)
	- Rapid clicking on the eart icon should not cause the counter to increase or decrease incorrectly (no duplicate or negative counts).
UI/UX
- The “Add to Favorites (heart)” icon is clearly visible and consistent in style across product lists.
- When hovered or clicked, the eart icon changes color/state (e.g., filled when added, outlined when not).
- The counter near the heart is displayed and visible.
## Cart
Positive scenarios
- In any product list (e.g "Recommended", or "Search Results")
	- Clicking the “Add to Cart” button adds the product to the Cart list.
	- After adding a product, the counter near the cart icon appears (or increases by 1 if other products are already added).
	- Clicking the "Add to Cart" button again removes the product from the Cart list.
	-  After removing the product, the counter decreases by 1 (or disappears if no products remain).
	- When reloading the page, previously added products remain in Cart (data is saved).
Negative scenarios
- In any product list (e.g "Recommended, or Search result)
	- Rapid clicking on the eart icon should not cause the counter to increase or decrease incorrectly (no duplicate or negative counts).
UI/UX
- The “Add to Cart” button is clearly visible and consistent in style across product lists.
- When hovered or clicked, the  “Add to Cart” button changes color/state (e.g., filled when added, outlined when not).
- The counter near the heart is displayed and visible.
## Order Delivery Options
Positive scenarios
- The chosen Order Pickup Point (OPP) remains selected and its address is displayed.
- Searching a street name shows available OPPs on that street (if any).
- If no OPPs are found on that street, the nearest pickup points are suggested.
- Map markers correspond to real OPPs (clicking a marker shows correct address).
Negative scenarios
-  Entering a very long string in the search field should be handled safely (trimmed or ignored).
UI/UX
- The selected OPP is visually highlighted on the map and in the list.
- Searching a street name changes the map view to that location.
- Map markers are large and clickable.