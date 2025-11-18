# Articles Folder

This folder contains all your articles. Each article is a standalone HTML file.

## How to Write a New Article

### Step 1: Copy the Template
1. Make a copy of `TEMPLATE.html`
2. Rename it to something descriptive (use dashes for spaces)
   - Example: `my-thoughts-on-education.html`
   - Use lowercase and dashes for URLs

### Step 2: Edit Your Article File
1. Open your new article file
2. Replace all the `[PLACEHOLDERS]` with your content:
   - `[ARTICLE TITLE]` - Your article title (appears in browser tab and at top of page)
   - `[DATE]` - Publication date (e.g., November 18, 2025)
   - `[CATEGORY]` - Category tag (Education, Technology, VC, etc.)
   - Replace the body content with your writing

### Step 3: Write Your Content

Use these HTML elements:

#### Paragraphs
```html
<p>Your paragraph text here.</p>
```

#### Headings
```html
<h2>Main Section Heading</h2>
<h3>Subsection Heading</h3>
```

#### Bullet Lists
```html
<ul>
    <li><strong>Point 1</strong> - Description</li>
    <li><strong>Point 2</strong> - Description</li>
</ul>
```

#### Numbered Lists
```html
<ol>
    <li>First item</li>
    <li>Second item</li>
</ol>
```

#### Quotes
```html
<blockquote>
    "Your quote here"
</blockquote>
```

#### Links
```html
<a href="https://example.com">Link text</a>
```

#### Bold Text
```html
<strong>bold text</strong>
```

#### Italic Text
```html
<em>italic text</em>
```

### Step 4: Add to Articles Page
1. Open `../articles.html`
2. Add a new article card in the `<div class="articles-grid">` section:

```html
<article class="article-card">
    <div class="article-meta">
        <span class="article-date">November 18, 2025</span>
        <span class="article-category">Education</span>
    </div>
    <h2 class="article-title">
        <a href="articles/your-article-filename.html">Your Article Title</a>
    </h2>
    <p class="article-excerpt">
        A brief description of your article (2-3 sentences).
    </p>
    <a href="articles/your-article-filename.html" class="read-more">
        Read More <i class="fas fa-arrow-right"></i>
    </a>
</article>
```

### Step 5: Preview
1. Open your article file in a browser to preview
2. Check that all links work
3. Make sure it looks good on mobile (resize your browser)

## Tips for Writing Great Articles

1. **Hook readers early** - Make your first paragraph compelling
2. **Use headings** - Break up long text with H2 and H3 headings
3. **Be concise** - Every word should add value
4. **Add personality** - Let your voice shine through
5. **Use examples** - Concrete examples make abstract concepts clear
6. **Edit ruthlessly** - Write, then cut 20%

## Article Categories

Some suggested categories:
- Education
- Technology
- Venture Capital
- Aerospace
- Music
- Leadership
- Innovation
- Career Advice

Feel free to create your own!

## File Naming Convention

Always use:
- Lowercase letters
- Dashes instead of spaces
- Descriptive names
- `.html` extension

Good: `building-better-schools.html`
Bad: `Article 1.html` or `MyArticle.html`
