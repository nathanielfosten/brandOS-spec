# [Brand Name] Brand Operating System

brandOS is a set of files that people and agents use to make work for [Brand Name]. The core captures what makes the brand recognizable. Installed plugins use that guidance to present reusable components and build finished artifacts.

## Start with the brand

Every core guide is shared by the entire team and its agents. Use the guide that answers the decision at hand, whether you’re preparing a conversation, shaping a product experience, or checking work against the brand.

Read [Signature Moves](signature-moves.md) first. Pick a move that fits the brief, then consult the parts of the brand that apply to the work.

| When you need to… | Read or use |
| --- | --- |
| Decide what to say and how to say it | [Verbal](brand/verbal/) covers audience, positioning, differentiation, messaging, voice and vocabulary. |
| Decide how something should look or behave | [Visual](brand/visual/) covers art direction, layout, type, color, motion, graphic elements and effects. |
| Apply an exact visual value | [Styles](brand/styles/README.md) provides approved token values and their corresponding CSS properties. |
| Choose an approved file | The [asset inventory](brand/assets/README.md) records which logo, font or animation to use and where to find it. |

## Plugin layer

The `plugins/` directory holds optional extensions to the core. Components and Artifacts are the two starter plugins. In a brand project, install either plugin by copying its folder into `plugins/` under the same name. The core is usable on its own. Each plugin has its own README as its entry point.

```text
signature-moves.md
brand/
  verbal/
  visual/
  styles/
  assets/
plugins/
  components/       Reusable pieces for use across formats
    registry/
    sandbox/
  artifacts/        Templates for complete deliverables
    templates/
```

To prepare a welcome email, use Signature Moves and Verbal directly. With the Artifacts plugin installed, start from a welcome-email template. With Components installed too, that template can reuse a registered call-to-action button. The button belongs to Components, the email layout belongs to Artifacts, and the rules for how the brand sounds and looks live in the core.
