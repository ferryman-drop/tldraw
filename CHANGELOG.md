# v2.0.0-alpha.14 (Tue Jul 04 2023)

### Release Notes t

#### Disable styles panel button on mobile when using the laser tool. ([#1704](https://github.com/tldraw/tldraw/pull/1704))

- Disable the styles panel button for laser tool on mobile.

#### remove lock option from highlighter ([#1703](https://github.com/tldraw/tldraw/pull/1703))

- We no longer show the tool lock option for highlighter - it didn't do anything anyway

#### [fix] penmode ([#1698](https://github.com/tldraw/tldraw/pull/1698))

- [fix] pen mode

#### Update readme ([#1686](https://github.com/tldraw/tldraw/pull/1686))

- Documentation: Updated readme to reflect recent library changes.

#### [docs] Fix the types in the Shapes example ([#1681](https://github.com/tldraw/tldraw/pull/1681))

- Documentation: Fix some incorrect types on the Shapes page.

#### [improvement] More nuanced cursor state ([#1682](https://github.com/tldraw/tldraw/pull/1682))

- Improve cursor timeouts and hiding logic.

#### Fix VS Code commits failing on bublic? ([#1680](https://github.com/tldraw/tldraw/pull/1680))

- [internal] fixed commits failing from bublic when using UI

#### [fix] Lock shortcut ([#1677](https://github.com/tldraw/tldraw/pull/1677))

- [@tldraw/editor] Fix lock tool shortcut

#### [fix] comma keyboard shortcuts ([#1675](https://github.com/tldraw/tldraw/pull/1675))

- [@tldraw/editor] Bug fixes on document events.

#### [improvement] add box sizing border box ([#1674](https://github.com/tldraw/tldraw/pull/1674))

- [@tldraw/editor] Add `box-sizing: border-box` to `tl-container`

#### [improvemnet] drop crc, Buffer dependency ([#1673](https://github.com/tldraw/tldraw/pull/1673))

- [@tldraw/editor] Remove peer dependency on buffer.

#### [improvement] export scribble manager ([#1671](https://github.com/tldraw/tldraw/pull/1671))

- [@tldraw/tldraw] Export `ScribbleManager`

#### [feature] add `meta` property to records ([#1627](https://github.com/tldraw/tldraw/pull/1627))

- todo

#### [fix] mutating `snapshot` in `migrateStoreSnapshot` ([#1663](https://github.com/tldraw/tldraw/pull/1663))

- [@tldraw/store] Fixed a bug that would cause `Store.migrateStoreSnapshot` to mutate its `snapshot` argument.

---

#### 🚀 Enhancement

