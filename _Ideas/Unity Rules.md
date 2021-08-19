- The grid is king, _long live the grid!_
- Always give assets specific, descriptive names
- Organize assets in well labeled folders
    - Try not to make more than three levels of folders
    - Sort items by naming them with group identifiers first so they group together when sorted by name
- Leave the original prefabs, and especially the original meshes, alone as much as possible
    - Duplicate and rename before making changes
- Make sure to select the entire hierarchy when exporting, not just the top layer items

**Pre-Unity Checklist**

- [ ] **Pivot** - Check that all pivots are in the correct location
- [ ] **Scale** - Ensure that the asset has been created at the correct scale
- [ ] **Nesting** - Make sure that objects are nested properly
- [ ] **Transformations** - Freeze all transformations, final step before export
- [ ] **Export** - Export to FBX, include smoothing groups, hierarchy, and animations (if present)

**Unity Checklist**

- [ ] **Colliders**
    1.  [ ] Everything that needs a collider has one
    2.  [ ] All colliders are the “lightest” type that will work, and
    3.  [ ] Objects that don't need them don't have them
- [ ] **Static or Dynamic**
    - [ ] Set objects that will never move to **Static**
    - [ ] Leave **Static** unchecked for everything else
    - [ ] When in doubt, leave **Static** unchecked
- [ ] Fine positioning
- [ ] Shadows
    - [ ] Casting shadows
    - [ ] Receiving shadows
