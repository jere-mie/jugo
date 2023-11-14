# Jugo

Jugo is a simple Hugo website that lets you create beautiful and fast web pages without the need for themes. Jugo is ideal for people who want to use Hugo's handy templating features and build system, but don't need themes and don't plan on writing list-form content like blog posts.

Jugo comes with two CSS libraries that help make your HTML look better with minimal effort: [Pico.css](https://picocss.com/) and [Bootstrap's grid system](https://getbootstrap.com/docs/5.3/layout/grid/). Pico.css is a minimalist CSS framework that adds basic styles to your HTML elements without the need for many CSS classes. The Bootstrap grid is a popular framework that provides a responsive grid system for your layout.

*Note that **only** the CSS related to Bootstrap's grid system is included in this project, not the entirety of Bootstrap. bootstrap-grid.min.css only comes out to roughly 51kb, and Pico.css comes out to roughly 72kb.*

## Getting Started

To use Jugo, you need to have [Hugo] installed on your computer. Hugo is a static site generator that transforms your content into a complete website. You can download Hugo from its [official website](https://gohugo.io/) or use your favourite package manager.

Once you have Hugo installed, you can clone this repository or download it as a ZIP file. Then, navigate to the Jugo folder and run the following command to start a local server:

```bash
hugo server
```

You can then open your browser and go to [http://localhost:1313](http://localhost:1313) to see your website in action.

## Deploying Your Website

When you are ready to deploy your website, you can use the `hugo` command to generate the static files in the `public` folder. You can then upload these files to any web hosting service or platform that supports static websites, such as GitHub Pages, Netlify, Vercel, etc.

## License

Jugo is licensed under the [MIT License], which means you can use it for any personal or commercial project as long as you give credit to the original author. Pico.css and bootstrap-grid.min.css are also licensed under the MIT License.
