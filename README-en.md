## README.md (English)
### Animated & Stylish Share Buttons

A collection of responsive and stylish social media share buttons with subtle CSS animations (floating and 'breathing' on hover). Color-coded to match the respective brands and easy to integrate into any web project.

#### Features
- Modern & Stylish Design: Clean and contemporary look for your website's sharing options.
- Subtle Animations: Engaging hover effects including a gentle float and a subtle 'breathing' color intensity change.
- Brand Color Integration: Buttons are styled with the official background colors of popular social media platforms.
- Responsive: Adapts seamlessly to different screen sizes and devices.
- Icon-Based: Utilizes SVG icons for crisp rendering on all resolutions (you need to provide your own SVG icons).
- Accessible: Includes sr-only text for screen reader users, ensuring accessibility.
- Easy to Integrate: Simple HTML and CSS structure for quick implementation.
#### Platforms Supported
- Facebook
- Twitter/X
- Email
- Threads
- Mastodon
- (You can easily add more by extending the HTML and CSS)
#### Customization
You can easily customize the appearance and behavior of the share buttons:
- Colors: Modify the background colors in the `.share-[platform]` classes to match your branding or preferred style.
- Button Size: Adjust the `width` and `height` properties of the `.share-button` class.
- Animation Intensity: Change the `translateY` value in the `@keyframes float` and the `rgba` color in `@keyframes breathe` to alter the animation effects.
- Hover Effects: Feel free to experiment with different `transform`, `box-shadow`, and other CSS properties in the `.share-button:hover` rule.
- Add More Platforms: Extend the HTML list with new `<li>` elements and create corresponding CSS rules (e.g., `.share-instagram`) with the platform's brand color.
#### Contributing
Contributions are welcome! If you have ideas for improvements, new animations, or bug fixes, please feel free to submit a pull request or open an issue.
#### License
This project is licensed under the MIT License - see the https://www.google.com/search?q=LICENSE file for details.
#### Acknowledgements
- Inspiration from various UI/UX design patterns for share buttons.
- Use of brand colors for a consistent user experience.


