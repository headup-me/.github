---
name: Change
about: Plan one tracked product, engineering, documentation, configuration, or operational change.
labels: planning:change
---

## Outcome

<!-- Describe one outcome and its intended scope. -->

## Scope

<!-- List what is included and what is explicitly out of scope. -->

## Execution

<!-- The agent passes the start gate in `How we work` § Tracked issues, in the handbook, before changing anything. -->

- Blocked by: <!-- Exact Issue references or `None`; mirror references with native GitHub dependencies. -->
- Start conditions: <!-- Exact non-Issue conditions, required state, and verification source, or `None`. -->
- Not in parallel with: <!-- Exact Issue references that no `Blocked by` chain already orders, each
  with the resource they share, or `None known`. Add the condition under which another Issue may
  overlap, when there is one. Write the same reference in the other Issue. -->
- Affected resources: <!-- Derive from Scope: every path the Issue creates, edits, or removes, plus
  every path and non-repository resource that must change because of those changes. Check inbound
  references, registration or wiring, and shared sources that must be extended instead of
  duplicated. Use exact resources or `None`; exclude this Issue's branch, worktree, and pull
  request. -->

## Visual checks

<!--
Required whenever this Issue names a visual requirement; delete the section when it names none.
See `How we work` § The visual protocol in the handbook. States, responsive behavior and tokens
stay in Figma and are not copied here.
-->

- Figma: <!-- the node URL, when more than one frame or component could match -->
- Implementation: <!-- exact component or route -->
- Test: <!-- the focused validation, and the documented width boundary or container query it runs at -->

## Executing agent

<!-- Optional in general; mandatory whenever an agent plans this Issue. -->

| Model | Effort | Context |
| ----- | ------ | ------- |
|       |        |         |

## Authoritative docs

<!-- List the docs pages that govern this Issue, in this repository's `docs/` or in the handbook, with the section when only part of a page applies, or `None — <concrete reason>`. Mark a page created by this Issue as `— to be created before <dependent work>`. -->

## Acceptance criteria

<!-- List verifiable conditions that must be true for this Issue to be closed. -->

### Changelog category

<!--
Write exactly one: Added, Changed, Fixed, Removed, Security, or None.
Add the matching changelog:* label yourself; no automation sets it.
-->

### No-changelog reason

<!-- Required only when the label is changelog:none. State the concrete reason. -->

## Changelog entry

<!--
Required for every changelog:* label other than changelog:none.
After removing HTML comments and trimming the field, write exactly one non-empty physical Markdown
line. A hard line break or wrapped second non-empty physical line is invalid. The category is
determined by the label; do not repeat it here.
Example: Head Up now shows a permanent update notice on Web, iOS, and Android.
-->
