# Horiseon-refactor

Introduction

Horiseon is a SEO (Search Engine Optimization) company based out of San Diego. Our main goal is to improve our customers online presents by helping them reach more customers.

Navigating our Website

1. Header

   - Image header shows our team oriented culture.
   - Provides a short description of our three areas of expertise.

2. Main Body

   - Provides a short description of our three areas of expertise.
   - You can access each section of the body by scrolling down the page OR by using the links within the Navbar.

3. Aside

   - Additional detail on how we help our customers.

4. Footer
   - Copy right and closing detail.

ADDITIONAL COMMENTS

Improving the readability and code.

# Matt Milici Comments

Hello! I highlighted a majority of the updates I made below to the starting file below.

1. HTML Clean Up

   - Changed the title from "Website" to "Milici Horiseon"
   - Included a favicon in the Title for additional custimization.
   - Updated a majority of the div tags to be semantic tags.

     - Added <nav> for the nav bar.
     - Added <aside> for the right column.
     - Added <section>'s for every grouping.
     - Added <footer> to the last section.

   - Added alt descriptions for all images... Incase any image isn't populated on a user screen.
   - I noticed an img tab had an opening and closing tag. We did not need the closing tab because images are self-closing.

2) CSS Clean Up

   - I removed alot of the repetition in the CSS file. There were a lot of declarations that had the same proporties and values. I was able to group these together using a comma. This resulted in less code. Woo!
   - I grouped the CSS Selectors together based off of their layout. For example, everything that impacts the Main Body is grouped together under the header "----- Main Body ---------". This helps understand what elements are going to be impacted when propterty values change.
   -
