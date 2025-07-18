## 0.2.0 (2025-07-09)

### 🚀 Features

- add GitHub Actions workflow for building and releasing assets ([e5ec4a3](https://github.com/windbase/windbase/commit/e5ec4a3))
- add VERSION constant from package.json to Vite config and declare in globals.d.ts ([59ebe41](https://github.com/windbase/windbase/commit/59ebe41))
- implement ToolbarMenu component with dropdown functionality for project management ([fbef377](https://github.com/windbase/windbase/commit/fbef377))

### ❤️ Thank You

- mxvsh @mxvsh

## 0.1.0 (2025-07-09)

### 🚀 Features

- init project with layout ([d531d02](https://github.com/windbase/windbase/commit/d531d02))
- update Tailwind configuration and layout metadata; fix SVG title and gradient colors ([6bf4fb9](https://github.com/windbase/windbase/commit/6bf4fb9))
- add new dependencies and refactor layout structure ([99e8c6e](https://github.com/windbase/windbase/commit/99e8c6e))
- add DarkModeButton, DefaultSidebar, and LivePreviewToolbar components ([5e656ee](https://github.com/windbase/windbase/commit/5e656ee))
- implement ElementPicker component and supporting elements and types for enhanced UI element selection ([51b40c6](https://github.com/windbase/windbase/commit/51b40c6))
- enhance builder state management with sidebar view and new element manipulation actions ([9093511](https://github.com/windbase/windbase/commit/9093511))
- add ElementLayers component for displaying elements and integrate popover for component addition in LivePreviewToolbar ([3be7488](https://github.com/windbase/windbase/commit/3be7488))
- implement recursive element manipulation functions for builder state management, including add, update, delete, and move actions ([b592754](https://github.com/windbase/windbase/commit/b592754))
- enhance ElementLayers component with tree structure for elements, drag-and-drop functionality, and improved selection handling ([52e88b0](https://github.com/windbase/windbase/commit/52e88b0))
- add hover functionality to elements in ElementLayers component for improved user interaction ([44f9b6c](https://github.com/windbase/windbase/commit/44f9b6c))
- implement live preview functionality with dynamic HTML generation and element interaction handling in LivePreview component ([943f35e](https://github.com/windbase/windbase/commit/943f35e))
- update builder state management to use BuilderElement references for selected and hovered elements, enhancing element interaction and state consistency ([6e2309f](https://github.com/windbase/windbase/commit/6e2309f))
- update button and text elements to be content editable and modify button styles for improved UI consistency ([bff0c9a](https://github.com/windbase/windbase/commit/bff0c9a))
- enhance LivePreview component with improved iframe initialization, dynamic element synchronization, and content update handling for better user interaction ([f35bf8d](https://github.com/windbase/windbase/commit/f35bf8d))
- add ElementProperties component for managing element classes and content, and integrate it into VisualBuilder for enhanced element editing capabilities ([1ed338a](https://github.com/windbase/windbase/commit/1ed338a))
- add getParentIds function to BuilderActions for retrieving all parent IDs of a given element, enhancing element hierarchy management ([4955912](https://github.com/windbase/windbase/commit/4955912))
- expand parent layers in ElementLayers component when an element is selected, improving user navigation and hierarchy visibility ([912739c](https://github.com/windbase/windbase/commit/912739c))
- add delete functionality to elements in ElementLayers component, allowing users to remove elements directly from the layer view ([209b912](https://github.com/windbase/windbase/commit/209b912))
- add inputAttributes to BuilderElement for enhanced input customization options, including placeholder and type selection ([f3e55d7](https://github.com/windbase/windbase/commit/f3e55d7))
- enhance ElementProperties component with dynamic attribute inputs and conditional content editing, improving user interaction and customization options ([6da32e1](https://github.com/windbase/windbase/commit/6da32e1))
- add live preview toolbar ID and update click event handling in VisualBuilder to prevent selection when clicking on the toolbar ([79edfb6](https://github.com/windbase/windbase/commit/79edfb6))
- update ElementPicker to handle element addition based on selected element context, enhancing user interaction and hierarchy management ([b8563a8](https://github.com/windbase/windbase/commit/b8563a8))
- refactor ElementProperties component to use memoization and callbacks for improved performance and maintainability, and enhance class management functionality ([f24c805](https://github.com/windbase/windbase/commit/f24c805))
- implement responsive mode functionality in LivePreviewArea and Toolbar components, allowing dynamic layout adjustments based on user selection ([68a2c05](https://github.com/windbase/windbase/commit/68a2c05))
- implement HTML to BuilderElement transformation and add basic authentication template for enhanced user interface flexibility ([bf73996](https://github.com/windbase/windbase/commit/bf73996))
- add template selection functionality to DefaultSidebar for improved user experience in template management ([d7d5cc7](https://github.com/windbase/windbase/commit/d7d5cc7))
- update renderElement and updateElementAttributes functions to support dynamic attributes and SVG handling for improved element rendering ([478dd4e](https://github.com/windbase/windbase/commit/478dd4e))
- add support for ordered lists in elements configuration to enhance list rendering capabilities ([066f2bc](https://github.com/windbase/windbase/commit/066f2bc))
- introduce CoreElement and EditorElement types along with transformation utilities for improved data handling and export functionality ([c9b7d54](https://github.com/windbase/windbase/commit/c9b7d54))
- update LivePreview styling and expand element definitions to include additional heading and text elements for improved content editing capabilities ([5a56fef](https://github.com/windbase/windbase/commit/5a56fef))
- add template definition and function for creating templates ([0cf1b96](https://github.com/windbase/windbase/commit/0cf1b96))
- add ImportButton component for importing HTML code into the builder ([dc0a95b](https://github.com/windbase/windbase/commit/dc0a95b))
- add windbase.svg graphic ([fdaa3b4](https://github.com/windbase/windbase/commit/fdaa3b4))
- implement ExportButton component for exporting elements as HTML ([6347a13](https://github.com/windbase/windbase/commit/6347a13))
- add keyboard shortcuts for undo and redo functionality in the visual builder ([b388350](https://github.com/windbase/windbase/commit/b388350))
- add command palette UI component for element picker ([c33e514](https://github.com/windbase/windbase/commit/c33e514))
- add HTML to Builder Elements transformation utilities ([6aadb7a](https://github.com/windbase/windbase/commit/6aadb7a))
- implement CodeEditor component and update ImportButton to use it for improved code editing experience ([#19](https://github.com/windbase/windbase/pull/19))
- add ColorPanel component for managing color properties, shadows, and text decorations with responsive breakpoints ([fa302eb](https://github.com/windbase/windbase/commit/fa302eb))
- add persistence to builder store using zustand middleware ([#21](https://github.com/windbase/windbase/pull/21))
- add WebAnalytics component ([6109afe](https://github.com/windbase/windbase/commit/6109afe))
- **builder:** update element deletion logic to select parent element when deleting selected element ([5a2fd67](https://github.com/windbase/windbase/commit/5a2fd67))
- **toolbar:** add undo/redo buttons with keyboard shortcuts and update tooltip text ([ff668fd](https://github.com/windbase/windbase/commit/ff668fd))
- **toolbar:** add functionality to preview HTML content in a new window ([#8](https://github.com/windbase/windbase/pull/8))
- **ui:** add editable class elements functionality ([#3](https://github.com/windbase/windbase/pull/3))

### 🩹 Fixes

- rename foreground color key to primary-foreground in Tailwind configuration ([1bf76dd](https://github.com/windbase/windbase/commit/1bf76dd))
- adjust padding and margin in ElementProperties component for improved layout consistency ([39b8eb5](https://github.com/windbase/windbase/commit/39b8eb5))
- improve layout responsiveness in VisualBuilder and ElementLayers components by adding overflow handling and sticky header for better user experience ([a1b1137](https://github.com/windbase/windbase/commit/a1b1137))
- enhance style handling in renderElement function to ensure proper concatenation and exclusion of inline styles from attributes for improved element rendering ([ad60dcd](https://github.com/windbase/windbase/commit/ad60dcd))
- expand element definitions to include label and definition list elements for enhanced content editing capabilities ([0401300](https://github.com/windbase/windbase/commit/0401300))
- update sidebar view to 'layers' after adding an element in ElementPicker for improved user experience ([41a1e49](https://github.com/windbase/windbase/commit/41a1e49))
- adjust element addition logic in ElementPicker to handle 'div' and other tags appropriately for improved functionality ([d375674](https://github.com/windbase/windbase/commit/d375674))
- adjust PopoverContent width and button text size in ElementPicker for better layout and usability ([5a54aa6](https://github.com/windbase/windbase/commit/5a54aa6))
- adjust ElementPicker component layout and button styles for improved usability ([f04b958](https://github.com/windbase/windbase/commit/f04b958))
- update import path for ElementCategory in editor-element type definition ([0830dd7](https://github.com/windbase/windbase/commit/0830dd7))
- selectedElement state sync in updateElement ([3f8b3a1](https://github.com/windbase/windbase/commit/3f8b3a1))
- update CodeEditor to use Dracula theme ([ab24a89](https://github.com/windbase/windbase/commit/ab24a89))
- replace fragment with div in ElementPicker for consistent DOM structure ([d9964d9](https://github.com/windbase/windbase/commit/d9964d9))
- **dialog:** remove unused zoom and slide animations for improved performance ([e2bc0c0](https://github.com/windbase/windbase/commit/e2bc0c0))
- **engine:** improve deleteElement logic to maintain selected element's parent ([c3bcbbe](https://github.com/windbase/windbase/commit/c3bcbbe))
- **styles:** update border-radius variable for improved UI consistency ([09c007c](https://github.com/windbase/windbase/commit/09c007c))
- **template:** integrate exportToFullHtml for HTML export functionality ([dbde105](https://github.com/windbase/windbase/commit/dbde105))
- **toolbar:** update tooltip text for undo and redo buttons to remove keyboard shortcuts ([f43b7a9](https://github.com/windbase/windbase/commit/f43b7a9))

### ❤️ Thank You

- Ansari Hassan @vectorCodes
- Monawwar Abdullah @mxvsh
- mxvsh @mxvsh
- Spandan Kumar @spandan-kumar