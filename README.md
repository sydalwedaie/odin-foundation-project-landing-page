# Landing Page Project - The Odin Project, Foundation

## What is This?

This is the solution to the [Landing Page challenge](https://www.theodinproject.com/lessons/foundations-landing-page) from The Odin Project. I built this project using the [Zenful Template](https://github.com/sydalwedaie/zenful-template), which I created to speed up my practice projects like this one. It uses [Vite](https://vitejs.dev/guide/) for the build process, [Tailwind CSS](https://tailwindcss.com/) for styling, and [Handlebars](https://handlebarsjs.com/) as a minimal templating engine.

## What I Learned

The main objective of this project is learning to use Flexbox for layouts. Specifically, I learned that after setting the flex-direction to column and horizontal centering with align-items, the size of the container is adjusted to the size of the content. That is why I needed to specify the width on the child element to force it to the desired width.

TailwindCSS feels weird, but satisfying. One needs to get used to writing utility classes directly in the HTML, and sometimes repeat them for common components. However, I can see its benefit in a large project; the least of which is letting go of coming up with unique class names!

Also, TailwindCSS is really meant to be used in a framework like React. Using _Handlebars_ has been a good enough alternative for this project. I could separate the different sections into components, which helped with keeping the HTML manageable with those Tailwind classes. It also helped with avoiding repetition of those classes for things like the nav links.

I used the Netlify CLI to set up a rudimentary CI/CD workflow. After pushing to GitHub, run `netlify init` and follow the onscreen instructions. From there, you will be able to update your live website by simply running `git push`.
