README
Overview
This CSS code is designed to create a visually appealing profile page layout similar to Instagram. It includes styling for profile sections, a responsive gallery grid for images, and an overlay feature that displays additional information on hover. The key components are organized into sections to maintain clarity and modularity.

Structure and Styling
Root and Global Styles
: Sets the base font size to 10px for easy scaling.
*::before, *::after: Ensures all elements use the border-box sizing model.
Body
body: Uses 'DM Sans' font, a full viewport height, a white background, dark gray text, and padding at the bottom.
Container
.container: Centers the content with a maximum width and 90% width for responsiveness.
Header
header: Adds vertical spacing to the header section.
Profile Section
.profile-image: Styles the profile image with specific dimensions, rounded corners, and a border.
.profile: Uses flexbox for alignment and wrapping, ensuring flexibility and spacing.
.profile-image img: Ensures the image covers its container proportionally.
.profile-user-settings: Uses flex-grow to occupy available space.
.profile-user-name: Sets font size and weight for the username.
.profile-edit-btn, .profile-settings-btn: Styles the buttons uniformly with padding, border, and background.
.profile-stats ul: Displays stats in a horizontal line without padding or margin.
.profile-stats li: Styles individual stats items with font size and line height.
.profile-stat-count: Makes the count bold.
.profile-bio: Adds top margin and sets the font size for the bio section.
Gallery Section
.gallery: Implements a grid layout for the gallery, with dynamic columns and spacing.
.gallery-image: Ensures images fill their container while maintaining aspect ratio.
Overlay Feature
.gallery-item: Positions the gallery items relative and makes them clickable.
.gallery-item-info: Initially hides the overlay content. Centers content within the overlay, positions it absolutely, and styles it with a semi-transparent background and white text.
.gallery-item
.gallery-item-info: Displays the overlay on hover using flexbox.
.gallery-item-likes, .gallery-item-comments: Aligns the likes and comments icons vertically.
Loader Animation
.loader: Styles the loader with specific dimensions, border, and animation.
@keyframes loader: Defines the rotating animation for the loader.
Media Queries
@media screen and (max-width: 900px): Adjusts the profile section for smaller screens, allowing wrapping and padding adjustments.
Notes
The grid-template-columns in the gallery section uses auto-fill and minmax to create a responsive grid.
The display: none property hides elements initially, and display: flex shows them on hover.
Flexbox properties ensure alignment and centering within various sections.
The loader animation is a simple rotating circle.
