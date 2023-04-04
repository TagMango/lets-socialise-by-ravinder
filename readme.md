# Let's Socialise Rendezvous (A Singles Meet)

## Creating a new page

1. Copy an existing page (take `pune-8th-april-1.html` for instance)
2. give a meaningful name to the file since that reflects in its hosted url.
3. change `./assets/{IMAGE_PATH}` to correct image file in assets folder (don't forget to get it made by Ashraf bhai)
4. change the price in `var originalPrice = ...;` ideally located at or around line 746.
5. change the time, age range or number of alcoholic drinks in the contents towards the bottom of the page if necessary.
6. upload the html file to `s3 > web-build-files > lets-socialise-ravinder` folder and the associated image to `assets` folder inside it.

## Change Coupon

1. There's an API called `check-ravinder-coupon`, go there and add a new entry into the `coupons` array.
2. add a `discountAmount` (the price deduction caused by that coupon)
3. `applicableFor` takes a regex, simply type in the entire file name (without the `.html`) if you're confused.
4. `code` is the coupon code, please type all of it in capital letters (irrespective of what Vinit sends you)

---

## Thank you.

You're doing God's work. (no, literally!)
