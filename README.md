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

![Using extension](/example.gif)

## Known Issues

- To use snippets effectively you will have to mannually import each ionic component used in the snippet `import { componetName } from @ionic/vue`. We are working on solving this issue.

- Snippets only when added on the top level and not working when added inside a `template` or `div` tag. [See stackoverflow post](https://stackoverflow.com/questions/65297548/how-to-add-vs-code-snippet-inside-a-template)

## Release Notes

### 0.1.0

Initial release.
