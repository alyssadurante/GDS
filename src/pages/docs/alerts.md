---
title: Alerts
description: Quidem magni aut exercitationem maxime rerum eos.
---

Alerts communicate important information in a section of a screen. Alerts are persistent, but can disappear when the user takes action or resolves the situation.

---

## Overview

By default, all alerts come with an icon and an area for content. A title and actions can also be added.

### Anatomy

![Success](https://res.cloudinary.com/dgcfg5cwe/image/upload/v1643605274/alert-anatomy_snivsu.svg)

1. **Icon and background color**: The icon and background color pairing indicates the message type and comes in the default styles for the message type.
2. **Title**: Titles should clearly and concisely indicate the purpose of the message.
3. **Description**: This should describe the issue and any action the user needs to take, if any. The message will grow along with the length of the description but should be as succinct as possible.
4. **Actions (optional)**: One or more links that enable the user to act on the section message content.

## When to use

- A user is taking a particular action that may have potentially destructive consequences
- A user needs to take action to keep moving through an experience
- There are connectivity or authentication issues

---

## Content

### Title

- Titles should clearly describe the issue or reason for the message.

### Body Copy

- Description text should be clear, concise, empathetic, and informative.
- Use active verbs to guide the user on any actions they need to take.

## Behavior

### Closing an alert

Alerts that include actions **require** the user to manually "Dismiss" the alert if they do not wish to interact with the alert.

## Variants

By default, all alerts come with an icon and an area for content. A `title` and `actions` can also be added.

### Information

The information alert is the default appearance used to signify a change in state or important information.

![Information](https://res.cloudinary.com/dgcfg5cwe/image/upload/v1643606049/Alert-info_eu1oiz.svg)

### Success

Use a success alert to let the user know that an action or event has happened successfully.

![Success](https://res.cloudinary.com/dgcfg5cwe/image/upload/v1643606049/Alert-success_hsefrr.svg)

### Warning

Use a warning section message to help users:

- avoid errors
- manage authentication issues
- take the actions needed to avoid potentially dangerous actions
- feel certain they're making the decision, for example, in confirmation modals

![Warning](https://res.cloudinary.com/dgcfg5cwe/image/upload/v1643606095/Alert-warning_fg2jke.svg)

### Error

Use an error section message to let the user know when:

- something destructive or critical has happened
- access has been denied
- there are connectivity issues

![Error](https://res.cloudinary.com/dgcfg5cwe/image/upload/v1643606133/Alert-error_qaazjv.svg)

### Actions

Use the actions prop to let users act on the content in the section message.

- something destructive or critical has happened
- access has been denied
- there are connectivity issues

![Actions](https://res.cloudinary.com/dgcfg5cwe/image/upload/v1643606049/Alert-actions_kz58qv.svg)
