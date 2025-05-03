# 📰 Blog Preview Card - Frontend Mentor Challenge

# 📌 Overview
This is a solution to the Frontend Mentor Blog Preview Card challenge. 
The goal was to build a responsive and visually appealing card using HTML and CSS to reinforce foundational layout and design principles.


<img src="../assets/images/Blog.png" alt="Blog perview Card Screenshot">

# 🔗 Links
* Live Site: View Live Demo <!-- Replace with your GitHub Pages, Netlify, or Vercel link -->
* Solution: Frontend Mentor Solution Page

# ⚙️ My Process
1. Set up the HTML structure using semantic tags.
2. Applied custom Google Fonts (Figtree).
3. Styled the card using Flexbox for layout and alignment.
4.Implemented a solid, directional box shadow.
5.Positioned avatar and author name using a flex container.

# 🛠️ Built With
* Semantic HTML5
* CSS3
* Flexbox
* Google Fonts
 *Mobile-first responsive design

 # 📚 What I Learned
* How to properly use flexbox to align elements horizontally and vertically.
* Styling box-shadow for strong visual impact on specific sides.
* Using :root and good CSS structure for maintainability.
* Structuring cards that adapt well to different screen sizes.

```html
<div id="btn"> Learning</div>
    <p id ="head">Published 21 Dec 2023</p>
    <h1 class="card-title">HTML & CSS foundations</h1>
    <p class="card-text">These languages are the backbone of every website, defining structure, content, and presentation.</p>
    <div class ="card-profile">
      <img src="../assets/images/image-avatar.webp" alt="Avatar" class="card-image-avatar">
        <div class="card-author">
           <p>Greg Hooper</p>
        </div>
     </div>
```
```css
card-author {
    font-size: 15px;
    font-weight: 800;
    color: #111111;
    margin-left:-500px;
}
.card-profile {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    margin-top: 40px; /* Push to bottom if using flex-column */
    gap: 10px; /* space between avatar and name */
    margin-left: 0;
}
```
# 🔗 Useful Resources
* CSS Flexbox Guide – CSS-Tricks
* MDN Box Shadow Documentation
* Frontend Mentor Community

# 👤 Author
* Name: Meron Teweldebrhan 
* Frontend Mentor Profile:(https://www.frontendmentor.io/profile/MeronTeweldebrhan)
* Website:https://meronpf.netlify.app/
* GitHub:https://github.com/MeronTeweldebrhan

# 🙏 Acknowledgments
Thanks to Frontend Mentor for the challenge and to Per Scholas instructors for their guidance and support throughout my learning journey.

