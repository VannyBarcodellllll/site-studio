# Site Studio

A visual website builder based on the About Me editor. The original About Me project remains separate.

Create multiple websites using personal, business, creative, or blank templates. Edit text directly, add and reorder sections, move objects, replace images, change fonts and colors, and preview desktop and mobile layouts.

Projects save automatically in this browser. Use the project library to reopen, rename, or duplicate them. Changes to one website do not affect another. A separate About Me copy is included as a starting project.

Export a standalone `index.html` file for hosting. The exported website contains your current design without the editor or project library. Download an editable JSON backup from the Save panel if you want to restore the project on another device or browser. Existing About Me builder backups can also be restored.

Open `index.html` directly, or run `npm start` with Node.js 20 or later and visit http://127.0.0.1:4177. No dependencies are required. This app edits websites created inside its builder; it does not import arbitrary HTML websites. Fonts load from Google Fonts when available, with system fallbacks.

Browser storage can be cleared or reach its quota, especially with large photos. Keep downloadable backups for work you want to preserve. Website exports are static pages; contact buttons can link to email or other pages, but no backend services are generated.
