# Skyrim VoicedFollower Modlist

A list of all voiced followers in skyrim, including the ID and file-name required to do patchless interactions

## Contributing

If a follower is missing just add the following information to mods.yml or open an issue with the mod-link:

```yml
- name: Idrinth Thalui - Custom Voiced male Altmer
  link: https://www.nexusmods.com/skyrimspecialedition/mods/69338
  file: IdrinthThalui.esp
  description: This follower, trainer, questgiver and merchant is a male Altmer, focussing on Restoration magic and twohanded, elven swords. Comes with custom dialogue and patrols the world! 
  author: Björn "Idrinth" Büttner
  adult-only: false
  version: 0.54.1
  followers:
  - name: Idrinth Thalui
    race: High Elf
    sex: male
    lines: 1837
    reference: 803
```

### Reference-ID

The reference id is the id of the placed actor in the world. if you are in the creation kit, it is on the top line to the right side. Remove the first two characters and any leading zeroes from it.

![Reference-ID](/reference-id.png)
