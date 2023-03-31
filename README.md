# Test Task for Circuitmess Job Application

This is a test task completed for a job application at Circuitmess. The task involved redesigning a Shopify section, adding custom metafields to products, adding "Show more" button which loads more products, and adjusting the responsiveness of the section to smaller resolutions and mobile devices.

## Implementation

The following steps were taken to complete the task:

1. The "Featured Collection" section in the Shopify free theme "Dawn" was used as a backbone.

2. The existing product cards were adjusted to match desired design.

3. The "Show more" button function was created from scratch to enable users to view more products beyond the initial three displayed.

4. The responsiveness of the section was adjusted to ensure that it displayed correctly on smaller resolutions and mobile devices.

## Previewing the Section

To preview the section:

1. Add the theme from this GitHub repository to your Shopify store and publish it.

2. Add the following two custom metafields to your products using Shopify's built-in metafields:
    - Minimum age metafield: 
        - Namespace and key: `custom.minimum_age` (final path: `product.metafields.custom.minimum_age`)
        - Data type: `Integer`
    - Product color metafield:
        - Namespace and key: `custom.color` (final path: `product.metafields.custom.color`)
        - Data type: `Color`

3. Add your products to a collection and sort them manually to display "Spencer", "Jay-D", and "Nibble" as the first three products.
    - add color and minimum age to metafields on bottom of product settings

4. On the homepage, add a section called "Featured Collection" and select the collection you created in step 3 in its customization options.

[Video preview](https://gyazo.com/941fa6ff17b11da3ee56d90b9a61c57d)

