## Contributing

[fork]: https://github.com/ORG/REPO/fork
[pr]: https://github.com/ORG/REPO/compare
[style]: STYLEGUIDE
[code-of-conduct]: CODE_OF_CONDUCT.md

Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great.

Please note that this project is released with a [Contributor Code of Conduct][code-of-conduct]. By participating in this project you agree to abide by its terms.

[Code of Conduct](#code-of-conduct)

[I don't want to read this whole thing, I just have a question!!!](#i-dont-want-to-read-this-whole-thing-i-just-have-a-question)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [HackAtHome and Packages](#hackathome-and-packages)
  * [HackAtHome Design Decisions](#design-decisions)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [JavaScript Styleguide](#javascript-styleguide)
  * [CoffeeScript Styleguide](#coffeescript-styleguide)
  * [Specs Styleguide](#specs-styleguide)
  * [Documentation Styleguide](#documentation-styleguide)

[Additional Notes](#additional-notes)
  * [Issue and Pull Request Labels](#issue-and-pull-request-labels)

## Code of Conduct

This project and everyone participating in it is governed by the [HackAtHome Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [hackathome@domomi.com](mailto:hackathome@domomi.com).

## I don't want to read this whole thing I just have a question!!!

> **Note:** [Please don't file an issue to ask a question.](https://blog.atom.io/2016/04/19/managing-the-deluge-of-atom-issues.html) You'll get faster results by using the resources below.

We have an official message board with a detailed FAQ and where the community chimes in with helpful advice if you have questions.

* [Discuss, the official HackAtHome and DomoMi message board](https://discuss.domomi.com)
* [HackAtHome FAQ](https://discuss.hackathome.domomi.com/c/faq)

If chat is more your speed, you can join the HackAtHome and DomoMi Slack team:

* [Join the HackAtHome and DomoMi Slack Team](https://hackathome-slack.herokuapp.com/)
    * Even though Slack is a chat service, sometimes it takes several hours for community members to respond &mdash; please be patient!
    * Use the `#hackathome` channel for general questions or discussion about HackAtHome
    * Use the `#domomi` channel for questions about DomoMi
    * Use the `#packages` channel for questions or discussion about writing or contributing to HackAtHome packages (both core and community)
    * Use the `#ui` channel for questions and discussion about HackAtHome UI and themes
    * There are many other channels available, check the channel list

## What should I know before I get started?

### HackAtHome and Packages

HackAtHome is a large open source project &mdash; it's made up of over [200 repositories](https://github.com/hackathome). When you initially consider contributing to HackAtHome, you might be unsure about which of those 200 repositories implements the functionality you want to change or report a bug for. This section should help you with that.

HackAtHome is intentionally very modular. Nearly every non-editor UI element you interact with comes from a package, even fundamental things like tabs and the status-bar. These packages are packages in the same way that packages in the [HackAtHome package repository](https://hackathome.domomi.com/packages) are packages, with one difference: they are bundled into the [default distribution](https://github.com/atom/atom/blob/10b8de6fc499a7def9b072739486e68530d67ab4/package.json#L58).

<a id="atom-packages-image"/>

![HackAtHome-packages](https://cloud.githubusercontent.com/assets/69169/10472281/84fc9792-71d3-11e5-9fd1-19da717df079.png)

To get a sense for the packages that are bundled with HackAtHome, you can go to `Settings` > `Packages` within HackAtHome and take a look at the Core Packages section.

## Submitting a pull request

0. [Fork][fork] and clone the repository
0. Create a new branch: `git checkout -b my-branch-name`
0. Make your change and remember to add tests
0. Build the project locally and run local tests
0. Push to your fork and [submit a pull request][pr]
0. Pat your self on the back and wait for your pull request to be reviewed and merged.

Here are a few things you can do that will increase the likelihood of your pull request being accepted:

- Follow the [style guide][link to styleguide].
- Write tests.
- Keep your change as focused as possible. If there are multiple changes you would like to make that are not dependent upon each other, submit them as separate pull requests.
- Write [good commit messages](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).

## Resources

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)
