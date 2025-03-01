# Auto-tag orders when another tag is added

Tags: Auto-Tag, Orders, Tag, Watch

Does exactly as it says. :)

* View in the task library: [usemechanic.com/task/auto-tag-orders-when-another-tag-is-added](https://usemechanic.com/task/auto-tag-orders-when-another-tag-is-added)
* Task JSON, for direct import: [task.json](../../tasks/auto-tag-orders-when-another-tag-is-added.json)
* Preview task code: [script.liquid](./script.liquid)

## Default options

```json
{
  "tags_to_watch_for_and_tags_to_add__keyval_required": null,
  "remove_tag_to_add_when_the_corresponding_tag_to_watch_for_is_removed__boolean": null
}
```

[Learn about task options in Mechanic](https://docs.usemechanic.com/article/471-task-options)

## Subscriptions

```liquid
shopify/orders/updated
```

[Learn about event subscriptions in Mechanic](https://docs.usemechanic.com/article/408-subscriptions)

## Documentation

Does exactly as it says. :)

Configure this task with order tags to watch for on the left, and associated tags to add on the right. (Feel free to use a comma-delimited list on the right side, too.) This task will run whenever an order is created or updated, tagging as configured.

## Installing this task

Find this task [in the library at usemechanic.com](https://usemechanic.com/task/auto-tag-orders-when-another-tag-is-added), and use the "Try this task" button. Or, import [this task's JSON export](../../tasks/auto-tag-orders-when-another-tag-is-added.json) – see [Importing and exporting tasks](https://docs.usemechanic.com/article/505-importing-and-exporting-tasks) to learn how imports work.

## Contributions

Found a bug? Got an improvement to add? Start here: [../../CONTRIBUTING.md](../../CONTRIBUTING.md).

## Task requests

Submit your [task requests](https://mechanic.canny.io/task-requests) for consideration by the Mechanic community, and they may be chosen for development and inclusion in the [task library](https://tasks.mechanic.dev/)!
