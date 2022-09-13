
<div align="center">
    <h1>Introduction </h1>
    <p>Toucaan is a <em>stack-agnostic vanilla styling framework for mobile apps and the web</em>.</p>
    <h1>Welcome to Intrinsic Design with:</h1>
    <a href="https://toucaan.com" rel="follow">
        <img src="header.svg" width="800">
    </a>
</div>

## Getting Started

##### Step-1
The first step is to add this repository at the root of your project, like so:

```bash
    $ git submodule add https://github.com/Toucaan/toucaan
```

That's it!

This one command above will add the Toucaan submodule to your project. Now you can start designing your app and go deep into each medium for intrinsic functionality. 

```bash
    $ git status
    On branch master
    Your branch is up-to-date with 'origin/master'.

    Changes to be committed:
    (use "git reset HEAD <file>..." to unstage)

        new file:   .gitmodules
        new file:   toucaan
```

> Notice the new `.gitmodules` file at the root. This file stores the mapping between your project’s URL and Toucaan. Commit it to your project.


##### Step-2
Open the `desktop.scss` file at `toucaan/app/desktop/` on your favorite editor and scroll to the bottom. Start writing your application css!

```css

/***** App specific style below. ******/

@import '../../palette/colors';

/* Samples:

@import './components/header';

@import './components/main';

@import './components/footer';

@import './components/hero';

@import './forms/login';

and so on… ****/

```

Move on to `app/mobile/mobile.scss` next to design for the phone specifically. 

Glance through the remaining subfolders and the `.scss` files that were added to your project. These will contain all the styling code for your apps across smartwatches, mobile phones, tablets (and foldables/bendables), electric vehicles, desktops, and smart TVs.

## Detailed Documentation
Documentation for Toucaan is available over [here](https://toucaan.com).

**_Remember, if Toucaan, then you-can-too!_** 🥳.

## Contribution and PRs 

- Please do not make any changes to this repo directly, and 
- Do not submit any PRs on this repo directly.

All your recommendations, fixes, or "research" on the topic of intrinsic design must be submitted to the following [repository](https://github.com/Toucaan/toucaan.research) instead.

## Getting started

Go here on the [documentation](https://www.toucaan.com/docs/getting-started) to start using Toucaan on your app project quickly.

## License

MIT Standard License

The Parity Public License 7.0.0.