# Sample Hugo Site

A sample static website built with [Hugo](https://gohugo.io/) using the [YinYang](https://github.com/joway/hugo-theme-yinyang) theme. See its preview [here](https://gigaarpit.github.io/sample-hugo-site/)

## Quick Start

### Prerequisites

- Hugo (extended version recommended)
- Git

### Setup

- Create a new repo on GitHub, and clone it on your computer

- [Download](https://github.com/gigaArpit/sample-hugo-site/archive/refs/heads/main.zip) content of this repo in the folder of above repo on your computer

- Start the development server:

   ```bash
   hugo server
   ```

### Add Content and Configuration

- The site configuration is managed in `hugo.toml` file.

- You can add new posts manually by creating a markdown file in the `content/posts` folder.

- Use the following front matter format

```markdown
    +++
    title = "Burn the Default"
    date = "2025-06-06"
    +++
```

## Deployment

This site can be deployed to various platforms including Netlify, Vercel, Cloudflare Pages etc. 

We have already added [a GitHub Action](.github/workflows/hugo.yml) in this repo which can automatically deploy it on the GitHub pages. To activate this GitHub Action, go to the *Settings -> Pages* of your repo, and set the build source to "GitHub Actions" under the *Build and deployment* heading. Your site will be deployed automatically every time you push some content to your repo. You can also link your custom domain to this deployed site.

## Credit and License

This site uses the [YinYang theme](https://github.com/joway/hugo-theme-yinyang) which provides clean and minimal design.

This project is open source and available under the [MIT License](LICENSE).

## Author

**Arpit Gupta**

- Twitter: [@gigaArpit](https://x.com/gigaArpit)
- GitHub: [gigaArpit](https://github.com/gigaArpit) 