# Just my list of things I have ported over

Format for the changelog of ported stuff
```
commit    // Shows commit from CC:T
commit2   // Shows a commit that is the same thing, just a clean up, only if right after
Title     // Commit Title
SubScript // Desc of commit
```

If a edit that is present in CC:T is not needed, I will skip over it.
Any and all references to an issue number, are to be found on CC:T's repo. not this oen

```md
5155e18de279a193c558aa029963486fd1294769
Added translation for Vietnamese
Co-authored-by: Boom <boom@flyingpackets.net>
```

```
7e121ff72f2b1504cd6af47b57500876682bac45
ae6124d1f477487abab1858abde8c4ec49dfee3c
Translations for Vienamese
Co-authored-by: Boom <boom@flyingpackets.net>
```

```
59de21eae29849988e77fad6bc335f5ce78dfec7
Handle tabs when parsing JSON
Fixes #539
```

```
748ebbe66bf0a4239bde34f557e4b4b75d61d990
Bump to 1.92.0
A tiny release, but there's new features so it's technically a minor
bump.
```

Cherry Picked because this update was partially related to forge updates rather than mod updates
```
8b4a01df27ff7f6fa9ffd9c2188c6e3166edd515
Update to Minecraft 1.16.3

I hope the Fabric folks now realise this is gonna be a race of who can
update first :p. Either way, this was a very easy update - only changes
were due to unrelated Forge changes.
```