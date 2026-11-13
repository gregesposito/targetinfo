> ### About this fork (gregesposito)
> Adds a **decimal ID** line (`ShowDecID`) next to the hex and full IDs. The decimal mob ID is the form used by `windower.ffxi.get_mob_by_id`, `settarget`, and the run-bot scripts, so you can copy it straight into code. The bundled `data/settings.xml` turns on `ShowDecID`, `ShowFullID`, `ShowHexID`, and `ShowSpeed`.
>
> **Load:** copy to `Windower/addons/TargetInfo/`, then `//lua load targetinfo`. It has no commands; edit `data/settings.xml` to change what's shown.

---

# TargetInfo #

This addon shows some memory information of your current target, provided the target is an NPC. This information is otherwise not available in the game.

Per settings file adjustable settings:

`ShowHexID`
  This ID is usually used when specifying mob IDs for NM placeholders.
`ShowFullID`
  The full ID, containing zone information and mob category as well.
`ShowSpeed`
  Shows percentual deviations from regular movement speed (+x% and -x%).
