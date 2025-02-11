# Flux Adopters

So you and your organisation are using Flux? That's great. We would love to hear from you! 💖

## Adding yourself

In this directory are a number of YAML files where you just need to add an entry for your company and upon merging it will automatically be added to our website.

Simply follow these steps:

1. (Optional) Add the logo of your organisation to `adopters/logos`. Good practice is for the logo to be called e.g. `<company>.png`.
1. Find the right `adopters/<project>.yaml` file. If you use e.g. Flux v2, this should be `adopters/flux-v2.yaml`.
1. Please add an entry to the file like this:

  ```yaml
      - name: Xenit
        url: https://xenit.se/
        logo: logos/xenit.png
  ```

1. It's really just the `name` of the organisation, `url` that links to its homepage, and the path to the `logo`. This can link off to `https` links too.
1. Save the file, `git add` all relevant files and commit using `git commit -s` (this is important because of [DCO](/contributing/#certificate-of-origin)).

Push this as a PR to `fluxcd/website` and a preview build will turn up.

Thanks a lot for your being part of our community - we very much appreciate it!

### Addendum

`/adopters/logo/logo-generic.png` is a slightly modified Flux logo.
