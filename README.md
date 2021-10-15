# lu-mod-schema

Describes the format of the database edits file (possibly also other things in the future)


Resources:
- https://json-schema.org/learn/
- https://cswr.github.io/JsonSchema/


Limitations of using json-schema for this:
- it's possible to add multiple components of the same type to an object
- no validation for referring to components in `#/components` by ID

These things should be validated manually by the mod manager (which handles installation of mods).
