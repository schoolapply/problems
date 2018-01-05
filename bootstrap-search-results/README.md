# Bootstrap search results

In this task we want you to build result pages for a site search. In this problem we expect you to use your [Bootstrap](https://getbootstrap.com/) skills, more specifically the HTML part.

- **tech**: Front-end with a focus on HTML and CSS
- **difficulty**: 2/5

## What to do

We've created some wireframes for a search UI that we'd like to have implemented in HTML and CSS. The goal is to recreate the wireframes utilizing [Bootstrap v4.0](https://getbootstrap.com/docs/4.0) code and best practices.

- Use the [grid system](https://getbootstrap.com/docs/4.0/layout/grid/) to create columns
- Use the [nav component](https://getbootstrap.com/docs/4.0/components/navs/) to create tabs
- Use the [card component](https://getbootstrap.com/docs/4.0/components/card/) where applicable

#### [Result listing](wireframes#artboard0)

This page shows search results filtered by location. In the top of the page is a navbar followed by a summary of the search terms followed by a tab UI where the user can navigate to other search views. Results are listed in the center-right columns and the user can further refine his filters in the left column. Each result has two call to action buttons - "apply now" and "shortlist".

> The [media object](https://getbootstrap.com/docs/4.0/layout/media-object/) is a good way of grouping search results.

#### [Article listing](wireframes#artboard1)

This page shows matched articles. Each article has a banner image and a summary that should be shown.

> [Card layout](https://getbootstrap.com/docs/4.0/components/card/#card-layout) is a great way of grouping cards.

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