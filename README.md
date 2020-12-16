# Ionic Vue VSCode Snippets

This extension adds ionic-vue snippets. Quickly add ionic-vue component code by simply typing `iv`. The `iv` prefix will show a rage of snippets to choose from. For example, `ivlabel` will add the label component code, `ivlist` will show the ionic vue list component code.

## Supported components
All snippets are sourced from [ionic website](https://ionicframework.com/docs/components).

- Badge
- Button
- Ripple
- Card
- Checkbox
- Chip
- Datetime
- FAB
- Grid
- Icon
- Input
- Textarea
- Item
- Item Divider
- Item Group
- Label
- List
- List Header
- Avatar
- Image
- Thumbnail
- Menu
- Backdrop
- Progress Bar
- Skeleton Text
- Spinner
- Radio Group
- Radio
- Range
- Refresher
- Router / Router Redirect
- Searchbar
- Segment / Segment Button
- Select / Select Option
- Slides
- Tabs / Tab bar / Tab Button

![Extension gif](/example.gif)

\!\[Extension gif\]\(/example.gif\)

## Known Issues

- To use snippets effectively you will have to mannually import each ionic component used in the snippet `import { componetName } from @ionic/vue`. We are working on solving this issue.

## Release Notes

### 0.1.3

Fix indentation for `<ion-grid>` and `<ion-item-group>`.
Added snippets for Backdrop, Progress Bar, Skeleton Text, Spinner, Radio Group, Radio, Range, Refresher, Router / Router Redirect, Searchbar, Segment / Segment Button, Select / Select Option, Slides and, Tabs / Tab bar / Tab Button.

### 0.1.2

[Fix](https://stackoverflow.com/a/65302060/616221) snippet scope for vue-html.

### 0.1.1

Added keywords to package.json

### 0.1.0

Initial release.
