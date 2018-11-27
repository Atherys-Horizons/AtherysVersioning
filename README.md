# AtherysVersioning
The versioning guide for all A'therys plugins

## Layout
`1.<major_version>.<minor_version>[A|B|R]`

All versions of A'therys plugins will begin with the number `1`. This will only be changes in case of drastic, completely incompatible changes in the codebase of a plugin. Like, for example, switching between frameworks ( Spigot to Sponge, or Sponge to Forge, etc. ).

`major_version` - This will change with every compatibility-breaking change. When this happens, the `minor_version` will be reset to `0`.

`minor_version` - This will change with non-compatibility-breaking changes.

`[A|B|R]` - Optional. This corresponds to Alpha, Beta and Release versions, respectively. If left out, it is understood that this is a Release version.

### Examples

`1.2.0A` - Major version 2, with no minor revisions, an Alpha version

`1.9.4R` - Major version 9, minor version 4, Release version, is equivalent to `1.9.4`
