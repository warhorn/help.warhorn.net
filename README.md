# help.warhorn.net

Warhorn Help Center - User documentation for [Warhorn](https://warhorn.net)

## Developers

See CONTRIBUTING.md for general contribution guidelines.

This documentation site is hosted on [GitHub Pages](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/getting-started-with-github-pages). It is built with the [Jekyll](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll) static site generator.

### Build and run the site locally

1. Install prerequisites - Git, Ruby, Bundler and Jekyll. See the [GitHub Pages docs](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll#prerequisites) for details.

2. Run the Jekyll server

```sh
$ bundle exec jekyll serve
Configuration file: none
            Source: /Users/bcm/Projects/warhorn/help.warhorn.net
       Destination: /Users/bcm/Projects/warhorn/help.warhorn.net/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
   GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.
                    done in 2.159 seconds.
 Auto-regeneration: enabled for '/Users/bcm/Projects/warhorn/help.warhorn.net'
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop.
```

You can ignore the warning about not finding GitHub API authentication.

3. Navigate to `http://localhost:4000` in your web browser.
