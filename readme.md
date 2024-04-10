# Simple Markdown + HTML

![Simple Markdown + HTML](https://placehold.co/1200x630?text=Simple%5CnMarkdown+%2B+HTML)

This project demonstrates a simple way to display Markdown content alongside HTML using the `index.html` file. The HTML file fetches and renders the Markdown content from the `readme.md` file.

## File Structure

```
.
├── index.html
└── readme.md
```

## index.html

The `index.html` file is the main HTML document that loads and displays the Markdown content. It consists of the following sections:

1. **Head**: Contains metadata, SEO tags, and Open Graph/Twitter tags for social media sharing.
2. **Body**: Includes a container element for the rendered Markdown content and the necessary scripts.

The `loadMarkdown` function in the script section fetches the Markdown file specified by `filePath`, converts it to HTML using the Marked library, and inserts the rendered HTML into the `markdown-container` element.

## Configuring SEO and Social Media Tags

To optimize your page for search engines and social media sharing, update the relevant tags in the `<head>` section of `index.html`:

- Modify the `<meta>` tags for description, author, and keywords.
- Update the Open Graph and Twitter tags with the appropriate URLs, titles, descriptions, and images for your page.

## Deploying the Static HTML and Markdown

You can deploy your static HTML and Markdown files using various easy and free hosting providers, such as:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

Choose the provider that best suits your needs and follow their documentation for deployment instructions.

## Customization

Feel free to customize the styles and layout of the `index.html` file to match your desired design. You can modify the CSS in the `<style>` section or link an external stylesheet.

That's it! You now have a simple way to display Markdown content alongside HTML. Enjoy creating and sharing your content!