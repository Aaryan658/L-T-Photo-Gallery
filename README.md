Photo Gallery

A modern, responsive photo gallery web application featuring a masonry layout with lightbox modal support, dynamic image captions, and smooth animations. Styled using Tailwind CSS and enhanced with custom CSS and Feather Icons, this project showcases a curated gallery of scenic photographs with beautiful, interactive user experience.

Features

1. Responsive masonry grid for displaying images of varied heights

2. Animated image entries and hover effects

3. Lightbox modal for enlarged image viewing with navigation and keyboard shortcuts

4. Captions and subcaptions for each photo (title and location)

5. Feather icons used for navigation and UI

6. Google Fonts for elegant heading and body typography

7. Custom theme using CSS variables for easy style customization

8. Fully client-side, no backend required

Tech Stack

HTML5

1. Tailwind CSS via CDN

2. Custom CSS for extended theming and animation

3. JavaScript (ES6)

4. Feather Icons

5. Google Fonts (Playfair Display, Inter)

6. Picsum.photos for sample royalty-free images

Getting Started

1. Download or clone this repository.

2. Open index.html in any modern browser.

3. No build tools or dependencies required—everything loads via CDN.

File Structure

File	Purpose
index.html	Main HTML page with structure and includes
embedded CSS	Custom theme & gallery styling (in <style>)
embedded JS	Gallery data, masonry logic, modal/lightbox
You can optionally split out the CSS/JS into their own files for easier maintenance.

How It Works
1. The gallery dynamically generates cards using a list of image metadata.

2. Clicking any image opens a modal viewer with navigation and image info.

3. Users can use the modal's next/prev buttons or keyboard arrows for navigation, and Esc to close.

4. The gallery adapts to all screen sizes using Tailwind's responsive column classes.

Customizing
1. Replace or edit the imageData array in the embedded script to use your own photos and captions.

2. Modify color variables in the <style> section under :root to change the theme.

3. Fonts and icons are loaded via CDN for instant styling.

4. Picsum.photos
