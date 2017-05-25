A prototype of a MySQL editor with syntax highlighting, autocomplete, and a sortable, searchable table with file exports; powered by [CodeMirror](https://codemirror.net/) and [DataTables](https://datatables.net/).


There are tags with a CodeMirror only editor version, and a CodeMirror and DataTables combo version with CSV, clipboard, and Excel exports.

* CodeMirror: https://github.com/chancyk/mysql_editor/tree/editor-only
* CodeMirror & DataTable: https://github.com/chancyk/mysql_editor/tree/editor-datatable


The DataTable version is setup with a mock `fake_post` function that can be replaced with the jQuery's `$.post`, and pointed at a server-side route, which upon response will dynamically create the DataTable.
