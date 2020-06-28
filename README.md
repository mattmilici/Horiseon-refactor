# Horiseon-refactor

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
     - Footing already existing so no change there.

   - Added alt descriptions for all images... Incase any image isn't populated on a user screen.
   - I noticed an img tab had an opening and closing tag. We did not need the closing tab because images are self-closing.

2) CSS Clean Up

   - I removed alot of the repetition in the CSS file. There were a lot of declarations that had the same proporties and values. I was able to group these together using a comma. This resulted in less code. Woo!
   - I grouped the CSS Selectors together based off their layout. For example, Everything that impacts the Main Body is grouped together under the header "----- Main Body ---------". this helps understand what elements are going to be impacted when propterty values change.
   -
