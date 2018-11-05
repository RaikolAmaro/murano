# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [1.5.7] - 2018-10-18

## Added
- Support for smart PayPal buttons

## [1.5.6] - 2018-10-04

## Added
- If you want your shoppers to ship to multiple addresses, now they can!

## Fixed
- If you use promo messages you want them to be as useful as possible to your
  shoppers, well they used to not update correctly when the cart content changed
  which was pretty silly. Now they update to help you sell more
  (fixes THEME-1643)
- The review form didn't have a default value selected for the star rating, now
  it does and it means no more reviews without ratings can be submitted

## [1.5.5] - 2018-07-05

## Fixed
- If you had lists in your category descriptions they were not showing up. Now
  they will, list away
- There was some jumpiness on the mobile product pages caused by the accordion
  we updated the styles so that wont happen any more

## [1.5.4] - 2018-06-28

## Added
- BC added a Newsletter summary section to allow you to explain what your
  newsletter is all about, now that summary will show in your footer if you have
  it and the newsletter section enabled in the control panel

## Fixed
- The US isn't the only place with states! Now Mogul allows customers to choose
  from the correct list of states when creating an account (fixes THEME-1608)
- iOS was making it hard for shoppers to add items to the cart if there was an
  optional file upload, we added the appropriate code to avoid that issue and
  now there should be no issues (THEME-1605)

## [1.5.3] - 2018-06-14

## Changed
- Update dependencies to pull from Github

## [1.5.2] - 2018-05-24

## Fixed
- There was some file name mismatching that broke when some people wanted to
  customize the theme. That has been remedied

## [1.5.1] - 2018-05-17

## Fixed
- Leave a review link from email now works! (THEME-1575)

## [1.5.0] - 2018-05-10

## Added
- AMP product pages are now supported in Mogul

## [1.4.4] - 2018-04-19

## Fixed
- No longer show year in copyright of AMP pages

## [1.4.3] - 2018-04-12

## Added
- Add a gift certificate image on the cart (THEME-1496)

## Fixed
- Product Details option now actually hides the details tabs (THEME-1559)

## [1.4.2] - 2018-03-29

## Added
- The checkout and order confirmation pages now support header and footer
  scripts

## [1.4.1] - 2018-03-20

## Fixed
- AMP will match your parent theme colors much better now
- Your image ratios have returned to their regularly scheduled program, we
  apologize for the interruption.

## [1.4.0] - 2018-03-15

## Added
- Welcome to the future of the internet, your theme now supports Google AMP
  category pages, happy mobile search browsing

## [1.3.0] - 2018-03-01

## Fixed
- Weird overlap of description onto related products in certain browsers

## Added
- You asked, we listened. Your GeoTrust seal can now be added to your site
  through theme settings

## [1.2.0] - 2018-02-15

## Fixed
- Product option dropdowns with out-of-stock options set as default led to
unavailable options being displayed, no more!

## Changed
- Update to webpack 3, update the way we interact with Stencil, BC's build
software

## [1.1.2] - 2018-01-18

## Fixed
- Show actual category totals not just the amount of products on the page
- Show variant stock levels

## [1.1.1] - 2018-01-04

## Added
- Pixelpop feature in config.json
- Address/phone number in the footer

## Fixed
- The way we show dropdown product options, you're welcome Safari!

## [1.1.0] - 2017-12-14

## Added
- If your mind is still not made up you can now change the product
options in the cart as well!

## [1.0.10] - 2017-12-07

## Fixed
- Account address form layout so fields are not out of line
- State field required toggle, doesn't just toggle, it only toggles if it's
  supposed to depending on the country

## Changed
- Added title to customized checkbox field to display consistently like other
  checkbox fields on the product page
- Move contact form errors to outside of contact form avoiding form layout
  breaking when an error occurs on forms with flexbox layouts

## Added
- Been missing some detail in your products? Well now you can see SKU, UPC
Manufacturing number and wait for Global Trade Information Number right beneath
the price.. if you want

## [1.0.9] - 2017-11-16
## Fixed
- Account signup forms no longer default to first country
- Account signup forms with a required checkbox no longer require all checkboxes

## [1.0.8] - 2017-11-09
## Changed
- Use stencil-utils v1.0.9
- Add package-lock.json

## [1.0.7] - 2017-10-26
## Added
- None is now an option for non-required multiple choice product options. Go
  ahead, change your mind.

## [1.0.6] - 2017-10-19
## Fixed
- Variant images now disappear from the slideshow/thumbnails when you navigate
  through the slideshow, a disappearing act, how's that for variety?
- Can now use imported gift certificate codes
- Gap on mobile screen slideshow, no more long sullen whitespace when a
  description is absent

## [1.0.5] - 2017-10-05
## Fixed
- Brand pages filter list actually shows all filters now, rather than hiding
  all of them in a black hold in space
- IE is now forced to render in non-compatibility mode, because compatibility
  mode usually breaks everything.. Thanks IE.

## [1.0.4] - 2017-09-21

## Fixed
- You can now make your descriptions beautiful using markup in the product page
  description tab. Now your lists can be bulleted and numbered!
  (fixes THEME-1423)
- Marketing banners now only display one at a time randomly. Your customers will
  be delighted with a different message every time they visit!
- Marketing top and bottom banners now accept markup so you can make your
  banners look pretty. Plus, the content appears in rows instead of columns.
  Which was kind of weird...

## [1.0.3] - 2017-09-07

## Fixed
- Images are no longer go into space infinitely on IE10 and 11 (fixes THEME-1405)
- Pre-order messages now show on product pages (fixes THEME-1404)
- Full description link has been obliterated from the quickshop description
- Content results tab is displayed when clicking on the 'view all results' link
  in the quick search, which is pretty neat
- BC-Core was updated to fix account issues with passwords

## Changed
- Product Grid Image Cropping theme setting has been updated to work with IE and
  Edge (Fill was removed)
- Product image grid ratios have been increased from 400x400 (small) to 800x800
  (medium), so your images are more beautiful

## [1.0.2] - 2017-08-08

### Fixed
- Fixed share buttons and product tabs on product pages from overlapping on iOS
  10.3
- Fixed product images being cut off in iOS 10.3

## [1.0.1] - 2017-08-04

### Fixed
- Fixed mobile filters overlapping on products for iOS
- Fixed misaligned gift wrapping text on cart page and removed extra space
- Fixed shipping calculator not updating state dropdown when recalculating
- Fixed compare button flashing on load for category, brand, and search results
  pages
- Fixed layout of share buttons on product page and blog posts and Google Plus
  icon not displaying
- Fixed compare page rating stars not hiding when ratings display is off in
  store admin
- Fixed homepage carousel pagination dot displaying if there is only one slide

## [1.0.0] - 2017-08-03

### Added
- Screenshots for the theme marketplace to display
- Price information and some meta for the release
