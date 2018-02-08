# How to Contribute

Thank you for your interest in contributing to IODIDE! There are many ways to contribute, and we appreciate all of them. Here are some guidelines & pointers for diving into it.

## Code of Conduct

IODIDE has adopted a [Code of Conduct](CODE-OF-CONDUCT.md) that we expect all contributors and core members to adhere to.

## Development

Work on IODIDE happens on Github. Core members and contributors can make Pull Requests to fix issues and add features, which all go through the same review process. We’ll detail how you can start making PRs below.

We’ll do our best to keep `master` in a non-breaking state, ideally with tests always passing. The unfortunate reality of software development is sometimes things break. As such, `master` cannot be expected to remain reliable at all times. We recommend using the latest stable version of IODIDE.

IODIDE follows semantic versioning (http://semver.org/) - major versions for breaking changes (x.0.0), minor versions for new features (0.x.0), and patches for bug fixes (0.0.x).

We keep a file, [CHANGELOG.md](CHANGELOG.md), outlining changes to IODIDE in each release. We like to think of the audience for changelogs as non-developers who primarily run the latest stable. So the change log will primarily outline user-visible changes such as new features and deprecations, and will exclude things that might otherwise be inconsequential to the end user experience, such as infrastructure or refactoring. 

## Bugs & Issues

We use [Github Issues](https://github.com/mozilla/iodide/issues) for announcing and discussing bugs and features. Use [this link](https://github.com/mozilla/iodide/issues/new) to report an bug or issue. We provide a template to give you a guide for how to file optimally. If you have the chance, please search the existing issues before reporting a bug. It's possible that someone else has already reported your error. This doesn't always work, and sometimes it's hard to know what to search for, so consider this extra credit. We won't mind if you accidentally file a duplicate report.

Core contributors are monitoring new issues & comments all the time, and will label & organize issues to align with development priorities.

## How to Contribute

Pull requests are the primary mechanism we use to change IODIDE. GitHub itself has some [great documentation](https://help.github.com/articles/about-pull-requests/) on using the Pull Request feature. We use the "fork and pull" model [described here](https://help.github.com/articles/about-pull-requests/), where contributors push changes to their personal fork and create pull requests to bring those changes into the source repository.

Please make pull requests against the `master` branch.

If you’re looking for a way to jump in and contribute, our list of [`good first issues`](https://github.com/mozilla/iodide/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) is a great place to start.

If you’d like to fix a currently-filed issue, please take a look at the comment thread on the issue to ensure no one is already working on it. If no one has claimed the issue, make a comment stating you’d like to tackle it in a PR. If someone has claimed the issue but has not worked on it in a few weeks, make a comment asking if you can take over, and we’ll figure it out from there.

We use [Jest](https://facebook.github.io/jest/) as our testing framework. Every PR will automatically run through our tests, and our test framework will alert you on Github if your PR doesn’t pass all of them. If your PR fails a test, try to figure out whether or not you can update your code to make the test pass again, or ask for help. As a policy we will not accept a PR that fails any of our tests, and will likely ask you to add tests if your PR adds new functionality. Writing tests can be scary, but they make open-source contributions easier for everyone to assess. Take a moment and look through how we’ve written our tests, and try to make your tests match. If you are having trouble, we can help you get started on our test-writing journey. 

We also rely on linting as a way of standardizing low-level style choices in the code. We use [Airbnb's Javascript Style Guide](https://github.com/airbnb/javascript) along with their [React Guide](https://github.com/airbnb/javascript/tree/master/react). The use of a linter in your development worflow means you can focus on the higher-level aspects of style. As such we will likely not accept any PRs that fail linting. If this feels like a hassle, we'd recommend roughly following the Development Workflow below so you don't have to sweat this detail!

## Contribution Prerequisites
<FILL IN HERE>

## Development Workflow

<FILL IN HERE>

## Style Guide

To reiterate, if you follow our Development Workflow, linting will take care of low-level style and formatting issues.

On a middle level, the best approach to ensuring your contributions are in the right style is to follow the example of any of the other components in the repository.

On a very high level, our goal is to make the source code for IODIDE simple as possible for users who are new to JS. To quote the famous [PEP-20 -- The Zen of Python](https://www.python.org/dev/peps/pep-0020/):

```
Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
...
```


## License

All contributions to IODIDE will be licensed under the [Mozilla Public License 2.0 (MPL 2.0)](https://www.mozilla.org/en-US/MPL/2.0/). This is considered a "weak copyleft" license. Check out the [tl;drLegal entry](https://tldrlegal.com/license/mozilla-public-license-2.0-(mpl-2)) for more information, as well as Mozilla's [MPL 2.0 FAQ](https://www.mozilla.org/en-US/MPL/2.0/FAQ/) if you need further clarification on what is and isn't permitted.


## Get in Touch

IRC / GITTER: <INSERT HERE>
MAILING LIST?: <INSERT HERE>


## Meeting Notes

The IODIDE team meets once a week to discuss the development of IODIDE, future plans, and priorities. You can find the meeting notes in a dedicated repository.