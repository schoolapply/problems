# Bootstrap search navigation

In this task we want you to build a quick-access UI for a site search embedded inside a navigation bar. In this problem we expect you to use your [Bootstrap](https://getbootstrap.com/) skills, more specifically the HTML part.

- **tech**: Front-end with a focus on HTML and CSS
- **difficulty**: 2/5

## What to do

We've created some wireframes for a search UI that we'd like to have implemented in HTML and CSS. The goal is to recreate the wireframes utilizing [Bootstrap v4.0](https://getbootstrap.com/docs/4.0) code and best practices.

- Use the [navbar component](https://getbootstrap.com/docs/4.0/components/navbar/) as a base
- Utilize [responsive breakpoints](https://getbootstrap.com/docs/4.0/layout/overview/#responsive-breakpoints) to your advantage

#### [Initial search UI](wireframes#artboard0)

This is the initial view of the search UI. The UI consists of a input box where the user can type their search embedded inside navigation bar located in the header of page header.

> Think about how to structure the navbar so that the search input is available on all screen sizes.

#### [Focused search input](wireframes#artboard1)

When the user focuses the the search input the UI should expand to occupy the full amount of horizontal space available.

> The preferred way to implement the expansion is to trigger it by hiding the additional navigation items using CSS only.

#### [Type ahead suggestions](wireframes#artboard2)

As the user types a grouped dropdown of highlighted matches is show to the user. This dropdown should overlap whatever content visible on the page but still be responsive for smaller screens.

> Think about how your HTML is impacted by keyboard navigation if the user want's to `tab` to a search result.

### How to start

- First read through the [contribution guidelines](../CONTRIBUTING.md) for instructions on how to set up a local repository and how to structure your work if you want a review
- We've included a [copy](template.html) of [template.html](https://github.com/creativetimofficial/now-ui-kit/blob/master/documentation/template.html) from [now-ui-kit](http://demos.creative-tim.com/now-ui-kit/index.html) with some cleanup and scrubbing applied that we want you to use as a foundation
- Implement each of the [wireframes](wireframes) in separate HTML files using the naming of the wireframe art boards as a guide
- Keep your files under this directory so they are easy to find

### Guidelines

- Make sure to be responsive and that the UI looks and feels nice both on mobile and desktop
- Performance is key - smaller is faster and faster is better
- We're using a customized Bootstrap theme called [now-ui-kit](http://demos.creative-tim.com/now-ui-kit/index.html) for our look and feel
- Usage of standard [Bootstrap components](https://getbootstrap.com/docs/4.0/components/alerts/https://getbootstrap.com/docs/4.0/components) is encouraged
- Usage of custom CSS and non-Bootstrap aligned HTML is discouraged