Generate a complete HTML, CSS, and JavaScript solution for a card slider that uses the Swiper.js library. The cards should be displayed in a single horizontal row with navigation buttons (next and previous) to move between cards. The cards should have fixed width, spacing between them, and should be responsive. The swiper container should allow cards to loop, with 4 cards visible at a time. The solution should include:

HTML: The HTML structure should contain a container with cards that have images, names, professions, and "Message" buttons. It should use Swiper's .swiper and .swiper-slide classes to manage the slider functionality.
CSS: The CSS should use Flexbox to display the cards horizontally in a single row, with fixed width for each card, and space between the cards. Each card should have a shadow effect, a hover effect for scaling, and should be centered in the page.
JavaScript: The Swiper initialization should:
Loop through the slides (loop: true).
Have navigation buttons (next and prev).
Have a pagination component with dynamic bullets (pagination: { clickable: true }).
Use responsive breakpoints for different screen sizes, showing 1 card on small screens, 2 cards on medium screens, and 4 cards on large screens.
The CSS and JS should be separate from the HTML to ensure modular and clean code. The card container should be responsive and work across all screen sizes.
