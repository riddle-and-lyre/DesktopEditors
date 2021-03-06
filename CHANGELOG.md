# Change log
## 4.8.6
### New features
#### All Editors
* Preinstalled plugins set
* Support SSO authorization
* Czech and Slovak languages in interface
* Macros
* Support of fods, fodt, fodp formats

### Fixes
#### All editors
* Fix bug with images paths

#### Document Editor
* JS Error while inserting empty cell to chart title (bug #36441)
* Fix red cross for images in some situations
* Fix bug with creating several synchronize tips
* Fix line end in thumbnails
* Fix paste simple text to equations
* Fix cursor while rotating object (bug #36114)
* Fix opening some docx (bug #35307)
* Fix chart legend blocking in coedit (bug #35492)
* Fix problem with setting tab several time (bug #34923)
* Fix printing in Edge (bug #35323)
* Fix help for moving shape by pixel (bug #34983)
* Fix special paste in fast co-edit (bug #35310)
* Fix duplicates in strict mode after special paste (bug #35312)
* Fixed bug with moving cursor to the start of the document after removing content control.
* Fix minor problems with co-edit in real time (bug #35398, #35399, #35400)
* A lot of fixes in translations

#### Spreadsheet Editor
* Fix a.Se is not a function error while opening file (bug #36344)
* Fix error with merge table colors
* Fix merge cells after apply table template (bug #36405)
* Fix JS error for some pivot table styles (bug #36290)
* Check xfIndexNumber when merging styles to avoid errors with column styles
* Fix conditional formatting while changing cell values (bug #36253)
* Fix change shape size by yellow markers (bug #35451)
* Fix case sensitive VLOOKUP and HLOOKUP (bug #35528, DocumentServer#140)
* Fix box for Show empty cells as in Russian (bug #35299)
* Fix sparkline type in setting window (bug #35296)
* Fix error in conditional formatting with formula and offset (duplicate variable) (bug #35334)
* Fix error in SEARCH formula (bug #35340)
* Fix freeze pane shadow not hiding (bug #35359)
* Fix showing hidden objects
* Fix VLOOKUP format cell
* A lot of fixes in translations

#### Presentation Editor
* Check buttons layout in reporter mode
* Disable scroll to target in selectwheel (empty selection)
* Fix applying image as background for several slides (bug #36399)
* Fix mouse slide scroll without change zoom (bug #28096)
* Don't disable prev-next buttons for slide demonstration
* Fix presentation demonstration: start from beginning
* Fix notes scroll
* Fix insert text operation duration (bug 36208)
* Fix browser zoom problem with reported pointer
* Fix bug with position of hyperlink tooltip and slide num tooltip
* Fix slide resize bug
* Fix search in text in placeholder (bug #36133)
* Fix layout in reported mode
* Fix js error in Tables_test.pptx (bug #17147)
* Fix comment reply duplication (bug #35408)
* Fix bug with drag-and-drop chart into title
* Fix changing presentation language if no shape selected (bug #35231)
* Fix columns in placeholder (bug #35074)
* Fix connector losing shape after moving shape in group (bug #35317)
* Fix hidden markers for connector on chart and image (bug #35300)
* Fix cell link after copy paste (bug #35362, DocumentServer#122)
* A lot of fixes in translations

#### Plugins
* Fix crash on unknown ole-object resize
* Fix problems with scroll

#### Converion
* Fix colors schemes for table cells (bug #36322)
* Fix problem with image in footnote (bug #36380)
* Fix saving some files to odt (bug #35389)
* Fix custom shape with connectors in xls
* Fix margins in ods
* Fix convert named range with formulas in ods
* Fix audio wav files in pptx
* Fix old standard ole in pptx


## 4.4.1
### New features
#### Document Editor
* Special Paste
* Rich text content support
* Translates for Paragraph Styles
* View mode with comments
* Option to hide solved comments
* Ability to specify custom columns

#### Spreadsheet Editor
* Formulas with conditional formatting
* Ability to specify custom delimiter for CSV import\export
* Added `ACOT`, `ACOTH`, `ARABIC`, `BASE`, `BETA.DIST`, `BETA.INV`, `BETADIST`,
        `BINOM.DIST`, `BINOM.INV`, `CEILING.MATH`, `CEILING.PRECISE`,
        `CHIDIST`, `CHIINV`, `CHISQ.DIST`, `CHISQ.DIST.RT`,
        `CHISQ.INV`, `CHISQ.INV.RT`, `COMBINA`, `CONCAT`, `CONFIDENCE.NORM`,
        `CONFIDENCE.T`, `COT`, `COTH`, `CSC`, `CSCH`, `DECIMAL`, `EXPON.DIST`, `F.DIST`,
        `F.DIST.RT`, `F.INV`, `F.INV.RT`, `FDIST`, `FINV`, `FLOOR.MATH`,
        `FLOOR.PRECISE`, `GAMMA`, `GAMMA.DIST`, `GAMMA.INV`, `GAMMA.PRECISE`,
        `GAMMADIST`, `GAMMAINV`, `GAUSS`, `IFNA`, `IMCOSH`, `IMCOT`, `IMCSC`,
        `IMCSCH`, `IMSEC`, `IMSECH`, `IMSINH `, `IMTAN`, `ISO.CEILING`,
        `LOGNORM.DIST`, `LOGNORM.INV`, `NUMBERVALUE`, `PERCENTILE.EXC`, `PERCENTILE.INC`,
        `PERCENTRANK.EXC`, `PERCENTRANK.INC`, `RANK`, `RANK.AVG`, `RANK.EQ`, `SEC`, `SECH`,
        `T.DIST`, `T.DIST.2T`, `T.DIST.RT`, `T.INV`, `T.INV.2T`, `TDIST`, `TINV`, `XOR` functions
* Exclude hidden rows from copy, autofill, formatting etc...
* Update active cell color        
* Frozen pane now with shadow        
* Translates for cell styles        
* Search and replace by select
* Option to hide solved comments
* Abitity to specify bullets and numbering for text in shape.
* Ability to specify columns for Text Areas
* Ability to add the connectors for the shapes
* Support `Shift+Delete`, `Ctrl+Insert` and `Shift+Insert` for cut/paste

#### Presentation Editor
* Ability to connect shapes via lines
* Ability to specify columns for Text Areas
* Ability to create bullet and number lists in the shapes
* Spellcheker
* Ability to download presentation as ODP

#### Plugins
* New type for plugin window (without borders, shadows, buttons)

#### Convertion
* Speedup for opening ooxml: windows 200%, linux 20%
* Better converting from/to RTF
* Better support of password protected ooxml, binary ms
* Support of password protected ppt

### Fixes
#### Spreadsheet Editor
* Fix duplicate text after carriage return [DocumentServer#109](https://github.com/ONLYOFFICE/DocumentServer/issues/109)


## 4.3.2
### New Features
#### Editors
* Full support of high-dpi monitors
* Ability to set alternative text for shapes

#### Document Editor
* Undo in Fast co-edit
* Do not hide `All changes saved` in bottom toolbar
* Adding and editing Footnotes
* New languages for spellchecker (43 in total)

#### Spreadsheet Editor
* Support `AVERAGEIFS`, `COUNTIFS`, `SUMIFS` formulas
* Formulas refactoring and improvements
* Totally new Cell Format window with more options
* Sort options window while sorting ranges
* Added direction of sort on filter buttons
* Added filter condition at statistical information
* Added special paste feature 
* Added support of surface chart
* New cell borders styles (11 in total)

#### Presentation Editor
* Undo in Fast co-edit

#### Convertion
* Optimization and speed-up
* Better support of all formats, including (but not limited to):

##### DOC
* Background page

##### XLS
* Data validation
* Decryptor

##### ODF
* Global settings for documents
* SVG refactor
* Background page (image, pattern, gradient)
* Convert smart art
* Sheet/Workbook views
* Support convert OLE objects (and other embedded)

##### RTF
* Generate replacement text hyperlink if absent
* Office digital signatures
* Extended drawings
* Custom shapes
* Text in drawing shapes

### Fixes
#### Document Editor
* Fixed an issue with drag-n-drop a table inside a footnote (bug #33548)
* Fixed an issue with crop of shape group (bug #33110)

#### Spreadsheet Editor
* Fixed an issue with absolute reference when inserting a new row (ONLYOFFICE/DocumentServer#41)
* Fixed an issue with onDocumentStateChange event (ONLYOFFICE/DocumentServer#88)
* Fixed an issue with formulas translation (ONLYOFFICE/DesktopEditors#23)
* Fixed an issue with password-protected xlsx (ONLYOFFICE/DesktopEditors#24)
* Fixed an issue with non-breaking space (ONLYOFFICE/DesktopEditors#26)
* Fixed an issue with AVERAGEA formula with text format
* Fixed an issue with broken workbook after list copy (bug #33588) 
* Fixed an issue with formula recalculation by F4 hotkey (bug #32901)
* Fixed an issue with SUMIFS formula (bug #33602)
* Fixed an issue with inserting image size (bug #33604)
* Fixed an issue with zero values sparklines (bug #33612)
* Fixed an issue with changing number format while changing regional format (bug #31395)
* Fixed an issue with replacing formula delimiters (bug #33608)
* Fixed an issue with cell size while drag'n'drop (bug #33607)
* Fixed an issue with cursor size in @2x (bug #33606)
* Fix broken files if changing style of unsupported charts (bug #34650)
* Fix stack error while copying a big array of formula data
* Fix rendering 3d diagram in small area (bug #34632)
* Fix change chart's range while applying preset


## 4.2.2
### Fixes
#### All Editors
* Do not perform save if there is no changes to save
* Fix a rare problem with saving file with specific type of Chart
* Fix problems with copy-paste

#### Document Editor
* Fix problem with losing changes while several users enter text at same time (bug #33726)
* Fix bug with positioning of cursor after function InsertContent.

#### Spreadsheet Editor
* Fix wrong order of elements in equations (bug #34029)
* Fix entering symbols with diacritical sign (bug #33908)
* Fix horizontal scroll by trackpad (bug #27197)
* Fix assembling files with Ranges in rare cases
* Fix convert xlsx to csv
* Fix `Match` formula return value in some cases (bug #33735)

#### Presentation Editor
* Fix a problem with saving file with notes, copied from Document Editor
* Fix a problem with saving file with chart, copied from Presentation Editor


## 4.2.1
### New Features
#### All Editors
* Ability to set dash type for shapes
* Better support of HiDPI systems

#### Document Editor
* Ability to open and edit Footnotes
* Ability to insert number of pages in document
* Redone Version History. Ability to hide minor features.

#### Spreadsheet Editor
* Add ability to insert Equations in Spreadsheet Editor
* Ability to open and edit Sparklines
* Add new formula `SUMIFS`
* Ability to select data from drop-down menu in context menu
* Add multiselect support
* Add rotation of 3D Charts
* Update and improve visual styles for all chart types
* Bring back `Freeze Panes` in `View Settings` menu
* New algorithm for calculating cell height

#### Presentation Editor
* Add ability to insert Equations in Presentation Editor

### Fixes
#### Document Editor
* Fix broken `Insert number of page` button
* Fix problem with duplicate of last hieroglyph
* Fix problem with changing chart type from 2D to 3D

#### Spreadsheet Editor
* Fix problem with empty cell while changing sparklines

#### x2t
* Improve compatibility with `doc` format
