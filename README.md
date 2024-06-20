# Welcome to the Angular tutorial

This tutorial will teach you the basic building blocks to start building great apps with Angular.

Each step represents a concept in Angular.

## Components in Angular

Components are the foundational building blocks for any Angular application. Each component has three parts:

- Typescript class;
- HTML template;
- CSS styles.

In this activity, we'll learn how to update the template and styles of a component.

---
This is a great opportunity for us to get started with Angular.

### Update the component template

Update the `template` property to read `Hello Universe`

```
template: `
    Hello Universe
`,
```
When you changed the HTML template, the preview updated with your message. Let's go one step further: change the color of the text.

### Update the component styles

Update the styles value and change the `color` property from `blue` to `#a144eb`.

```
styles: `
    :host {
        color: #a144eb;
    }
`,
```
When you check the preview, you'll find that the text color will be changed.

In Angular, you can use all the browser supported CSS and HTML that's available. If you'd like, you can store your template and styles in separate files.
