# [Brand Name] Brand Operating System

The brandOS defines not only how [Brand Name] looks and sounds, but contains tools specific to the brand, empowering the creation of branded artifacts across an organization.

This operating system is a set of markdown and web files that contain guidence and templates for building. There is nothing to run. This brandOS is source of truth for the [Brand Name] brand.

## How to use BrandOS

Begin by reading `taste.md` -- it defines what makes a delivered artifact feel like [Brand Name].

Then, depending what the user is trying to create, read:

TODO:
[Render instruction TOC]

## Folder and file structure

TODO:
[Render brandOS folder structure]

## How to use the design system

### Fonts

TODO:

### Tokens and styles

TODO: rewrite this
`agent/visual/visual-system.json` is authoritative for every visual value: color, type,
spacing, radius, effects. `agent/visual/tokens.css` is generated from it as plain custom
properties, with no build step.

The markdown files carry rules and reasoning, and name values by token only.
That split is deliberate: a value lives in exactly one place, so a hex in a
document can never drift from the hex in the code.

### Component registry

The brandOS is an evolving system. Each component that exists within the OS also lives in a component registry that other [Company Name] tools may call. These components are agnostic in format (not filetype), based on behavior and intent so users and agents may create new components as needed.

The component registry lives beside the components folder, in [`registry`](../artifacts/components/registry/).

## Building artifacts

Based on the request, find the appropriate [`template`](../artifacts/templates/) to base your new artifact on. Gather the necessary context and proceed to generate the requested artifact for the user.

Use the [`brand/`](../brand/) content alongside the component registry and taste.md to build the requested artifact.