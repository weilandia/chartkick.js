# Contributing

First, thanks for wanting to contribute. You’re awesome! :heart:

## Questions

Use [Stack Overflow](https://stackoverflow.com/) with the tag `chartkick`.

## Feature Requests

Create an issue. Start the title with `[Idea]`.

## Issues

Think you’ve discovered an issue?

1. Search existing issues to see if it’s been reported.
2. Try the `master` branch to make sure it hasn’t been fixed.

If the above steps don’t help, create an issue. Include:

- Recreate the problem by forking [this gist](https://gist.github.com/ankane/2e92c0ff9c138db7bf482209920466bf). Include a link to your gist and the output in the issue.
- For exceptions, include the complete backtrace.

## Pull Requests

Fork the project and create a pull request. A few tips:

- Keep changes to a minimum. If you have multiple features or fixes, submit multiple pull requests.
- Follow the existing style. The code should read like it’s written by a single person.

If you’re looking for ideas, [try here](https://github.com/ankane/chartkick.js/issues?q=is%3Aissue+is%3Aopen+label%3A%22enhancement%22).

Feel free to open an issue to get feedback on your idea before spending too much time on it.

Also, note that we aren’t currently accepting new chart types.

## Dev Setup

To get started with development and testing:

```sh
git clone https://github.com/ankane/chartkick.js.git
cd chartkick.js
yarn
yarn build

# start web server
yarn global add serve
serve
```

And visit [http://localhost:5000/examples](http://localhost:5000/examples) in your browser.

---

This contributing guide is released under [CCO](https://creativecommons.org/publicdomain/zero/1.0/) (public domain). Use it for your own project without attribution.
