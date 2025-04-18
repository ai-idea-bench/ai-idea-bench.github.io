# Academic Project Website Template

This is a clean, modern template for academic project websites. It's designed to showcase research projects, papers, or academic work in an engaging way.

## Features

- Responsive design that works on desktop and mobile devices
- Clean, gradient background with professional styling
- Sections for project title, key points, resources, and team information
- Placeholder for a feature image or diagram
- Easy to customize with your own content

## How to Use

1. Clone or download this repository
2. Edit the `index.html` file to add your project information:
   - Update the title and subtitle
   - Modify the key points to highlight your research contributions
   - Add your team members and affiliations
   - Update the resource links to point to your paper, code, or dataset
3. Replace the image placeholder with your project's key visual
4. Customize the `style.css` file to match your preferred color scheme if needed

## Customization Tips

### Changing Colors

The main gradient background can be modified in the `style.css` file:

```css
body {
    background: linear-gradient(135deg, #1e5799 0%, #2989d8 50%, #7db9e8 100%);
}
```

The accent color (currently gold) for titles can be changed here:

```css
.project-title, .project-subtitle {
    color: #FFC107;
}
```

### Adding Sections

To add more content sections, uncomment and modify the additional-content div:

```html
<div class="additional-content">
    <!-- Add your custom sections here -->
</div>
```

### Changing Icons

This template uses Font Awesome icons. You can change any icon by replacing the class names:

```html
<i class="fas fa-database"></i>
```

Find alternative icons at [Font Awesome](https://fontawesome.com/icons).

## Credits

This template was inspired by academic project websites in the machine learning and computer vision communities.

## License

This template is available under the MIT License. Feel free to use and modify it for your academic projects. 