- `@tldraw/editor`
  - [improvement] More nuanced cursor state [#1682](https://github.com/tldraw/tldraw/pull/1682) ([@steveruizok](https://github.com/steveruizok))
  - [improvement] export scribble manager [#1671](https://github.com/tldraw/tldraw/pull/1671) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/tlschema`, `@tldraw/ui`, `@tldraw/utils`, `@tldraw/validate`
  - [feature] add `meta` property to records [#1627](https://github.com/tldraw/tldraw/pull/1627) ([@steveruizok](https://github.com/steveruizok))

#### 🐛 Bug Fix

- Lokalise: Translations update [#1694](https://github.com/tldraw/tldraw/pull/1694) ([@TodePond](https://github.com/TodePond))
- `@tldraw/ui`
  - Disable styles panel button on mobile when using the laser tool. [#1704](https://github.com/tldraw/tldraw/pull/1704) ([@MitjaBezensek](https://github.com/MitjaBezensek))
  - remove lock option from highlighter [#1703](https://github.com/tldraw/tldraw/pull/1703) ([@SomeHats](https://github.com/SomeHats))
  - [fix] Lock shortcut [#1677](https://github.com/tldraw/tldraw/pull/1677) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`
  - [fix] penmode [#1698](https://github.com/tldraw/tldraw/pull/1698) ([@steveruizok](https://github.com/steveruizok))
  - [fix] indicator not updating [#1696](https://github.com/tldraw/tldraw/pull/1696) ([@steveruizok](https://github.com/steveruizok))
  - [fix] comma keyboard shortcuts [#1675](https://github.com/tldraw/tldraw/pull/1675) ([@steveruizok](https://github.com/steveruizok))
  - [improvement] add box sizing border box [#1674](https://github.com/tldraw/tldraw/pull/1674) ([@steveruizok](https://github.com/steveruizok))
  - [improvemnet] drop crc, Buffer dependency [#1673](https://github.com/tldraw/tldraw/pull/1673) ([@steveruizok](https://github.com/steveruizok))
  - [fix] Shape rendering [#1670](https://github.com/tldraw/tldraw/pull/1670) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/state`
  - [fix] rename `global` in @tldraw/state to avoid collissions [#1672](https://github.com/tldraw/tldraw/pull/1672) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/store`
  - [fix] mutating `snapshot` in `migrateStoreSnapshot` [#1663](https://github.com/tldraw/tldraw/pull/1663) ([@steveruizok](https://github.com/steveruizok))

#### 🏠 Internal

- [infra] use huppy token for publish-new [#1687](https://github.com/tldraw/tldraw/pull/1687) ([@ds300](https://github.com/ds300))
- Fix VS Code commits failing on bublic? [#1680](https://github.com/tldraw/tldraw/pull/1680) ([@TodePond](https://github.com/TodePond))

#### 📝 Documentation

- Update readme [#1686](https://github.com/tldraw/tldraw/pull/1686) ([@TodePond](https://github.com/TodePond))
- [docs] Update multiple test [#1685](https://github.com/tldraw/tldraw/pull/1685) ([@steveruizok](https://github.com/steveruizok))
- [docs] Fix the types in the Shapes example [#1681](https://github.com/tldraw/tldraw/pull/1681) ([@TodePond](https://github.com/TodePond))

#### Authors: 5

- alex ([@SomeHats](https://github.com/SomeHats))
- David Sheldrick ([@ds300](https://github.com/ds300))
- Lu Wilson ([@TodePond](https://github.com/TodePond))
- Mitja Bezenšek ([@MitjaBezensek](https://github.com/MitjaBezensek))
- Steve Ruiz ([@steveruizok](https://github.com/steveruizok))

---

# v2.0.0-alpha.13 (Wed Jun 28 2023)

### Release Notes

#### Fix crash when rotating a deleted shape ([#1658](https://github.com/tldraw/tldraw/pull/1658))

- Fixed a crash when trying to rotate a deleted shape.

#### [improvement] store snapshot types ([#1657](https://github.com/tldraw/tldraw/pull/1657))

- [dev] Rename `StoreSnapshot` to `SerializedStore`
- [dev] Create new `StoreSnapshot` as type related to `getSnapshot`/`loadSnapshot`

#### [fix] pen mode touches ([#1655](https://github.com/tldraw/tldraw/pull/1655))

- Removes three touches to cancel pen mode feature.

#### (2/2) [docs] Fix links to API. ([#1654](https://github.com/tldraw/tldraw/pull/1654))

- Documentation: Simplified links to the API reference.

#### (1/2) [docs] Restore some missing changes ([#1652](https://github.com/tldraw/tldraw/pull/1652))

- None (Docs internals)

#### [docs] Remove embeds page ([#1653](https://github.com/tldraw/tldraw/pull/1653))

- Documentation: Removed unused Embeds page.

#### Fix text shapes not having colour ([#1649](https://github.com/tldraw/tldraw/pull/1649))

- None: Fixes an unreleased bug.

#### Styles API docs ([#1641](https://github.com/tldraw/tldraw/pull/1641))

--

#### Styles API follow-ups ([#1636](https://github.com/tldraw/tldraw/pull/1636))

--

#### docs: remove not accepting contributions notice ([#1647](https://github.com/tldraw/tldraw/pull/1647))

- Remove not accepting contributions notice from README

#### Fix SVG cursors not being used ([#1639](https://github.com/tldraw/tldraw/pull/1639))

- None: Fixing an unreleased bug.

#### [docs] Add table of contents to Editor page ([#1642](https://github.com/tldraw/tldraw/pull/1642))

- Documentation: Added a table of contents to the Editor page.

#### speed up playwright and add visual regression tests ([#1638](https://github.com/tldraw/tldraw/pull/1638))

--

#### [docs] Allow sidebar to be scrolled on short screens ([#1632](https://github.com/tldraw/tldraw/pull/1632))

- Documentation: Fixed the sidebar being unscrollable on some short screens.

#### [docs] Add feedback when you search ([#1633](https://github.com/tldraw/tldraw/pull/1633))

- Documentation: Added some immediate feedback when you search.

#### [docs] Separate some pages out of the Docs section ([#1626](https://github.com/tldraw/tldraw/pull/1626))

- Documentation: Restructured the sidebar for clarity.

#### [docs] Fix wrong cursor when hovering buttons ([#1630](https://github.com/tldraw/tldraw/pull/1630))

- Documentation: Fixed the wrong cursor showing when hovering some buttons.

#### [docs] Tighten up wording & structure of Usage page ([#1624](https://github.com/tldraw/tldraw/pull/1624))

- Documentation: Impoved clarity of wording and structure of the Usage page.

#### [docs] Tighten up Editor page introduction ([#1622](https://github.com/tldraw/tldraw/pull/1622))

- Documentation: Simplified the Editor page.

#### [docs] Tighten up Introduction page ([#1621](https://github.com/tldraw/tldraw/pull/1621))

- Documentation: Simplified the Introduction page.

#### Lokalise: Translations update ([#1618](https://github.com/tldraw/tldraw/pull/1618))

- Added more translations for Simplified Chinese.

#### [docs] Simplify paths for uncategorised pages ([#1619](https://github.com/tldraw/tldraw/pull/1619))

- Documentation: Cleaned up some paths.

#### `ShapeUtil` refactor, `Editor` cleanup ([#1611](https://github.com/tldraw/tldraw/pull/1611))

- [editor] renames `defaultProps` to `getDefaultProps`
- [editor] removes `outline`, `outlineSegments`, `handles`, `bounds`
- [editor] renames `renderBackground` to `backgroundComponent`

#### Revert "Update dependencies (#1613)" ([#1617](https://github.com/tldraw/tldraw/pull/1617))

-

#### Remove on drop override ([#1612](https://github.com/tldraw/tldraw/pull/1612))

- [editor] Remove `onDropOverride`

#### Make resizeBox a regular function ([#1610](https://github.com/tldraw/tldraw/pull/1610))

- [editor] Change `resizeBox` to be a regular function.

#### Rename `ShapeUtil.render` -> `ShapeUtil.component` ([#1609](https://github.com/tldraw/tldraw/pull/1609))

- [editor] rename `ShapeUtil.render` to `ShapeUtil.component`

#### tldraw.css ([#1607](https://github.com/tldraw/tldraw/pull/1607))

- [tldraw] Removes `editor.css` and `ui.css` exports, replaces with `tldraw.css`

#### [fix] camera culling ([#1602](https://github.com/tldraw/tldraw/pull/1602))

- [editor] Adds `Editor.cameraState`
- Adds smart culling to make panning and zooming more smooth

#### Styles API ([#1580](https://github.com/tldraw/tldraw/pull/1580))

-

#### (1/2) Timeout collaborator cursors ([#1525](https://github.com/tldraw/tldraw/pull/1525))

- Brought back cursor timeouts. Collaborator cursors now disappear after 3 seconds of inactivity.

#### Remove `@tldraw/utils` from the docs site ([#1596](https://github.com/tldraw/tldraw/pull/1596))

- [docs] Removed an internal utilities package.

#### (1/2) Cursor Chat - Presence ([#1487](https://github.com/tldraw/tldraw/pull/1487))

- [dev] Added support for cursor chat presence.

#### [docs] Add barebones note about translations ([#1593](https://github.com/tldraw/tldraw/pull/1593))

- [docs] Added brief info on how to join as a translations contributor.

#### [refactor] snapping ([#1589](https://github.com/tldraw/tldraw/pull/1589))

- [editor] fix bug in snapping

#### remove `ShapeUtil.transform` ([#1590](https://github.com/tldraw/tldraw/pull/1590))

- [editor] Remove `ShapeUtil.transform`

#### Change app to editor in docs ([#1592](https://github.com/tldraw/tldraw/pull/1592))

- [docs] Updated 'App' to 'Editor'.

#### Make sure loading screens use dark mode user preference. ([#1552](https://github.com/tldraw/tldraw/pull/1552))

- Make sure our loading and error screens take dark mode setting into account.

#### remove `ShapeUtil.point` ([#1591](https://github.com/tldraw/tldraw/pull/1591))

- [editor] Remove `ShapeUtil.point`

#### [fix] Remove group shape export backgrounds ([#1587](https://github.com/tldraw/tldraw/pull/1587))

- Fix image exports for groups

#### Add tsdocs to Editor methods ([#1581](https://github.com/tldraw/tldraw/pull/1581))

- [dev] Added initial documentation for the Editor class.

#### add presence to yjs example ([#1582](https://github.com/tldraw/tldraw/pull/1582))

- [editor] Add presence to yjs example.

#### Add optional generic to `updateShapes` / `createShapes` ([#1579](https://github.com/tldraw/tldraw/pull/1579))

- [editor] adds an optional shape generic to `updateShapes` and `createShapes`

#### fix: properly remove awareness from store ([#1565](https://github.com/tldraw/tldraw/pull/1565))

- Add a brief release note for your PR here.

#### [improvement] Embed shape cleanup ([#1569](https://github.com/tldraw/tldraw/pull/1569))

- [editor] Remove unused props for `TLEditorShape`
- [editor] Adds `canUnmount` property to embed definitions

#### Move the loading of assets to the TldrawEditorWithReadyStore so that all code paths load the assets. ([#1561](https://github.com/tldraw/tldraw/pull/1561))

- Fix a problem where assets were not loading in some cases (snapshots).

#### Add anchor targets to our headings. ([#1571](https://github.com/tldraw/tldraw/pull/1571))

- Improve documentation to include anchor targets.

#### shapes folder, move tools into shape defs ([#1574](https://github.com/tldraw/tldraw/pull/1574))

n/a

#### mini `defineShape` API ([#1563](https://github.com/tldraw/tldraw/pull/1563))

[dev-facing, notes to come]

#### Lokalise: Translations update ([#1572](https://github.com/tldraw/tldraw/pull/1572))

- Added and updates translations for Italian, Russian, and Ukrainian.

#### Fix README typo ([#1451](https://github.com/tldraw/tldraw/pull/1451))

- None

#### yjs example ([#1560](https://github.com/tldraw/tldraw/pull/1560))

- [editor] Adds yjs example project

#### `ExternalContentManager` for handling external content (files, images, etc) ([#1550](https://github.com/tldraw/tldraw/pull/1550))

- [editor] add `ExternalContentManager` for plopping content onto the canvas
- [editor] remove `onCreateAssetFromFile` prop
- [editor] remove `onCreateBookmarkFromUrl` prop
- [editor] introduce `ExternalContentManager`
- [editor] add cleanup function to `onMount`

#### Misc sync fixes ([#1555](https://github.com/tldraw/tldraw/pull/1555))

- Fixes a handful of state management bugs that manifest in multiplayer rooms

#### [Docs] Change some editor properties to methods ([#1553](https://github.com/tldraw/tldraw/pull/1553))

- [docs] Fixed some methods that were incorrectly marked as properties.

#### [Docs] Change some internal methods to public ([#1554](https://github.com/tldraw/tldraw/pull/1554))

- [docs] Changed some Editor methods from internal to public.

#### Use unpkg as a default for serving assets. ([#1548](https://github.com/tldraw/tldraw/pull/1548))

- Use unpkg asset hosting as a default.

#### hoist opacity out of props ([#1526](https://github.com/tldraw/tldraw/pull/1526))

[internal only for now]

#### Fix arrows with weird bends crashing ([#1540](https://github.com/tldraw/tldraw/pull/1540))

- Fixed a rare crash that could happen when you try to curve an arrow with zero distance.

#### [feature] add vertical align to note shape ([#1539](https://github.com/tldraw/tldraw/pull/1539))

- Adds vertical align prop to note shapes

#### [fix] Shift key code / nudge ([#1537](https://github.com/tldraw/tldraw/pull/1537))

- Fix shift key nudging

#### scale exported canvases when they reach the browsers max size ([#1536](https://github.com/tldraw/tldraw/pull/1536))

- Fix a bug where sometimes exports would fail when they were too big for your browser. Now, they're scaled down to the max supported size.

#### [fix] control click on mac ([#1535](https://github.com/tldraw/tldraw/pull/1535))

- Fix control click to open menu on Mac

#### Fix being able to undo following ([#1531](https://github.com/tldraw/tldraw/pull/1531))

- Fixed a bug where you could undo viewport-following and viewport-unfollowing.

#### Select locked shapes on long press ([#1529](https://github.com/tldraw/tldraw/pull/1529))



#### highlighter fixes ([#1530](https://github.com/tldraw/tldraw/pull/1530))

[aq bug fixes]

#### Lokalise: Translations update ([#1515](https://github.com/tldraw/tldraw/pull/1515))

- Added and updated community translations for Galician, Italian, Romanian, Russian, Ukrainian, and Traditional Chinese.

#### Simplify static cursors ([#1520](https://github.com/tldraw/tldraw/pull/1520))

- (editor) Simplifies the cursors in our CSS.

#### Renaming types, shape utils, tools ([#1513](https://github.com/tldraw/tldraw/pull/1513))

- Renaming of types, shape utils, tools

#### tlschema cleanup ([#1509](https://github.com/tldraw/tldraw/pull/1509))

- [editor] Remove `app.createShapeId`
- [tlschema] Cleans up exports

#### Rename tlstore to store ([#1507](https://github.com/tldraw/tldraw/pull/1507))

- Replace @tldraw/tlstore with @tldraw/store

#### Rename tlvalidate to validate ([#1508](https://github.com/tldraw/tldraw/pull/1508))

- Rename tlvalidate to validate

#### Filter out unused assets. ([#1502](https://github.com/tldraw/tldraw/pull/1502))

- Optimize file size of exported files.

#### Cleanup @tldraw/ui types / exports ([#1504](https://github.com/tldraw/tldraw/pull/1504))

- [editor] clean up / unify types

#### rename app to editor ([#1503](https://github.com/tldraw/tldraw/pull/1503))

- Rename `App` to `Editor` and many other things that reference `app` to `editor`.

#### Revert 09c36781 & tweak linting ([#1501](https://github.com/tldraw/tldraw/pull/1501))

[internal-only]

#### Add support for locking shapes ([#1447](https://github.com/tldraw/tldraw/pull/1447))

- Add support for locking shapes.

#### [3/3] Highlighter styling ([#1490](https://github.com/tldraw/tldraw/pull/1490))

Highlighter pen is here! 🎉🎉🎉

#### [2/3] renderer changes to support "sandwich mode" highlighting ([#1418](https://github.com/tldraw/tldraw/pull/1418))

[not yet!]

#### [1/3] initial highlighter shape/tool ([#1401](https://github.com/tldraw/tldraw/pull/1401))

[internal only change layout ground work for highlighter]

#### [feature] reduce motion ([#1485](https://github.com/tldraw/tldraw/pull/1485))

- [editor] Add `reduceMotion` user preference
- Add reduce motion option to preferences

#### [feature] Easier store persistence API + persistence example ([#1480](https://github.com/tldraw/tldraw/pull/1480))

- [tlstore] adds `getSnapshot` and `loadSnapshot`

#### Add DSL to make writing shape-layout test cases much easier ([#1413](https://github.com/tldraw/tldraw/pull/1413))

[internal only change]

#### Feature flags rework ([#1474](https://github.com/tldraw/tldraw/pull/1474))

[internal only change]

#### [tiny] add isPageId ([#1482](https://github.com/tldraw/tldraw/pull/1482))

- [tlschema] Add `isPageId`

#### [minor] Mark tlsync-client internal APIs ([#1481](https://github.com/tldraw/tldraw/pull/1481))

- Removes internal APIs from `@tldraw/tlsync-client`

#### [refactor] update record names ([#1473](https://github.com/tldraw/tldraw/pull/1473))

- [editor] rename record types

#### remove safari special-casing for paste ([#1470](https://github.com/tldraw/tldraw/pull/1470))

[fixes a regression introduced during this release]

#### Don't allow `g` keyboard shortcut in readonly mode, show laser tool in the toolbar ([#1459](https://github.com/tldraw/tldraw/pull/1459))

- Disable geo tool shortcut in readonly mode. Show laser on the toolbar.

#### [mini-feature] Following indicator ([#1468](https://github.com/tldraw/tldraw/pull/1468))

- Adds viewport following indicator

#### [chore] refactor user preferences ([#1435](https://github.com/tldraw/tldraw/pull/1435))

- Add a brief release note for your PR here.

#### Add translations for "Leave shared project" action ([#1394](https://github.com/tldraw/tldraw/pull/1394))

- None

#### update use-gesture ([#1453](https://github.com/tldraw/tldraw/pull/1453))

- Updates use-gesture to fix pinch gesture bug on iPad.

#### Add migration for horizontal alignment ([#1443](https://github.com/tldraw/tldraw/pull/1443))

- Add support for legacy alignment options.

#### Stricter ID types ([#1439](https://github.com/tldraw/tldraw/pull/1439))

[internal only, covered by #1432 changelog]

#### [refactor] restore createTLSchema ([#1444](https://github.com/tldraw/tldraw/pull/1444))

- [editor] Simplifies custom shape definition
- [tldraw] Updates props for <TldrawEditor> component to require a `TldrawEditorConfig`.

#### Fix cursor shadow getting clipped ([#1441](https://github.com/tldraw/tldraw/pull/1441))

- Fixed a bug where custom cursors could have their shadow clipped.

#### Add SVG cursors for all cursor types ([#1416](https://github.com/tldraw/tldraw/pull/1416))

- Added consistent custom cursors.

#### [refactor] remove `createTLSchema` ([#1440](https://github.com/tldraw/tldraw/pull/1440))

- [tlschema] Removes `createTLSchema` in favor of `TldrawEditorConfig`

#### [refactor] Remove `TLShapeDef`, `getShapeUtilByType`. ([#1432](https://github.com/tldraw/tldraw/pull/1432))

- [tlschema] Update props of `createTLSchema`
- [editor] Update props of `TldrawEditorConfig`
- [editor] Remove `App.getShapeUtilByType`
- [editor] Update `App.getShapeUtil` to take a type rather than a shape

#### [refactor] record migrations ([#1430](https://github.com/tldraw/tldraw/pull/1430))

- [tlschema] Improve `defineMigrations`
- [editor] Simplify migration definitions

#### Measure individual words instead of just line breaks for text exports ([#1397](https://github.com/tldraw/tldraw/pull/1397))

- Add a brief release note for your PR here.

#### Update docs links + guides + build ([#1422](https://github.com/tldraw/tldraw/pull/1422))

* [docs] Updated guides to get assets from the new `tldraw/tldraw` repo instead of the old `tldraw/tldraw-examples`.
* [docs] Updated an old CodeSandbox link to the new StackBlitz.

#### Create @tldraw/indices package ([#1426](https://github.com/tldraw/tldraw/pull/1426))

- [@tldraw/editor] Remove fractional indices code into `@tldraw/indices`
- [@tldraw/indices] Create library for fractional indices code

#### [feature] Add checkbox to toolbar ([#1423](https://github.com/tldraw/tldraw/pull/1423))

- Adds missing checkbox to toolbar.

#### [improvement] set horizontal position using text alignment ([#1419](https://github.com/tldraw/tldraw/pull/1419))

- Geo shapes and sticky notes now position their labels based on their alignment.

#### [fix] reorder handles in front of selection ([#1420](https://github.com/tldraw/tldraw/pull/1420))

- Fix a bug where handles would appear behind selection indicators.

#### [feature] add laser pointer ([#1412](https://github.com/tldraw/tldraw/pull/1412))

- Adds the laser pointer tool.

#### [firefox] Fix the pointer getting stuck down when you press the control key ([#1390](https://github.com/tldraw/tldraw/pull/1390))

- [Firefox] Fixed a bug where the pointer could get stuck down when the control key is held down.

#### Vertical text alignment for geo shapes ([#1414](https://github.com/tldraw/tldraw/pull/1414))

- This adds vertical text alignment property to geo shapes.

#### [fix] page menu, drag handle css ([#1406](https://github.com/tldraw/tldraw/pull/1406))

- Fix styling in the page menu

#### Switch to new collaborators component ([#1405](https://github.com/tldraw/tldraw/pull/1405))

- [Breaking] Removes the old version of LiveCollaborators, replacing it with the new one based on `TLInstancePresence`

#### [improvement] refactor paste to support multi-line text ([#1398](https://github.com/tldraw/tldraw/pull/1398))

- Improves clipboard logic when pasting text
- Adds support for pasting multi-line text
- Adds maximum widths when pasting single-line text
- Adds support for RTL languages when pasting multi-line or wrapped text
- Strips leading indentation when pasting text

#### remove url state, to private ([#1402](https://github.com/tldraw/tldraw/pull/1402))

- [editor] remove `useUrlState`

#### Don't allow the users to use keyboard shortcuts to select tools in readonly mode. ([#1382](https://github.com/tldraw/tldraw/pull/1382))

- Disable keyboard shortcut events for tools in readonly mode. We only allow the select, hand tools, and zoom tool.

#### [fix] Don't synchronize isReadOnly ([#1396](https://github.com/tldraw/tldraw/pull/1396))

- Removes the isReadOnly value from the `user_document_settings` record type.

#### fix pasted tabs not getting converted to space ([#1388](https://github.com/tldraw/tldraw/pull/1388))

- Fixed a bug where pasted tabs wouldn't get converted into spaces.

#### Delete an empty text shape when clicking on another text shape. ([#1384](https://github.com/tldraw/tldraw/pull/1384))

- Fix a problem with empty text shapes not getting deleted if you clicked on another text shape.

#### Fix setting the grid mode. ([#1386](https://github.com/tldraw/tldraw/pull/1386))

- Fix grid mode toggle.

#### Update codesandbox + example link ([#1368](https://github.com/tldraw/tldraw/pull/1368))

- [docs] Fixed some links to examples.

#### Fix selection foreground being misaligned ([#1380](https://github.com/tldraw/tldraw/pull/1380))

- None (fix for a bug that hasn't released)

#### Expand selection outline for single-selected draw shape ([#1379](https://github.com/tldraw/tldraw/pull/1379))

- Improve selection outlines around horizontal or vertical draw shapes

#### Add localizations for snapshots links ([#1347](https://github.com/tldraw/tldraw/pull/1347))

- Add localization for creating snapshot links.

#### [fix] pointer location not updating when moving over editing shape ([#1378](https://github.com/tldraw/tldraw/pull/1378))

- Fix a bug where the pointer location would not update when moving the pointer over an editing shape.

#### [perf] deleteShapes ([#1373](https://github.com/tldraw/tldraw/pull/1373))

- Perf improvement for deleting shapes in a document with lots of pages.

#### Neaten up pr template ([#1369](https://github.com/tldraw/tldraw/pull/1369))

- None: internal

#### fix a couple of consistency assumptions ([#1365](https://github.com/tldraw/tldraw/pull/1365))

- Fixes a couple of minor consistency bugs affecting shape updating and page deletion in multiplayer contexts.

#### Disable nightly/on-demand webdriver scripts ([#1366](https://github.com/tldraw/tldraw/pull/1366))

None

#### avoid lazy race conditions ([#1364](https://github.com/tldraw/tldraw/pull/1364))

[internal only]

#### Adds CI for webdriver tests ([#1343](https://github.com/tldraw/tldraw/pull/1343))

- Github action CI workflows added for webdriver tests
- Refactored e2e test runner

#### enable eslint for test files ([#1363](https://github.com/tldraw/tldraw/pull/1363))

internal-only change

#### [perf] make ensureStoreIsUsable scale better ([#1362](https://github.com/tldraw/tldraw/pull/1362))

- Add a brief release note for your PR here.

#### Export Events stuff ([#1360](https://github.com/tldraw/tldraw/pull/1360))

- [ui] export the `TLUiEventSource` type
- [ui] export the `EventsProviderProps ` type
- [ui] export the `useEvents ` hook

#### presence-related fixes ([#1361](https://github.com/tldraw/tldraw/pull/1361))

- Fix a bug where creating a page could throw an error in some multiplayer contexts.

#### [improvement] rename onEvent to onUiEvent ([#1358](https://github.com/tldraw/tldraw/pull/1358))

- [docs] Adds docs for ui events
- [tldraw] Renames `onEvent` to `onUiEvent`

#### [docs] Update links in docs ([#1357](https://github.com/tldraw/tldraw/pull/1357))

- [docs] Update links in docs to point to the tldraw repository rather than tldraw-examples.

#### [improvement] Ui events followup ([#1354](https://github.com/tldraw/tldraw/pull/1354))

- [ui] Adds source to ui events data object
- [ui] Corrects source for toolbar events
- [ui] Corrects source for clipboard events
- [examples] Updates events example

#### [fix] various text ([#1350](https://github.com/tldraw/tldraw/pull/1350))

- Allow leading whitespace

#### [chore] Bump nanoid ([#1349](https://github.com/tldraw/tldraw/pull/1349))

- Remove unused userId and instanceId props from AppOptions

#### Fix "copy as png" in firefox when `dom.events.asyncClipboard.clipboardItem` is enabled ([#1342](https://github.com/tldraw/tldraw/pull/1342))

- Fix "copy as png" in firefox when `dom.events.asyncClipboard.clipboardItem` is enabled

#### Rework the assets package for strategy-specific imports ([#1341](https://github.com/tldraw/tldraw/pull/1341))

- [dev] If you're using the `@tldraw/assets` package, you need to update your code to `import { getAssetUrlsByImport } from '@tldraw/assets/imports'` instead of `import { getBundlerAssetUrls } from '@tldraw/assets`

---

#### 💥 Breaking Change

- [minor] Mark tlsync-client internal APIs [#1481](https://github.com/tldraw/tldraw/pull/1481) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/store`
  - [tweak] migrate store snapshot arguments [#1659](https://github.com/tldraw/tldraw/pull/1659) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/store`, `@tldraw/tlschema`
  - [improvement] store snapshot types [#1657](https://github.com/tldraw/tldraw/pull/1657) ([@steveruizok](https://github.com/steveruizok))
  - Rename tlstore to store [#1507](https://github.com/tldraw/tldraw/pull/1507) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/ui`
  - [fix] react component runaways, error boundaries [#1625](https://github.com/tldraw/tldraw/pull/1625) ([@steveruizok](https://github.com/steveruizok))
  - Tidy up [#1600](https://github.com/tldraw/tldraw/pull/1600) ([@steveruizok](https://github.com/steveruizok))
  - Use unpkg as a default for serving assets. [#1548](https://github.com/tldraw/tldraw/pull/1548) ([@MitjaBezensek](https://github.com/MitjaBezensek))
  - Switch to new collaborators component [#1405](https://github.com/tldraw/tldraw/pull/1405) ([@ds300](https://github.com/ds300))
  - [improvement] Ui events followup [#1354](https://github.com/tldraw/tldraw/pull/1354) ([@steveruizok](https://github.com/steveruizok))
  - [feature] ui events [#1326](https://github.com/tldraw/tldraw/pull/1326) ([@orangemug](https://github.com/orangemug) [@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/tldraw`, `@tldraw/tlschema`
  - `ShapeUtil` refactor, `Editor` cleanup [#1611](https://github.com/tldraw/tldraw/pull/1611) ([@steveruizok](https://github.com/steveruizok))
  - [refactor] restore createTLSchema [#1444](https://github.com/tldraw/tldraw/pull/1444) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`
  - Remove on drop override [#1612](https://github.com/tldraw/tldraw/pull/1612) ([@steveruizok](https://github.com/steveruizok))
  - Rename `ShapeUtil.render` -> `ShapeUtil.component` [#1609](https://github.com/tldraw/tldraw/pull/1609) ([@steveruizok](https://github.com/steveruizok))
  - [fix] camera culling [#1602](https://github.com/tldraw/tldraw/pull/1602) ([@steveruizok](https://github.com/steveruizok))
  - remove `ShapeUtil.transform` [#1590](https://github.com/tldraw/tldraw/pull/1590) ([@steveruizok](https://github.com/steveruizok))
  - remove `ShapeUtil.point` [#1591](https://github.com/tldraw/tldraw/pull/1591) ([@steveruizok](https://github.com/steveruizok))
  - remove url state, to private [#1402](https://github.com/tldraw/tldraw/pull/1402) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/tldraw`, `@tldraw/ui`
  - tldraw.css [#1607](https://github.com/tldraw/tldraw/pull/1607) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/tlschema`, `@tldraw/ui`, `@tldraw/utils`, `@tldraw/validate`
  - Styles API [#1580](https://github.com/tldraw/tldraw/pull/1580) ([@SomeHats](https://github.com/SomeHats) [@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/tldraw`, `@tldraw/tlschema`, `@tldraw/utils`, `@tldraw/validate`
  - mini `defineShape` API [#1563](https://github.com/tldraw/tldraw/pull/1563) ([@SomeHats](https://github.com/SomeHats))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/tldraw`, `@tldraw/ui`
  - `ExternalContentManager` for handling external content (files, images, etc) [#1550](https://github.com/tldraw/tldraw/pull/1550) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/tlschema`, `@tldraw/ui`
  - hoist opacity out of props [#1526](https://github.com/tldraw/tldraw/pull/1526) ([@SomeHats](https://github.com/SomeHats))
  - Add support for project names [#1340](https://github.com/tldraw/tldraw/pull/1340) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
  - [refactor] Remove `TLShapeDef`, `getShapeUtilByType`. [#1432](https://github.com/tldraw/tldraw/pull/1432) ([@steveruizok](https://github.com/steveruizok) [@SomeHats](https://github.com/SomeHats))
  - [fix] Don't synchronize isReadOnly [#1396](https://github.com/tldraw/tldraw/pull/1396) ([@ds300](https://github.com/ds300))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/store`, `@tldraw/tlschema`, `@tldraw/ui`
  - Independent instance state persistence [#1493](https://github.com/tldraw/tldraw/pull/1493) ([@ds300](https://github.com/ds300))
  - tlschema cleanup [#1509](https://github.com/tldraw/tldraw/pull/1509) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/ui`
  - Renaming types, shape utils, tools [#1513](https://github.com/tldraw/tldraw/pull/1513) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/tlschema`, `@tldraw/validate`
  - Rename tlvalidate to validate [#1508](https://github.com/tldraw/tldraw/pull/1508) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/file-format`, `@tldraw/tlschema`, `@tldraw/ui`
  - Cleanup @tldraw/ui types / exports [#1504](https://github.com/tldraw/tldraw/pull/1504) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/indices`, `@tldraw/tldraw`, `@tldraw/ui`
  - rename app to editor [#1503](https://github.com/tldraw/tldraw/pull/1503) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/tldraw`, `@tldraw/tlschema`, `@tldraw/ui`
  - [refactor] User-facing APIs [#1478](https://github.com/tldraw/tldraw/pull/1478) ([@steveruizok](https://github.com/steveruizok))
  - [chore] refactor user preferences [#1435](https://github.com/tldraw/tldraw/pull/1435) ([@ds300](https://github.com/ds300))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/tlschema`, `@tldraw/ui`
  - [refactor] update record names [#1473](https://github.com/tldraw/tldraw/pull/1473) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/tlschema`
  - [refactor] remove `createTLSchema` [#1440](https://github.com/tldraw/tldraw/pull/1440) ([@steveruizok](https://github.com/steveruizok))
  - [refactor] record migrations [#1430](https://github.com/tldraw/tldraw/pull/1430) ([@steveruizok](https://github.com/steveruizok))
  - [chore] Bump nanoid [#1349](https://github.com/tldraw/tldraw/pull/1349) ([@ds300](https://github.com/ds300))
- `@tldraw/editor`, `@tldraw/indices`, `@tldraw/utils`
  - Create @tldraw/indices package [#1426](https://github.com/tldraw/tldraw/pull/1426) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/ui`
  - [improvement] rename onEvent to onUiEvent [#1358](https://github.com/tldraw/tldraw/pull/1358) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/assets`, `@tldraw/tlschema`
  - Rework the assets package for strategy-specific imports [#1341](https://github.com/tldraw/tldraw/pull/1341) ([@SomeHats](https://github.com/SomeHats))

#### 🚀 Enhancement

- [feature] Easier store persistence API + persistence example [#1480](https://github.com/tldraw/tldraw/pull/1480) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/tlschema`, `@tldraw/ui`
  - Styles API follow-ups [#1636](https://github.com/tldraw/tldraw/pull/1636) ([@SomeHats](https://github.com/SomeHats) [@steveruizok](https://github.com/steveruizok))
  - (1/2) Cursor Chat - Presence [#1487](https://github.com/tldraw/tldraw/pull/1487) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`
  - Make resizeBox a regular function [#1610](https://github.com/tldraw/tldraw/pull/1610) ([@steveruizok](https://github.com/steveruizok))
  - [improvement] set horizontal position using text alignment [#1419](https://github.com/tldraw/tldraw/pull/1419) ([@steveruizok](https://github.com/steveruizok))
  - [fix] pointer location not updating when moving over editing shape [#1378](https://github.com/tldraw/tldraw/pull/1378) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/tlschema`
  - [fix] yjs presence [#1603](https://github.com/tldraw/tldraw/pull/1603) ([@steveruizok](https://github.com/steveruizok))
  - (1/2) Timeout collaborator cursors [#1525](https://github.com/tldraw/tldraw/pull/1525) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
  - [feature] add vertical align to note shape [#1539](https://github.com/tldraw/tldraw/pull/1539) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`
  - Add optional generic to `updateShapes` / `createShapes` [#1579](https://github.com/tldraw/tldraw/pull/1579) ([@steveruizok](https://github.com/steveruizok))
  - move v1 migration code into file-format [#1499](https://github.com/tldraw/tldraw/pull/1499) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/ui`
  - Add support for locking shapes [#1447](https://github.com/tldraw/tldraw/pull/1447) ([@MitjaBezensek](https://github.com/MitjaBezensek) [@steveruizok](https://github.com/steveruizok))
  - [feature] reduce motion [#1485](https://github.com/tldraw/tldraw/pull/1485) ([@steveruizok](https://github.com/steveruizok))
  - [mini-feature] Following indicator [#1468](https://github.com/tldraw/tldraw/pull/1468) ([@steveruizok](https://github.com/steveruizok))
  - Add SVG cursors for all cursor types [#1416](https://github.com/tldraw/tldraw/pull/1416) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
  - [improvement] refactor paste to support multi-line text [#1398](https://github.com/tldraw/tldraw/pull/1398) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/assets`, `@tldraw/editor`, `@tldraw/ui`
  - [3/3] Highlighter styling [#1490](https://github.com/tldraw/tldraw/pull/1490) ([@SomeHats](https://github.com/SomeHats) [@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/primitives`
  - [2/3] renderer changes to support "sandwich mode" highlighting [#1418](https://github.com/tldraw/tldraw/pull/1418) ([@SomeHats](https://github.com/SomeHats))
- `@tldraw/assets`, `@tldraw/editor`, `@tldraw/tlschema`, `@tldraw/ui`
  - [1/3] initial highlighter shape/tool [#1401](https://github.com/tldraw/tldraw/pull/1401) ([@SomeHats](https://github.com/SomeHats))
  - [feature] add laser pointer [#1412](https://github.com/tldraw/tldraw/pull/1412) ([@steveruizok](https://github.com/steveruizok))
  - Vertical text alignment for geo shapes [#1414](https://github.com/tldraw/tldraw/pull/1414) ([@MitjaBezensek](https://github.com/MitjaBezensek) [@steveruizok](https://github.com/steveruizok))
- `@tldraw/ui`
  - [feature] Add checkbox to toolbar [#1423](https://github.com/tldraw/tldraw/pull/1423) ([@steveruizok](https://github.com/steveruizok))
  - Add stuff for new 'share project' flow [#1403](https://github.com/tldraw/tldraw/pull/1403) ([@ds300](https://github.com/ds300))
  - Snapshot link menu translations [#1399](https://github.com/tldraw/tldraw/pull/1399) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/assets`, `@tldraw/ui`
  - open menus refactor [#1400](https://github.com/tldraw/tldraw/pull/1400) ([@steveruizok](https://github.com/steveruizok))

#### 🐛 Bug Fix

- Lokalise: Translations update [#1618](https://github.com/tldraw/tldraw/pull/1618) ([@TodePond](https://github.com/TodePond))
- Fa translation [#1500](https://github.com/tldraw/tldraw/pull/1500) ([@mokazemi](https://github.com/mokazemi) [@steveruizok](https://github.com/steveruizok))
- Lokalise: Translations update [#1572](https://github.com/tldraw/tldraw/pull/1572) ([@TodePond](https://github.com/TodePond))
- Update changelog. Bump version. [#1546](https://github.com/tldraw/tldraw/pull/1546) ([@MitjaBezensek](https://github.com/MitjaBezensek))
- Lokalise: Translations update [#1515](https://github.com/tldraw/tldraw/pull/1515) ([@TodePond](https://github.com/TodePond))
- VS Code version bump, changelog. [#1497](https://github.com/tldraw/tldraw/pull/1497) ([@MitjaBezensek](https://github.com/MitjaBezensek))
- Fix issue template label not getting applied [#1428](https://github.com/tldraw/tldraw/pull/1428) ([@TodePond](https://github.com/TodePond))
- Bump version. [#1421](https://github.com/tldraw/tldraw/pull/1421) ([@MitjaBezensek](https://github.com/MitjaBezensek))
- Update community translations + remove unused translations [#1356](https://github.com/tldraw/tldraw/pull/1356) ([@TodePond](https://github.com/TodePond))
- [docs] Update links in docs [#1357](https://github.com/tldraw/tldraw/pull/1357) ([@steveruizok](https://github.com/steveruizok))
- [chore] Add label options to PR template [#1339](https://github.com/tldraw/tldraw/pull/1339) ([@ds300](https://github.com/ds300))
- Fix publishing [#1338](https://github.com/tldraw/tldraw/pull/1338) ([@SomeHats](https://github.com/SomeHats))
- Update README.md [#1331](https://github.com/tldraw/tldraw/pull/1331) ([@steveruizok](https://github.com/steveruizok))
- [docs] editor API [#1328](https://github.com/tldraw/tldraw/pull/1328) ([@steveruizok](https://github.com/steveruizok))
- [docs] Add missing params docs [#1223](https://github.com/tldraw/tldraw/pull/1223) ([@TodePond](https://github.com/TodePond))
- Add link to original tldraw within issue template [#1225](https://github.com/tldraw/tldraw/pull/1225) ([@TodePond](https://github.com/TodePond))
- Fix issue templates not appearing [#1228](https://github.com/tldraw/tldraw/pull/1228) ([@TodePond](https://github.com/TodePond))
- [improvement] readme / contributing [#1199](https://github.com/tldraw/tldraw/pull/1199) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
- [improvement] add bug report / feature request [#1218](https://github.com/tldraw/tldraw/pull/1218) ([@steveruizok](https://github.com/steveruizok))
- add `env` and prefix output options to exec [#1217](https://github.com/tldraw/tldraw/pull/1217) ([@SomeHats](https://github.com/SomeHats))
- [wip] Going bublic [#1195](https://github.com/tldraw/tldraw/pull/1195) ([@SomeHats](https://github.com/SomeHats) [@ds300](https://github.com/ds300) [@orangemug](https://github.com/orangemug) [@steveruizok](https://github.com/steveruizok) [@TodePond](https://github.com/TodePond))
- [chore] use explicit yarn in clean script [#1216](https://github.com/tldraw/tldraw/pull/1216) ([@ds300](https://github.com/ds300))
- fix husky install [#1212](https://github.com/tldraw/tldraw/pull/1212) ([@SomeHats](https://github.com/SomeHats))
- Alex/test [#1202](https://github.com/tldraw/tldraw/pull/1202) ([@SomeHats](https://github.com/SomeHats))
- `@tldraw/editor`
  - Fix crash when rotating a deleted shape [#1658](https://github.com/tldraw/tldraw/pull/1658) ([@TodePond](https://github.com/TodePond))
  - [fix] pen mode touches [#1655](https://github.com/tldraw/tldraw/pull/1655) ([@steveruizok](https://github.com/steveruizok))
  - Fix text shapes not having colour [#1649](https://github.com/tldraw/tldraw/pull/1649) ([@TodePond](https://github.com/TodePond))
  - Fix SVG cursors not being used [#1639](https://github.com/tldraw/tldraw/pull/1639) ([@TodePond](https://github.com/TodePond))
  - [fix] tldraw file drop [#1616](https://github.com/tldraw/tldraw/pull/1616) ([@steveruizok](https://github.com/steveruizok))
  - Make sure loading screens use dark mode user preference. [#1552](https://github.com/tldraw/tldraw/pull/1552) ([@MitjaBezensek](https://github.com/MitjaBezensek) [@steveruizok](https://github.com/steveruizok))
  - [fix] Remove group shape export backgrounds [#1587](https://github.com/tldraw/tldraw/pull/1587) ([@steveruizok](https://github.com/steveruizok))
  - Move the loading of assets to the TldrawEditorWithReadyStore so that all code paths load the assets. [#1561](https://github.com/tldraw/tldraw/pull/1561) ([@MitjaBezensek](https://github.com/MitjaBezensek))
  - shapes folder, move tools into shape defs [#1574](https://github.com/tldraw/tldraw/pull/1574) ([@SomeHats](https://github.com/SomeHats))
  - offset drop point by editor client rect [#1564](https://github.com/tldraw/tldraw/pull/1564) ([@BrianHung](https://github.com/BrianHung))
  - More misc sync fixes [#1559](https://github.com/tldraw/tldraw/pull/1559) ([@ds300](https://github.com/ds300))
  - Misc sync fixes [#1555](https://github.com/tldraw/tldraw/pull/1555) ([@ds300](https://github.com/ds300))
  - [fix] Shift key code / nudge [#1537](https://github.com/tldraw/tldraw/pull/1537) ([@steveruizok](https://github.com/steveruizok))
  - scale exported canvases when they reach the browsers max size [#1536](https://github.com/tldraw/tldraw/pull/1536) ([@SomeHats](https://github.com/SomeHats))
  - [fix] control click on mac [#1535](https://github.com/tldraw/tldraw/pull/1535) ([@steveruizok](https://github.com/steveruizok))
  - Fix being able to undo following [#1531](https://github.com/tldraw/tldraw/pull/1531) ([@TodePond](https://github.com/TodePond))
  - send user prefs data in broadcast msg [#1466](https://github.com/tldraw/tldraw/pull/1466) ([@ds300](https://github.com/ds300))
  - Fix positioning of default cursor [#1458](https://github.com/tldraw/tldraw/pull/1458) ([@TodePond](https://github.com/TodePond))
  - change pointer cursor to white [#1454](https://github.com/tldraw/tldraw/pull/1454) ([@TodePond](https://github.com/TodePond))
  - Fix cursor shadow getting clipped [#1441](https://github.com/tldraw/tldraw/pull/1441) ([@TodePond](https://github.com/TodePond))
  - Fix new wobble [#1431](https://github.com/tldraw/tldraw/pull/1431) ([@TodePond](https://github.com/TodePond))
  - [fix] laser pointer [#1429](https://github.com/tldraw/tldraw/pull/1429) ([@steveruizok](https://github.com/steveruizok))
  - [fix] reorder handles in front of selection [#1420](https://github.com/tldraw/tldraw/pull/1420) ([@steveruizok](https://github.com/steveruizok))
  - [firefox] Fix the pointer getting stuck down when you press the control key [#1390](https://github.com/tldraw/tldraw/pull/1390) ([@TodePond](https://github.com/TodePond))
  - fix viewport following [#1411](https://github.com/tldraw/tldraw/pull/1411) ([@ds300](https://github.com/ds300))
  - fix pasted tabs not getting converted to space [#1388](https://github.com/tldraw/tldraw/pull/1388) ([@TodePond](https://github.com/TodePond))
  - Delete an empty text shape when clicking on another text shape. [#1384](https://github.com/tldraw/tldraw/pull/1384) ([@MitjaBezensek](https://github.com/MitjaBezensek))
  - Fix setting the grid mode. [#1386](https://github.com/tldraw/tldraw/pull/1386) ([@MitjaBezensek](https://github.com/MitjaBezensek))
  - Fix selection foreground being misaligned [#1380](https://github.com/tldraw/tldraw/pull/1380) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
  - Expand selection outline for single-selected draw shape [#1379](https://github.com/tldraw/tldraw/pull/1379) ([@SomeHats](https://github.com/SomeHats))
  - [fix] Allow interactions with embeds in readonly mode [#1333](https://github.com/tldraw/tldraw/pull/1333) ([@MitjaBezensek](https://github.com/MitjaBezensek))
  - [perf] deleteShapes [#1373](https://github.com/tldraw/tldraw/pull/1373) ([@ds300](https://github.com/ds300))
  - fix a couple of consistency assumptions [#1365](https://github.com/tldraw/tldraw/pull/1365) ([@ds300](https://github.com/ds300))
  - [fix] various text [#1350](https://github.com/tldraw/tldraw/pull/1350) ([@steveruizok](https://github.com/steveruizok))
  - [fix] tabs in text exports [#1323](https://github.com/tldraw/tldraw/pull/1323) ([@steveruizok](https://github.com/steveruizok))
  - [fix] update useTransform.ts [#1327](https://github.com/tldraw/tldraw/pull/1327) ([@steveruizok](https://github.com/steveruizok))
  - [improvement] dragging start distance on coarse pointer [#1220](https://github.com/tldraw/tldraw/pull/1220) ([@steveruizok](https://github.com/steveruizok))
  - [fix] SVG export for arrows with labels but no arrowheads [#1229](https://github.com/tldraw/tldraw/pull/1229) ([@steveruizok](https://github.com/steveruizok))
  - add docs for TLShapeUtil [#1215](https://github.com/tldraw/tldraw/pull/1215) ([@TodePond](https://github.com/TodePond))
  - [fix] publish [#1222](https://github.com/tldraw/tldraw/pull/1222) ([@ds300](https://github.com/ds300))
  - [fix] typo in isFocusingInput [#1221](https://github.com/tldraw/tldraw/pull/1221) ([@ds300](https://github.com/ds300))
  - [feat] new LiveCollaborators behind feature flag [#1219](https://github.com/tldraw/tldraw/pull/1219) ([@ds300](https://github.com/ds300))
  - [fix] collaborator render order [#1213](https://github.com/tldraw/tldraw/pull/1213) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/ui`
  - 3/2 Cursor chat [#1623](https://github.com/tldraw/tldraw/pull/1623) ([@steveruizok](https://github.com/steveruizok))
  - [fix] embeds [#1578](https://github.com/tldraw/tldraw/pull/1578) ([@steveruizok](https://github.com/steveruizok))
  - highlighter fixes [#1530](https://github.com/tldraw/tldraw/pull/1530) ([@SomeHats](https://github.com/SomeHats))
  - Feature flags rework [#1474](https://github.com/tldraw/tldraw/pull/1474) ([@SomeHats](https://github.com/SomeHats))
  - remove svg layer, html all the things, rs to tl [#1227](https://github.com/tldraw/tldraw/pull/1227) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
  - Added `pHYs` to import/export of png images [#1200](https://github.com/tldraw/tldraw/pull/1200) ([@orangemug](https://github.com/orangemug) [@steveruizok](https://github.com/steveruizok))
- `@tldraw/tldraw`
  - [fix] tldraw api report [#1615](https://github.com/tldraw/tldraw/pull/1615) ([@steveruizok](https://github.com/steveruizok))
  - Fix to not ignore the `userId` option for `<Tldraw/>` component in `@tldraw/tldraw` [#1205](https://github.com/tldraw/tldraw/pull/1205) ([@orangemug](https://github.com/orangemug))
- `@tldraw/editor`, `@tldraw/primitives`
  - [refactor] snapping [#1589](https://github.com/tldraw/tldraw/pull/1589) ([@steveruizok](https://github.com/steveruizok))
  - Fix arrows with weird bends crashing [#1540](https://github.com/tldraw/tldraw/pull/1540) ([@TodePond](https://github.com/TodePond))
  - ensure that fixed points stay fixed [#1523](https://github.com/tldraw/tldraw/pull/1523) ([@steveruizok](https://github.com/steveruizok))
  - Use `strokePathData` for `<ShapeFill/>` path to avoid bugs in the inner path algo [#1207](https://github.com/tldraw/tldraw/pull/1207) ([@orangemug](https://github.com/orangemug) [@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/tlschema`
  - update exports for user presence [#1583](https://github.com/tldraw/tldraw/pull/1583) ([@steveruizok](https://github.com/steveruizok))
  - [improvement] Embed shape cleanup [#1569](https://github.com/tldraw/tldraw/pull/1569) ([@steveruizok](https://github.com/steveruizok))
  - Add migration for horizontal alignment [#1443](https://github.com/tldraw/tldraw/pull/1443) ([@MitjaBezensek](https://github.com/MitjaBezensek) [@steveruizok](https://github.com/steveruizok))
  - [chore] move schema construction to tlschema package [#1334](https://github.com/tldraw/tldraw/pull/1334) ([@ds300](https://github.com/ds300))
- `@tldraw/assets`, `@tldraw/editor`, `@tldraw/ui`, `@tldraw/utils`
  - Asset improvements [#1557](https://github.com/tldraw/tldraw/pull/1557) ([@MitjaBezensek](https://github.com/MitjaBezensek))
- `@tldraw/ui`
  - Use `"Toggle locked"` [#1538](https://github.com/tldraw/tldraw/pull/1538) ([@steveruizok](https://github.com/steveruizok))
  - Select locked shapes on long press [#1529](https://github.com/tldraw/tldraw/pull/1529) ([@steveruizok](https://github.com/steveruizok))
  - remove safari special-casing for paste [#1470](https://github.com/tldraw/tldraw/pull/1470) ([@SomeHats](https://github.com/SomeHats))
  - Don't allow `g` keyboard shortcut in readonly mode, show laser tool in the toolbar [#1459](https://github.com/tldraw/tldraw/pull/1459) ([@MitjaBezensek](https://github.com/MitjaBezensek) [@steveruizok](https://github.com/steveruizok))
  - Fix people menu button border on android [#1471](https://github.com/tldraw/tldraw/pull/1471) ([@TodePond](https://github.com/TodePond))
  - [fix] lock option for laser tool [#1460](https://github.com/tldraw/tldraw/pull/1460) ([@steveruizok](https://github.com/steveruizok))
  - Add laser keyboard shortcut. [#1467](https://github.com/tldraw/tldraw/pull/1467) ([@MitjaBezensek](https://github.com/MitjaBezensek))
  - [fix] make follow icon visible on iPad [#1462](https://github.com/tldraw/tldraw/pull/1462) ([@steveruizok](https://github.com/steveruizok))
  - [fix] page item submenu [#1461](https://github.com/tldraw/tldraw/pull/1461) ([@steveruizok](https://github.com/steveruizok))
  - Add translations for "Leave shared project" action [#1394](https://github.com/tldraw/tldraw/pull/1394) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
  - [fix] page menu, drag handle css [#1406](https://github.com/tldraw/tldraw/pull/1406) ([@steveruizok](https://github.com/steveruizok))
  - Don't allow the users to use keyboard shortcuts to select tools in readonly mode. [#1382](https://github.com/tldraw/tldraw/pull/1382) ([@MitjaBezensek](https://github.com/MitjaBezensek))
  - Disabling middle click paste in favour of panning [#1335](https://github.com/tldraw/tldraw/pull/1335) ([@orangemug](https://github.com/orangemug) [@steveruizok](https://github.com/steveruizok))
  - Export Events stuff [#1360](https://github.com/tldraw/tldraw/pull/1360) ([@steveruizok](https://github.com/steveruizok))
  - Fix "copy as png" in firefox when `dom.events.asyncClipboard.clipboardItem` is enabled [#1342](https://github.com/tldraw/tldraw/pull/1342) ([@orangemug](https://github.com/orangemug))
  - [tiny] rename show menu paste [#1332](https://github.com/tldraw/tldraw/pull/1332) ([@steveruizok](https://github.com/steveruizok))
  - update @radix-ui/react-popover to 1.0.6-rc.5 [#1206](https://github.com/tldraw/tldraw/pull/1206) ([@SomeHats](https://github.com/SomeHats))
- `@tldraw/file-format`
  - Filter out unused assets. [#1502](https://github.com/tldraw/tldraw/pull/1502) ([@MitjaBezensek](https://github.com/MitjaBezensek))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/tlschema`, `@tldraw/ui`, `@tldraw/utils`
  - Stricter ID types [#1439](https://github.com/tldraw/tldraw/pull/1439) ([@SomeHats](https://github.com/SomeHats) [@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/primitives`, `@tldraw/ui`
  - Measure individual words instead of just line breaks for text exports [#1397](https://github.com/tldraw/tldraw/pull/1397) ([@SomeHats](https://github.com/SomeHats))
- `@tldraw/tlschema`
  - [perf] make ensureStoreIsUsable scale better [#1362](https://github.com/tldraw/tldraw/pull/1362) ([@ds300](https://github.com/ds300))
- `@tldraw/editor`, `@tldraw/utils`
  - presence-related fixes [#1361](https://github.com/tldraw/tldraw/pull/1361) ([@ds300](https://github.com/ds300))
- `@tldraw/assets`, `@tldraw/editor`, `@tldraw/tlschema`, `@tldraw/ui`
  - [feature] `check-box` geo shape [#1330](https://github.com/tldraw/tldraw/pull/1330) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/assets`, `@tldraw/editor`, `@tldraw/tldraw`, `@tldraw/ui`
  - New vite-based examples app [#1226](https://github.com/tldraw/tldraw/pull/1226) ([@SomeHats](https://github.com/SomeHats))
- `@tldraw/assets`, `@tldraw/file-format`, `@tldraw/polyfills`, `@tldraw/primitives`, `@tldraw/tldraw`, `@tldraw/tlschema`, `@tldraw/ui`, `@tldraw/utils`
  - [wip] Going bublic [#1195](https://github.com/tldraw/tldraw/pull/1195) ([@SomeHats](https://github.com/SomeHats) [@ds300](https://github.com/ds300) [@orangemug](https://github.com/orangemug) [@steveruizok](https://github.com/steveruizok) [@TodePond](https://github.com/TodePond))
- `@tldraw/assets`, `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/polyfills`, `@tldraw/primitives`, `@tldraw/tldraw`, `@tldraw/tlschema`, `@tldraw/ui`, `@tldraw/utils`
  - [chore] update lazyrepo [#1211](https://github.com/tldraw/tldraw/pull/1211) ([@ds300](https://github.com/ds300))
  - [lite] upgrade lazyrepo [#1198](https://github.com/tldraw/tldraw/pull/1198) ([@ds300](https://github.com/ds300))
  - [wip] Going bublic [#1195](https://github.com/tldraw/tldraw/pull/1195) ([@SomeHats](https://github.com/SomeHats) [@ds300](https://github.com/ds300) [@orangemug](https://github.com/orangemug) [@steveruizok](https://github.com/steveruizok) [@TodePond](https://github.com/TodePond))
- `@tldraw/tlschema`, `@tldraw/ui`
  - [fix] pick a better default language [#1201](https://github.com/tldraw/tldraw/pull/1201) ([@steveruizok](https://github.com/steveruizok) [@TodePond](https://github.com/TodePond))
- `@tldraw/assets`, `@tldraw/editor`, `@tldraw/tldraw`, `@tldraw/tlschema`, `@tldraw/ui`, `@tldraw/utils`
  - derived presence state [#1204](https://github.com/tldraw/tldraw/pull/1204) ([@ds300](https://github.com/ds300))

#### ⚠️ Pushed to `main`

- Update publish-new.yml ([@steveruizok](https://github.com/steveruizok))
- Update lerna.json ([@steveruizok](https://github.com/steveruizok))
- Update publish-new.ts ([@steveruizok](https://github.com/steveruizok))
- change App to Editor in docs ([@TodePond](https://github.com/TodePond))
- rename api.mdx to editor.mdx ([@TodePond](https://github.com/TodePond))
- remove e2e files ([@steveruizok](https://github.com/steveruizok))
- main: notify huppy after release ([@SomeHats](https://github.com/SomeHats))
- main: exclude @tldraw/assets from vite dep optimization to fix examples links ([@SomeHats](https://github.com/SomeHats))
- `@tldraw/assets`, `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/indices`, `@tldraw/polyfills`, `@tldraw/primitives`, `@tldraw/store`, `@tldraw/tldraw`, `@tldraw/tlschema`, `@tldraw/ui`, `@tldraw/utils`, `@tldraw/validate`
  - update lazyrepo ([@ds300](https://github.com/ds300))

#### 🏠 Internal

- [chore] bump vscode extension to 2.0.9 [#1662](https://github.com/tldraw/tldraw/pull/1662) ([@steveruizok](https://github.com/steveruizok))
- untrack generated files [#1646](https://github.com/tldraw/tldraw/pull/1646) ([@steveruizok](https://github.com/steveruizok))
- Update pr template [#1570](https://github.com/tldraw/tldraw/pull/1570) ([@steveruizok](https://github.com/steveruizok))
- Add contributor license agreement. [#1556](https://github.com/tldraw/tldraw/pull/1556) ([@steveruizok](https://github.com/steveruizok))
- Reinstate auto [#1524](https://github.com/tldraw/tldraw/pull/1524) ([@ds300](https://github.com/ds300))
- [infra] use npx to run auto [#1521](https://github.com/tldraw/tldraw/pull/1521) ([@ds300](https://github.com/ds300))
- Revert 09c36781 & tweak linting [#1501](https://github.com/tldraw/tldraw/pull/1501) ([@SomeHats](https://github.com/SomeHats))
- [fix] eslint from brivate [#1498](https://github.com/tldraw/tldraw/pull/1498) ([@steveruizok](https://github.com/steveruizok))
- [chore] remove webdriver dependencies / scripts [#1488](https://github.com/tldraw/tldraw/pull/1488) ([@steveruizok](https://github.com/steveruizok))
- [fix] local e2e script [#1442](https://github.com/tldraw/tldraw/pull/1442) ([@steveruizok](https://github.com/steveruizok))
- [chore] remove yarnrc-private.yml [#1427](https://github.com/tldraw/tldraw/pull/1427) ([@steveruizok](https://github.com/steveruizok))
- [fix] example routes on vercel [#1391](https://github.com/tldraw/tldraw/pull/1391) ([@steveruizok](https://github.com/steveruizok))
- Neaten up pr template [#1369](https://github.com/tldraw/tldraw/pull/1369) ([@TodePond](https://github.com/TodePond))
- remove references to tldraw-lite [#1367](https://github.com/tldraw/tldraw/pull/1367) ([@SomeHats](https://github.com/SomeHats))
- `@tldraw/editor`, `@tldraw/ui`
  - Explicit shape type checks [#1594](https://github.com/tldraw/tldraw/pull/1594) ([@steveruizok](https://github.com/steveruizok))
  - [improvement] bookmark shape logic [#1568](https://github.com/tldraw/tldraw/pull/1568) ([@steveruizok](https://github.com/steveruizok))
  - Simplify static cursors [#1520](https://github.com/tldraw/tldraw/pull/1520) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/ui`
  - move some kbds into actions and tools [#1585](https://github.com/tldraw/tldraw/pull/1585) ([@BrianHung](https://github.com/BrianHung) [@steveruizok](https://github.com/steveruizok))
  - Add localizations for snapshots links [#1347](https://github.com/tldraw/tldraw/pull/1347) ([@MitjaBezensek](https://github.com/MitjaBezensek))
- `@tldraw/editor`
  - use the right TLEventHandlers [#1486](https://github.com/tldraw/tldraw/pull/1486) ([@judicaelandria](https://github.com/judicaelandria) [@steveruizok](https://github.com/steveruizok))
  - yjs example [#1560](https://github.com/tldraw/tldraw/pull/1560) ([@steveruizok](https://github.com/steveruizok))
  - rename app folder to editor [#1528](https://github.com/tldraw/tldraw/pull/1528) ([@steveruizok](https://github.com/steveruizok))
  - [fix] overlay rendering issues [#1389](https://github.com/tldraw/tldraw/pull/1389) ([@steveruizok](https://github.com/steveruizok))
  - Remove commented code in App [#1377](https://github.com/tldraw/tldraw/pull/1377) ([@steveruizok](https://github.com/steveruizok))
  - enable eslint for test files [#1363](https://github.com/tldraw/tldraw/pull/1363) ([@SomeHats](https://github.com/SomeHats))
- `@tldraw/tlschema`
  - restore styles sets exports [#1512](https://github.com/tldraw/tldraw/pull/1512) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/primitives`
  - replace console.log with nicelog [#1496](https://github.com/tldraw/tldraw/pull/1496) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/indices`, `@tldraw/primitives`, `@tldraw/tldraw`, `@tldraw/ui`
  - [chore] remove benchmark [#1489](https://github.com/tldraw/tldraw/pull/1489) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/tlschema`
  - [tiny] add isPageId [#1482](https://github.com/tldraw/tldraw/pull/1482) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`, `@tldraw/file-format`, `@tldraw/polyfills`, `@tldraw/primitives`, `@tldraw/tldraw`, `@tldraw/tlschema`, `@tldraw/ui`, `@tldraw/utils`
  - avoid lazy race conditions [#1364](https://github.com/tldraw/tldraw/pull/1364) ([@SomeHats](https://github.com/SomeHats))

#### 📝 Documentation

- [fix] remove docs scripts [#1651](https://github.com/tldraw/tldraw/pull/1651) ([@steveruizok](https://github.com/steveruizok))
- (2/2) [docs] Fix links to API. [#1654](https://github.com/tldraw/tldraw/pull/1654) ([@TodePond](https://github.com/TodePond))
- (1/2) [docs] Restore some missing changes [#1652](https://github.com/tldraw/tldraw/pull/1652) ([@TodePond](https://github.com/TodePond))
- [docs] Remove embeds page [#1653](https://github.com/tldraw/tldraw/pull/1653) ([@TodePond](https://github.com/TodePond))
- docs: remove not accepting contributions notice [#1647](https://github.com/tldraw/tldraw/pull/1647) ([@gabrielchl](https://github.com/gabrielchl))
- [docs] Add table of contents to Editor page [#1642](https://github.com/tldraw/tldraw/pull/1642) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
- remove docs (again) [#1643](https://github.com/tldraw/tldraw/pull/1643) ([@steveruizok](https://github.com/steveruizok))
- [1/2] Move docs to brivate [#1640](https://github.com/tldraw/tldraw/pull/1640) ([@steveruizok](https://github.com/steveruizok))
- [docs] Allow sidebar to be scrolled on short screens [#1632](https://github.com/tldraw/tldraw/pull/1632) ([@TodePond](https://github.com/TodePond))
- [docs] Add feedback when you search [#1633](https://github.com/tldraw/tldraw/pull/1633) ([@TodePond](https://github.com/TodePond))
- [docs] Separate some pages out of the Docs section [#1626](https://github.com/tldraw/tldraw/pull/1626) ([@TodePond](https://github.com/TodePond))
- [docs] Fix wrong cursor when hovering buttons [#1630](https://github.com/tldraw/tldraw/pull/1630) ([@TodePond](https://github.com/TodePond))
- [docs] Tighten up wording & structure of Usage page [#1624](https://github.com/tldraw/tldraw/pull/1624) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
- [docs] Tighten up Editor page introduction [#1622](https://github.com/tldraw/tldraw/pull/1622) ([@TodePond](https://github.com/TodePond))
- [docs] Tighten up Introduction page [#1621](https://github.com/tldraw/tldraw/pull/1621) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
- [docs] Simplify paths for uncategorised pages [#1619](https://github.com/tldraw/tldraw/pull/1619) ([@TodePond](https://github.com/TodePond))
- Auto content refresh for docs site [#1606](https://github.com/tldraw/tldraw/pull/1606) ([@steveruizok](https://github.com/steveruizok))
- Remove `@tldraw/utils` from the docs site [#1596](https://github.com/tldraw/tldraw/pull/1596) ([@TodePond](https://github.com/TodePond))
- [docs] Add barebones note about translations [#1593](https://github.com/tldraw/tldraw/pull/1593) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
- Change app to editor in docs [#1592](https://github.com/tldraw/tldraw/pull/1592) ([@TodePond](https://github.com/TodePond))
- add presence to yjs example [#1582](https://github.com/tldraw/tldraw/pull/1582) ([@steveruizok](https://github.com/steveruizok))
- fix: properly remove awareness from store [#1565](https://github.com/tldraw/tldraw/pull/1565) ([@shahriar-shojib](https://github.com/shahriar-shojib) [@steveruizok](https://github.com/steveruizok))
- Add anchor targets to our headings. [#1571](https://github.com/tldraw/tldraw/pull/1571) ([@MitjaBezensek](https://github.com/MitjaBezensek))
- Fix README typo [#1451](https://github.com/tldraw/tldraw/pull/1451) ([@fossinating](https://github.com/fossinating) [@steveruizok](https://github.com/steveruizok))
- Update examples links to point to examples folder. [#1522](https://github.com/tldraw/tldraw/pull/1522) ([@steveruizok](https://github.com/steveruizok))
- Update docs links + guides + build [#1422](https://github.com/tldraw/tldraw/pull/1422) ([@TodePond](https://github.com/TodePond))
- Update codesandbox + example link [#1368](https://github.com/tldraw/tldraw/pull/1368) ([@TodePond](https://github.com/TodePond))
- `@tldraw/editor`
  - [improvement] custom shapes example [#1660](https://github.com/tldraw/tldraw/pull/1660) ([@steveruizok](https://github.com/steveruizok))
  - Add tsdocs to Editor methods [#1581](https://github.com/tldraw/tldraw/pull/1581) ([@TodePond](https://github.com/TodePond) [@steveruizok](https://github.com/steveruizok))
  - [Docs] Change some editor properties to methods [#1553](https://github.com/tldraw/tldraw/pull/1553) ([@TodePond](https://github.com/TodePond))
  - [Docs] Change some internal methods to public [#1554](https://github.com/tldraw/tldraw/pull/1554) ([@TodePond](https://github.com/TodePond))
- `@tldraw/editor`, `@tldraw/tlschema`
  - Styles API docs [#1641](https://github.com/tldraw/tldraw/pull/1641) ([@SomeHats](https://github.com/SomeHats) [@steveruizok](https://github.com/steveruizok))
- `@tldraw/tlschema`
  - TLSchema readme [#1506](https://github.com/tldraw/tldraw/pull/1506) ([@steveruizok](https://github.com/steveruizok))

#### 🧪 Tests

- speed up playwright and add visual regression tests [#1638](https://github.com/tldraw/tldraw/pull/1638) ([@SomeHats](https://github.com/SomeHats) [@huppy-bot[bot]](https://github.com/huppy-bot[bot]))
- Disable nightly/on-demand webdriver scripts [#1366](https://github.com/tldraw/tldraw/pull/1366) ([@orangemug](https://github.com/orangemug))
- Adds CI for webdriver tests [#1343](https://github.com/tldraw/tldraw/pull/1343) ([@orangemug](https://github.com/orangemug))
- Added initial webdriver tests [#1337](https://github.com/tldraw/tldraw/pull/1337) ([@orangemug](https://github.com/orangemug))
- `@tldraw/editor`
  - update editor tests [#1547](https://github.com/tldraw/tldraw/pull/1547) ([@steveruizok](https://github.com/steveruizok))
  - Add DSL to make writing shape-layout test cases much easier [#1413](https://github.com/tldraw/tldraw/pull/1413) ([@SomeHats](https://github.com/SomeHats))
- `@tldraw/editor`, `@tldraw/ui`
  - Add playwright tests [#1484](https://github.com/tldraw/tldraw/pull/1484) ([@steveruizok](https://github.com/steveruizok))

#### 🔩 Dependency Updates

- [chore] update wdio-vscode-service [#1346](https://github.com/tldraw/tldraw/pull/1346) ([@ds300](https://github.com/ds300))
- `@tldraw/editor`, `@tldraw/state`, `@tldraw/store`, `@tldraw/tlschema`, `@tldraw/ui`
  - Incorporate signia as @tldraw/state [#1620](https://github.com/tldraw/tldraw/pull/1620) ([@steveruizok](https://github.com/steveruizok) [@ds300](https://github.com/ds300))
- `@tldraw/assets`, `@tldraw/editor`, `@tldraw/polyfills`, `@tldraw/tldraw`, `@tldraw/ui`
  - Revert "Update dependencies (#1613)" [#1617](https://github.com/tldraw/tldraw/pull/1617) ([@SomeHats](https://github.com/SomeHats))
  - Update dependencies [#1613](https://github.com/tldraw/tldraw/pull/1613) ([@steveruizok](https://github.com/steveruizok))
- `@tldraw/editor`
  - update use-gesture [#1453](https://github.com/tldraw/tldraw/pull/1453) ([@ds300](https://github.com/ds300))

#### Authors: 13

- [@huppy-bot[bot]](https://github.com/huppy-bot[bot])
- alex ([@SomeHats](https://github.com/SomeHats))
- Brian Hung ([@BrianHung](https://github.com/BrianHung))
- David ([@fossinating](https://github.com/fossinating))
- David Sheldrick ([@ds300](https://github.com/ds300))
- Gabriel Lee ([@gabrielchl](https://github.com/gabrielchl))
- Judicael ([@judicaelandria](https://github.com/judicaelandria))
- Lu Wilson ([@TodePond](https://github.com/TodePond))
- Mitja Bezenšek ([@MitjaBezensek](https://github.com/MitjaBezensek))
- Mohammad Kazemi ([@mokazemi](https://github.com/mokazemi))
- Orange Mug ([@orangemug](https://github.com/orangemug))
- Shahriar Shojib ([@shahriar-shojib](https://github.com/shahriar-shojib))
- Steve Ruiz ([@steveruizok](https://github.com/steveruizok))
