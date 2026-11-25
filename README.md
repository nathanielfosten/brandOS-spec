# [Brand Name] Brand Operating System

brandOS is a set of files that people and agents use to make work for [Brand Name]. The core captures what makes the brand recognizable. Installed apps use that guidance to present reusable components and build finished artifacts.

## Start with the brand

Read [Signature Moves](signature-moves.md) first. Pick a move that fits the brief, then consult the parts of the brand that apply to the work.

| When you need to… | Read or use |
| --- | --- |
| Decide what to say and how to say it | [Verbal](brand/verbal/) covers audience, positioning, differentiation, messaging, voice and vocabulary. |
| Decide how something should look or behave | [Visual](brand/visual/) covers art direction, layout, type, color, motion, graphic elements and effects. |
| Apply an exact visual value | [Styles](brand/styles/) holds the token source, `tokens.json`, and its CSS representation, `brand.css`. Refer to tokens by name in guidance and components. |
| Choose an approved file | [Assets](brand/assets/) holds logos, fonts and animations. |

## Installed apps

The `apps/` directory holds the optional visual layer. This scaffold includes two starter app folders. In a brand project, install either app by copying its folder into `apps/` under the same name. The core is usable on its own. Each app has its own README as its entry point.

```text
signature-moves.md
brand/
  verbal/
  visual/
  styles/
  assets/
apps/
  components/       Reusable pieces for use across formats
    registry/
    sandbox/
  artifacts/        Templates for complete deliverables
    templates/
```

For a welcome email, a writer can use Signature Moves and Verbal directly. With the Artifacts app installed, they can start from a welcome-email template. With Components installed too, that template can reuse a registered call-to-action button. The button belongs to Components, the email layout belongs to Artifacts, and the rules for how the brand sounds and looks live in the core.
