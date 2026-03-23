# yixinhuang48.github.io

Personal academic website for Yixin Huang — Research Assistant at UCSD Hao AI Lab, focused on LLM systems, evaluation, and GPU-accelerated ML infrastructure.

Live at: [yixinhuang48.github.io](https://yixinhuang48.github.io)

## Structure

```
.
├── index.html          # Main page (About, Projects, Blog, Announcements, Contact)
├── style.css           # Primary stylesheet
├── styles.css          # Additional styles
├── script.js           # Navigation and interactivity
├── yixin_resume.pdf    # Current resume (update as needed)
├── my_photo.jpg        # Profile photo (full size)
├── my_photo_small.jpg  # Profile photo (compressed)
└── blog/
    └── context-learn-in-public.html   # Blog post: Context & Learn in Public
```

## Adding content

**New blog post:** Create a new HTML file in `blog/`, then add a `<article class="blog-card">` entry in `index.html` under `#blog`, and a matching `<article class="announcement-card">` under `#announcements`.

**Update resume:** Replace `yixin_resume.pdf` and commit.

**New project:** Add a `<div class="project-card">` block in the `#projects` section of `index.html`.
