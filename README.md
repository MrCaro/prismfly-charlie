# Prismfly Shopify Code Challenge - Charlie

## Features

Added a `collection filters` section that allows to

- Load products based on collection type without refreshing the page
- The desktop `tap/filter` and mobile `dropdown` are synced i.e if you select `Bedroom` on desktop and you resize your screen it will show the `Bedroom` as the selected filter (dropdowmn)
- Users can manually add Collections to the `section`
- The AJAX request is cache for better performance
- Styles were loaded from the collections page to avoid rewriting code (DRY approach)
- Doesn't create conflicts with other sections within the `home page`.