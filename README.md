# 🚀 GZBL's Security Blog

This is the source code repository for my personal cybersecurity blog.

**The blog is live and can be viewed at:**

### [https://gzbl-dev.github.io/sec-blog](https://gzbl-dev.github.io/sec-blog)

---

## 🧐 Purpose

This site serves as my public knowledge base, where I publish:
* CTF Writeups (Hack The Box, TryHackMe, etc.)
* Research on security tools (Blue Team & Red Team).
* Study notes and guides on web vulnerabilities.

## 🛠️ Tech Stack

This blog is built and hosted with:
* **Generator:** [Jekyll](https://jekyllrb.com/)
* **Theme:** [Chirpy Theme](https://github.com/cotes2020/jekyll-theme-chirpy)
* **Hosting:** [GitHub Pages](https://pages.github.com/)

---

## ✍️ How to Add a New Post (Notes for myself)

1.  Create a new file in the `_posts/` folder.
2.  The filename must follow the format: `YYYY-MM-DD-title-of-post.md`.
3.  Add the Jekyll front matter to the top of the file:

    ```yaml
    ---
    title: Post Title
    date: YYYY-MM-DD HH:MM:SS +/-TTTT
    categories: [Category]
    tags: [tag1, tag2]
    ---
    ```
4.  Write the rest of the post using Markdown.
5.  Commit and Push. GitHub Actions will automatically deploy it.
