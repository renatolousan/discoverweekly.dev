<div align="center">
  <a href="https://discoverweekly.dev"><img src="public/favicon/android-chrome-512x512.png" alt="DiscoverWeekly.dev logo" height="160"></a>

  <br/>

  <p><strong>DiscoverWeekly.dev</strong> - The playlists made by devs, every Wednesday.</p>

  <br/>

![Progressive Web Apps](https://img.shields.io/website?label=Progressive%20Web%20Apps&url=https%3A%2F%2Fdiscoverweekly.dev)
[![GitHub release](https://img.shields.io/github/release/peterpeterparker/discoverweekly.dev/all?logo=GitHub)](https://github.com/peterpeterparker/discoverweekly.dev/releases/latest)
[![Tweet](https://img.shields.io/twitter/url?url=https%3A%2F%discoverweekly.dev)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fdiscoverweekly.dev&text=Checkout%20DiscoverWeekly.dev%20by%20%40daviddalbusco%20%F0%9F%A4%9F)

</div>

## Table of contents

- [Contributing](#contributing)
- [Add a new playlist](#add-a-new-playlist)
- [Run the project locally](#run-the-project-locally)
- [License](#license)

## Contributing

Make sure you have a recent version of [Node.js installed](https://nodejs.org/en/) (LTS recommended).

Fork and clone this repository. Head over to your terminal and run the following command:

```
git clone git@github.com:[YOUR_USERNAME]/discoverweekly.dev.git
cd discoverweekly.dev
npm ci
npm run add:playlist
```

## Add a new playlist

`npm run add:playlist` will ask for your name and create a file in `./content/playlists/`.

Continue by editing this generated `Markdown` file.

Have a look at the [CONTRIBUTING.md](./CONTRIBUTING.md) for further information about the edition of your playlist details.

Commit the changes and [open a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## Run the project locally

This project is a [Next.js](https://nextjs.org/) project.

```
npm run dev
```

## License

MIT © [David Dal Busco](mailto:david.dalbusco@outlook.com)
