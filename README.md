# Open Civic Tech Camp Portfolio

A simple, static portfolio website showcasing civic tech projects and community contributions.

## 🌟 About

This is a lightweight, static HTML website that serves as a central hub for Open Civic Tech projects. The site features a clean, modern design with:

- Profile section for @civictechie
- Project cards with descriptions and links
- Responsive design that works on all devices
- Easy navigation between project pages

## 🚀 Getting Started

### View the Site

Simply open `index.html` in your web browser to view the homepage.

### File Structure

```
/
├── index.html                      # Main homepage with project cards
├── nyc-311-chat-assistant.html     # NYC 311 project detail page
└── README.md                       # This file
```

## 🤝 Contributing

We welcome contributions from the civic tech community! If you'd like to add your project to this portfolio:

### How to Submit Your Project

1. **Fork this repository**
2. **Create your project page** (HTML file)
   - Use the existing project pages as templates
   - Keep the design consistent with the main site
   - Ensure your page is self-contained (or use relative links)
3. **Add your project card to `index.html`**
   - Copy one of the existing project card blocks
   - Update the title, description, and link
   - Add appropriate badge tags
4. **Submit a Pull Request**
   - Include a brief description of your project
   - Tag your PR with `new-project`

### Project Card Template

Add this to the `.project-cards` section in `index.html`:

```html
<a href="your-project-page.html" class="project-card">
    <h2>🎯 Your Project Title</h2>
    <p>A brief description of your civic tech project and what problem it solves.</p>
    <div class="project-meta">
        <span class="badge">Technology</span>
        <span class="badge purple">Category</span>
        <span class="badge blue">Tag</span>
    </div>
</a>
```

## 📋 Project Guidelines

When submitting your project page, please ensure:

- ✅ Your HTML is valid and well-formatted
- ✅ The page is responsive (works on mobile/tablet/desktop)
- ✅ All links and resources work correctly
- ✅ The design is consistent with the existing site aesthetic
- ✅ Your project description is clear and concise
- ✅ You include relevant tags/badges for categorization

## 🎨 Design Philosophy

This site maintains a clean, accessible design using:

- Gradient backgrounds (#667eea to #764ba2)
- Clear typography with system fonts
- Card-based layouts
- Smooth animations and hover effects
- Mobile-first responsive design

## 📦 Technologies Used

- HTML5
- CSS3 (Grid, Flexbox)
- Vanilla JavaScript (for interactive features)
- No external dependencies or frameworks

## 🏗️ Current Projects

1. **The Bridge Bot Project** - AI assistant for families of kids with Autism
2. **Equitable Mapping Design Challenge** - Hackathon for mapping inequality
3. **NYC 311 Chat Assistant** - Educational chatbot workshop materials

## 📝 License

This project is open source and available for civic tech community use.

## 🙋 Questions?

For questions or support, please open an issue in this repository.

---

**Built with ❤️ for opencivic.tech by Femmecubator**
