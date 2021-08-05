# ACCESSIBILITY AT [ECOSIA](https://www.ecosia.org/)

At 🌳[Ecosia](https://www.ecosia.org/)🌳, we take A11y very seriously. We have good accessibility standards in place in both Design and Engineering. But of course, we're definitely not perfect, given our limited ability (we're "too able" to test accessible products adequately and must rely on simulators).

Just like this Hackathon organized by _Code Institute x Trust In SODA_, we hosted our own internal Hackathon to develop and improve our product on the Accessibility side.
The list on the README.md are a little output of all the resources we got as inpiration, tools we used, to better ourselves.

Among other, these are the topics on which we worked:

* We have automated testing in place using Lighthouse which does fundamental accessibility checks on every single piece of code we produce. If a code change doesn’t pass the Lighthouse test, it cannot be deployed into production.
* For nearly every feature we built over the past year (2019/2020), we have had the engineers using the feature with VoiceOver or similar screen readers to ensure it is usable that way.
* Our Design System enforces fairly strict standards for colour contrast and interaction states
* Where possible, we implement keyboard interactions strictly according to the [ARIA Authoring Practices](https://www.w3.org/WAI/standards-guidelines/aria/) specification
* We supress motions (animations and transitions) if the user so desires and instructs their browser to
* We use ARIA features not only for keyboard navigation compliance but also device-agnostic and independent a11y concerns
And of course:
we keep sharing resources and best practices within our Frontend Guild, to keep the topic fresh and expand our knowledge: we've decided to do that because, as frontend devs, we simply care very much.