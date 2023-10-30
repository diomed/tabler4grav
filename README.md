<h1 align='center'>TABLER</h1>

<p align='center'>
  Minimal theme for <a href='http://github.com/getgrav/grav'>Grav CMS</a>. No dependencies, improved directory structure, optimized build process and freedom to create.
</p>

### Installation

#### [Grav Package Manager](http://learn.getgrav.org/advanced/grav-gpm) (Recommended)

``` sh
$ cd path/to/grav
$ bin/gpm install tabler
$ cd /user/themes/tabler
$ yarn
```

#### [Grav Admin Plugin](https://github.com/getgrav/grav-plugin-admin)

Log in to admin panel go to `Themes > Add` search for Tabler and click `Install`. After that, `Activate` the theme.
> Using this method you will have to manually copy files from `user/themes/tabler/_demo/pages` to `user/pages`

#### Manual

``` sh
$ cd path/to/grav/user/themes
$ git clone https://github.com/diomed/tabler.git
$ cd gravnd-zero
$ yarn
```
> Using this method you will have to manually copy files from `user/themes/tabler/_demo/pages` to `user/pages`

### Usage

1. Start your dev server

2. Run yarn/npm script

  ``` sh
  # Compile .scss, .js, .twig files and add sourcemaps.
  $ yarn dev

  # Same as dev but watches files for changes and runs Browsersync.
  # Once files are saved, they are recompiled and Browsersyn refreshes the browsers.
  $ yarn watch

  # Prepares the files for production minifying them and removing sourcemaps.
  $ yarn production
  ```

> Before starting I recommend to review settings in `webpack.mix.js`

### [Contribute](CONTRIBUTING.md)

See [CONTRIBUTING.md](CONTRIBUTING.md)
