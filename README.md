READ ME 

Below are the edits  I did in the CSS to create the faux Instagram page. 

Structure and Styling
Global Styles


: Sets base font size to 10px.
*:: before, *::after: Ensures all elements use border-box sizing.



body: Uses 'DM Sans' font, full viewport height, white background, dark gray text.



.container: Centers content with a max width and 90% width for responsiveness.



.profile-image: Styles profile image with dimensions, rounded corners, and a border.


.profile: Uses flexbox for alignment and wrapping.


.profile-user-settings: Uses flex-grow to occupy space.


.profile-user-name: Sets font size and weight.


.profile-edit-btn, .profile-settings-btn: Styles buttons uniformly.


.profile-stats ul: Displays stats horizontally.


.profile-bio: Adds top margin and sets font size.


.gallery: Implements a responsive grid layout.


.gallery-image: Ensures images fill their container while maintaining aspect ratio.

Overlay Feature

.gallery-item: Positions items relatively and makes them clickable.


.gallery-item-info: Hides overlay initially, centers content, and styles it.


.gallery-item-info: Shows overlay on hover using flexbox.


Loader Animation
.loader: Styles the loader with dimensions, border, and animation.


Media Queries
@media screen and (max-width: 900px): Adjusts the profile section for smaller screens.


This CSS code provides a responsive and interactive profile page similar to Instagram.

