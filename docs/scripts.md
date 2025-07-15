# Scripts

Scripts in Home Assistant are sequences of actions that can be run manually, from automations, or by voice.

---

## Useful Examples

- [iCloud3 Start Script](https://github.com/gcobb321/icloud3) – Trigger tracking updates manually.
- [Good Night Routine](https://community.home-assistant.io/t/good-night-script/52686) – Turn off lights, lock doors, arm alarm.
- [Media Control Sequences](https://github.com/CCOSTAN/Home-AssistantConfig) – Turn on receiver, select input, set volume, play source.

---

## General Script Techniques

- Use `delay:` steps to add pauses between actions
- Use `choose:` to build branching logic
- Combine with `input_booleans` for conditional execution
- Call other scripts from inside a script

---

## Resources for Learning

- [Script Docs](https://www.home-assistant.io/docs/scripts/) – Official documentation
- [Script Examples Thread](https://community.home-assistant.io/t/share-your-scripts/53613) – Community-contributed examples

---

## Tools for Power Users

- [AppDaemon](https://github.com/AppDaemon/appdaemon) – Write Python apps with full HA access
- [Jinja2 Templating](https://www.home-assistant.io/docs/configuration/templating/) – For dynamic script content
- [Node-RED](https://nodered.org/) – Visual editor that complements scripting

---

> ⚡ Scripts are your home’s secret sauce — learn 'em, love 'em.
