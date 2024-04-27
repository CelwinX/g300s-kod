// Place your settings in the file "Packages/User/Preferences.sublime-settings",
// which overrides the settings in here.
//
// Settings may also be placed in syntax-specific setting files, for
// example, in Packages/User/Python.sublime-settings for python files.
{
	// Sets the colors used within the text area.
	// The value "auto" will switch between the "light_color_scheme" and
	// "dark_color_scheme" based on the operating system appearance.
	"color_scheme": "Mariana.sublime-color-scheme",

	// Controls the "color_scheme" when set to "auto"
	"light_color_scheme": "Breakers.sublime-color-scheme",
	"dark_color_scheme": "Mariana.sublime-color-scheme",

	// Note that the font_face and font_size are overridden in the platform
	// specific settings file, for example, "Preferences (Linux).sublime-settings".
	// Because of this, setting them here will have no effect: you must set them
	// in your User File Preferences.
	"font_face": "",
	"font_size": 10,

	// Valid options on all platforms are:
	//  - "no_bold": Disables bold text
	//  - "no_italic": Disables italic text
	// Antialiasing options:
	//  - "no_antialias": Disables antialiasing
	//  - "gray_antialias": Uses grayscale antialiasing instead of subpixel
	// Ligature options:
	//  - "no_liga": Disables standard ligatures (OpenType liga feature)
	//  - "no_clig": Disables contextual ligatures (OpenType clig feature)
	//  - "no_calt": Disables contextual alternatives (OpenType calt feature)
	//  - "dlig": Enables discretionary ligatures (OpenType dlig feature)
	//  - "ss01": Enables OpenType stylistic set 1. Can enable sets 1 to 10
	//        by changing the last two digits.
	// Windows-only options:
	//  - "directwrite": (default) Use DirectWrite for font rendering
	//  - "gdi": Use GDI for font rendering
	//  - "dwrite_cleartype_classic": Only applicable to "directwrite" mode,
	//        should render fonts similar to traditional GDI
	//  - "dwrite_cleartype_natural": Only applicable to "directwrite" mode,
	//        should render fonts similar to ClearType "natural quality" GDI
	//  - "subpixel_antialias": Force ClearType antialiasing when disabled
	//        at system level
	// Mac-only options:
	//  - "no_round": Don't round glyph widths for monospace fonts when
	//        "font_size" is small.
	"font_options": [],
	// Font options for theme text. Valid options are the same as
	// "font_options", except "no_bold" and "no_italic" are not supported
	"theme_font_options": [],

	// Characters that are considered to separate words
	"word_separators": "./\\()\"'-:,.;<>~!@#$%^&*|+=[]{}`~?",

	// Set to false to prevent line numbers being drawn in the gutter
	"line_numbers": true,

	// Set to false to hide the gutter altogether
	"gutter": true,

	// Spacing between the gutter and the text
	"margin": 4,

	// Fold buttons are the triangles shown in the gutter to fold regions of text
	"fold_buttons": true,

	// Hides the fold buttons unless the mouse is over the gutter
	"fade_fold_buttons": true,

	// Indicate modified lines in the gutter
	// - true: Enables modified line indicators on all files
	// - "auto": Enables modified line indicators on tracked files within Git
	// - false: Disables modified line indicators
	"mini_diff": true,

	// Columns in which to display vertical rulers
	"rulers": [],

	// Set to true to turn spell checking on by default
	"spell_check": false,

	// The number of spaces a tab is considered equal to
	"tab_size": 4,

	// Set to true to insert spaces when tab is pressed
	"translate_tabs_to_spaces": false,

	// If translate_tabs_to_spaces is true, use_tab_stops will make tab and
	// backspace and delete insert/delete up to the next tabstop
	"use_tab_stops": true,

	// Set to false to disable detection of tabs vs. spaces on load
	"detect_indentation": true,

	// Calculates indentation automatically when pressing enter
	"auto_indent": true,

	// Makes auto indent a little smarter, e.g., by indenting the next line
	// after an if statement in C. Requires auto_indent to be enabled.
	"smart_indent": true,

	// Adds whitespace up to the first open bracket when indenting. Requires
	// auto_indent to be enabled.
	"indent_to_bracket": false,

	// Trims white space added by auto_indent when moving the caret off the
	// line.
	"trim_automatic_white_space": true,

	// Disables horizontal scrolling if enabled.
	// May be set to true, false, or "auto", where it will be disabled for
	// source code, and otherwise enabled.
	"word_wrap": "auto",

	// Set to a value other than 0 to force wrapping at that column rather than
	// the window width. See "wrap_width_style" for extra options.
	"wrap_width": 0,

	// Controls how the "wrap_width" setting is applied. The following options
	// are available:
	// - "constant": Always wrap at exactly the wrap width.
	// - "min": Wrap at the wrap width or less if there is less space available.
	"wrap_width_style": "constant",

	// Set to false to prevent word wrapped lines from being indented to the same
	// level
	"indent_subsequent_lines": true,

	// Draws text centered in the window rather than left aligned
	"draw_centered": false,

	// Controls auto pairing of quotes, brackets etc
	"auto_match_enabled": true,

	// Automatically close HTML and XML tags when </ is entered.
	"auto_close_tags": true,

	// Word list to use for spell checking. May also be a list of dictionaries.
	"dictionary": "Packages/Language - English/en_US.dic",

	// Sets which scopes are checked for spelling errors
	"spelling_selector": "markup.raw, source string.quoted - punctuation - meta.preprocessor.include, source comment - source comment.block.preprocessor, -(source, constant, keyword, storage, support, variable, markup.underline.link, meta.tag)",

	// Set to true to draw a border around the visible rectangle on the minimap.
	// The color of the border will be determined by the "minimap_border" key
	// in the color scheme
	"draw_minimap_border": false,

	// Always visualise the viewport on the minimap, as opposed to only
	// showing it on mouse over
	"always_show_minimap_viewport": false,

	// If enabled, will highlight any line with a caret
	"highlight_line": false,

	// If enabled, will highlight the gutter for any line with a caret
	"highlight_gutter": true,

	// If enabled, will highlight the line number in the gutter for any line
	// with a caret depending on the color scheme
	"highlight_line_number": true,

	// Valid values are "smooth", "phase", "blink" and "solid". Previous
	// versions of Sublime Text used "smooth" by default.
	"caret_style": "solid",

	// These settings control the size of the caret
	"caret_extra_top": 4,
	"caret_extra_bottom": 4,
	"caret_extra_width": 1,

	// When enabled, the caret will be drawn as a rectangle, using the width
	// of the current character
	"block_caret": false,

	// Set to false to disable underlining the brackets surrounding the caret
	"match_brackets": true,

	// Set to false if you'd rather only highlight the brackets when the caret is
	// next to one
	"match_brackets_content": true,

	// Set to false to not highlight square brackets. This only takes effect if
	// match_brackets is true
	"match_brackets_square": true,

	// Set to false to not highlight curly brackets. This only takes effect if
	// match_brackets is true
	"match_brackets_braces": true,

	// Set to false to not highlight angle brackets. This only takes effect if
	// match_brackets is true
	"match_brackets_angle": false,

	// Enable visualization of the matching tag in HTML and XML
	"match_tags": true,

	// Highlights other occurrences of the currently selected text
	"match_selection": true,

	// Additional spacing at the top of each line, in pixels
	"line_padding_top": 0,

	// Additional spacing at the bottom of each line, in pixels
	"line_padding_bottom": 0,

	// Set to false to disable scrolling past the end of the buffer.
	// On Mac, this value is overridden in the platform specific settings, so
	// you'll need to place this line in your user settings to override it.
	//
	// This setting may also be set to a number between 0.0 and 1.0 to specify
	// how much scrolling past the end of the buffer should be allowed. 0.5
	// scrolls halfway and 0.0 is the same as false.
	"scroll_past_end": true,

	// Set the number of context lines to show when scrolling to reveal. This
	// affects all selection changes, like selection dragging, page-up/page-down
	// and moving the caret.
	"scroll_context_lines": 0,

	// This controls what happens when pressing up or down when on the first
	// or last line.
	// On Mac, this value is overridden in the platform specific settings, so
	// you'll need to place this line in your user settings to override it.
	"move_to_limit_on_up_down": false,

	// Controls when white space is drawn. Any of the following options may be
	// combined:
	// - "selection": Draw white space under the current selection.
	// - "leading": Draw any white space between the beginning of a line and the
	//              first character.
	// - "enclosed": Draw white space enclosed by other characters.
	// - "trailing": Draw white space following the last character on a line.
	// - "isolated": Draw white space on lines containing no other characters.
	// - "all": All of the above, ie. always draw white space.
	//
	// These options may be further refined by appending any of the following
	// separated by an underscore:
	// - "none": Don't draw this kind of white space.
	// - "tabs": Only draw tabs here.
	// - "spaces": Only draw spaces here.
	// - "mixed": Only draw white space that does not match the indentation
	//            style. For example if "translate_tabs_to_spaces" is true only
	//            draw tabs.
	// - "mixed_tabs": Like "mixed" but only draw tabs.
	// - "mixed_spaces": Like "mixed" but only draw spaces.
	// - "all": Draw both tabs and spaces. This is the default.
	//
	// Note that options are applied in sequence. So a later option may override
	// an earlier one.
	//
	// Examples:
	// - ["selection", "trailing", "isolated"]:
	//     Draw white space at the end of any lines and under the selection.
	//
	// - ["all_tabs", "selection"]:
	//     Draw tabs anywhere and any white space under the selection.
	//
	// - ["all_mixed"]:
	//     Draw any white space that does not match the indentation style.
	//
	// - ["leading_mixed", "isolated_mixed"]:
	//     Draw any indentation that does not match the indentation style.
	//
	// - ["selection_mixed_tabs"]:
	//     Draw only tabs under the selection and only if the indentation style
	//     is spaces.
	//
	// - ["all_tabs", "selection"]:
	//     Draw all tabs and any white space under the selection.
	//
	// - ["all", "selection_none"]:
	//     Inverse of the default. Draw white space everywhere except under the
	//     selection.
	"draw_white_space": ["selection"],

	// Controls how non-ascii white space is drawn.
	// - "none": Draw unicode white space verbatim, eg. hiding zero-width
	//           spaces.
	// - "punctuation": Draw codepoints of unicode white space defined as
	//                  punctuation. This includes NBSP, but excludes the CJK
	//                  Ideographic Space.
	// - "all": Draw codepoints of all non-ascii space characters.
	"draw_unicode_white_space": "punctuation",

	// Controls whether unicode bidi characters are drawn as codepoints.
	"draw_unicode_bidi": true,

	// Control characters (or white space if enabled) can be drawn as either hex
	// or using their abbreviation:
	// - "hex": Draw characters using their hex encoding, ie. <0xA0>
	// - "names": Draw characters using their abbreviation, ie. <NBSP>
	"control_character_style": "hex",

	// Controls what type of columns selection description ("Line X, Column Y"
	// in the status bar) uses:
	// - "virtual": Count virtual columns. Tabs count as their width in spaces.
	// - "real": Count real columns. Tabs count as one column.
	"selection_description_column_type": "virtual",

	// Set to false to turn off the indentation guides.
	// The color and width of the indent guides may be customized by editing
	// the corresponding .tmTheme file, and specifying the colors "guide",
	// "activeGuide" and "stackGuide"
	"draw_indent_guides": true,

	// Controls how the indent guides are drawn. Options may be combined, with
	// valid options being:
	//  - "draw_normal" - will draw plain indent guides for every indentation
	//    group
	//  - "draw_active" - will draw indent guides for the group
	//    containing the caret in a different color
	//  - "draw_active_single" - will draw the right-most indent guide in the
	//    group containing the caret in a different color
	//  - "solid" - can be combined with any of the draw_* options to draw
	//    solid instead of stippled lines
	"indent_guide_options": ["draw_normal"],

	// Controls where trailing white space is removed on save.
	// - "none": Do not remove any trailing white space on save.
	// - "all": Remove all trailing white space on save.
	// - "not_on_caret": Only remove white space that won't affect the caret.
	//                   When used in conjunction with "save_on_focus_lost" and
	//                   certain desktop environments that frequently make the
	//                   application lose focus this avoids the caret jumping
	//                   around a lot.
	"trim_trailing_white_space_on_save": "none",

	// Only trim white space on save for the parts of a file that have been
	// modified by you. If there is trailing white space in other parts of the
	// file they are left alone.
	"trim_only_modified_white_space": true,

	// Set to true to ensure the last line of the file ends in a newline
	// character when saving
	"ensure_newline_at_eof_on_save": false,

	// Set to true to automatically save files when switching to a different file
	// or application
	"save_on_focus_lost": false,

	// The encoding to use when the encoding can't be determined automatically.
	// ASCII, UTF-8 and UTF-16 encodings will be automatically detected.
	"fallback_encoding": "Western (Windows 1252)",

	// Encoding used when saving new files, and files opened with an undefined
	// encoding (e.g., plain ascii files). If a file is opened with a specific
	// encoding (either detected or given explicitly), this setting will be
	// ignored, and the file will be saved with the encoding it was opened
	// with.
	"default_encoding": "UTF-8",

	// Files containing null bytes are opened as hexadecimal by default
	"enable_hexadecimal_encoding": true,

	// Determines what character(s) are used to terminate each line in new files.
	// Valid values are 'system' (whatever the OS uses), 'windows' (CRLF) and
	// 'unix' (LF only).
	"default_line_ending": "system",

	// When enabled, hovering over a word will show a popup listing all
	// possible locations for the definition symbol. Requires index_files.
	"show_definitions": true,

	// When enabled, pressing tab will insert the best matching completion.
	// When disabled, tab will only trigger snippets or insert a tab.
	// Shift+tab can be used to insert an explicit tab when tab_completion is
	// enabled.
	"tab_completion": true,

	// Enable auto complete to be triggered automatically when typing.
	"auto_complete": true,

	// The maximum file size where auto complete will be automatically triggered.
	"auto_complete_size_limit": 4194304,

	// The delay, in ms, before the auto complete window is shown after typing
	"auto_complete_delay": 50,

	// Controls what scopes auto complete will be triggered in
	"auto_complete_selector": "meta.tag, source - comment - string.quoted.double.block - string.quoted.single.block - string.unquoted.heredoc",

	// Additional situations to trigger auto complete
	"auto_complete_triggers":
	[
		{"selector": "text.html, text.xml", "characters": "<"},
		{"selector": "punctuation.accessor", "rhs_empty": true},
	],

	// By default, auto complete will commit the current completion on enter.
	// This setting can be used to make it complete on tab instead.
	// Completing on tab is generally a superior option, as it removes
	// ambiguity between committing the completion and inserting a newline.
	"auto_complete_commit_on_tab": false,

	// Controls if auto complete is shown when snippet fields are active.
	// Only relevant if auto_complete_commit_on_tab is true.
	"auto_complete_with_fields": false,

	// Controls what happens when pressing the up key while the first item in
	// the auto complete window is selected: if false, the window is hidden,
	// otherwise the last item in the window is selected. Likewise for the
	// down key when the last item is selected.
	"auto_complete_cycle": false,

	// Auto complete will used indexed data to provide completions from other
	// files when this is enabled
	"auto_complete_use_index": true,

	// If previously-selected completions should be automatically selected
	"auto_complete_use_history": false,

	// Controls how the auto complete results are reordered when typing:
	// - "none" will fully reorder the results according to how well the
	//   completion matches the typed text.
	// - "some" will partially reorder the results, taking into account how
	//   well the completion matches whats typed, and likelihood of the
	//   completion.
	// - "strict" will never reorder the results.
	"auto_complete_preserve_order": "some",

	// Add trailing symbols (e.g., '.', '()') if the auto complete engine
	// thinks they're likely enough
	"auto_complete_trailing_symbols": false,

	// Add a space after completions if the auto complete engine thinks
	// they're likely enough
	"auto_complete_trailing_spaces": true,

	// Snippets will not be included in the auto complete when this is
	// false. They can still be triggered by typing their tab trigger in, and
	// pressing tab when auto complete is not showing.
	"auto_complete_include_snippets": true,

	// When this is set to false, snippets won't be present in the auto
	// complete dialog when typing, instead they'll only be shown in the auto
	// complete dialog when it's explicitly triggered
	"auto_complete_include_snippets_when_typing": true,

	// Syntax will not be detected for files larger than this size. This makes
	// loading large files significantly faster. Set to 0 to always perform
	// syntax detection. The default is 16MiB.
	"syntax_detection_size_limit": 16777216,

	// A list of wildcard patterns specifying which snippet files to ignore.
	// For example, to ignore all the default C++ snippets, set this to
	// ["C++/*"]
	"ignored_snippets": [],

	// These settings hide various parts of the UI automatically when typing.
	// Moving the mouse will show them again.
	"auto_hide_menu": false,
	"auto_hide_tabs": false,
	"auto_hide_status_bar": false,

	// Related to auto_hide_tabs, if this is enabled, tabs will be momentarily
	// displayed when switching files. Tabs will automatically hidden upon
	// resuming typing or after a fixed amount of time.
	"reveal_tabs_with_timeout": false,

	// When false, disables alt-tapping revealing the menu when hidden on Linux
	// and Windows. Does not affect auto hiding or toggling the menu through
	// the command palette.
	"reveal_menu": true,

	// If true, when typing the mouse pointer/cursor will be hidden. Moving the
	// pointer will unhide it. This setting has no effect on macOS.
	"hide_pointer_while_typing": true,

	// By default, shift+tab will only unindent if the selection spans
	// multiple lines. When pressing shift+tab at other times, it'll insert a
	// tab character - this allows tabs to be inserted when tab_completion is
	// enabled. Set this to true to make shift+tab always unindent, instead of
	// inserting tabs.
	"shift_tab_unindent": false,

	// If true, the copy and cut commands will operate on the current line
	// when the selection is empty, rather than doing nothing.
	"copy_with_empty_selection": true,

	// If true, the selected text will be copied into the find panel when it's
	// shown.
	// On Mac, this value is overridden in the platform specific settings.
	"find_selected_text": true,

	// When auto_find_in_selection is enabled, the "Find in Selection" flag will
	// be enabled automatically when multiple lines of text are selected.
	// "find_only" or "replace_only" may also be used to only enable this
	// behavior for the find or replace panel respectively.
	"auto_find_in_selection": false,

	// This determines whether the find panel is closed when the "Find All"
	// or "Replace All" buttons are pressed. Note this does not change the
	// keybinding behavior.
	"close_find_after_find_all": true,
	"close_find_after_replace_all": true,

	// Whether to highlight find results in the scrollbar
	"highlight_find_results_in_scrollbar": true,

	// The maximum number of find results to show in the scroll bar. If this
	// number is exceeded no results will be shown. Use 0 to remove this limit.
	"find_scroll_highlights_limit": 8192,

	// The maximum file size that the "Highlight matches" option is used for.
	// Highlighting all matches requires searching the whole file while typing
	// the search query which can quickly get slow. Use 0 to remove this limit.
	"find_highlight_matches_max_size": 16777216, // 16MiB

	// Same as "find_highlight_matches_max_size" but used when regex is enabled.
	"find_regex_highlight_matches_max_size": 1048576, // 1MiB

	// The maximum output size for find-in-files. Prevents searches with a large
	// number of results from using too much memory. Use 0 to remove this limit.
	"find_in_files_max_result_size": 16777216, // 16MiB

	// When drag_text is enabled, clicking on selected text will begin a
	// drag-drop operation.
	"drag_text": true,

	// Take focus when a file is dragged and dropped onto Sublime Text. On
	// Windows this value is overidden to true in the platform specific
	// settings.
	"focus_on_file_drop": false,

	//
	// User Interface Settings
	//

	// The theme controls the look of Sublime Text's UI (buttons, tabs, scroll
	// bars, etc)
	// The value "auto" will switch between the "light_theme" and "dark_theme"
	// based on the operating system appearance.
	"theme": "auto",

	// Controls the "theme" when to "auto"
	"light_theme": "Default.sublime-theme",
	"dark_theme": "Default Dark.sublime-theme",

	// Adaptive theme only: controls if a custom or default title bar is used.
	// Note that on Windows, the hamburger menu is used whenever this is
	// enabled and the adaptive theme is in use.
	"themed_title_bar": true,

	// Controls the style of file tabs for the Default, Default Dark, and
	// Adaptive themes.
	// Options: "rounded", "square"
	//   The value "angled" provides the tab style from Sublime Text 3, but is
	//   only compatible with the Default and Adaptive themes, and will not
	//   support new features like inactive pane dimming.
	"file_tab_style": "rounded",

	// If inactive sheets should have their background slightly modified to
	// make input focus more obvious.
	"inactive_sheet_dimming": true,

	// Set to 0 to disable smooth scrolling. Set to a value between 0 and 1 to
	// scroll slower, or set to larger than 1 to scroll faster
	"scroll_speed": 1.0,

	// Controls side bar animation when expanding or collapsing folders
	"tree_animation_enabled": true,

	// Controls animation throughout the application
	"animation_enabled": true,

	// Makes tabs with modified files more visible
	"highlight_modified_tabs": false,

	// Hides the tab close button when false
	"show_tab_close_buttons": true,

	// Determines which side the close button is on
	"show_tab_close_buttons_on_left": false,

	// Show folders in the side bar in bold
	"bold_folder_labels": false,

	// Draw divider lines between sections of the UI when using the Adaptive theme
	"adaptive_dividers": false,

	// Draw shadows under popup windows
	"popup_shadows": true,

	// Mac only. Controls use of macOS tabs in 10.12 and newer. Each native tab
	// contains an entire project, thus allowing multiple projects in a single
	// window. Valid values are "system", "preferred" and "disabled".
	"native_tabs": "system",

	// Valid values are "system", "enabled" and "disabled"
	"overlay_scroll_bars": "system",

	// Allows tabs to scroll left and right, instead of simply shrinking
	"enable_tab_scrolling": true,

	// Hides the buttons for scrolling tabs left/right, requiring use of a
	// trackpad or mouse scroll wheel
	"hide_tab_scrolling_buttons": false,

	// Hides the new tab button
	"hide_new_tab_button": false,

	// Display the toggle sidebar button in the status bar
	"show_sidebar_button": true,

	// Display the git status in the status bar, requires the show_git_status
	// setting to be enabled
	"show_git_status_in_status_bar": true,

	// Display file encoding in the status bar
	"show_encoding": false,

	// Display line endings in the status bar
	"show_line_endings": false,

	// Display indentation in the status bar
	"show_indentation": true,

	// Display syntax in the status bar
	"show_syntax": true,

	// Magnifies the entire user interface. Sublime Text must be restarted for
	// this to take effect. 1.0 is normal scale, 0.0 allows for auto-detection
	// based on text scale with older Linux configurations that don't fully
	// support GTK display scaling.
	"ui_scale": 0.0,

	// Enables hardware accelerated rendering. This moves rendering to your GPU,
	// allowing for faster rendering at higher resolutions. Changing this
	// setting requires an application restart to take effect.
	// - "none": Performs CPU rendering.
	// - "opengl": Uses OpenGL for rendering. Minimum required version is 4.1
	//
	// On Mac, this value is overridden in the platform specific settings.
	"hardware_acceleration": "none",

	//
	// Application Behavior Settings
	//

	// Exiting the application with hot_exit enabled will cause it to close
	// immediately without prompting. Unsaved modifications and open files will
	// be preserved and restored when next starting.
	//
	// Closing a window with an associated project will also close the window
	// without prompting, preserving unsaved changes in the workspace file
	// alongside the project.
	//
	// Hot exit has different modes to choose from:
	// - "always": Always perform a hot exit when the application exits. This
	//             includes when the last window is closed on relevant
	//             platforms.
	// - "only_on_quit": Only perform a hot exit when the application is asked
	//                   to exit, not when the last window is closed. This
	//                   setting is only used on Windows and Linux.
	// - "disabled": Disable hot exit.
	"hot_exit": "always",

	// remember_full_screen will allow Sublime Text to start in full screen
	// mode if it was exited in full screen mode. When set to false, Sublime
	// Text will never start in full screen mode.
	"remember_full_screen": false,

	// remember_workspace makes Sublime Text remember what workspace each window
	// was in last. When set to false the OS left to determine which workspace
	// a window is opened in. This doesn't work with Wayland.
	"remember_workspace": true,

	// remember_layout makes Sublime Text start with the same layout it closed
	// with. Only applies when hot_exit is disabled.
	"remember_layout": false,

	// Mac only. If the user's default shell should be invoked to obtain the
	// user's customized environment variables. May be a boolean, or a string
	// of the path the shell to invoke. Sublime Text must be restarted for this
	// to take effect.
	"shell_environment": true,

	// Whether to reload a file if it has changed on disk.
	"reload_file_on_change": true,

	// Always prompt before reloading a file, even if the file hasn't been
	// modified. If a file has unsaved changes, a prompt will always be shown.
	// Will only show if "reload_file_on_change" is true.
	"always_prompt_for_file_reload": false,

	// When reopening Sublime Text close saved files that have been deleted from
	// the filesystem (Unsaved files will not be closed). If this setting is
	// false no files will be closed, instead they will be restored as empty
	// files.
	//
	// This is useful when working from an unstable networked file system where
	// tabs would be lost if the connection wasn't active.
	"close_deleted_files": true,

	// When files are opened from a file explorer or from the command line, this
	// controls whether a new window is created or not.
	// - "never": Never open a new window unless no window is open.
	// - "always": Always open files in a new window.
	// - "finder_only": (macOS only) Only open files in a new window when
	//                  opening them from finder or dragging onto the dock icon.
	//
	// On Mac, this value is overridden in the platform specific settings.
	"open_files_in_new_window": "never",

	// Mac only: This controls if an empty window is created at startup or not.
	"create_window_at_startup": true,

	// Mac only: Show recent files on the Touch Bar.
	"show_navigation_bar": true,

	// Mac only: Use global find clipboard.
	"use_find_clipboard": true,

	// Set to true to close windows as soon as the last file is closed, unless
	// there's a folder open within the window.
	// On Mac, this value is overridden in the platform specific settings, so
	// you'll need to place this line in your user settings to override it.
	"close_windows_when_empty": false,

	// Show the full path to files in the title bar. On Mac, this value is
	// overridden in the platform specific settings, with a default value of
	// false.
	"show_full_path": true,

	// Show the relative path to files in the title bar. This overrides
	// show_full_path for files that are listed in the side bar, however
	// show_full_path is still used for other files.
	"show_rel_path": false,

	// Show "project - file" or "file - project" in the title bar.
	"show_project_first": false,

	// Shows the Build Results panel when building. If set to false, the Build
	// Results can be shown via the Tools/Build Results menu.
	"show_panel_on_build": true,

	// Shows build errors just under the line on which they occur.
	"show_errors_inline": true,

	// Shows git repository information next to files in sidebar and in
	// the status bar. Sublime Text has to be restarted for this to take
	// effect.
	"show_git_status": true,

	// Enables showing git status for a git repository in the user's home
	// directory. This is disabled by default since it is typically accidental
	// and can cause heavy CPU usage related to file system watches.
	"allow_git_home_dir": false,

	// This setting determines whether tracked Git files should be diffed
	// against the index or HEAD.
	// Valid values are "index" or "head"
	"git_diff_target": "index",

	// The path to the Sublime Merge executable. This should only be set if
	// Sublime Merge is not installed in a standard location, such as when
	// using a portable install. Set to 'null' to hide Sublime Merge
	// integrations.
	"sublime_merge_path": "",

	// Preview file contents when clicking on a file in the side bar. Double
	// clicking or editing the preview will open the file and assign it a tab.
	// - true: Always preview on click, including right click
	// - false: Never preview
	// - "only_left": Only preview on left click, right click will change the
	//                selection but not preview the file.
	"preview_on_click": true,

	// Controls the behavior when clicking on a single file in the sidebar
	// that's already open.
	// - true: If the file is already open in any group it will be selected.
	// - false: Only if the file is open in the focused group will it be
	//          selected, otherwise a new view into the file is opened.
	"select_across_groups": false,

	// Controls the maximum number of lines kept in the console's history. Note
	// a large limit will increase memory usage. Use 0 to remove any limit.
	"console_max_history_lines": 3000,

	// folder_exclude_patterns and file_exclude_patterns control which files
	// are listed in folders on the side bar. These can also be set on a per-
	// project basis.
	"folder_exclude_patterns": [".svn", ".git", ".hg", "CVS", ".Trash", ".Trash-*"],
	"file_exclude_patterns": ["*.pyc", "*.pyo", "*.exe", "*.dll", "*.obj","*.o", "*.a", "*.lib", "*.so", "*.dylib", "*.ncb", "*.sdf", "*.suo", "*.pdb", "*.idb", ".DS_Store", ".directory", "desktop.ini", "*.class", "*.psd", "*.db", "*.sublime-workspace"],
	// These files will still show up in the side bar, but won't be included in
	// Goto Anything or Find in Files
	"binary_file_patterns": ["*.jpg", "*.jpeg", "*.png", "*.gif", "*.ttf", "*.tga", "*.dds", "*.ico", "*.eot", "*.pdf", "*.swf", "*.jar", "*.zip"],

	// File indexing parses all files in the side bar, and builds an index of
	// their symbols. This is required for Goto Definition to work.
	"index_files": true,

	// Set the number threads to use for indexing. A value of 0 will make
	// Sublime Text guess based on the number of cores. Use the index_files
	// setting to disable all workers. This requires a restart to take effect.
	"index_workers": 0,

	// Sets whether the indexer should exclude files ignored by git
	"index_exclude_gitignore": true,

	// Whether unknown file extensions should be checked for indexing or skipped
	// entirely. If a file extension is not being recognised we suggest
	// setting/changing the default syntax for that extension instead of turning
	// this setting off.
	"index_skip_unknown_extensions": true,

	// index_exclude_patterns indicate which files won't be indexed.
	"index_exclude_patterns": ["*.log"],

	// When Vintage, the vi emulation package, is enabled
	// (see ignored_packages, below), this setting controls if files are opened
	// in command mode or insert mode by default
	"vintage_start_in_command_mode": false,

	// Yank commands can place the text in either an internal register, or in
	// the system clipboard.
	"vintage_use_clipboard": false,

	// By default Vintage will interpret all ctrl+<key> key bindings as
	// regular Sublime Text key bindings. Set this to true to make ctrl keys
	// act as they do in vim, instead (e.g., ctrl+f to move forward a page).
	"vintage_ctrl_keys": false,

	// relative_line_numbers will draw each line number as the distance from
	// the current line. Useful in conjunction with Vintage.
	"relative_line_numbers": false,

	// List any packages to ignore here. When removing entries from this list,
	// a restart may be required if the package contains plugins.
	"ignored_packages": ["Vintage"]
}
diff --git a/src/main/java/net/minecraft/server/EntityHuman.java b/src/main/java/net/minecraft/server/EntityHuman.java
index 4f024cf..547421b 100644
--- a/src/main/java/net/minecraft/server/EntityHuman.java
+++ b/src/main/java/net/minecraft/server/EntityHuman.java
@@ -21,6 +21,7 @@ import org.bukkit.event.player.PlayerItemConsumeEvent;
 import org.bukkit.event.player.PlayerVelocityEvent;
 // CraftBukkit end
 import org.spigotmc.ProtocolData; // Spigot - protocol patch
+import org.spigotmc.SpigotConfig;
 
 public abstract class EntityHuman extends EntityLiving implements ICommandListener {
 
@@ -959,7 +960,12 @@ public abstract class EntityHuman extends EntityLiving implements ICommandListen
 
                     if (flag2) {
                         if (i > 0) {
-                            entity.g((double) (-MathHelper.sin(this.yaw * 3.1415927F / 180.0F) * (float) i * 0.5F), 0.1D, (double) (MathHelper.cos(this.yaw * 3.1415927F / 180.0F) * (float) i * 0.5F));
+                            // Kohi start - configurable knockback
+                            entity.g(
+                                    (double) (-MathHelper.sin(this.yaw * 3.1415927F / 180.0F) * (float) i * SpigotConfig.knockbackExtraHorizontal),
+                                    SpigotConfig.knockbackExtraVertical,
+                                    (double) (MathHelper.cos(this.yaw * 3.1415927F / 180.0F) * (float) i * SpigotConfig.knockbackExtraHorizontal));
+                            // Kohi end
                             this.motX *= 0.6D;
                             this.motZ *= 0.6D;
                             this.setSprinting(false);
diff --git a/src/main/java/net/minecraft/server/EntityLiving.java b/src/main/java/net/minecraft/server/EntityLiving.java
index 63d22ad..9acf58d 100644
--- a/src/main/java/net/minecraft/server/EntityLiving.java
+++ b/src/main/java/net/minecraft/server/EntityLiving.java
@@ -18,6 +18,7 @@ import org.bukkit.event.entity.EntityRegainHealthEvent;
 // CraftBukkit end
 
 import org.bukkit.craftbukkit.SpigotTimings; // Spigot
+import org.spigotmc.SpigotConfig;
 
 public abstract class EntityLiving extends Entity {
 
@@ -831,18 +832,21 @@ public abstract class EntityLiving extends Entity {
     public void a(Entity entity, float f, double d0, double d1) {
         if (this.random.nextDouble() >= this.getAttributeInstance(GenericAttributes.c).getValue()) {
             this.al = true;
-            float f1 = MathHelper.sqrt(d0 * d0 + d1 * d1);
-            float f2 = 0.4F;
-
-            this.motX /= 2.0D;
-            this.motY /= 2.0D;
-            this.motZ /= 2.0D;
-            this.motX -= d0 / (double) f1 * (double) f2;
-            this.motY += (double) f2;
-            this.motZ -= d1 / (double) f1 * (double) f2;
-            if (this.motY > 0.4000000059604645D) {
-                this.motY = 0.4000000059604645D;
+            // Kohi start - configurable knockback
+            double magnitude = MathHelper.sqrt(d0 * d0 + d1 * d1);
+
+            this.motX /= SpigotConfig.knockbackFriction;
+            this.motY /= SpigotConfig.knockbackFriction;
+            this.motZ /= SpigotConfig.knockbackFriction;
+
+            this.motX -= d0 / magnitude * SpigotConfig.knockbackHorizontal;
+            this.motY += SpigotConfig.knockbackVertical;
+            this.motZ -= d1 / magnitude * SpigotConfig.knockbackHorizontal;
+
+            if (this.motY > SpigotConfig.knockbackVerticalLimit) {
+                this.motY = SpigotConfig.knockbackVerticalLimit;
             }
+            // Kohi end
         }
     }
     diff --git a/src/main/java/net/minecraft/server/EntityHuman.java b/src/main/java/net/minecraft/server/EntityHuman.java
index 8bb39ec..4f024cf 100644
--- a/src/main/java/net/minecraft/server/EntityHuman.java
+++ b/src/main/java/net/minecraft/server/EntityHuman.java
@@ -18,6 +18,7 @@ import org.bukkit.event.player.PlayerBedEnterEvent;
 import org.bukkit.event.player.PlayerBedLeaveEvent;
 import org.bukkit.event.player.PlayerDropItemEvent;
 import org.bukkit.event.player.PlayerItemConsumeEvent;
+import org.bukkit.event.player.PlayerVelocityEvent;
 // CraftBukkit end
 import org.spigotmc.ProtocolData; // Spigot - protocol patch
 
@@ -947,6 +948,13 @@ public abstract class EntityHuman extends EntityLiving implements ICommandListen
                         // CraftBukkit end
                     }
 
+                    // Kohi start
+                    // Save the victim's velocity before they are potentially knocked back
+                    double victimMotX = entity.motX;
+                    double victimMotY = entity.motY;
+                    double victimMotZ = entity.motZ;
+                    // Kohi end
+
                     boolean flag2 = entity.damageEntity(DamageSource.playerAttack(this), f);
 
                     if (flag2) {
@@ -957,6 +965,31 @@ public abstract class EntityHuman extends EntityLiving implements ICommandListen
                             this.setSprinting(false);
                         }
 
+                        // Kohi start
+                        // If the attack caused knockback, send the new velocity to the victim's client immediately,
+                        // and undo the change. Otherwise, if movement packets from the victim are processed before
+                        // the end of the tick, then friction may reduce the velocity considerably before it's sent
+                        // to the client, particularly if the victim was standing on the ground when those packets
+                        // were generated. And because this glitch is also likely to make server-side velocity very
+                        // inconsistent, we simply reverse the knockback after sending it so that KB, like most other
+                        // things, doesn't affect server velocity at all.
+                        if (entity instanceof EntityPlayer && entity.velocityChanged) {
+                            EntityPlayer attackedPlayer = (EntityPlayer) entity;
+                            PlayerVelocityEvent event = new PlayerVelocityEvent(attackedPlayer.getBukkitEntity(),
+                                                                                attackedPlayer.getBukkitEntity().getVelocity());
+                            this.world.getServer().getPluginManager().callEvent(event);
+                            if (!event.isCancelled()) {
+                                attackedPlayer.getBukkitEntity().setVelocityDirect(event.getVelocity());
+                                attackedPlayer.playerConnection.sendPacket(new PacketPlayOutEntityVelocity(attackedPlayer));
+                            }
+
+                            attackedPlayer.velocityChanged = false;
+                            attackedPlayer.motX = victimMotX;
+                            attackedPlayer.motY = victimMotY;
+                            attackedPlayer.motZ = victimMotZ;
+                        }
+                        // Kohi end
+
                         if (flag) {
                             this.b(entity);
                         }
diff --git a/src/main/java/org/bukkit/craftbukkit/entity/CraftPlayer.java b/src/main/java/org/bukkit/craftbukkit/entity/CraftPlayer.java
index bcd956f..093d381 100644
--- a/src/main/java/org/bukkit/craftbukkit/entity/CraftPlayer.java
+++ b/src/main/java/org/bukkit/craftbukkit/entity/CraftPlayer.java
@@ -53,6 +53,7 @@ import org.bukkit.event.player.PlayerGameModeChangeEvent;
 import org.bukkit.event.player.PlayerRegisterChannelEvent;
 import org.bukkit.event.player.PlayerTeleportEvent;
 import org.bukkit.event.player.PlayerUnregisterChannelEvent;
+import org.bukkit.event.player.PlayerVelocityEvent;
 import org.bukkit.inventory.InventoryView.Property;
 import org.bukkit.map.MapView;
 import org.bukkit.metadata.MetadataValue;
@@ -60,6 +61,7 @@ import org.bukkit.plugin.Plugin;
 import org.bukkit.plugin.messaging.StandardMessenger;
 import org.bukkit.potion.PotionEffectType;
 import org.bukkit.scoreboard.Scoreboard;
+import org.bukkit.util.Vector;
 
 @DelegateDeserialization(CraftOfflinePlayer.class)
 public class CraftPlayer extends CraftHumanEntity implements Player {
@@ -1473,4 +1475,37 @@ public class CraftPlayer extends CraftHumanEntity implements Player {
         return kohi;
     }
     // Kohi end
+
+    // Kohi start
+    @Override
+    public void setVelocity(Vector vel) {
+        // To be consistent with old behavior, set the velocity before firing the event
+        this.setVelocityDirect(vel);
+
+        PlayerVelocityEvent event = new PlayerVelocityEvent(this, vel.clone());
+        this.getServer().getPluginManager().callEvent(event);
+
+        if(!event.isCancelled()) {
+            // Set the velocity again in case it was changed by event handlers
+            this.setVelocityDirect(event.getVelocity());
+
+            // Send the new velocity to the player's client immediately, so it isn't affected by
+            // any movement packets from this player that may be processed before the end of the tick.
+            // Without this, player velocity changes tend to be very inconsistent.
+            this.getHandle().playerConnection.sendPacket(new PacketPlayOutEntityVelocity(this.getHandle()));
+        }
+
+        // Note that cancelling the event does not restore the old velocity, it only prevents
+        // the packet from sending. Again, this is to be consistent with old behavior.
+    }
+
+    public void setVelocityDirect(Vector vel) {
+        entity.motX = vel.getX();
+        entity.motY = vel.getY();
+        entity.motZ = vel.getZ();
+        if (entity.motY > 0) {
+            entity.fallDistance = 0.0f;
+        }
+    }
+    // Kohi end
 }
 knockbackFriction = 2.0D;
knockbackHorizontal = 0.35D;
knockbackVertical = 0.35D;
knockbackVerticalLimit = 0.4D;
knockbackExtraHorizontal = 0.425D;
knockbackExtraVertical = 0.085D;
/*
 * Copyright (c) 2016, 2017, 2018, 2019 FabricMC
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *     http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */

package net.fabricmc.installer.client;

import java.io.IOException;
import java.net.URL;
import java.nio.file.Files;
import java.nio.file.Path;

import net.fabricmc.installer.LoaderVersion;
import net.fabricmc.installer.util.InstallerProgress;
import net.fabricmc.installer.util.Reference;
import net.fabricmc.installer.util.Utils;

public class ClientInstaller {
	public static String install(Path mcDir, String gameVersion, LoaderVersion loaderVersion, InstallerProgress progress) throws IOException {
		System.out.println("Installing " + gameVersion + " with fabric " + loaderVersion.name);

		String profileName = String.format("%s-%s-%s", Reference.LOADER_NAME, loaderVersion.name, gameVersion);

		Path versionsDir = mcDir.resolve("versions");
		Path profileDir = versionsDir.resolve(profileName);
		Path profileJson = profileDir.resolve(profileName + ".json");

		if (!Files.exists(profileDir)) {
			Files.createDirectories(profileDir);
		}

		/*

		This is a fun meme

		The vanilla launcher assumes the profile name is the same name as a maven artifact, how ever our profile name is a combination of 2
		(mappings and loader). The launcher will also accept any jar with the same name as the profile, it doesnt care if its empty

		 */
		Path dummyJar = profileDir.resolve(profileName + ".jar");
		Files.deleteIfExists(dummyJar);
		Files.createFile(dummyJar);

		URL profileUrl = new URL(Reference.getMetaServerEndpoint(String.format("v2/versions/loader/%s/%s/profile/json", gameVersion, loaderVersion.name)));
		Utils.downloadFile(profileUrl, profileJson);

		progress.updateProgress(Utils.BUNDLE.getString("progress.done"));

		return profileName;
	}
}
####################################################
#   KnockbackMaster by xDefcon <luigi@xdefcon.com>
# www.spigotmc.org/resources/knockbackmaster.42721/
#                Configuration File
####################################################

# Should the plugin notify OPs when a new update is released? (SUGGESTED VALUE IS "true")
update-notify: true

# Toggle debug mode (leave it as false if not requested by the developer).
debug: false


#**************************************************#
#                    KNOCKBACK                     #
#**************************************************#
# Section related to the Knockback multipliers.
# 1.0 means "standard" KB, for instance 1 block.
# 1.1 means 10% more than the previous knockback.
# Please consider that the knockback is processed
# with a certain order.
#
# FOR CUSTOM KNOCKBACK (PER WORLD), PLEASE CHECK AT
# THE VERY BOTTOM OF THIS CONFIG FILE.
#**************************************************#
knockback:
  # Should the knockback module (normal,sprinting,in-air,enchantment) be enabled?
  # Setting this to "false" will let the Spigot server handle the hits and the related knockback.
  enabled: true

  # DEFAULT KNOCKBACK VALUES
  # THE FOLLOWING APPLIES FOR WORLD/REGIONS SETTINGS THAT ARE NOT SPECIFIED ABOVE
  # Example: If you want in worldB a different "normal.vertical" modifier, just create
  # a world above and specify JUST "normal.vertical" value (or just the values you want to be different),
  # all the others will be taken from the following default ones. The same applies for WorldGuard Regions
  #
  normal:
    # Horizontal knockback, affects only X and Z coordinate values.
    horizontal: 0.4
    # Vertical knockback, affects only Y coordinate value.
    vertical: 0.36

  # Sprinting knockback values. This multipliers will be used if the damager is sprinting
  # By default in Minecraft, if the damager player is sprinting, he deals more knockback to the damaged one.
  # This is the reason of PvP movement-related actions like W-tapping.
  sprinting:
    # Select the sprinting module system. Available values: "standard" and "legacy".
    # "standard" is the new module that will improve the sprinting detection (better detection)
    # "legacy" is the old method (pre v2.10.0) that you may find better if you started with a version below 2.10.0.
    # If you set "legacy" as method, you should set the "knockback.air.horizontal" multiplier to 1.0 to achieve the exact same
    # as version 2.9 and below.
    mode: "standard"
    # Horizontal sprint knockback, affects only X and Z coordinate values.
    horizontal: 0.8
    # Vertical sprint knockback, affects only Y coordinate value.
    vertical: 0.42

  # Air knockback values. Section related to the knockback that a player should receive if in air.
  # Usually, if the damaged player is taking damage while he's in the air, he will receive less knockback
  # both horizontally and vertically.
  air:
    # Air Multiplier, 1.0 means no difference, 0.8 means 20% less knockback while in air.
    horizontal: 0.6
    vertical: 0.8

  # Enchantment section.
  enchantment:
    # Knockback enchantment multipliers. You can configure a specific multiplier (or value) for each knockback level (Knockback I, II, etc.)
    # If you have, for instance, KnockbackIV, you can add '4' after '3'. If you set 1.10, this results in a 10% increase.
    # If you set 2.15, this results in a 115% increase. The default values are similar to the standard Knockback I and II.
    #
    # If you do NOT want multipliers but instead you want custom values for a specific knockback enchantment level,
    # you can add "horizontal" and "vertical" to the specific knockback level like following example.
    #
    # You can have all of the following values as multipliers, values or both, like in the example below that works like this:
    # Knockback I will have a 105% increase in knockback.normal or knockback.sprinting values
    # Knockback II will have a 190% increase
    # Knockback III will overwrite knockback.normal values and sets them to 1.1 and 0.45 relatively.
    # Please note that in the example below, the lines after '3' must have correct spacing or the config file will be invalid.
    knockback-level:
      '1': 2.05
      '2': 2.9
      '3': # Knockback III is not achievable in vanilla minecraft
        horizontal: 1.1
        vertical: 0.45
      # If the enchantment level is none of the above, this multiplier will be used. This can only be a multiplier.
      other: 3.5
      # Should the knockback be the same also if the player is sprinting? (set to true for vanilla-like experience).
      ignore-sprinting: true

    # Section related to the knockback caused by the thorns enchantment
    # You can choose to increase or decrease the knockback that players receive when attacking an armor with the thorns
    # enchantment.
    #
    # Please note that everything related to the percentages of receiving an hit by the enchantment are not
    # modified by the plugin and the vanilla behaviour remains: https://minecraft.gamepedia.com/Thorns
    thorns:
      # Should the plugin edit the THORNS knockback?
      enabled: false
      # Horizontal value. This is a value that will override the one defined in normal.horizontal or sprinting.horizontal
      horizontal: 0.4
      # Vertical value (same as horizontal, but for the other axis)
      vertical: 0.38


  # Section related to the knockback caused by BOW
  bow:
    # Toggle this to false if you want to use the Minecraft's standard method to handle the KB of a bow.
    enabled: true

    # Standard bow KB, horizontal and vertical
    normal:
      horizontal: 0.75
      vertical: 0.35

    # Air BOW knockback values. Section related to the knockback that a player should receive if in air.
    air:
      # Air Multiplier, 1.0 means no difference, 0.8 means 20% less knockback while in air.
      in-air-multiplier: 0.8

    # Enchantment section.
    enchantment:
      # Punch (Arrow Knockback) enchantment multipliers. You can configure a specific multiplier for each knockback level (Punch I, II, etc.)
      # If you have, for instance, PunchIII, you can add '3' after '2'. If you set 1.10, this results in a 10% increase.
      # If you set 2.15, this results in a 115% increase. The default values are similar to the standard Punch I and II.
      punch-level:
        '1': 2.0
        '2': 2.85
        # If the enchant level is none of the above, this multiplier will be used.
        other: 3.0

#**************************************************#
#                     W-TAPPING                    #
#**************************************************#
w-tap:
  # Should the w-tap manager be enabled and check when a player is w-tapping?
  enabled: true

  # Set this to true to enable debug mode. Debug mode will send a notification to OPs every tick that notify them
  # when he is w-tapping or not. This is useful to check the w-tap values to see if the delays works for your pvp style.
  debug: false

  # How long (in ticks, 1 tick = 50ms) should the player stand still before detecting him as NOT moving?
  not-moving-delay: 2

  # What is the maximum delay (ms) between pressing W key twice (sprinting/not sprinting) for detecting a player as w-tapping?
  # Lower value = pressing W faster for valid w-tap. Higher value = more easy to w-tap.
  # (Please set values near multiples of 50 like: 150, 160, 195, 200, 455 to be more accurate as possible.)
  sprinting-delay-ms: 200

  # Section related to W-tap knockback modifiers. The knockback will be multiplied by this value.
  # 1.05 means 5% MORE knockback while 0.98 means 2% LESS knockback (suggestion: keep this values between -10% and +10%)
  knockback-modifier:
      # kb modifiers for attacker player, this is the knockback (modifier) you DEAL if w-tapping:
      as-damager:
          horizontal: 1.05
          vertical: 1.03
      # kb modifiers for damaged player, this is the knockback (modifier) you RECEIVE if w-tapping:
      as-damaged:
          horizontal: 0.95
          vertical: 0.97

#**************************************************#
#                   COMBO MODE                     #
#**************************************************#
combo-mode:
  # Should the combo mode be enabled?
  enabled: false
  # A list of worlds where the combo mode should be disabled.
  disabled-worlds:
    - "exampleDisabledWorld1"
    - "exampleDisabledWorld2"

  # Enables the compatibility with minecraft versions above 1.9 (new combat system) and with plugins such as OldCombatMechanics
  # Set this to true if you are using versions above 1.9 and you are using OldCombatMechanics or similar plugins.
  # Set this to false if your server version is 1.8 or lower.
  19-compatibility: false

  # Select the type of the combo mode. 1 means that the combo mode will be enabled when a player eats an enchanted golden apple.
  # 2 means a PERMANENT combo mode, from the login, to the logout of a player.
  type: 1

  # Section related for the knockback in combo mode. These values will replace the "knockback.normal" and
  # "knockback.sprinting" values and will be applied only if the damaged player is in combo mode.
  # Please consider that the "knockback.air.in-air-multiplier" is still valid here, and you should edit it if you
  # want the players in combo to go too high when hit (some people like this behavior, some does not).
  knockback:
    # Standard knockback combo values. This multipliers will be used if the damaged player is in combo mode.
    normal:
      horizontal: 0.42
      vertical: 0.32

    # Sprinting knockback values. This multipliers will be used if the damager is sprinting and if the damaged player is in combo mode.
    sprinting:
      horizontal: 0.85
      vertical: 0.37

    # Combo mode air knockback values. Section related to the knockback that a player should receive if in air
    # and he is in combo mode.
    air:
      # Air Multiplier, 1.0 means no difference, 0.6 means 40% less knockback while in air.
      horizontal: 0.6
      vertical: 0.6

      # When enabled, height-control module will allow you to set a new vertical multiplier when the player is too high
      # from the ground (configurable as height-blocks). This is useful to avoid getting players too high when in combo mode.
      #
      # NOTE: this module adds little computational effort to calculate the height of a player during combat, it won't hurt performance
      # and it is here because you requested it. I recommend to find good combo-mode knockback values and no-damage-ticks so this
      # module won't be needed as the players will naturally fall down and not exceed a certain height.
      height-control:
        enabled: false
        # From what distance from the ground should we apply the new-vertical multiplier?
        # 5.2 means that if the player is above 5.2 blocks from the ground then the new-vertical multiplier will be used.
        height-blocks: 5.2
        # The new vertical multiplier that has to be used ONLY when the player is above "height-blocks" from the ground,
        # this will overwrite the combo-mode.knockback.air.vertical multiplier.
        # 0.1 means 90% less vertical knockback, 0 means no vertical knockback.
        new-vertical: 0.1

  # Set this to true if you want to notify players when combo mode is enabled (after eating gapple)
  # and disabled (when the time is expired). You can edit the messages in the messages.yml config file.
  notify-player: true

  # How long should the combo effect be active? Set this value in seconds.
  gapple-duration: 30

  # No damage ticks. This value represent the number of ticks (1 tick = 50ms) that should occur between 2 hits.
  # The standard minecraft value of this parameter is 20
  # The logic behind how this value is processed in minecraft is not as "logical" as you may think but basically
  # the following is true: LOWER no-damage-ticks values means HIGHER max hits per second.
  # EXAMPLE: If you set the following value to 5, the players will receive not more than 1 hit every 5 ticks (250ms);
  # EXAMPLE 2: If you set the following value to 3, the players will receive not more than 1 hit every 3 ticks (150ms).
  no-damage-ticks: 3

#**************************************************#
#                   RANDOMIZER                     #
#**************************************************#
randomizer:
  # Set this to false if you want to DISABLE the randomize feature.
  enabled: true

  # Section related to random knockback modifiers. Values are in percentage.
  modifier:
    # Horizontal maximum percentage factor. (5 means that a maximum of 5% will be randomly added for each hit)
    horizontal: 4
    # Vertical maximum percentage factor.
    vertical: 2

#**************************************************#
#                 PER-WORLD KNOCKBACK              #
#**************************************************#
# Custom knockback for specific worlds. Please specify world names lower-case!
# How does it work?
# 1) KnockbackMaster will read the values above in "knockback" section and consider them as DEFAULT.
# 2) If a custom world name is specified here, the related values will overwrite the DEFAULT ones.
# 3) You have to specify ONLY the values you want to be different from the DEFAULT ones
#
# EXAMPLE:
# If you want to modify just the knockback.normal.horizontal and vertical values for world "MyCustomKbWorld1"
# you have to write just 2 values under "mycustomworld1" section (note that world names must be lower-case)
# you can follow the default example below:
custom-worlds:
  # Set to TRUE to enable custom KB by specifying worlds below.
  enabled: false
  worlds:
    # Example world 1 (you can remove or edit this)
    mycustomkbworld1:
      knockback:
        normal:
          horizontal: 0.2
          vertical: 0.23
        sprinting:
          mode: "legacy"
        bow:
          air:
            in-air-multiplier: 0.8
    # You can add/remove as many worlds as you want
    mycustomkbworld2:
      knockback:
        normal:
          horizontal: 1.1
          From b7afc36b9d4c06ef92f073c0625b3c3578153078 Mon Sep 17 00:00:00 2001
From: Noksio <matthew.steglinski@utoronto.ca>
Date: Mon, 1 Aug 2016 22:07:27 -0400
Subject: [PATCH] Fix the relog on the player knockback


diff --git a/src/main/java/net/minecraft/server/EntityHuman.java b/src/main/java/net/minecraft/server/EntityHuman.java
index 1a8e5dc..afa674f 100644
--- a/src/main/java/net/minecraft/server/EntityHuman.java
+++ b/src/main/java/net/minecraft/server/EntityHuman.java
@@ -1,15 +1,8 @@
 package net.minecraft.server;
 
-import java.util.Collection;
-import java.util.Iterator;
-import java.util.List;
-import java.util.UUID;
-
 import com.google.common.base.Objects;
 import net.minecraft.util.com.google.common.base.Charsets;
 import net.minecraft.util.com.mojang.authlib.GameProfile;
-
-// CraftBukkit start
 import org.bukkit.Bukkit;
 import org.bukkit.craftbukkit.entity.CraftHumanEntity;
 import org.bukkit.craftbukkit.entity.CraftItem;
@@ -21,8 +14,15 @@ import org.bukkit.event.player.PlayerBedEnterEvent;
 import org.bukkit.event.player.PlayerBedLeaveEvent;
 import org.bukkit.event.player.PlayerDropItemEvent;
 import org.bukkit.event.player.PlayerItemConsumeEvent;
+import org.bukkit.event.player.PlayerVelocityEvent
+import org.spigotmc.ProtocolData;
+
+import java.util.Collection;
+import java.util.Iterator;
+import java.util.List;
+import java.util.UUID;
+
+// CraftBukkit start
 // CraftBukkit end
-import org.spigotmc.ProtocolData; // Spigot - protocol patch
 
 public abstract class EntityHuman extends EntityLiving implements ICommandListener {
 
@@ -951,6 +951,14 @@ public abstract class EntityHuman extends EntityLiving implements ICommandListen
                         // CraftBukkit end
                     }
 
+                    // CraftBukkit start
+                    // Save the victim's velocity before they are potentially knocked back
+                    double victimMotX = entity.motX;
+                    double victimMotY = entity.motY;
+                    double victimMotZ = entity.motZ;
+                    // CraftBukkit end
+                    
+
                     boolean flag2 = entity.damageEntity(DamageSource.playerAttack(this), f);
 
                     if (flag2) {
@@ -961,6 +969,24 @@ public abstract class EntityHuman extends EntityLiving implements ICommandListen
                             this.setSprinting(false);
                         }
 
+                        // NoksioSpigot start
+                        // If the attack caused knockback, send the new velocity to the victim's client immediately,
+                        // and undo the change. Otherwise, if movement packets from the victim are processed before
+                        // the end of the tick, then friction may reduce the velocity considerably before it's sent
+                        // to the client, particularly if the victim was standing on the ground when those packets
+                        // were generated. And because this glitch is also likely to make server-side velocity very
+                        // inconsistent, we simply reverse the knockback after sending it so that KB, like most other
+                        // things, doesn't affect server velocity at all.
+                        if (entity instanceof EntityPlayer && entity.velocityChanged) {
+                            EntityPlayer attackedPlayer = (EntityPlayer) entity;
+
+                            PlayerVelocityEvent event = new PlayerVelocityEvent(attackedPlayer.getBukkitEntity(), attackedPlayer.getBukkitEntity().getVelocity());
+                            this.world.getServer().getPluginManager().callEvent(event);
+                            if(!event.isCancelled()){
+                                attackedPlayer.getBukkitEntity().setVelocityDirect(event.getVelocity());
+                                attackedPlayer.playerConnection.sendPacket(new PacketPlayOutEntityVelocity(attackedPlayer));
+                            }
+                            attackedPlayer.velocityChanged = false;
+                            attackedPlayer.motX = victimMotX;
+                            attackedPlayer.motY = victimMotY;
+                            attackedPlayer.motZ = victimMotZ;
+                        }
+                        // NoksioSpigot end
+
                         if (flag) {
                             this.b(entity);
                         }
diff --git a/src/main/java/org/bukkit/craftbukkit/entity/CraftPlayer.java b/src/main/java/org/bukkit/craftbukkit/entity/CraftPlayer.java
index 9384cbe..5067399 100644
--- a/src/main/java/org/bukkit/craftbukkit/entity/CraftPlayer.java
+++ b/src/main/java/org/bukkit/craftbukkit/entity/CraftPlayer.java
@@ -1336,6 +1336,16 @@ public class CraftPlayer extends CraftHumanEntity implements Player {
         // Spigot end
     }
 
+    @Override
+    public void setVelocity(org.bukkit.util.Vector vel) {
+        setVelocityDirect(vel);
+
+        org.bukkit.event.player.PlayerVelocityEvent event = new org.bukkit.event.player.PlayerVelocityEvent(this, vel.clone());
+        getServer().getPluginManager().callEvent(event);
+        if (!event.isCancelled()) {
+            setVelocityDirect(event.getVelocity());
+            getHandle().playerConnection.sendPacket(new PacketPlayOutEntityVelocity(getHandle()));
+        }
+    }
+
+    public void setVelocityDirect(org.bukkit.util.Vector vel) {
+        this.entity.motX = vel.getX();
+        this.entity.motY = vel.getY();
+        this.entity.motZ = vel.getZ();
+    }
+
     // Spigot start
     private final Player.Spigot spigot = new Player.Spigot()
     {
-- 
2.8.4 (Apple Git-73)
package host.serenity.serenity.modules.combat;

import host.serenity.serenity.api.help.ValueDescription;
import host.serenity.serenity.api.module.Module;
import host.serenity.serenity.api.module.ModuleCategory;
import host.serenity.serenity.api.value.BooleanValue;
import host.serenity.serenity.api.value.FloatValue;
import host.serenity.serenity.api.value.ModuleValue;
import host.serenity.serenity.event.network.ReceivePacket;
import host.serenity.serenity.util.iface.S27PacketExplosionExtension;
import host.serenity.synapse.Listener;
import net.minecraft.network.play.server.S12PacketEntityVelocity;
import net.minecraft.network.play.server.S27PacketExplosion;

public class AntiKnockback extends Module {

    @ModuleValue
    @ValueDescription("Adds the applied knockback to your current velocity, instead of setting it.")
    public BooleanValue additive = new BooleanValue("additive", true);

    @ModuleValue
    @ValueDescription("Adjusts the relative amount (0 to 1) of the horizontal knockback to be applied.")
    public FloatValue horizontal = new FloatValue("horizontal", 0);

    @ModuleValue
    @ValueDescription("Adjusts the relative amount (0 to 1) of the vertical knockback to be applied.")
    public FloatValue vertical = new FloatValue("vertical", 0);

    public AntiKnockback() {
        super("Anti Knockback", 0xFEFF71, ModuleCategory.COMBAT);

        listeners.add(new Listener<ReceivePacket>() {
            @Override
            public void call(ReceivePacket event) {
                if (event.getPacket() instanceof S12PacketEntityVelocity && ((S12PacketEntityVelocity) event.getPacket()).getEntityID() == mc.thePlayer.getEntityId()) {
                    S12PacketEntityVelocity packet = (S12PacketEntityVelocity) event.getPacket();
                    event.setCancelled(true);

                    double motionX = packet.getMotionX() / 8000D * horizontal.getValue();
                    double motionY = packet.getMotionY() / 8000D * vertical.getValue();
                    double motionZ = packet.getMotionZ() / 8000D * horizontal.getValue();

                    if (additive.getValue()) {
                        motionX += mc.thePlayer.motionX;
                        motionY += mc.thePlayer.motionY;
                        motionZ += mc.thePlayer.motionZ;
                    }

                    mc.thePlayer.motionX = motionX;
                    mc.thePlayer.motionY = motionY;
                    mc.thePlayer.motionZ = motionZ;
                }
                if (event.getPacket() instanceof S27PacketExplosion) {
                    S27PacketExplosion packet = (S27PacketExplosion) event.getPacket();

                    float motionX = packet.func_149149_c();
                    float motionY = packet.func_149144_d();
                    float motionZ = packet.func_149147_e();

                    motionX *= horizontal.getValue();
                    motionZ *= vertical.getValue();

                    S27PacketExplosionExtension packetExtension = (S27PacketExplosionExtension) packet;

                    packetExtension.setVelocityX(motionX);
                    packetExtension.setVelocityY(motionY);
                    packetExtension.setVelocityZ(motionZ);
                }
            }
        });
    }
}
using System;
using System.Linq;
using System.Threading;
using System.Threading.Tasks;
using System.Windows.Forms;
using System.Collections.Generic;
using Memory;

namespace Reach
{
    public partial class Main : Form
    {
        Mem M = new Mem();

        //Arrays
        string arrayReach = "00 00 00 00 00 00 08 40";
        string arrayReachBuffer = "00 00 00 00 00 00 12 40";

        //Bools
        bool isScanning = false;

        //Enums and Lists
        IEnumerable<long> aReach; 
        IEnumerable<long> aReachBuffer; 
        List<long> lReach = new List<long>(); 
        List<long> lReachBuffer = new List<long>(); 

        //Doubles
        double reachVal;
        double reachBufferVal;

        //Constructor
        public Main()
        {
            InitializeComponent();
        }

        //Form Load
        private async void Main_Load(object sender, EventArgs e)
        {
            M.OpenProcess("javaw"); //Opening the Minecraft process
            await Task.Run(() => scanReach()); //Starting the Reach scan
            tmrReach.Start(); //Starting the Reach process
        }

        //Scanning for 3.0 Double and 4.5 Double
        public async void scanReach()
        {
            isScanning = true;
            aReach = await M.AoBScan(0, 90000000, arrayReach, false, true); //Reading the addresses of 3.0 Double
            aReachBuffer = await M.AoBScan(0, 90000000, arrayReachBuffer, false, true); //Reading the addresses of 4.5 Double
            lReach.AddRange(aReach.ToList()); //Adding all the addresses to a list, so we don't overwrite them when we rescan our reach
            lReachBuffer.AddRange(aReachBuffer.ToList()); // ::
            isScanning = false;
        }

        //Actual Reach process
        private async void tmrReach_Tick(object sender, EventArgs e)
        {

            if (M.OpenProcess("javaw") && !isScanning) //Checking if Minecraft is opened and if we are scanning
            {

                foreach (var aBuffer in lReachBuffer) //Looping through every address in the List for 4.5 Double
                {

                    foreach (var aReach in lReach) //Looping through every address in the List for 3.0 Double
                    {

                        if (aBuffer.ToString("X").Length == 7 && aReach.ToString("X").Length == 7) //Checking if the 4.5 Double address has a zero in the beginning
                        {

                            if (aBuffer.ToString("X").Substring(0, 3) == aReach.ToString("X").Substring(0, 3)) //Checking if the addresses are similar
                            {
                                reachVal = M.ReadDouble(aReach.ToString("X")); //Scanning the value of 3.0 Double
                                reachBufferVal = M.ReadDouble(aBuffer.ToString("X")); //Scanning the value of 4.5 Double

                                aList.Items.Add("Reach: " + aReach.ToString("X") + " | " + reachVal.ToString()); //Printing the address and value of the address in the Listbox (3.0 Double)                            
                                aList.Items.Add("ReachBuffer: " + aBuffer.ToString("X") + " | " + reachBufferVal.ToString()); //Printing the address and value of the address in the Listbox (4.5 Double)

                                if (reachVal.ToString().Length < 5 && reachVal.ToString().Length > 0)     //Checking if the Length of the 3.0 Double value is min. 1 and max. 4 
                                {                                                                         //Because if the value corrupts and we edit it, it will crash the game.

                                    if (chckReach.Checked) //Checking if we want Reach to be enabled
                                    {
                                        await Task.Run(() => M.WriteMemory(aReach.ToString("X"), "double", "6,0"));  //Overwriting 3.0 Double to 6.0
                                        await Task.Run(() => M.WriteMemory(aBuffer.ToString("X"), "double", "7,5")); //Overwriting 4.5 Double to 7.5, because otherwise we'll only have 4.5 blocks of Reach
                                    }
                                    else
                                    {
                                        await Task.Run(() => M.WriteMemory(aReach.ToString("X"), "double", "3,0")); //Changing to the default values if we don't want Reach to be enabled.
                                        await Task.Run(() => M.WriteMemory(aBuffer.ToString("X"), "double", "4,5"));
                                    }

                                }

                            }

                        }                 

                    }

                }     

            }

        }

        //Rescanning all the addresses
        private async void tmrRescan_Tick(object sender, EventArgs e)
        {
            if (M.OpenProcess("javaw"))
            {
                await Task.Run(() => scanReach()); //Starting the scan process of Reach
            }
        }
    }
}
Changelog:
Build 1722:
	LexManos: Bump version in prep for new Recomended Build.

Build 1.8.9-11.15.0.1721:
	LexManos: Loosen TileEntity's default hasCapability implementation. Modders should specifically opt in.

Build 1.8.9-11.15.0.1720:
	vikestepftb:
		Add EntityTravelToDimensionEvent
		
		Resolve Merge Conflict
		
		Move event call inside conditional

Build 1.8.9-11.15.0.1719:
	fry: Fixed minor race condition between mouse clicks and TESR in the animation example.

Build 1.8.9-11.15.0.1718:
	fry:
		Model animation system.
		Main things of interest:
		  * IAnimationStateMachine - state machine for animations; can load
		    from json.
		  * AnimationTESR - automatic TESR for animated models.
		  * AnimationModelBase - same for entities.
		  * ITimeValue - time-varying value, used to control animation
		    parameters from code.
		
		  * TESRs can now be batched - look at TESR.renderTileEntityFast +
		    TE.hasFastRenderer.
		  * RegionRenderCache is not accessible to TESRs and other client-side
		    logic - MinecraftForgeClient.getRegionRenderCache.
	fry: Sometimes I forget how much trivial things are missing from Java 6.

Build 1.8.9-11.15.0.1716:
	t.tomkins: Fixed: BlockPos passed to isBeaconBase
	rwtema:
		Add IItemHandler capability
		
		Add the actual patches that I forgot.
		
		Add simple implementations of IStorage and the factory methods.
		
		Add ItemStackHandler. A simple IItemHandler implementaton.
		
		return nulls, not throw nulls.
		
		Move the vanilla wrappers to a separate class for now.
		
		Minor clean ups of VanillaWrapper code.
		
		Inline static methods.
		
		Add comments.
		
		Minor cleanup of code.
		
		Remove redundant size field and add a validate slot index method.
		
		Minor formatting issues.
		
		Break early If stacksize to insert is 0.
		
		Remove setByte() methods.
		
		Throw exception if IItemHandler can't be modifyed in NBT loading.
		
		Replace event handler with patches
		
		Add capability to mine cart inventory entities.
		
		Change formatting and registration of capability.
		
		Make InventoryPlayer implements IItemHandler because why not. Also added a field to allow mods that add additional player inventory space to publicly expose them.
		
		Reduce patch sizes
		
		Lazy initialization of the item handler for vanilla tiles.
		
		Minor formatting changes.
		
		Create a single vanilla chest item handler that will merge with adjacent chests when detected. Added hooks to reset the cached adjacent value when a block update is detected and when a chunk loads.
		
		Revert "Make InventoryPlayer implements IItemHandler because why not. Also added a field to allow mods that add additional player inventory space to publicly expose them."
		
		This reverts commit 306d4a37fd0e8c8a0754411c013b750dfe8e2c87.
		
		Fix furnace derp
		
		Replace double chest code with a simpler method.
		
		Vanilla wrappers implement IItemHandlerModifiable (since they are modifiable)
		
		Minor code cleanups
		
		Add an onContentsChanged() and onLoad() callback methods.to the default implementation.
		
		Add slot as a parameter in the callback method.
		
		Change IItemHandlerModifiable.setStackInSlot() to void, and added a note about not being intended for cross-mod use.
		
		Improve ItemStackHandler handling of errored NBT.
		
		Make the stacks array protected.
		
		Fix a lot of derps in SlotItemHandler.
		
		Fix derp in ItemStackHandler
		
		Clarify comments on IItemHandler
		
		ItemStackHandler no longer caches the stack array in local variable.
		
		Clean up the Chests code to make intentions clearer
		
		Vanilla hoppers have their cooldown activated when an item is inserted. Made this behavior part of an item handler (rather than the insertion code)
		
		Fix mistake in ItemStackHandler
		
		More documentation of potential edge cases in getStackInSlot()
		
		Make limit checking more resiliant.
	LexManos: Fix J6 compile error in IItemHandler PR.

Build 1.8.9-11.15.0.1715:
	blay09: Fix items being dropped out of a GuiContainer when dealing with a slot outside of the xSize/ySize boundaries.

Build 1.8.9-11.15.0.1714:
	asiekierka: Fix #2388

Build 1.8.9-11.15.0.1713:
	LexManos: Fix invalid ServerHangWatchdog patch causing it to not apply.
	LexManos:
		Restore OreDictionary.getOres(String, boolean) and doeOreNameExist(String) functions that went MIA in git merge issue.
		Original Commit: https://github.com/MinecraftForge/MinecraftForge/commit/cd3bbfb02c9fcd4ce4bbf00f460dfdd6a386d107

Build 1.8.9-11.15.0.1712:
	minecrell: Strip console formatting codes for Vanilla log file

Build 1.8.9-11.15.0.1711:
	iLexiconn:
		Fixed makeItemStack ignoring stackSize
		
		Fixes #2376

Build 1.8.9-11.15.0.1710:
	fry: Fixed error detection login in ModelLoader, reduced the maximum number of printed stack traces to 5 per domain.

Build 1.8.9-11.15.0.1709:
	LexManos: Fix Deobfusication transformer throwing verification errores in Eclipse development environments.
	LexManos: Fix forge logging not working correctly in ForgeDev.

Build 1.8.9-11.15.0.1708:
	fry: Correctly handle error caused by missing/malformed bucket model definition file.

Build 1.8.9-11.15.0.1707:
	LexManos: Call deserialze on capabilities in ItemStack.setItem. Closes #2384

Build 1.8.9-11.15.0.1706:
	LexManos: Fix ItemStacks not getting the parent capability provider from items. Closes #2383

Build 1.8.9-11.15.0.1705:
	bartek.bok: Allow sleeping without bed
	kashike: Skip hang detection on first run of the server hang watchdog

Build 1.8.9-11.15.0.1703:
	fry: Fixed missing model error reporting, made block and item variants sort before loading, to make the splash screen info more useful.

Build 1.8.9-11.15.0.1702:
	cpw: Fix spruce not growing properly

Build 1.8.9-11.15.0.1701:
	cpw: Fixed problem with LAN connections seeing the original ProxyPacket and consuming the first byte. Closes #2373

Build 1.8.9-11.15.0.1700:
	cpw: Fix shouldRefresh not to be so over-eager about modded TEs. Should fix Packet21 causing a TE reset.

Build 1.8.9-11.15.0.1699:
	LexManos: Clone FML packet indexes if channel is not open. Fixes potential threading issue.

Build 1.8.9-11.15.0.1698:
	bernhard.bonigl:
		Default bucket model is empty, allow bucket model without fluid.
		This allows capsules, cans, bottles,... to use the same item model for their item variant. Also it's makes much more sense.

Build 1.8.9-11.15.0.1697:
	tehgeek: Add GuiScreenEvent.BackgroundDrawnEvent

Build 1.8.9-11.15.0.1696:
	cpw:
		Fix problem which meant runtime deobf to MCP names wasn't working. SRG named mods located in the mods dir of a dev
		environment will now load normally.

Build 1.8.9-11.15.0.1695:
	LexManos:
		New Capability system allowing for more manageable world object features.
		
		When combined with @Optional this should address all issues of soft dependancy on mods/apis.
		This also addresses the issue of dynamic functionality in TileEntities/Entities.
		
		Current capability providers: TileEntity, Entity, ItemStack
		
		Also added INBTSerializeable, a generic interface for game objects that can be written to/from NBT tags.
		
		Vanilla capabilities will be coming soon, mostly on request and review.
		So start requesting capabiliteis on vanilla/Forge features.

Build 1.8.9-11.15.0.1694:
	LexManos: Fixed GuiWrongMinecraft having wrong Log file name. Closes #2348
	LexManos: Fix jline server console not showing colored text. Closes #2334
	LexManos: Fixed banners not droping the correct item when harvested using modded mechanics. Closes #2258

Build 1.8.9-11.15.0.1693:
	LexManos: Remove dead code in JarDiscoverer. Closes #2346
	LexManos: Made WrongMinecraftVersionException and ModSortingException a bit easier to read in log files. Closes: #2345

Build 1.8.9-11.15.0.1692:
	fry: Catch GROUND item transform type with the forge hook too.

Build 1.8.9-11.15.0.1691:
	fry: Implemented face culling for item models, improves performance slightly. Closes #2326

Build 1.8.9-11.15.0.1690:
	vincent.lee:
		Fix visual effect entity persisting longer than it should
		
		Fix derp

Build 1.8.9-11.15.0.1689:
	LexManos: Fixed issue with WorldServer.getTileEntities when being called with ranges that overlap chunks oddly. Closes #2350

Build 1.8.9-11.15.0.1688:
	fry: Made block model loading bar more robust, and fixed the count.

Build 1.8.9-11.15.0.1687:
	fry: Added progress bar for the ModelLoader.

Build 1.8.9-11.15.0.1686:
	fry: Model loader improvements: adding custom data/textures to models that don't need them doesn't cause a error now, since it's common to put those in the defaults section of the blockstate json; you can get IModel associated with the variant now - using ModelLoaderRegistry.getModel; MultiLayerModel should now respect transformations applied to it, and respect part transformations.
	fry: Derp.

Build 1.8.9-11.15.0.1684:
	cpw: STFU I know how to code. *shouts* get off my lawn!

Build 1.8.9-11.15.0.1683:
	cpw: Make the parent dir tree for the dep extractor

Build 1.8.9-11.15.0.1682:
	fry: Changed default implementation of Block.getExtendedState. Closes #2309.

Build 1.8.9-11.15.0.1681:
	fry: Fixed perspective transformation handling for fluid models, changed inventory fluid model to use unrotated still texture.
	fry: Don't crash on exception during loading of item variants from blockstate jsons.
	fry: Fixed implementation if IRetexturableModel in ItemLayerModel. Closes #2244.
	fry: Java6 + Eclipse + Gradle strike again.

Build 1.8.9-11.15.0.1677:
	fry: Fixed invalid flow vector caching of still fluids.

Build 1.8.9-11.15.0.1676:
	fry: Fixed random offset not working properly for flatly-lit models.

Build 1.8.9-11.15.0.1675:
	cpw: Explicitly close the file.

Build 1.8.9-11.15.0.1674:
	cpw:
		Add a simple ContainedDep mechanic- mods can contain other mods or libs, and can specify them using a manifest tag: "ContainedDeps".
		This is a space separated (manifest standard) list of jar files that are to be extracted into the version specific directory.
		
		There's also a special system property "fml.skipContainedDeps" that will allow for runtime skipping of extraction of contained deps (a comma separated list, based on the file name).

Build 1.8.9-11.15.0.1673:
	LexManos:
		Added new get/setRegistryName functions to Item and Block.
		And helper functions in GameRegistry to allow for registering using those names automatically.
		This is to simplify registration and get rid of the horrible hacks users are doing now with 'unlocalised names'.

Build 1.8.9-11.15.0.1672:
	cpw: Move substitution activation after id loading. This should fix the problem of null for existing object.

Build 1.8.9-11.15.0.1671:
	fry: SidedProxy now has sensible default values - nested ClientProxy and ServerProxy classes.

Build 1.8.9-11.15.0.1670:
	mattmess1221: Add links for messages and other commands

Build 1.8.9-11.15.0.1669:
	fry: Reverted Render registration changes due to them working.

Build 1.8.9-11.15.0.1668:
	fry: Fixed RenderingRegistry not working. Closes #2312.
	fry: Nobody is left behind.

Build 1.8.9-11.15.0.1666:
	cpw: Fix that the dummy registry entries don't allow clients connecting to servers. Also fix that it repeatedly nags about missing stuff in the world.

Build 1.8.9-11.15.0.1665:
	LexManos: Fix boss health bar rendering when debug overlay is enabled. Closes #2328

Build 1.8.9-11.15.0.1664:
	LexManos: Allow for default 1.8.8 mods to be loaded. Should be SRG compatible.
	LexManos: Fix J6 compile issue with ModelFluid.
	LexManos: Swap Mod and Realms button to fix new realms 'notification' icon.

Build 1.8.9-11.15.0.1663:
	fry: Restored transparency to the Forge logo.

Build 1.8.9-11.15.0.1662:
	fry: Updated the forge logo to a higher-quality GIF file. Closes #2276.

Build 1.8.9-11.15.0.1661:
	fry: Fixed broken leaky caching of OBJ models.
	fry: Fixed wrong import.

Build 1.8.9-11.15.0.1659:
	fry: Caching of fluid models. Fixes  #2145.

Build 1.8.9-11.15.0.1658:
	fry: TESRs registering in preinit don't break pistons anymore. Fixes #2298.

Build 1.8.9-11.15.0.1657:
	fry: Fixed color disabling not working for forge pipeline. Closes #2286.

Build 1.8.9-11.15.0.1656:
	fry: 1.8.9 update

Build 1.8.8-11.15.0.1655:
	tehgeek: Allow server to access Potion isBadEffect()
	cpw: 1.8.8 initial work
	cpw: regenerate reference patchset at patches.mcp. These will be used to generate a new patchtree under patches.
	cpw: Test of mcp patching
	cpw:
		Patches and rejected patches. Note: some which had imports are not listed here because they need
		to be refactored not to have imports.
		Progress: https://gist.github.com/cpw/29695e426e2b122cf8ff
	fry: Updated various rendering-related patches and classes to 1.8.8; forge still uses vecmath.
	fry: Fix generics and error in the BlockState patch.
	fry: FontRenderer + Item patch update; WorldVertexBufferUploader patch derp fix.
	fry: IntegratedServer, World, EnumChatFormatting and EnumFacing
	fry: WorldProvider, WorldType, WorldServer, WorldServerMulti
	fry: EntityAIAttackOnCollide, ServerStatusResponse, MinecraftServer, NetHandlerLoginServer, Vec3, BiomeGenBase, AnvilChunkLoader, ChunkProviderServer, MapGenRavine, MinecraftServer updated; fix in Block, GuiIngameForge; can load the world and play with ~20 more manual error fixes.
	fry: BlockOre, BlockRotatedPillar, SoundManager, EntityPlayerSP, GuiScreen, GuiAchievements, GuiContainer, BlockModelRenderer, ContainerEnchantment, Slot updated manually and imports removed; GitSlot patch updated.
	cpw: Delete rejects that I initially processed.
	cpw:
		LoadingScreenRenderer,Minecraft,GuiContainerCreative,PlayerControllerMP,LanguageManager,Locale,SimpleReloadableResourceManager,EntityList,EntityLivingBase,EntityWither,EntityMinecart,EntityPlayerMP
		
		NethanlderPlayClient patch is now in vanilla. The FMLCommonHandler future exception catcher is not needed anymore, it's in Util. The caching of player profiles is now in vanilla (SkinManager).
	fry: Updated FML Gui methods to WorldRenderer API changes.
	fry: EntityPlayer patch updated.
	fry: GuiButton, GuiChat, GuiCreateWorld, GuiIngameMenu, ServerListEntryNormal, GuiStats rejects updated.
	fry: RenderEntityItem, RenderPlayer, RendererLivingEntity, LayerArmorBase, ItemStack rejects fixed; changed Armor Layer hook to catch LayerBipedArmor only.
	fry: ItemRenderer, RenderGlobal, StateMap, RenderItem rejects updated.
	fry: TileEntity and TileEntityHopper rejects fixed, GuiOverlayDebug patch fixed.
	fry: PlayerManager, PlayerProfileCache, ServerConfigurationManager, NetHandlerHandshakeTCP rejects fixed; ItemInWorldManager patch error fixed.
	fry: ItemBlock, ItemBow, ItemMonsterPlacer, ItemReed, ItemSign rejects fixed.
	fry: Manually updated WorldChunkManager, Chunk and BiomeDecorator patches, removed imports.
	fry: TextureMap, TextureManager and Stitcher rejects fixed.
	fry: EntityRenderer, StringTranslate rejects fixed.
	fry: Overlay patch fix: use the correct block position.
	cpw:
		Enchantment,EnchantmentHelper,EntityEnderman,EntityZombie,EntityVillager,FurnaceRecipes,RecipeFireworks,RecipeRepairItem,NetworkSystem,S00PacketServerInfo
		PotionEffect,StatList,Session,WeightedRandomChestContent,Explosion,ExtendedBlockStorage,SaveHandler.
		
		All NBT patches seem to have been merged upstream, so removing. The IntegratedServer and MinecraftServer pending queue changes also removed, as fixed upstream.
	cpw: WorldGen rejects, lots of them. Couple of small fixes elsewhere.
	cpw: Fix a newly missing AT. Remove all CL_ references. OBFID is gone.
	cpw: All the patches done? Some code fixups.. It begins.
	cpw: A few tweaks, things are starting to work now..
	fry: Model stuff: updated to generics, fixed various warnings, added handling of new perspective types.
	cpw: Some generic and other warning cleanups
	fry: ExtendedBlockState, Properties generic updates.
	cpw: Remove a suppression
	cpw: This should be everything needed to separate blocks and items completely.
	fry: Implemented interpolation of TRSR transformations; B3D: added interpolation capabilities to B3DState, animated TESR example in ModelAnimationTest (pure TESR right now, no separation inside the example model between the static and dynamic parts right now).
	kashike: Use the FMLSecurityManager checkPermission(Permission) method for context-based permission checks. Fixes #2067
	fry: B3D loader: removed 2 redundand null checks, changed constructor args to final to fix (java6?) inner arg error.
	fry: Fix holes in generated item models.
	fry: Removed face doubles from item models.
	minecrell: Add jline-based console with colors and tab-completion
	cpw: Fix a typesig that was broken
	cpw: Re-add trove and vecmath. Mojang no longer ship them.
	cpw: Use the 2.1 snapshot for FG
	fry: Fixed forge lighting working incorrectly outside 0x1000000 coordinates.
	cpw: Back to srgnames for patches. We should be starting to look OK now.
	cpw: Small tweak to the OUT/ERR logger - should skip the Throwable stuffs now.
	cpw:
		Fix weird patch issue where the this FG commit: https://github.com/MinecraftForge/ForgeGradle/commit/2f0ca9921b961133689d29b807333241010a802d
		breaks if the exact end of a line is a srgname. Not ideal, but should work.
	cpw: Fix derpy fir trees in the taiga. So many patches. See if we can find any more mistakes?!
	fry: Fixed NPE is B3D loader caused by the missing vertex normal; updated the example chest model - it's now has 2 meshes; Updated ModelAnimationDebug - it now uses the new chest model, renders the base with the static world renderer, and only the lid with the TESR.
	cpw: Update mappings to 20151122.
	LexManos: Update universal manifest for 1.8.8's json.
	cpw: Cleanup Fluid deprecations stuff.
	cpw:
		OMG! Documentation? WUT? I haz lost my mind.
		Also, Functional interface for IMC. Senders can send a classname implementing Guava's function, and receivers
		will be able to get that function, and do, well, whatever, really. Probably best for those callback type
		scenarios, connecting up APIs and stuffs.
	cpw: Fix MDK for 1.8.8 using FG2.1 snapshot
	cpw: Yeah, amount is NOT deprecated.
	cpw: ONE EVENT BUS TO RULE THEM ALL AND IN THE DARKNESS FIRE THEM!
	cpw: Deprecate it as well, because hey, it's redundant now.
	cpw: Clean up some very long dead code. Bukkit hasn't existed in a very long time now. IASM never worked, and I'm not about to implement it.
	cpw: Cleaning up some derpy names
	cpw: More cleanups, some documentation, a bunch of deprecations.
	lordillyohs:
		Remove trailing */ in the build.gradle
		
		Signed-off-by: Anthony Anderson <lordillyohs@gmail.com>
	cpw: Fix button and lever placement problem. Closes #2204
	cpw: Fix up a couple of patches, affected by the recent update
	cpw:
		Add .exc for StatList patch
		
		More tweaking
	lumien231: Fixed: The Integrated Server not being stopped when exiting a singleplayer world to the main menu
	cpw: Propogate AbortException. Closes #2206. Also fix tracing printstream when printStackTrace is called.
	LexManos: Bump version for new Minecraft version.
	LexManos: Fixed placing blocks on snow layers with more then one layer.
	LexManos: Fixed Large mushrooms generating incorrectly.
	LexManos: Removed IItemRenderer class, all functionality is possible with new rendering system.
	LexManos: Compiler warnings pass, undeprecated SplashProgress related stuff.
	cpw: Giant registry fixup
	LexManos: Add chunk loading protection to WorldSever.getTileEntitiesIn, may prevent orphanced chunks and a CME in EntityPlayerMP. Note: The 'max' parameters are NON-inclusive.
	cpw: Fix up blockstate rebuild. Closes #2221. Also fix formatting. IDEA has differences. Solved now.
	bernhard.bonigl: Add a PotionRegistry to handle dynamic distribution and remapping of Potion IDs
	cpw: Fix problem with spam from registry on loading a second world. Empty the staging.
	cpw: Some tweaks - GameRegistry is modder facing API, so avoid having MC methods there. Fix a couple of registry bugs.
	cpw: Fixup Jline integration
	cpw: A few fixes
	cpw: Allow entity selectors to select "." in entity names. Closes #2125
	cpw: Be noisy when API is in a coremod. It'll never work and modders should realize that fact.
	cpw:
		Fix language adapter loading.
		
		The language adapter is now properly picked up after the mod is loaded
		on the classpath, fixing the ClassNotFoundException occurring before.
		Also fixed some minor formatting and made it throw a full
		RuntimeException on failure.
		
		Fix up some formatting
	cpw: Most requested feature of all time? TileEntity init method called after it's ready to roll. remove all the if (firstTicks)
	mark.a.woodman:
		Initialize sources list
		
		Fixes crash NPE thrown by addFile()
	cpw: Clean up chunk patch.
	liach: Fix typo in `guava`
	cpw: Add a flag to the modidremapping event. If the remapevent is because the registry is refreezing, it'll be true.
	minecrell:
		Improve the console command completer
		
		- Fix space after command getting removed when completing a
		  subcommand together with the command prefix
		- Add support for completing without input (shows command list)
		- Sort command completion results
		- Fix console spamming command prefixes after closing the input stream
	bernhard.bonigl: Add shouldRender() to Potions that allows to hide them completely in the inventory
	LexManos: Remove MCP reference patches.
	LexManos: Fixed colored leather armor, and custom armor textures.
	fry: Fixed orientations of generated item faces. Fixes #2215.
	fry: Workaround for https://github.com/google/guava/issues/738
	bx9j52xd: Fixed that oldLight is not being used.
	LexManos: Fixed ModList GUI rendering incorrectly. Closes #2254
	LexManos: Add EMERALD and SILVERFISH to GenerateMinable event. Closes #1158
	LexManos: Deprecate int IDs in FluidRegistry. Modders should only ever use the String name. Also add a 'friendly' exception when attempting to get an ID for a unregistered fluid. Closes #1374
	LexManos: Fix wrong EventType passed for Emerald ore-gen.
	AlgorithmX2:
		Added doesSideBlockRendering to provide finer grain face culling.
		Implemented for BlockStairs and BlockSlab.
	cpw: Use ItemStack.hasEffect. closes #2230
	minzmann: Update PotionEffect.java.patch
	cpw: Fix derpage when loading a 1.8 world, with persistent state being entirely ignored in that case.
	AlgorithmX2: Add getHighlightTip allowing a item to override its displayed renderToolHightlight.
	cpw:
		A test for issue #1848. Please try this with any mods you can @ 1.8.8, and see if you still get log spam of any kind (not just the
		log message from the issue either).
	AlgorithmX2: Added addLandingEffects allowing mods to override landing particles, for blocks that require world information to determine textures.
	LexManos: Fix enchanting applying the same enchantment multiple times. Closes #2273
	fry:
		Preparations for the Animation system.
		Changes to the Model API - IModelState now works with Optional. Handling of parts of the model is not optional, and coordinate space/result interpretation is up to the caller. IModel doesn't extend IModelPart by default anymore; MapModelState uses composition to achieve previous functionality, IModelPart implementations are disjoint now. Updated perspective handing to the new API, removed IPerspectiveState (MapModelState is now the same thing). Perspective transforms for the default fluid model.
	fry: IModel can now depend on a variant definition (ModelResourceLocation); added MultiLayerModel - simple model that'll render correctly in multiple layers + example of using it.
	fry: Fixed java6 errors in previous commit.
	fry: Forge pipeline will now take original model lightmap into account, if present.
	fry: Delayed quad list resolution in MultiModel, fixes NPE in MultiLayerModel.
	fry: LightUtil.pack and .unpack now work correctly with unpacked arrays of size <4.
	fry: Fix dependency resolution for models with custom data/textures.
	jadran.kotnik: Fix client side commands adding parts of the color codes on autocomplete (prefix "7" and suffix "r").
	fry: Fixed NPE caused by accessing undefined layer in MultiLayerModel.
	bernhard.bonigl:
		Add a dynamic bucket model that displays the animated liquid contained
		Has a config option (default off) that replaces the vanilla buckets with the forge bucket model
		
		New original bucket textures from mr_hazard
	LexManos:
		Fixed registry issues that prevented connecting to 1.8 Forge servers.
		More precisely: Servers with missing registries default back to frozen version.
		Throw descriptive error if we do not have any information.
	LexManos: Fixed vanilla bug related to spawning entities on top of fences. Closes #2303
	cpw: Fix the channel handler naming. It now uses the standard netty namer for it, by careful use of cunning reflection.
	cpw: Fix up persistent substitution. Should close #2259
	cpw:
		Blocks are no longer erased from the registry if the mod isn't present. This means that modded blocks can potentially retain their IDs
		even if they are temporarily not present in the game. Currently TileEntity data associated with the block is erased.
	cpw: Try and fix registry NPE when substitution is active.
	cpw: Capture ItemBlock remaps.
	cpw: Actually use the delegate for the itemblock
	cpw: Try and make sure active substitutions are immediately available in the block to item map.
	fry: Added an ability to register custom item variants, not ending with "#inventory". Should allow grouping multiple item models into 1 blockstate json.
	fry: Fixed random block position offset not applying correctly.
	LexManos: Fix Button/Torch/Lever placement on stairs and slabs. Closes #2291
	diesieben07: Allow forge-type spawn-eggs to spawn child entities when clicking EntityAgeable
	bernhard.bonigl: Add a hook for custom particle spawning for slimes
	bernhard.bonigl:
		Fix bucket replacement not loading the bucket model by itself if replacing buckets.
		This happens when no other mod that uses the bucket model is present.
		Also added a simple method for registering the bucket model, should give
		modders an idea on how to use the general model.

Build 1.8.8-11.15.0.1654-1.8.8:
	bernhard.bonigl:
		Fix bucket replacement not loading the bucket model by itself if replacing buckets.
		This happens when no other mod that uses the bucket model is present.
		Also added a simple method for registering the bucket model, should give
		modders an idea on how to use the general model.

Build 1.8.8-11.15.0.1653-1.8.8:
	bernhard.bonigl: Add a hook for custom particle spawning for slimes

Build 1.8.8-11.15.0.1652-1.8.8:
	diesieben07: Allow forge-type spawn-eggs to spawn child entities when clicking EntityAgeable

Build 1.8.8-11.15.0.1651-1.8.8:
	LexManos: Fix Button/Torch/Lever placement on stairs and slabs. Closes #2291

Build 1.8.8-11.15.0.1650-1.8.8:
	fry: Fixed random block position offset not applying correctly.

Build 1.8.8-11.15.0.1649-1.8.8:
	fry: Added an ability to register custom item variants, not ending with "#inventory". Should allow grouping multiple item models into 1 blockstate json.

Build 1.8.8-11.15.0.1647-1.8.8:
	cpw: Try and make sure active substitutions are immediately available in the block to item map.

Build 1.8.8-11.15.0.1646-1.8.8:
	cpw: Actually use the delegate for the itemblock

Build 1.8.8-11.15.0.1645-1.8.8:
	cpw: Capture ItemBlock remaps.

Build 1.8.8-11.15.0.1644-1.8.8:
	cpw: Try and fix registry NPE when substitution is active.

Build 1.8.8-11.15.0.1643-1.8.8:
	cpw:
		Blocks are no longer erased from the registry if the mod isn't present. This means that modded blocks can potentially retain their IDs
		even if they are temporarily not present in the game. Currently TileEntity data associated with the block is erased.

Build 1.8.8-11.15.0.1642-1.8.8:
	cpw: Fix up persistent substitution. Should close #2259

Build 1.8.8-11.15.0.1641-1.8.8:
	cpw: Fix the channel handler naming. It now uses the standard netty namer for it, by careful use of cunning reflection.

Build 1.8.8-11.15.0.1640-1.8.8:
	LexManos: Fixed vanilla bug related to spawning entities on top of fences. Closes #2303

Build 1.8.8-11.15.0.1639-1.8.8:
	LexManos:
		Fixed registry issues that prevented connecting to 1.8 Forge servers.
		More precisely: Servers with missing registries default back to frozen version.
		Throw descriptive error if we do not have any information.

Build 1.8.8-11.15.0.1638-1.8.8:
	bernhard.bonigl:
		Add a dynamic bucket model that displays the animated liquid contained
		Has a config option (default off) that replaces the vanilla buckets with the forge bucket model
		
		New original bucket textures from mr_hazard

Build 1.8.8-11.15.0.1637-1.8.8:
	fry: Fixed NPE caused by accessing undefined layer in MultiLayerModel.

Build 1.8.8-11.15.0.1636-1.8.8:
	jadran.kotnik: Fix client side commands adding parts of the color codes on autocomplete (prefix "7" and suffix "r").

Build 1.8.8-11.15.0.1635-1.8.8:
	fry: Fix dependency resolution for models with custom data/textures.

Build 1.8.8-11.15.0.1634-1.8.8:
	fry: LightUtil.pack and .unpack now work correctly with unpacked arrays of size <4.

Build 1.8.8-11.15.0.1633-1.8.8:
	fry: Delayed quad list resolution in MultiModel, fixes NPE in MultiLayerModel.

Build 1.8.8-11.15.0.1632-1.8.8:
	fry: IModel can now depend on a variant definition (ModelResourceLocation); added MultiLayerModel - simple model that'll render correctly in multiple layers + example of using it.
	fry: Fixed java6 errors in previous commit.
	fry: Forge pipeline will now take original model lightmap into account, if present.

Build 1.8.8-11.15.0.1630-1.8.8:
	LexManos: Fix enchanting applying the same enchantment multiple times. Closes #2273
	fry:
		Preparations for the Animation system.
		Changes to the Model API - IModelState now works with Optional. Handling of parts of the model is not optional, and coordinate space/result interpretation is up to the caller. IModel doesn't extend IModelPart by default anymore; MapModelState uses composition to achieve previous functionality, IModelPart implementations are disjoint now. Updated perspective handing to the new API, removed IPerspectiveState (MapModelState is now the same thing). Perspective transforms for the default fluid model.

Build 1.8.8-11.15.0.1628-1.8.8:
	AlgorithmX2: Added addLandingEffects allowing mods to override landing particles, for blocks that require world information to determine textures.

Build 1.8.8-11.15.0.1627-1.8.8:
	AlgorithmX2: Add getHighlightTip allowing a item to override its displayed renderToolHightlight.

Build 1.8.8-11.15.0.1626-1.8.8:
	cpw:
		A test for issue #1848. Please try this with any mods you can @ 1.8.8, and see if you still get log spam of any kind (not just the
		log message from the issue either).

Build 1.8.8-11.15.0.1625-1.8.8:
	minzmann: Update PotionEffect.java.patch

Build 1.8.8-11.15.0.1624-1.8.8:
	cpw: Fix derpage when loading a 1.8 world, with persistent state being entirely ignored in that case.

Build 1.8.8-11.15.0.1623-1.8.8:
	bernhard.bonigl: Add shouldRender() to Potions that allows to hide them completely in the inventory

Build 1.8.8-11.15.0.1622-1.8.8:
	minecrell:
		Improve the console command completer
		
		- Fix space after command getting removed when completing a
		  subcommand together with the command prefix
		- Add support for completing without input (shows command list)
		- Sort command completion results
		- Fix console spamming command prefixes after closing the input stream

Build 1.8.8-11.15.0.1621-1.8.8:
	cpw: Use ItemStack.hasEffect. closes #2230

Build 1.8.8-11.15.0.1620-1.8.8:
	liach: Fix typo in `guava`

Build 1.8.8-11.15.0.1619-1.8.8:
	AlgorithmX2:
		Added doesSideBlockRendering to provide finer grain face culling.
		Implemented for BlockStairs and BlockSlab.

Build 1.8.8-11.15.0.1618-1.8.8:
	LexManos: Fix wrong EventType passed for Emerald ore-gen.

Build 1.8.8-11.15.0.1617-1.8.8:
	LexManos: Deprecate int IDs in FluidRegistry. Modders should only ever use the String name. Also add a 'friendly' exception when attempting to get an ID for a unregistered fluid. Closes #1374

Build 1.8.8-11.15.0.1616-1.8.8:
	LexManos: Add EMERALD and SILVERFISH to GenerateMinable event. Closes #1158

Build 1.8.8-11.15.0.1615-1.8.8:
	LexManos: Fixed ModList GUI rendering incorrectly. Closes #2254

Build 1.7.10-10.13.4.1614-1.7.10:
	LexManos: Fix dispensers equipping armor on players in the wrong slot Closes #1649

Build 1.8.8-11.15.0.1613-1.8.8:
	bx9j52xd: Fixed that oldLight is not being used.

Build 1.8.8-11.15.0.1612-1.8.8:
	fry: Workaround for https://github.com/google/guava/issues/738

Build 1.8.8-11.15.0.1611-1.8.8:
	fry: Fixed orientations of generated item faces. Fixes #2215.

Build 1.8.8-11.15.0.1610-1.8.8:
	LexManos: Remove MCP reference patches.
	LexManos: Fixed colored leather armor, and custom armor textures.

Build 1.8.8-11.15.0.1609-1.8.8:
	cpw: Add a flag to the modidremapping event. If the remapevent is because the registry is refreezing, it'll be true.

Build 1.8.8-11.15.0.1608-1.8.8:
	cpw: Clean up chunk patch.

Build 1.8.8-11.15.0.1607-1.8.8:
	mark.a.woodman:
		Initialize sources list
		
		Fixes crash NPE thrown by addFile()

Build 1.8.8-11.15.0.1606-1.8.8:
	cpw: Most requested feature of all time? TileEntity init method called after it's ready to roll. remove all the if (firstTicks)

Build 1.8.8-11.15.0.1605-1.8.8:
	cpw:
		Fix language adapter loading.
		
		The language adapter is now properly picked up after the mod is loaded
		on the classpath, fixing the ClassNotFoundException occurring before.
		Also fixed some minor formatting and made it throw a full
		RuntimeException on failure.
		
		Fix up some formatting

Build 1.8.8-11.15.0.1604-1.8.8:
	cpw: Be noisy when API is in a coremod. It'll never work and modders should realize that fact.

Build 1.8.8-11.15.0.1603-1.8.8:
	tehgeek: Allow server to access Potion isBadEffect()

Build 1.8.8-11.15.0.1602-1.8.8:
	kashike: Use the FMLSecurityManager checkPermission(Permission) method for context-based permission checks. Fixes #2067

Build 1.8.8-11.15.0.1601-1.8.8:
	cpw: Allow entity selectors to select "." in entity names. Closes #2125

Build 1.8.8-11.15.0.1600-1.8.8:
	minecrell: Add jline-based console with colors and tab-completion
	bernhard.bonigl: Add a PotionRegistry to handle dynamic distribution and remapping of Potion IDs
	cpw: Some tweaks - GameRegistry is modder facing API, so avoid having MC methods there. Fix a couple of registry bugs.
	cpw: Fixup Jline integration
	cpw: A few fixes

Build 1.8.8-11.15.0.1596-1.8.8:
	cpw: Fix problem with spam from registry on loading a second world. Empty the staging.

Build 1.8.8-11.15.0.1595-1.8.8:
	lumien231: Fixed: The Integrated Server not being stopped when exiting a singleplayer world to the main menu

Build 1.8.8-11.15.0.1594-1.8.8:
	LexManos: Add chunk loading protection to WorldSever.getTileEntitiesIn, may prevent orphanced chunks and a CME in EntityPlayerMP. Note: The 'max' parameters are NON-inclusive.
	cpw: Fix up blockstate rebuild. Closes #2221. Also fix formatting. IDEA has differences. Solved now.

Build 1.8.8-11.15.0.1592-1.8.8:
	cpw: Giant registry fixup

Build 1.8.8-11.15.0.1591-1.8.8:
	LexManos: Bump version for new Minecraft version.
	LexManos: Fixed placing blocks on snow layers with more then one layer.
	LexManos: Fixed Large mushrooms generating incorrectly.
	LexManos: Removed IItemRenderer class, all functionality is possible with new rendering system.
	LexManos: Compiler warnings pass, undeprecated SplashProgress related stuff.

Build 1.8.8-11.14.4.1590-1.8.8:
	cpw: Propogate AbortException. Closes #2206. Also fix tracing printstream when printStackTrace is called.

Build 1.8.8-11.14.4.1589-1.8.8:
	cpw: Fix up a couple of patches, affected by the recent update
	cpw:
		Add .exc for StatList patch
		
		More tweaking

Build 1.8.8-11.14.4.1588-1.8.8:
	cpw: Fix button and lever placement problem. Closes #2204

Build 1.8.8-11.14.4.1587-1.8.8:
	lordillyohs:
		Remove trailing */ in the build.gradle
		
		Signed-off-by: Anthony Anderson <lordillyohs@gmail.com>

Build 1.8.8-11.14.4.1586-1.8.8:
	cpw: Cleaning up some derpy names
	cpw: More cleanups, some documentation, a bunch of deprecations.

Build 1.8.8-11.14.4.1585-1.8.8:
	cpw: Deprecate it as well, because hey, it's redundant now.
	cpw: Clean up some very long dead code. Bukkit hasn't existed in a very long time now. IASM never worked, and I'm not about to implement it.

Build 1.8.8-11.14.4.1584-1.8.8:
	cpw: ONE EVENT BUS TO RULE THEM ALL AND IN THE DARKNESS FIRE THEM!

Build 1.8.8-11.14.4.1583-1.8.8:
	cpw: Fix MDK for 1.8.8 using FG2.1 snapshot
	cpw: Yeah, amount is NOT deprecated.

Build 1.8.8-11.14.4.1582-1.8.8:
	cpw:
		OMG! Documentation? WUT? I haz lost my mind.
		Also, Functional interface for IMC. Senders can send a classname implementing Guava's function, and receivers
		will be able to get that function, and do, well, whatever, really. Probably best for those callback type
		scenarios, connecting up APIs and stuffs.

Build 1.8.8-11.14.4.1581-1.8.8:
	cpw: Cleanup Fluid deprecations stuff.

Build 1.8.8-11.14.4.1580-1.8.8:
	LexManos: Update universal manifest for 1.8.8's json.

Build 1.8.8-11.14.4.1579-1.8.8:
	fry: Fixed NPE is B3D loader caused by the missing vertex normal; updated the example chest model - it's now has 2 meshes; Updated ModelAnimationDebug - it now uses the new chest model, renders the base with the static world renderer, and only the lid with the TESR.
	LexManos: Fix incorrect position passes to Block.getExplosionResistance from entities.
	LexManos: Moved client side Block.onBlockDestroyed to after Item.onBlockDestroyed to match server order.
	LexManos: Enable the normal ModList GUI in game. Use GL_SCISSOR to support the transparent in-game GUI.
	Choonster.2010: BiomeManager: Fix off-by-one errors
	LexManos: Fix bold font rendering, Unicode is 2x pixel density of normal.
	LexManos: Fix invalid position passed to isAir/getLight in World.playAmbientSound
	fry: Fixed forge lighting working incorrectly outside 0x1000000 coordinates.
	fry: Implemented interpolation of TRSR transformations; B3D: added interpolation capabilities to B3DState, animated TESR example in ModelAnimationTest (pure TESR right now, no separation inside the example model between the static and dynamic parts right now).
	fry: B3D loader: removed 2 redundand null checks, changed constructor args to final to fix (java6?) inner arg error.
	fry: Fix holes in generated item models.
	fry: Removed face doubles from item models.
	fry: Fixed forge lighting working incorrectly outside 0x1000000 coordinates.
	cpw: Update mappings to 20151122.

Build 1.8-11.14.4.1577:
	fry: Implemented interpolation of TRSR transformations; B3D: added interpolation capabilities to B3DState, animated TESR example in ModelAnimationTest (pure TESR right now, no separation inside the example model between the static and dynamic parts right now).
	fry: B3D loader: removed 2 redundand null checks, changed constructor args to final to fix (java6?) inner arg error.
	fry: Fix holes in generated item models.
	fry: Removed face doubles from item models.
	fry: Fixed forge lighting working incorrectly outside 0x1000000 coordinates.

Build 1.8.8-11.14.4.1576-1.8.8:
	cpw: Fix derpy fir trees in the taiga. So many patches. See if we can find any more mistakes?!

Build 1.8.8-11.14.4.1575-1.8.8:
	cpw: Small tweak to the OUT/ERR logger - should skip the Throwable stuffs now.
	cpw:
		Fix weird patch issue where the this FG commit: https://github.com/MinecraftForge/ForgeGradle/commit/2f0ca9921b961133689d29b807333241010a802d
		breaks if the exact end of a line is a srgname. Not ideal, but should work.

Build 1.8-11.14.4.1572:
	LexManos: Fix invalid position passed to isAir/getLight in World.playAmbientSound

Build 1.8-11.14.4.1571:
	Choonster.2010: BiomeManager: Fix off-by-one errors

Build 1.8-11.14.4.1570:
	LexManos: Fix bold font rendering, Unicode is 2x pixel density of normal.

Build 1.8-11.14.4.1569:
	LexManos: Enable the normal ModList GUI in game. Use GL_SCISSOR to support the transparent in-game GUI.

Build 1.8-11.14.4.1568:
	LexManos: Fix incorrect position passes to Block.getExplosionResistance from entities.
	LexManos: Moved client side Block.onBlockDestroyed to after Item.onBlockDestroyed to match server order.

Build 1.7.10-10.13.4.1566-1.7.10:
	scott: Add an event hook to allow overriding of fuels recognized by vanilla fuel handling.

Build 1.8-11.14.4.1565:
	lumien231: Fix Client Login Issue when logging into a non existent dimension

Build 1.7.10-10.13.4.1564-1.7.10:
	LexManos: Fixed skulls not placing on fences like vanilla {Vanilla is buggy -.-} Closes #2185

Build 1.8-11.14.4.1563:
	LexManos: Bump version for Recomended Build.

Build 1.8-11.14.3.1562:
	LexManos:
		Merge pull request #2179 from arideus101/patch-1
		
		Fixed issue where custom colored armor wouldn't be colored. (reverted from commit dee0b2084b519419bbf97d8ad177204830ea2b07)

Build 1.8-11.14.3.1561:
	jasondoyle528: Allows Custom Armor Coloring to be done easily

Build 1.8-11.14.3.1560:
	gabizou:
		Fix a possible NPE when checking supertypes of interfaces. Closes #2176.
		
		Signed-off-by: Gabriel Harris-Rouquette <gabizou@me.com>

Build 1.8-11.14.3.1559:
	bjoern:
		Fix possible crash in EventBus
		
		There is currently no way to check if an event handler has been registered or not.
		But when trying to unregister a not-registered event handler, Minecraft crashes with a NullPointerException.
		This is a simple fix to prevent such crashes.
	cpw: Fix substitutions for recipes and oredict recipes. Should mean that substitutions start working properly.
	cpw:
		OreDictionary will warn if there's an invalid ore being registered now, rather than just
		using -1 and doing weird things with the list as a result.
	cpw: Two more corner cases in the oredictionary. Should work for all cases now.
	cpw:
		Fix firing the remap event. It always fires now, and additionally fires when the registry reverts to frozen.
		Most mods refer to the gameregistry for ids they care about, so this shouldn't affect anything significantly,
		but if your mod was dependent on their being content in the remap event, and only acting on that content,
		empty content means it's "reverted to frozen" state - the state at the start of the game.

Build 1.7.10-10.13.4.1558-1.7.10:
	cpw:
		Fix firing the remap event. It always fires now, and additionally fires when the registry reverts to frozen.
		Most mods refer to the gameregistry for ids they care about, so this shouldn't affect anything significantly,
		but if your mod was dependent on their being content in the remap event, and only acting on that content,
		empty content means it's "reverted to frozen" state - the state at the start of the game.

Build 1.7.10-10.13.4.1557-1.7.10:
	cpw: Two more corner cases in the oredictionary. Should work for all cases now.

Build 1.8-11.14.3.1556:
	LexManos: Fixed Open url confirm screen not showing URL.
	LexManos: Fixed Stronghold Library not having anything in it's chests.

Build 1.8-11.14.3.1555:
	diesieben07: Fix GameData.findBlock

Build 1.8-11.14.3.1554:
	fry: Fixed anaglyph transformation not being applied in the forge lighting fully.

Build 1.8-11.14.3.1553:
	fry: Provide ItemCameraTransforms for vanilla models when possible.

Build 1.8-11.14.3.1552:
	fry: OBJ loader: reworked texture resolution: keys now have to start with #, like every other model loader; models without explicit library now work, remapping is possible by using the key "#OBJModel.Default.Texture.Name"; in addition to remapping by material name, remapping by texture name works too, like in other model formats.

Build 1.8-11.14.3.1551:
	fry: Performace fix for item rendering.

Build 1.8-11.14.3.1550:
	Choonster.2010:
		Fix texture error message for broken textures
		
		-- Fixes #2100
		-- Iterates over badTextureDomains instead of missingTextures.keySet()
		as a domain can have broken textures without any missing textures

Build 1.8-11.14.3.1549:
	fry: Obj loader: fix vertices shared between faces having the same attributed (uvs/normals).
	the.f1repl4ce: Fixed a bug that caused the config option name to overlap with the selectable values when using GuiConfigEntries.SelectValueEntry, fixes #2114
	fry: OBJ model: use original vertex material when defining face.
	fry: Fixed block color multiplier not being cached properly in the forge renderer, performance improvement.
	LexManos: Merge FML and Forge lang file, and update crowdin project.
	LexManos:
		Redesign the ModList GUI to use a scrolling list for the main body content.
		Allowing for larger information to be displayed.
		URLs are auto-detected and now clickable.
		Mod Logos are now centered, it looks better.
	LexManos:
		Introduce a new centralized version checking system.
		Using the @Mod annotation mods can opt-in to a centrally controlled update system.
		This is PURELY a notification system and will NOT automatically download any updates.
		The End User can control which mods check for updates and disabel the system entirely using the Forge Config and GUI.
		Format for the json the URL must point to is described here: https://gist.github.com/LexManos/7aacb9aa991330523884

Build 1.8-11.14.3.1543:
	fry: Fix color multiplier applied incorrectly for items.
	fry: OBJ loader: fixed another whitespace-related issue; removed unused "modifyUVs" property for now; added the "flip-v" property to switch between OpenGL-style and DirextX-style model UVs; fixed normals - they are now correct in-world, still a bit strange for the items; fixed normals a little bit for B3D models too.

Build 1.7.10-10.13.4.1541-1.7.10:
	cpw:
		OreDictionary will warn if there's an invalid ore being registered now, rather than just
		using -1 and doing weird things with the list as a result.

Build 1.7.10-10.13.4.1539-1.7.10:
	diesieben07: Fix CME when entities are spawned from EntityJoinWorldEvent
	bernhard.bonigl: Fix Potion IDs above 127
	Abrar Syed: Update FG version to 2.0.2
	fry: Changed how the forge lighting system handles holey models for opaque blocks; it now mimics vanilla behaviour, which allows light to pass through them.
	fry: Fix for the previous commit - transparent blocks were handled improperly.
	glstillman: OBJLoader: Quick bandages to support/fix the new way that face/vertex normals are calculated, a very quick bandage to patch TextureCoordinates for the time being, and the Parser now uses a Pattern to split strings on whitespace instead of only splitting on " ".
	cpw: Fix substitutions for recipes and oredict recipes. Should mean that substitutions start working properly.

Build 1.8-11.14.3.1532:
	fry: Fixed normal calculation for vanilla models, fixed the grass darkening and simular issues.
	fry: More lighting fixes, flat lighting now works correctly for grass and torches.

Build 1.8-11.14.3.1530:
	fry: Fixed piston rendering (WorldRenderer offset wasn't applied); fixed TESR being registered too early in one of the debug mods.

Build 1.8-11.14.3.1529:
	glstillman: Fixed a bug with item model loading that would occur if ModelBakery.addVariantName() was called with the same string location parameter for 2 different items, and the string pointed to a location that didn't exist, where ModelLoader.loadAnyModel() would substitute the blockdefinition in for the item model, but wouldn't remove the original input location from the loadingModels list, which would cause the location from the second call to throw an IllegalStateException even though that location now has a model.
	fry:
		Perspective awareness for vanilla and multi models, fixes #2148.
		Improved error handling in MultiModel.
	fry: Fixed generic bug in MultiModel
	fry: Fixed AO being applied to OBJ model transparency, and OBJ loader trying to force the loading of the builtin white texture.
	fry: Provide a IModel for "builtin/generated", fixes #2147
	fry: Fixed another generic issue in MultiModel.

Build 1.8-11.14.3.1525:
	fry: Small fix for reworked classic lighting

Build 1.8-11.14.3.1524:
	fry: Added OBJ loader for the ModelLoaderRegistry system.

Build 1.8-11.14.3.1523:
	fry:
		Model pipeline system.
		Should replace all ad-hoc quad generation methods in forge, and make IBakedModel -> WorldRenderer data transfer faster. Added IVertexConsumer + helper classes; lighting that works correctly for non-axis-aligned faces using the new infrastructure. Changed smooth lighting algorithm, now it should work correctly for everything.
		New block lighter can be disabled in the forge config options.
	fry: Added back in the lost class

Build 1.8-11.14.3.1521:
	simonbarnes1:
		Add Guava and Apache to LaunchClassLoader exclusion list on server
		
		Move exclusions to common place. Less likely to get out of sync

Build 1.8-11.14.3.1520:
	bk1325: Add PlayerSetSpawnEvent

Build 1.8-11.14.3.1519:
	fry: '#' is now added automatically to the beginning of the texture names in B3D models, and the remapping is expected via the blockstate JSON, since it's more reasonable than adding it to the file name in the modelling program or matching the resource location with the filename.

Build 1.8-11.14.3.1518:
	fry: Fixes Attributes.transform affecting only 1 vertex.

Build 1.7.10-10.13.4.1517-1.7.10:
	bjoern:
		Fix possible crash in EventBus
		
		There is currently no way to check if an event handler has been registered or not.
		But when trying to unregister a not-registered event handler, Minecraft crashes with a NullPointerException.
		This is a simple fix to prevent such crashes.

Build 1.8-11.14.3.1516:
	luacs1998: Fix a possible crash in EventBus

Build 1.8-11.14.3.1515:
	rubensworks: Fix dispenser action for modded spawn eggs

Build 1.8-11.14.3.1514:
	LexManos: Update Gradle wrapper to 2.7
	LexManos: Fix entity count being incorrect for spawning logic. Now filter out 'persistant' entities.

Build 1.8-11.14.3.1513:
	foka_12: Disallow conflicting furnace recipes

Build 1.8-11.14.3.1512:
	fry: Workaround for MinecraftForge/ForgeGradle#256

Build 1.8-11.14.3.1511:
	cpw:
		FMLNetworkHandler.openGui should not try and open a GUI on a FakePlayer.
		Fixes #2082 and probably dozens of mod errors. Also, side benefit of the
		merged codebase! FML code can ref Forge code!

Build 1.8-11.14.3.1510:
	laci200270: Update FMLSecurityManager.java
	cpw: Format a bit better

Build 1.8-11.14.3.1509:
	fry: Much requested temporary hack for items and TESRs. Context: #1582, #1597, #1713, #2058 and others.

Build 1.8-11.14.3.1508:
	vorquel: Fix faulty Channel name

Build 1.8-11.14.3.1507:
	simonbarnes1: Use already provided profile for the player's own skin

Build 1.8-11.14.3.1506:
	cpw:
		More cleanup of the default eclipse workspace. The project is now called "MDKExample" not "Minecraft".
		The project tree is now contemporary, instead of a copy from 1.5.x era MC. The launches are cleaned up, and refer to
		a better default "runDir" of "run" rather than "eclipse".. Updating to FG2.0.1 which will contain relevant binary fixes.

Build 1.8-11.14.3.1505:
	cpw: Fix eclipse workspace inside the mdk - don't run it through the tokenconverter. Also add in CREDITS-fml.txt to the MDK - it's still required.

Build 1.8-11.14.3.1504:
	LexManos:
		Fixed issue where config folder would not be created before SplashProgress tried to read from it.
		Default macs to disable the new loading screen due to to many macs having issues.
		Users can enable it again by editing their config.
		Catch and gracefully handle more errors when starting up the Splash Screen.

Build 1.8-11.14.3.1503:
	diesieben07: Re-introduce RenderBlockOverlayEvent, seems to have been missed during 1.8 update
	Abrar Syed: removed broken and duplicate AT lines
	Abrar Syed: added hardcoded fml version file
	Abrar Syed: DeobfuscationData no longer required at dev time
	Abrar Syed: removed old unnecessary stuff
	Abrar Syed: Added FG2 buildscript + updated for Gradle 2.4
	Abrar Syed: added jenkins compat tasks
	Abrar Syed: fixed local-building fail with changelog
	Abrar Syed: updated installed gradle. not finished
	Abrar Syed: fixed deployment credentials
	cpw: FML is no more. FML has ceased to be. FML's expired and gone to meet its maker. FML's a stiff! Bereft of life, FML rests in peace.
	cpw: Vestigal fml-ectomy.
	cpw:
		FML's metabolic processes are now history. FML's off the twig. FML's kicked the bucket, FML's shuffled off this mortal coil,
		run down the curtain and joined the bleedin' choir invisible!! THIS IS AN EX-PROJECT!
	Abrar Syed: added MDK package
	cpw: Fix MDK task - it now runs.
	cpw: The final nail in the coffin. BYE!
	cpw:
		Trying to fix the MDK to include gradle wrapper, but the gradle-wrapper.jar is
		corrupted. @AbrarSyed can you take a look?
	cpw:
		Fix packaging the gradle wrapper properly. There is still a problem with
		the MDK- it fails to run setupDecompWorkspace.
		
		Filed an issue at ForgeGradle, since this seems to be something FG2 shouldn't
		be doing, but is?
		
		https://github.com/MinecraftForge/ForgeGradle/issues/235
	cpw: Remove patches
	cpw: Fix ciWriteBuildNumber task. Ugly, but it works.
	cpw: Fix crowdin task. Good luck jenkins, lets roll!
	cpw: Fix crowdin again. Run, jenkins, for god's sake, run!
	LexManos: Update gradle wrapper and fix changelog task.

Build 1.8-11.14.3.1502:
	cpw: ObjectHolder works great, but it should be a lot less spammy about failed lookups. They're usually mod options.
	cpw: Actually rebuild the fluidNames each rebuild, don't just try and force changes in. Should fix #1973
	cpw:
		Wake up the FluidRegistry before any mods start loading. Should stop mods claiming to own water or lava (depending on who accessed
		FluidRegistry first)
	cpw: Be a little bit more helpful when the ObjectHolder misses. Should help figure out what is going in in #2006
	cpw: Cherry pick some changes from 1.8 for inner class discovery, also fix the negativecache. Closes #1872

Build 1.8-11.14.3.1501:
	LexManos: Fix placing skulls on fence posts. Closes #2055

Build 1.8-11.14.3.1500:
	starbuck: Fix harvest logic running in addition to shearable logic

Build 1.8-11.14.3.1499:
	glstillman: Fixed a bug with ExtendedBlockStates containing at least one IProperty and one IUnlistedProperty not allowing blocks to be placed.

Build 1.8-11.14.3.1498:
	liach: Add an EnumHelper hook and fixed an issue

Build 1.8-11.14.3.1497:
	simonbarnes1: Fix placing signs with NBT prompting for text

Build 1.8-11.14.3.1496:
	Zaggy1024:
		Fixed a Forge blockstates json removing models causing an NPE in the loader.
		Fixed the deep clone of a V1 Variant not cloning the submodels properly.

Build 1.8-11.14.3.1495:
	clienthax: Signed-off-by: Clienthax <clienthax@gmail.com>

Build 1.8-11.14.3.1494:
	rubensworks: Make EnumFacing events available server-side

Build 1.8-11.14.3.1493:
	rubensworks: Fix source block check for BlockFluidClassic

Build 1.7.10-10.13.4.1492-1.7.10:
	cpw: Cherry pick some changes from 1.8 for inner class discovery, also fix the negativecache. Closes #1872

Build 1.8-11.14.3.1491:
	diesieben07: Allow the new entity eggs to be created via middle-click

Build 1.7.10-10.13.4.1490-1.7.10:
	cpw: Actually rebuild the fluidNames each rebuild, don't just try and force changes in. Should fix #1973
	cpw:
		Wake up the FluidRegistry before any mods start loading. Should stop mods claiming to own water or lava (depending on who accessed
		FluidRegistry first)
	cpw: Be a little bit more helpful when the ObjectHolder misses. Should help figure out what is going in in #2006

Build 1.8-11.14.3.1487:
	fry: Custom transformations in forge blockstate json.

Build 1.8-11.14.3.1486:
	LexManos: Fixed ItemMonsterPlacer.getEggInfo missing return. Closes #1975

Build 1.8-11.14.3.1485:
	jadran.kotnik: Fixed error GUIs showing a white screen and replaced a rogue direct GL call.

Build 1.8-11.14.3.1484:
	izooDee5: Fix particle texture of the generated item models.

Build 1.8-11.14.3.1483:
	bernhard.bonigl: Fix StateMap always mapping properties to the "minecraft" domain instead of the mods, causing it to not find BlockState definitions.

Build 1.8-11.14.3.1482:
	LexManos: Add debug for max texture size and output when Texture Atlas can not stitch all textures.

Build 1.7.10-10.13.4.1481-1.7.10:
	cpw: ObjectHolder works great, but it should be a lot less spammy about failed lookups. They're usually mod options.

Build 1.8-11.14.3.1480:
	LexManos: More descripotive error if Patcher is passed invalid data for vanilla classes.

Build 1.8-11.14.3.1479:
	fry: Fixed perspective transformations for item models.
	fry: Vanilla models can now use custom textures. Fixes #1962
	fry: There's no Map.getOrDefault in java6.

Build 1.8-11.14.3.1476:
	LexManos: Fix AT for Block constructor.

Build 1.8-11.14.3.1475:
	fry: Added ItemLayerModel - less awkward, simpler and faster version of ItemModelGenerator.

Build 1.8-11.14.3.1474:
	LexManos: Throw more descriptive errors when mods attempt to register invalid global entity IDs.
	LexManos: Include the thread state in the potential error handleing for SplashProgress.
	LexManos: Fixed Wavefront Object Importer reading files with integer values. Closes #1651, #1654
	LexManos: Create config folder in SplashProgress if it does not exist.
	LexManos: Add the stitching allocation stage to loading screen.
	LexManos:
		Make TextureMap for items and blocks skip the first pass of loading/stitching textures.
		Should decrease loading times for large packs.
		May cause issues with some mods so use -Dfml.skipFirstTextureLoad=false to disable.
	LexManos: Add TextureManager to loading screen.
	LexManos: Time each bar in the loading screen and print it to the log, useful information to see where most time is spent in loading.
	cpw:
		Mods that are extracted to the mods dir by unzipping or whatever will now cause the game to crash. Too much info is in the META-INF now,
		and more will be being added. Extracting to the mods dir just completely breaks that.

Build 1.8-11.14.3.1473:
	jamioflan:
		Added CameraSetup sub-event for camera angles
		
		Allows players to alter yaw and pitch of renderViewEntity, but more importantly, adds the ability to roll the view.
		
		Added camera roll hook

Build 1.7.10-10.13.4.1472-1.7.10:
	michafla: fix logic for guessing mesa tag in biome dict
	cpw:
		Mods that are extracted to the mods dir by unzipping or whatever will now cause the game to crash. Too much info is in the META-INF now,
		and more will be being added. Extracting to the mods dir just completely breaks that.

Build 1.7.10-10.13.4.1470-1.7.10:
	LexManos: Add TextureManager to loading screen.
	LexManos: Time each bar in the loading screen and print it to the log, useful information to see where most time is spent in loading.

Build 1.7.10-10.13.4.1469-1.7.10:
	LexManos: Create config folder in SplashProgress if it does not exist.
	LexManos: Add the stitching allocation stage to loading screen.
	LexManos:
		Make TextureMap for items and blocks skip the first pass of loading/stitching textures.
		Should decrease loading times for large packs.
		May cause issues with some mods so use -Dfml.skipFirstTextureLoad=false to disable.

Build 1.8-11.14.3.1468:
	LexManos: Patch line number update. Ignore this.
	LexManos:
		New system in EntityRegistry to allow modders to register spawn eggs.
		For entites that do not use the global ID system.
		{Which no mod entity should}
		Vanilla spawn eggs will now detect a 'entity_name' entry in it's NBT data and use that for spawning/rendering.

Build 1.8-11.14.3.1467:
	foka_12: Change permission levels on ore recipes parameters

Build 1.8-11.14.3.1466:
	foka_12:
		Fixed NPE when calling canBrew
		
		Oversight on my part,
		
		If the ingredient doesn't return true in Item.isPotionIngredient, Items.potionitem.getEffects(stack) returns null, causing an NPE to be thrown later on.
		
		This invalidates #1947.

Build 1.8-11.14.3.1465:
	LexManos: Use Guava instead of Nio for J6 compatibility.

Build 1.8-11.14.3.1464:
	fry: Added fluid renderer.

Build 1.8-11.14.3.1463:
	LexManos: Make Item.shouldCauseReequipAnimation is bit more precise and copy over the new item for rendering even if the animation is diabled.

Build 1.8-11.14.3.1462:
	LexManos: Add vanilla block rotation support back in for certain blocks that were missed in 1.8 update. Closes #1903

Build 1.8-11.14.3.1461:
	xxmicloxx: Bugfix for B3DLoader

Build 1.8-11.14.3.1460:
	dan:
		Fix incorrect block position in BlockReed canPlaceBlockAt
		
		block.canSustainPlant is called on the wrong block position.  It should be called on the block below (the 'soil' block).

Build 1.8-11.14.3.1459:
	tehgeek: Add GuiScreenEvents for keyboard and mouse input

Build 1.8-11.14.3.1458:
	t.tomkins:
		Player sensitive version of Block.getPickBlock
		
		Block.getPickBlock was patched in 1.7 but was overlooked in 1.8.
		
		Closes: https://github.com/MinecraftForge/MinecraftForge/issues/1709
	LexManos: Add Item.shouldCauseReequipAnimation to allow modders more control over the 'Reequip' animation.

Build 1.8-11.14.3.1457:
	LexManos: Fixed compile issues with irtimaled's PR.

Build 1.7.10-10.13.4.1456-1.7.10:
	irtimaled:
		Copy fortress.dat from vanilla location
		
		Fixes #1747
		
		If the dat file isn't in the dimension specific folder but is present in the vanilla data folder then copy it over.
	LexManos: Make FML Gui classes use GlStateManager. Closes FML#615
	LexManos: Fixed Wavefront Object Importer reading files with integer values. Closes #1651, #1654

Build 1.8-11.14.3.1453:
	LexManos: Cleanup code format in LayerBreakingTest.
	LexManos: Fixup model loading errors not being printed by making ICustomModelLoader.loadModel propogate IOExceptions as needed.

Build 1.7.10-10.13.4.1452-1.7.10:
	LexManos: Include the thread state in the potential error handleing for SplashProgress.

Build 1.7.10-10.13.4.1451-1.7.10:
	LexManos: Throw more descriptive errors when mods attempt to register invalid global entity IDs.

Build 1.8-11.14.3.1450:
	LexManos: Bump version for new RB.
	LexManos: Cleanup some spammy output.
	LexManos: Quiet ClassPatchManager debug spam by default. Reenable using -Dfml.debugClassPatchManager=true.
	LexManos: Quiet FMLControlledNamespacedRegistry debug spam by default. Reenable using -Dfml.debugRegistryEntries=true.
	LexManos: Quiet CrashReport class pre-loading debug, no flag to re-enable.
	LexManos: Cleanup mod signature data table. Easily seperating those mods with signatures vs those with none.
	LexManos: Cleanup mod state dump to be easier to read by displaying the states in abreviation and placing them before the mod info.

Build 1.8-11.14.3.1449:
	clarsson: Fixing two IndexOutBoundsExceptions from the BiomeDictionary

Build 1.7.10-10.13.4.1448-1.7.10:
	LexManos: Cleanup mod state dump to be easier to read by displaying the states in abreviation and placing them before the mod info.

Build 1.7.10-10.13.4.1447-1.7.10:
	LexManos: Cleanup some spammy output.
	LexManos: Quiet ClassPatchManager debug spam by default. Reenable using -Dfml.debugClassPatchManager=true.
	LexManos: Quiet FMLControlledNamespacedRegistry debug spam by default. Reenable using -Dfml.debugRegistryEntries=true.
	LexManos: Quiet CrashReport class pre-loading debug, no flag to re-enable.
	LexManos: Cleanup mod signature data table. Easily seperating those mods with signatures vs those with none.

Build 1.8-11.14.3.1446:
	LexManos: Copy over parent's modelSet value in variants as well.
	LexManos: Bump version for new RB

Build 1.7.10-10.13.4.1445-1.7.10:
	LexManos: Bump version for new RB.

Build 1.8-11.14.2.1444:
	cpw:
		Fix up the client/server fluid race condition that could cause the game to bail when an SSP game connects.
		There's still a teeny gap, but it's MUCH less prominent than it was before.

Build 1.8-11.14.2.1443:
	lumien231: Added LivingExperienceDropsEvent to change the amount of experience an entity drops

Build 1.8-11.14.2.1442:
	jcoleman350: Added ItemMap type check to item frames and ItemRenderer, enabling vanilla style rendering for custom maps

Build 1.8-11.14.2.1441:
	LexManos: Redefine removal value in IRetextureableModel from null to empty string {""} due to ImmutibleMap not allowing null Values. Closes #1927

Build 1.8-11.14.2.1440:
	foka_12: Added a brewing registry system

Build 1.8-11.14.2.1439:
	LexManos: Limit Sign text to 384 json characters and strip control codes. This is 1.8.7's Sign fix. Thanks Searge.
	LexManos: Remove worlds from WorldBorder when unloaded tol prevent memory leak, Closes #1923
	LexManos: Missed patch for sign fix.

Build 1.8-11.14.2.1437:
	cpw:
		Attempt to synchronize the state for vanilla client completions and quit the handler if the vanilla
		thread has already setup the connection. Should fix #1924

Build 1.8-11.14.2.1436:
	LexManos: Change custom payload lock to be buffer itself incase multiple packets use the same backend buffer. Closes #1908

Build 1.8-11.14.2.1435:
	Fuami.cake:
		Added Breaking Animation for Smart Models, Checking each layer.
		Added Layered Smart Render Test.

Build 1.8-11.14.2.1434:
	LexManos: Update README.txt

Build 1.8-11.14.2.1433:
	fry: Fixed missing variant logging; added the possibility to specify the item variant in the blockstate json.
	fry: fixed AT missing for getModelBlockDefinition
	fry:
		B3D Improvements
		 - fixed keyframe transformation application
		 - textures are now resolved the same way as in vanilla models
		 - added the ability to use forge blockstate texture information
		 - removed unused code from the B3D example

Build 1.8-11.14.2.1431:
	fry: Fixed partial variant detection in the forge blockstate loader.

Build 1.8-11.14.2.1430:
	LexManos: Mitigate potential issue with users requesting lots of server status information by caching ServerStatus json.

Build 1.8-11.14.2.1429:
	clienthax:
		Add missing forge patch from 1.8 port
		https://github.com/MinecraftForge/MinecraftForge/blob/1.7.10/patches/minecraft/net/minecraft/client/Minecraft.java.patch#L88

Build 1.7.10-10.13.3.1428-1.7.10:
	cpw:
		Fix up the client/server fluid race condition that could cause the game to bail when an SSP game connects.
		There's still a teeny gap, but it's MUCH less prominent than it was before.

Build 1.8-11.14.2.1427:
	LexManos:
		Hook BlockState's Json loading to add support for simplified Forge format.
		See https://github.com/MinecraftForge/MinecraftForge/pull/1885 for more details.

Build 1.8-11.14.2.1426:
	cpw:
		Attempt to disable the new splash screen if there are errors detected finishing up. Print a slightly more helpful error message.
		
		(cherry picked from commit e3211eec0469dc6717943010d584207b7abdb1e0)
		
		Conflicts:
			fml/src/main/java/cpw/mods/fml/client/SplashProgress.java
	cpw:
		Finish loading screen before going fullscreen. Closes MinecraftForge/FML#662
		
		(cherry picked from commit 19d7e16fa6a28c5665de1ed6e50d8699e865bff2)
		
		Conflicts:
			fml/patches/minecraft/net/minecraft/client/Minecraft.java.patch
	cpw: So we can't print a lot of unicode in the splash screen, so restrict to a hard subset we know we CAN print, closes #1910
	LexManos: Fixed missing import in last merge.

Build 1.7.10-10.13.3.1424-1.7.10:
	cpw: So we can't print a lot of unicode in the splash screen, so restrict to a hard subset we know we CAN print, closes #1910

Build 1.8-11.14.2.1423:
	AlgorithmX2: Allow placing item frames on Solid Block Faces (isSideSolid)

Build 1.7.10-10.13.3.1422-1.7.10:
	cpw:
		Attempt to disable the new splash screen if there are errors detected finishing up. Print a slightly more helpful error message.
		
		(cherry picked from commit e3211eec0469dc6717943010d584207b7abdb1e0)
		
		Conflicts:
			fml/src/main/java/cpw/mods/fml/client/SplashProgress.java
	cpw:
		Finish loading screen before going fullscreen. Closes MinecraftForge/FML#662
		
		(cherry picked from commit 19d7e16fa6a28c5665de1ed6e50d8699e865bff2)
		
		Conflicts:
			fml/patches/minecraft/net/minecraft/client/Minecraft.java.patch

Build 1.8-11.14.2.1421:
	cpw:
		MinecraftForge/FML@12ccf9cf49b76140841cdc5a459422ae4781de1a Rather than try to fall back to the backup level.dat in case of weirdness in the ID map, just fail hard. There is probably a serious modder derp in this case and there's nothing FML can do to recover the situation except avoid making it worse.
		MinecraftForge/FML@e8cd368da30661ed2898fff232e2db787edcbdcc It's an IllegalState not an IllegalArgument *sigh*
		MinecraftForge/FML@2be9c743424c92f8799a6af1d59d60edd65e6bf0 And fix itemblocks being removed, leaving behind a residual block. This is a legitimate action - use the missing mapping event to let the mod tell us about it
		MinecraftForge/FML@7d8804cf656081d1570068f52e9bfc7140b21a65 You can't setAction to BLOCKONLY
		MinecraftForge/FML@c73861efe67594ee9995bc93744cab06bd6647d1 Cherry-pick 01aaa7dc97480b381ca0d192ec65016d7baeb747 Fix mods defined via --mods or --modListFile launch args not being searched for coremods. #560
		MinecraftForge/FML@94c45b48c1265e7c4f60f591d413fa545787d354 Fix json cache crash, handle the file much more cleanly. Probably an MC JIRA since it's a vanilla bug. Closes #619
	cpw:
		Forge really should have always supported the concept of an "exact spawn". Individual world providers can still
		change this behaviour of course, but for default maps it makes sense to support it as a config option.
	cpw:
		Removed fluidID from ItemStack.
		
		This fixes a rather huge issue where FluidStacks on the client could be desynced if a modder was unaware of it.
		
		This is a breaking change but can be mitigated with a transformer to the getter getFluidID().
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	cpw: Add in a fluidid transformer
	cpw: Fix formatting
	cpw:
		Allow for duplicate Fluid Blocks. It's annoying to be sure but just as with the OreDictionary, we'll have to handle it.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	cpw:
		You shouldn't be creating FluidStacks from unregistered Fluids. Warn clearly on failed registrations, and make a useful log message for failed fluidstack
		creations. Should help a lot with tracking down broken mods that are doing this wrongly.
	LexManos: MinecraftForge/FML@31cf2a9cab6d1977d31436220d9612eaa13d4e0f Remove J7 only constructor in EnhancedRuntimeException, J6 compiling compatibility restored.
	LexManos: Restore binary compatibility issues in FluidRegistry caused by recent changes.
	me:
		Fix FluidRegsitry.registerFluid
		
		FluidRegistry:
		```java
		    static BiMap<String, Fluid> fluids = HashBiMap.create();
		    static BiMap<Fluid, Integer> fluidIDs = HashBiMap.create();
		...
		    public static boolean registerFluid(Fluid fluid)
		    {
		        if (fluidIDs.containsKey(fluid.getName()))
		            ^^^^^^^
		```
		There is definitely should be fluids instead fluidIDs. This mistake broke many mods.
	kinglemming:
		Fixes #1782
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	kinglemming:
		Fixes FluidContainerRegistry properly - no more corner case where client/server mods disagree.
		
		Also clarifies the 2x Fluid registration error message somewhat.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	kinglemming:
		Adds a warning to the FluidContainerRegistry when a mod does something stupid! Also denies the registration.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	cpw:
		MinecraftForge/FML@ce791cb1f2cf983ef77b1e5c4028ddefab394062 Rework EventSubscriptionTransformer to bake @Cancelable and @HasResult values, should increase EventBus performance even more by removing logic from Event constructors.
		MinecraftForge/FML@852710962a9b6d7c8e2ca188c715eebb2da44c2a Clean up some dead code
	cpw: MinecraftForge/FML@be5ec06e3144d55a03d125f3ce364eade3771f4f Cleaning up the missing resource stack spam, and condensing the information into a usefully understandable format.
	cpw: MinecraftForge/FML@0da1263ff9ede99267c03728a1c823b8056d5e44 Enhance error output for bad textures a bit more and try and capture more types of error..
	cpw:
		Fluids are now tracked internally by mod. This allows for the server and the world to specify a "default"
		in the case of a possible alternative fluid implementation. If you always called registerFluid, things
		should work pretty seamlessly, but if you didn't (gating with an isFluidRegistered check for example)
		you should change to register anyway. This way, even if you're not default in the overall instance, you may
		become default if you're the only mod present on a server, for example, or in a world save.
		
		This should radically decrease the mixups caused by mod load ordering problems, and other issues around fluid
		tracking.
	cpw: Fix NPE - Closes #1794
	cpw: And handle the null case in the constructor itself. Closes #1794 (again)
	cpw:
		MinecraftForge/FML@dfce4cd8d023a546c4c21405db182b8ddcd38633 Allow registering custom language adapters.
		MinecraftForge/FML@9fecd72cf0bd483ae7bc2ce821ae6b2f5e5b9c65 Some tidyup of the PR
		MinecraftForge/FML@10ac2a4fd972e923a60d23d10e8f297b8584f565 Fix itemCtorArgs javadoc in registerBlock
		MinecraftForge/FML@86f70d37a40bbeaf7c389a14adcd8311ba5584df Patch TracingPrintStream to handle Kotlin IO.
	kinglemming:
		Adjusts OreDictionary to prevent invalid registrations.
		Getting Ore Names for a non-existent ore will no longer automatically add that Name to the list nor generate an ID.
		
		Tweaks a warning message in the FluidContainerRegistry. No functionality change.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	LexManos:
		Revert KL's change, requesting a ore WILL register it.
		
		Registering like this and returning a new empty list allows for modders to register their recipes and such without requiring to be executed after someone actually adds an item. If handled properly this allows for more flexible load orders, and more responsive code.
	kinglemming:
		Adds some new Ore querying functionality.
		
		Also attempts to size initial Hashmaps in a logical manner.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	cpw:
		Fixed NBTSizeTracker missing a lot of data being read. Also made new NBT object allocation claim 32-bits in the size tracker.
		
		(cherry picked from commit de066a86da281d381b0e3ab9e83682720327049c)
		
		Conflicts:
			patches/minecraft/net/minecraft/nbt/CompressedStreamTools.java.patch
			patches/minecraft/net/minecraft/nbt/NBTTagList.java.patch
	cpw: Verify that the fluid registry doesn't contain "junk" fluids thru reflection.
	cpw: MinecraftForge/FML@8f9e3a7e30c8cc436dcb8d94b18b4634e0376339 Exceptions during construction phase should not propogate and cause an immediate crash. Closes #638
	cpw: Change logging to avoid the String.format bug. Closes #1809
	cpw: Actually use the override constraint in ticket requests. Closes #1802
	cpw:
		Reformat ItemArmor$ArmorMaterial.getBaseItem to use an if/then/else structure. The switch
		causes the generation of an internal class which may derp custom armor addition.
		Closes #1799
	cpw: Make FluidStack hold a delegate for the fluid. This can then float based on what is "live" at present.
	cpw: Fix static initializer derp.
	cpw: Replace the OLD fluid in the fluidID map, not the new one..
	cpw:
		Expose the fluid that a block was constructed with, useful for 'non-default'
		configuration of fluidblocks. Shouldn't be used outside of this purpose.
	cpw: MinecraftForge/FML@d14d1a8fea4c9242c944079ab8e4cdd516dfce4c Update to use the inherited jar format. Simplifies a lot..
	cpw:
		MinecraftForge/FML@a39482c4b7ac2883f821619b47ff31e0b6e74b29 Splash screen implementation
		MinecraftForge/FML@01fea095cdcd80c2ae9f0ebfd1c72242b3f2dbf8 Merge branch '1.7.10-load-progress' of github.com:RainWarrior/FML into 1.7.10
		MinecraftForge/FML@364b4bbbb0d4d168f9a63fa62a09e4e2fa213039 Call some loader stuffs
		MinecraftForge/FML@61a891280d15f9f17e28bf86a427f32de5a8983e Make sure to close the splash screen if there's gonna be an error display
	fry:
		MinecraftForge/FML@5785a9c9e8d76b91a03ed1f9791aeee1cb7ea00b Fix up multiple injections of cmdline files via versionspecificmoddir. Closes #645
		MinecraftForge/FML@bd117be9c3e3919f3c29538cde80e3eb8fa48368 Correctly track exceptions thrown in the loading screen rendering thread
	cpw:
		MinecraftForge/FML@36688e781aae67fb1e4e7047acf689edeeac7ddb Add in resource reloading to the bar. Tidy up some of the labels a bit.
		MinecraftForge/FML@a1dc465a55612ecdd44e6cde3adc0f1d53c6d97b More progress bar action!
		MinecraftForge/FML@bfcbf4ef4366fd3d8bfd20adafb63a857bb0dd53 More progress bar hooks
		MinecraftForge/FML@a6670c415ee97e771020921e00773c4c15e7512e Thread errors should be correctly displayed in the crash report now
		MinecraftForge/FML@9a16d26186d27029cae32a19c09ddf48f7cba22e fixed bar text positioning
		MinecraftForge/FML@0059c630281b7105c0532d2dba1bec27cf0323b2 Track mipmaps and texture upload
		MinecraftForge/FML@ef5f809752e87e369235e98a63027e9347185cd9 Fix broken log message in vanilla.
	cpw:
		MinecraftForge/FML@4fe7b469b5ba156d4a786cd9e105b18cca7c271a Loading screen: logo rotation is now optional; initial support for animated textures - animation rate is fixed for now.
		MinecraftForge/FML@31ae43590a2ba771d69b6c6513bcd5fe87ae8f8f Fix trying to close the screen during error.
	cpw: MinecraftForge/FML@94821fac98e64d9b8ad7434ed23a621850a8e11c Add a config file that lets you add additional soft dependencies at runtime - injectedDependencies.json
	cpw: MinecraftForge/FML@2ed00c4da0ee76eb15e28eb8ee2c07a3096155c2 Splash progress screen will not load in the presence of optifine anymore.
	cpw: MinecraftForge/FML@dda431353953457608c38aacb060ef82ddc88883 Revert "Merge pull request #650 from luacs1998/1.7.10" This undoes the seriously broken change from Sponge to support Mixins, that breaks a wide variety of coremods. Given the widespread incompatibility it introduces, it won't be re-added at 1.7.10.
	fry:
		Updated FML:
		MinecraftForge/FML@2ed00c4da0ee76eb15e28eb8ee2c07a3096155c2 Splash progress screen will not load in the presence of optifine anymore.
		MinecraftForge/FML@adcf2247c69f68415033a3c0b2c527053733514c Loading screen: moved config file to the standard config directory; added the option to load textures from the custom resource pack
		MinecraftForge/FML@91338433fa74e782e237643632de2cc5e17ee280 Add classloader exclusion for ASM
		MinecraftForge/FML@7c10b93a2ded2799d41b73b67a2766c31e992d8a Synchronize the available libraries. Turns out we've been forcing a newer apache commons-lang(3.2.1) for a long time, also sync the dev guava - we've been forcing 17 for a long time too. Bumping commons-lang to 3.3.2 since that's what Mojang are shipping with 1.8. It has no observable ill effects Closes MinecraftForge/FML#651
		MinecraftForge/FML@8ccfa24764a3f4854f5334c0da1224286175e13b Merge pull request MinecraftForge/FML#650 from luacs1998/1.7.10
		MinecraftForge/FML@b2650a0bdb7d69010a55de518e76591a6c417e87 Optifine can tell us when they're ready for the new splash screen.
		MinecraftForge/FML@02a5a58a1cbb25cd3baecf1535950e4780b7810f Fix the ordering of the messages, so they make sense now.
		MinecraftForge/FML@dda431353953457608c38aacb060ef82ddc88883 Revert "Merge pull request MinecraftForge/FML#650 from luacs1998/1.7.10" This undoes the seriously broken change from Sponge to support Mixins, that breaks a wide variety of coremods. Given the widespread incompatibility it introduces, it won't be re-added at 1.7.10.
		MinecraftForge/FML@5dbb481732bf4bcf8b0c5c02806051a933e6587e Eliminated texture name allocation race condition
		MinecraftForge/FML@450b82ca0e13cf889a42eeb198b67115a4851031 Updated default forge logo to animated gif; reverted config folder resolution to Minecraft class due to Loader not being initialized at the point it's needed
	cpw: MinecraftForge/FML@0b84b6aa297bdf6ab9f010e340f286442cb242dc Expose the state of the loader
	cpw:
		Attempt to fix the slow loading problem. Instead of forcing the main thread to wait around
		on every call to processWindowMessages, we will simply skip it, if the mutex is already
		claimed by the display thread. This should fix slow loading issues seen by some with
		the new loading screen.
	cpw: Hardcode the FML version in-game as a specific value.
	cpw: Strip control codes in progress bar messages. They cause crashes sometimes.
	cpw:
		Clean up transformers a bit. Can't use COMPUTE_FRAMES even though it's required - the game refuses to even
		run if I do. Note for j8: when we force Java8 classes, all coremods will need a thorough overhaul - the
		current way we do things is not sustainable when Java8 becomes the universal norm.
	cpw:
		Add in an ItemStackHolder - a way to inject ItemStacks without having to have complex lookup code everywhere.
		
		Example: https://gist.github.com/cpw/9af398451a20459ac263
	cpw: Bump minor version # to 2 because of the fluid changes (mirroring what happening in 1.7.10)

Build 1.7.10-10.13.3.1420-1.7.10:
	cpw:
		Add in an ItemStackHolder - a way to inject ItemStacks without having to have complex lookup code everywhere.
		
		Example: https://gist.github.com/cpw/9af398451a20459ac263

Build 1.8-11.14.1.1419:
	LexManos: Fixed damage reduction rate of vanilla armor incorrectly scaling with armor's current durability.

Build 1.8-11.14.1.1418:
	AlgorithmX2: Fix Partial Face Lighting on Top/Bottom Faces ; Vanilla MC-80148

Build 1.8-11.14.1.1417:
	LexManos: Force netty downgrade on dedicated server to match client. Netty bug: https://github.com/netty/netty/issues/2302 Closes #1848

Build 1.8-11.14.1.1416:
	LexManos: Fixed command exploit with C12

Build 1.8-11.14.1.1415:
	LexManos: Fixes  MC-75630 - Exploit with signs and command blocks

Build 1.8-11.14.1.1414:
	LexManos: Finish loading screen before going fullscreen. Closes MinecraftForge/FML#662

Build 1.8-11.14.1.1413:
	LexManos: Loosen up ServerChatEvent to support IChatComponent Closes #1893
	LexManos: Cleanup a lot of spammy output. Everything hidden behind environment flags now. Scale anvil image down 50%
	LexManos: Attempt to disable the new splash screen if there are errors detected finishing up. Print a slightly more helpful error message.

Build 1.8-11.14.1.1412:
	me: Add true support for unicode fonts

Build 1.8-11.14.1.1411:
	diesieben07: Fix crash when texture loading throws RuntimeException without message

Build 1.8-11.14.1.1410:
	xxt1g3lxx.xxt1g3lxx: Changed forge command tab completion to use getListOfStringsMatchingLastWord()

Build 1.8-11.14.1.1409:
	xxt1g3lxx.xxt1g3lxx: Added tab completion

Build 1.7.10-10.13.3.1408-1.7.10:
	cpw: Strip control codes in progress bar messages. They cause crashes sometimes.
	cpw:
		Clean up transformers a bit. Can't use COMPUTE_FRAMES even though it's required - the game refuses to even
		run if I do. Note for j8: when we force Java8 classes, all coremods will need a thorough overhaul - the
		current way we do things is not sustainable when Java8 becomes the universal norm.

Build 1.7.10-10.13.3.1407-1.7.10:
	cpw: Hardcode the FML version in-game as a specific value.

Build 1.7.10-10.13.3.1406-1.7.10:
	cpw: Merged FML into Forge's repo. FML is no longer developed seperatly.

Build 1.8-11.14.1.1405:
	cpw: Merged FML into Forge's repo. FML is no longer developed seperatly.

Build 1.8-11.14.1.1404:
	tmtravlrsmail:
		Initialized the Nether Fortress chest loot
		
		Forced the nether fortress chest loot to initialize in ChestGenHooks
		like the other types.
		
		Changed tabs to spaces. Silly Eclipse.

Build 1.7.10-10.13.3.1403-1.7.10:
	fry:
		Updated FML:
		MinecraftForge/FML@2ed00c4da0ee76eb15e28eb8ee2c07a3096155c2 Splash progress screen will not load in the presence of optifine anymore.
		MinecraftForge/FML@adcf2247c69f68415033a3c0b2c527053733514c Loading screen: moved config file to the standard config directory; added the option to load textures from the custom resource pack
		MinecraftForge/FML@91338433fa74e782e237643632de2cc5e17ee280 Add classloader exclusion for ASM
		MinecraftForge/FML@7c10b93a2ded2799d41b73b67a2766c31e992d8a Synchronize the available libraries. Turns out we've been forcing a newer apache commons-lang(3.2.1) for a long time, also sync the dev guava - we've been forcing 17 for a long time too. Bumping commons-lang to 3.3.2 since that's what Mojang are shipping with 1.8. It has no observable ill effects Closes MinecraftForge/FML#651
		MinecraftForge/FML@8ccfa24764a3f4854f5334c0da1224286175e13b Merge pull request MinecraftForge/FML#650 from luacs1998/1.7.10
		MinecraftForge/FML@b2650a0bdb7d69010a55de518e76591a6c417e87 Optifine can tell us when they're ready for the new splash screen.
		MinecraftForge/FML@02a5a58a1cbb25cd3baecf1535950e4780b7810f Fix the ordering of the messages, so they make sense now.
		MinecraftForge/FML@dda431353953457608c38aacb060ef82ddc88883 Revert "Merge pull request MinecraftForge/FML#650 from luacs1998/1.7.10" This undoes the seriously broken change from Sponge to support Mixins, that breaks a wide variety of coremods. Given the widespread incompatibility it introduces, it won't be re-added at 1.7.10.
		MinecraftForge/FML@5dbb481732bf4bcf8b0c5c02806051a933e6587e Eliminated texture name allocation race condition
		MinecraftForge/FML@450b82ca0e13cf889a42eeb198b67115a4851031 Updated default forge logo to animated gif; reverted config folder resolution to Minecraft class due to Loader not being initialized at the point it's needed
	cpw: MinecraftForge/FML@0b84b6aa297bdf6ab9f010e340f286442cb242dc Expose the state of the loader

Build 1.8-11.14.1.1402:
	silfadur: Added hook for  IPerspectiveAwareModel in RenderItem.renderItemIntoGUI for  ItemCameraTransforms.TransformType.GUI

Build 1.7.10-10.13.3.1401-1710ls:
	fry:
		Updated FML:
		MinecraftForge/FML@2ed00c4da0ee76eb15e28eb8ee2c07a3096155c2 Splash progress screen will not load in the presence of optifine anymore.
		MinecraftForge/FML@adcf2247c69f68415033a3c0b2c527053733514c Loading screen: moved config file to the standard config directory; added the option to load textures from the custom resource pack
		MinecraftForge/FML@91338433fa74e782e237643632de2cc5e17ee280 Add classloader exclusion for ASM
		MinecraftForge/FML@7c10b93a2ded2799d41b73b67a2766c31e992d8a Synchronize the available libraries. Turns out we've been forcing a newer apache commons-lang(3.2.1) for a long time, also sync the dev guava - we've been forcing 17 for a long time too. Bumping commons-lang to 3.3.2 since that's what Mojang are shipping with 1.8. It has no observable ill effects Closes MinecraftForge/FML#651
		MinecraftForge/FML@8ccfa24764a3f4854f5334c0da1224286175e13b Merge pull request MinecraftForge/FML#650 from luacs1998/1.7.10
		MinecraftForge/FML@b2650a0bdb7d69010a55de518e76591a6c417e87 Optifine can tell us when they're ready for the new splash screen.
		MinecraftForge/FML@02a5a58a1cbb25cd3baecf1535950e4780b7810f Fix the ordering of the messages, so they make sense now.
		MinecraftForge/FML@dda431353953457608c38aacb060ef82ddc88883 Revert "Merge pull request MinecraftForge/FML#650 from luacs1998/1.7.10" This undoes the seriously broken change from Sponge to support Mixins, that breaks a wide variety of coremods. Given the widespread incompatibility it introduces, it won't be re-added at 1.7.10.
		MinecraftForge/FML@5dbb481732bf4bcf8b0c5c02806051a933e6587e Eliminated texture name allocation race condition
		MinecraftForge/FML@450b82ca0e13cf889a42eeb198b67115a4851031 Updated default forge logo to animated gif; reverted config folder resolution to Minecraft class due to Loader not being initialized at the point it's needed

Build 1.7.10-10.13.3.1400-1.7.10:
	cpw: MinecraftForge/FML@dda431353953457608c38aacb060ef82ddc88883 Revert "Merge pull request #650 from luacs1998/1.7.10" This undoes the seriously broken change from Sponge to support Mixins, that breaks a wide variety of coremods. Given the widespread incompatibility it introduces, it won't be re-added at 1.7.10.

Build 1.7.10-10.13.3.1399-1.7.10:
	cpw:
		MinecraftForge/FML@a39482c4b7ac2883f821619b47ff31e0b6e74b29 Splash screen implementation
		MinecraftForge/FML@01fea095cdcd80c2ae9f0ebfd1c72242b3f2dbf8 Merge branch '1.7.10-load-progress' of github.com:RainWarrior/FML into 1.7.10
		MinecraftForge/FML@364b4bbbb0d4d168f9a63fa62a09e4e2fa213039 Call some loader stuffs
		MinecraftForge/FML@61a891280d15f9f17e28bf86a427f32de5a8983e Make sure to close the splash screen if there's gonna be an error display
	fry:
		MinecraftForge/FML@5785a9c9e8d76b91a03ed1f9791aeee1cb7ea00b Fix up multiple injections of cmdline files via versionspecificmoddir. Closes #645
		MinecraftForge/FML@bd117be9c3e3919f3c29538cde80e3eb8fa48368 Correctly track exceptions thrown in the loading screen rendering thread
	cpw:
		MinecraftForge/FML@36688e781aae67fb1e4e7047acf689edeeac7ddb Add in resource reloading to the bar. Tidy up some of the labels a bit.
		MinecraftForge/FML@a1dc465a55612ecdd44e6cde3adc0f1d53c6d97b More progress bar action!
		MinecraftForge/FML@bfcbf4ef4366fd3d8bfd20adafb63a857bb0dd53 More progress bar hooks
		MinecraftForge/FML@a6670c415ee97e771020921e00773c4c15e7512e Thread errors should be correctly displayed in the crash report now
		MinecraftForge/FML@9a16d26186d27029cae32a19c09ddf48f7cba22e fixed bar text positioning
		MinecraftForge/FML@0059c630281b7105c0532d2dba1bec27cf0323b2 Track mipmaps and texture upload
		MinecraftForge/FML@ef5f809752e87e369235e98a63027e9347185cd9 Fix broken log message in vanilla.
	cpw:
		MinecraftForge/FML@4fe7b469b5ba156d4a786cd9e105b18cca7c271a Loading screen: logo rotation is now optional; initial support for animated textures - animation rate is fixed for now.
		MinecraftForge/FML@31ae43590a2ba771d69b6c6513bcd5fe87ae8f8f Fix trying to close the screen during error.
	cpw: MinecraftForge/FML@94821fac98e64d9b8ad7434ed23a621850a8e11c Add a config file that lets you add additional soft dependencies at runtime - injectedDependencies.json
	cpw: MinecraftForge/FML@2ed00c4da0ee76eb15e28eb8ee2c07a3096155c2 Splash progress screen will not load in the presence of optifine anymore.

Build 1.8-11.14.1.1398:
	Zaggy1024: Fixed a bug which caused the light level not to update when a block implements Block.getLightValue(IBlockAccess, BlockPos) to change the light value for different block states.

Build 1.8-11.14.1.1397:
	Parker Young: Fixes MC-52974: Host's skin doesn't load in LAN

Build 1.8-11.14.1.1396:
	Zaggy1024: Removed @SideOnly(Side.CLIENT) from EnumWorldBlockLayer.

Build 1.7.10-10.13.3.1395-1710ls:
	cpw: MinecraftForge/FML@94821fac98e64d9b8ad7434ed23a621850a8e11c Add a config file that lets you add additional soft dependencies at runtime - injectedDependencies.json

Build 1.7.10-10.13.3.1394-1710ls:
	cpw:
		MinecraftForge/FML@4fe7b469b5ba156d4a786cd9e105b18cca7c271a Loading screen: logo rotation is now optional; initial support for animated textures - animation rate is fixed for now.
		MinecraftForge/FML@31ae43590a2ba771d69b6c6513bcd5fe87ae8f8f Fix trying to close the screen during error.

Build 1.7.10-10.13.3.1393-1710ls:
	cpw:
		MinecraftForge/FML@36688e781aae67fb1e4e7047acf689edeeac7ddb Add in resource reloading to the bar. Tidy up some of the labels a bit.
		MinecraftForge/FML@a1dc465a55612ecdd44e6cde3adc0f1d53c6d97b More progress bar action!
		MinecraftForge/FML@bfcbf4ef4366fd3d8bfd20adafb63a857bb0dd53 More progress bar hooks
		MinecraftForge/FML@a6670c415ee97e771020921e00773c4c15e7512e Thread errors should be correctly displayed in the crash report now
		MinecraftForge/FML@9a16d26186d27029cae32a19c09ddf48f7cba22e fixed bar text positioning
		MinecraftForge/FML@0059c630281b7105c0532d2dba1bec27cf0323b2 Track mipmaps and texture upload
		MinecraftForge/FML@ef5f809752e87e369235e98a63027e9347185cd9 Fix broken log message in vanilla.

Build 1.8-11.14.1.1392:
	LexManos: Cleanup RenderEntityItem patch, fixes Z-fighting issue in EntityItems. Closes #1824

Build 1.7.10-10.13.3.1391-1710ls:
	fry:
		MinecraftForge/FML@5785a9c9e8d76b91a03ed1f9791aeee1cb7ea00b Fix up multiple injections of cmdline files via versionspecificmoddir. Closes #645
		MinecraftForge/FML@bd117be9c3e3919f3c29538cde80e3eb8fa48368 Correctly track exceptions thrown in the loading screen rendering thread

Build 1.8-11.14.1.1390:
	jadran.kotnik:
		Extracted the creation of RegionRenderCache into a method.
		Classes extending RegionRenderCache can change the behavior of the cache, allowing to visually change blocks (schematics etc).

Build 1.7.10-10.13.3.1388-1.7.10:
	cpw: MinecraftForge/FML@d14d1a8fea4c9242c944079ab8e4cdd516dfce4c Update to use the inherited jar format. Simplifies a lot..

Build 1.7.10-10.13.3.1385-1.7.10:
	cpw:
		Expose the fluid that a block was constructed with, useful for 'non-default'
		configuration of fluidblocks. Shouldn't be used outside of this purpose.

Build 1.7.10-10.13.3.1384-1.7.10:
	cpw: Replace the OLD fluid in the fluidID map, not the new one..

Build 1.7.10-10.13.3.1383-1.7.10:
	cpw: Fix static initializer derp.

Build 1.7.10-10.13.3.1382-1.7.10:
	cpw: Make FluidStack hold a delegate for the fluid. This can then float based on what is "live" at present.

Build 1.7.10-10.13.3.1381-1.7.10:
	cpw:
		Reformat ItemArmor$ArmorMaterial.getBaseItem to use an if/then/else structure. The switch
		causes the generation of an internal class which may derp custom armor addition.
		Closes #1799

Build 1.7.10-10.13.3.1380-1.7.10:
	cpw: Actually use the override constraint in ticket requests. Closes #1802

Build 1.7.10-10.13.3.1379-1.7.10:
	cpw: Change logging to avoid the String.format bug. Closes #1809

Build 1.7.10-10.13.3.1378-1.7.10:
	cpw: MinecraftForge/FML@8f9e3a7e30c8cc436dcb8d94b18b4634e0376339 Exceptions during construction phase should not propogate and cause an immediate crash. Closes #638

Build 1.7.10-10.13.3.1377-1.7.10:
	cpw: Verify that the fluid registry doesn't contain "junk" fluids thru reflection.

Build 1.7.10-10.13.3.1376-1.7.10:
	cpw:
		Fixed NBTSizeTracker missing a lot of data being read. Also made new NBT object allocation claim 32-bits in the size tracker.
		
		(cherry picked from commit de066a86da281d381b0e3ab9e83682720327049c)
		
		Conflicts:
			patches/minecraft/net/minecraft/nbt/CompressedStreamTools.java.patch
			patches/minecraft/net/minecraft/nbt/NBTTagList.java.patch

Build 1.8-11.14.1.1375:
	LexManos: Fixed NBTSizeTracker missing a lot of data being read. Also made new NBT object allocation claim 32-bits in the size tracker.

Build 1.7.10-10.13.3.1374-1.7.10:
	kinglemming:
		Adds some new Ore querying functionality.
		
		Also attempts to size initial Hashmaps in a logical manner.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>

Build 1.7.10-10.13.3.1373-1.7.10:
	LexManos:
		Revert KL's change, requesting a ore WILL register it.
		
		Registering like this and returning a new empty list allows for modders to register their recipes and such without requiring to be executed after someone actually adds an item. If handled properly this allows for more flexible load orders, and more responsive code.

Build 1.7.10-10.13.3.1372-1.7.10:
	kinglemming:
		Adjusts OreDictionary to prevent invalid registrations.
		Getting Ore Names for a non-existent ore will no longer automatically add that Name to the list nor generate an ID.
		
		Tweaks a warning message in the FluidContainerRegistry. No functionality change.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>

Build 1.8-11.14.1.1371:
	cpw:
		MinecraftForge/FML@888e489394e52abdfb349fbfbd7f8e153b5af124 Allow registering custom language adapters.
		MinecraftForge/FML@906f94ca143f756f40404fde38af32b2481d0673 Some tidyup of the PR
		MinecraftForge/FML@1c025f18433df868859022eea8e6d198444736de Patch TracingPrintStream to handle Kotlin IO.

Build 1.7.10-10.13.3.1370-1.7.10:
	cpw:
		MinecraftForge/FML@dfce4cd8d023a546c4c21405db182b8ddcd38633 Allow registering custom language adapters.
		MinecraftForge/FML@9fecd72cf0bd483ae7bc2ce821ae6b2f5e5b9c65 Some tidyup of the PR
		MinecraftForge/FML@10ac2a4fd972e923a60d23d10e8f297b8584f565 Fix itemCtorArgs javadoc in registerBlock
		MinecraftForge/FML@86f70d37a40bbeaf7c389a14adcd8311ba5584df Patch TracingPrintStream to handle Kotlin IO.

Build 1.7.10-10.13.3.1369-1.7.10:
	cpw: And handle the null case in the constructor itself. Closes #1794 (again)

Build 1.7.10-10.13.3.1368-1.7.10:
	cpw: Fix NPE - Closes #1794

Build 1.7.10-10.13.3.1367-1.7.10:
	cpw:
		Fluids are now tracked internally by mod. This allows for the server and the world to specify a "default"
		in the case of a possible alternative fluid implementation. If you always called registerFluid, things
		should work pretty seamlessly, but if you didn't (gating with an isFluidRegistered check for example)
		you should change to register anyway. This way, even if you're not default in the overall instance, you may
		become default if you're the only mod present on a server, for example, or in a world save.
		
		This should radically decrease the mixups caused by mod load ordering problems, and other issues around fluid
		tracking.

Build 1.7.10-10.13.3.1366-1.7.10:
	cpw: MinecraftForge/FML@0da1263ff9ede99267c03728a1c823b8056d5e44 Enhance error output for bad textures a bit more and try and capture more types of error..

Build 1.7.10-10.13.3.1365-1.7.10:
	cpw: MinecraftForge/FML@be5ec06e3144d55a03d125f3ce364eade3771f4f Cleaning up the missing resource stack spam, and condensing the information into a usefully understandable format.

Build 1.7.10-10.13.3.1364-1.7.10:
	cpw:
		MinecraftForge/FML@ce791cb1f2cf983ef77b1e5c4028ddefab394062 Rework EventSubscriptionTransformer to bake @Cancelable and @HasResult values, should increase EventBus performance even more by removing logic from Event constructors.
		MinecraftForge/FML@852710962a9b6d7c8e2ca188c715eebb2da44c2a Clean up some dead code

Build 1.7.10-10.13.3.1363-1.7.10:
	kinglemming:
		Adds a warning to the FluidContainerRegistry when a mod does something stupid! Also denies the registration.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>

Build 1.7.10-10.13.3.1362-1.7.10:
	kinglemming:
		Fixes FluidContainerRegistry properly - no more corner case where client/server mods disagree.
		
		Also clarifies the 2x Fluid registration error message somewhat.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>

Build 1.8-11.14.1.1361:
	LexManos: MinecraftForge/FML@4a753227adb805d29f3bf245c3f8427193c35544 Rework EventSubscriptionTransformer to bake @Cancelable and @HasResult values, should increase EventBus performance even more by removing logic from Event constructors.

Build 1.7.10-10.13.3.1360-1.7.10:
	kinglemming:
		Fixes #1782
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>

Build 1.8-11.14.1.1359:
	Abrar Syed: changed run configs to GradleStarts

Build 1.7.10-10.13.3.1358-1.7.10:
	me:
		Fix FluidRegsitry.registerFluid
		
		FluidRegistry:
		```java
		    static BiMap<String, Fluid> fluids = HashBiMap.create();
		    static BiMap<Fluid, Integer> fluidIDs = HashBiMap.create();
		...
		    public static boolean registerFluid(Fluid fluid)
		    {
		        if (fluidIDs.containsKey(fluid.getName()))
		            ^^^^^^^
		```
		There is definitely should be fluids instead fluidIDs. This mistake broke many mods.

Build 1.8-11.14.1.1357:
	LexManos:
		Updated FML:
		MinecraftForge/FML@c8160311d580f2dfccdf796a5243e16844787cb6 Stop IllegalFormatConversionException thrown if @Mod has flagged client-only or server-only
		MinecraftForge/FML@9a894952afb526436649f608f7af5992b97f044c Merge pull request #627 from GotoLink/patch-1
		MinecraftForge/FML@40faac64520d1a197f08eaa9a0f850e7df43359a Remove J7 only constructor in EnhancedRuntimeException, J6 compiling compatibility restored.

Build 1.7.10-10.13.3.1356-1.7.10:
	LexManos: MinecraftForge/FML@31cf2a9cab6d1977d31436220d9612eaa13d4e0f Remove J7 only constructor in EnhancedRuntimeException, J6 compiling compatibility restored.
	LexManos: Restore binary compatibility issues in FluidRegistry caused by recent changes.

Build 1.7.10-10.13.3.1355-1.7.10:
	cpw:
		Removed fluidID from ItemStack.
		
		This fixes a rather huge issue where FluidStacks on the client could be desynced if a modder was unaware of it.
		
		This is a breaking change but can be mitigated with a transformer to the getter getFluidID().
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	cpw: Add in a fluidid transformer
	cpw: Fix formatting
	cpw:
		Allow for duplicate Fluid Blocks. It's annoying to be sure but just as with the OreDictionary, we'll have to handle it.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	cpw:
		You shouldn't be creating FluidStacks from unregistered Fluids. Warn clearly on failed registrations, and make a useful log message for failed fluidstack
		creations. Should help a lot with tracking down broken mods that are doing this wrongly.

Build 1.8-11.14.1.1354:
	ohai.iChun: Readded but deprecated the old RenderPlayerEvent that were deleted. Sorry, Lex.

Build 1.8-11.14.1.1353:
	ohai.iChun:
		Reimplement RenderPlayerEvent that was removed in the port to 1.8 from 1.7.10.
		RenderPlayerEvent.Specials was removed because the special effects are done in the LayerRenderer now.

Build 1.7.10-10.13.2.1352-1.7.10:
	cpw:
		Forge really should have always supported the concept of an "exact spawn". Individual world providers can still
		change this behaviour of course, but for default maps it makes sense to support it as a config option.

Build 1.7.10-10.13.2.1351-1.7.10:
	cpw:
		MinecraftForge/FML@12ccf9cf49b76140841cdc5a459422ae4781de1a Rather than try to fall back to the backup level.dat in case of weirdness in the ID map, just fail hard. There is probably a serious modder derp in this case and there's nothing FML can do to recover the situation except avoid making it worse.
		MinecraftForge/FML@e8cd368da30661ed2898fff232e2db787edcbdcc It's an IllegalState not an IllegalArgument *sigh*
		MinecraftForge/FML@2be9c743424c92f8799a6af1d59d60edd65e6bf0 And fix itemblocks being removed, leaving behind a residual block. This is a legitimate action - use the missing mapping event to let the mod tell us about it
		MinecraftForge/FML@7d8804cf656081d1570068f52e9bfc7140b21a65 You can't setAction to BLOCKONLY
		MinecraftForge/FML@c73861efe67594ee9995bc93744cab06bd6647d1 Cherry-pick 01aaa7dc97480b381ca0d192ec65016d7baeb747 Fix mods defined via --mods or --modListFile launch args not being searched for coremods. #560
		MinecraftForge/FML@94c45b48c1265e7c4f60f591d413fa545787d354 Fix json cache crash, handle the file much more cleanly. Probably an MC JIRA since it's a vanilla bug. Closes #619

Build 1.8-11.14.1.1350:
	LexManos:
		Updated FML:
		MinecraftForge/FML@1de3bf733aef754f15de55006b1750376871feb0 Fix FML's package for net.miencraftforge on maven. Fixes uploading of new builds. Note: 1.7.10 builds are bug fixes only while FML/Forge for 1.8 stabelizes.
		MinecraftForge/FML@05ecefb53857ecc1dc52d4a577ed593c26da9659 Update to ASM5 for Java 8 support
		MinecraftForge/FML@1112c455b9758c38eab385f48578bad17c0180f9 Merge pull request #595 from Grinch/master
	LexManos: Fixed potential NPEs in Structure code caused by componenets not being able to load.
	cpw:
		MinecraftForge/FML@6b0ae369eb9b8cf89eb9d53fe997a6e5ef222093 Try and improve performance of the registry by avoiding superType.cast.
		MinecraftForge/FML@dfebcafd49550b8c3f90c6c028ef0d7f3a13e607 Something I meant to add a long time ago, but it got overlooked. My apologies. Presend the (int) dimension ID in the serverhello packet. This should be 100% backward compatible with existing servers but bumping a server to this version will allow clients with this version as well to now login in dimensions outside the byte range. Probably fixes a bunch of mods that add dimensions.
		MinecraftForge/FML@6011419fa055c1375d05189f9bf0d86705c9c0ec Clean up my patch. Terrible person I am..
		MinecraftForge/FML@c6bbd0e82de3d8f7993d70aa7be3f883b3afbc47 Forgot that I need a noarg ctor. I'm so rusty.
		MinecraftForge/FML@6edc1635de163c41b6b5dfe02bee13d6a9c5aa4d Need to load the dimension from disk - do it without filling out the player so that the normal player loading (including events) works properly
	cpw:
		MinecraftForge/FML@4ca6f6e19f3c3147fcf48c58669f55478a9a1345 What a dumb oversight. One needs to copy the active substitution set to the active gamedata. Doesn't work well otherwise.
		MinecraftForge/FML@6f6cec96be73b4c94999cf60dc00741f3f3c2cc2 Substitutions need to be activated when they're registered, otherwise they won't appear in world, ever.
		MinecraftForge/FML@13ac015f0c36b8e2091ae332c556be315429f4c8 Change iterator behaviour for the registry - include substitutions in the standard iterator, so that vanilla MC methods visit them (so they can get textures etc). The fml special one only visits the absolute set, used mostly for sanity checking and serialization.
	LexManos:
		MinecraftForge/FML@24cb4a42c4e4bddde95c0e49d1f8b8bcc20c626d Enhance output of common FML errors in crash reports and server GUI.
		Force load anonymous minecraft classes used in crash reports. This prevents some crashes being hiddedn behind class definiton exceptions.
	cpw: Experimental "fix" for the weird rendering in the Acheivements screen. Thanks skyboy for spotting this.
	cpw:
		Comment on previous commit fix - it worked. Thanks to skyboy and tterrag for investigating and verifying.
		A chest as an acheivement icon will recreate the original problem, for note.
	cpw:
		Update FML - merge the 1.7.10 changes in to forge @ 1.8. Wow git is (sorta) AWESOME!
		
		MinecraftForge/FML@6b0ae369eb9b8cf89eb9d53fe997a6e5ef222093 Try and improve performance of the registry by avoiding superType.cast.
		MinecraftForge/FML@dfebcafd49550b8c3f90c6c028ef0d7f3a13e607 Something I meant to add a long time ago, but it got overlooked. My apologies. Presend the (int) dimension ID in the serverhello packet. This should be 100% backward compatible with existing servers but bumping a server to this version will allow clients with this version as well to now login in dimensions outside the byte range. Probably fixes a bunch of mods that add dimensions.
		MinecraftForge/FML@6011419fa055c1375d05189f9bf0d86705c9c0ec Clean up my patch. Terrible person I am..
		MinecraftForge/FML@c6bbd0e82de3d8f7993d70aa7be3f883b3afbc47 Forgot that I need a noarg ctor. I'm so rusty.
		MinecraftForge/FML@6edc1635de163c41b6b5dfe02bee13d6a9c5aa4d Need to load the dimension from disk - do it without filling out the player so that the normal player loading (including events) works properly
		MinecraftForge/FML@4ca6f6e19f3c3147fcf48c58669f55478a9a1345 What a dumb oversight. One needs to copy the active substitution set to the active gamedata. Doesn't work well otherwise.
		MinecraftForge/FML@6f6cec96be73b4c94999cf60dc00741f3f3c2cc2 Substitutions need to be activated when they're registered, otherwise they won't appear in world, ever.
		MinecraftForge/FML@13ac015f0c36b8e2091ae332c556be315429f4c8 Change iterator behaviour for the registry - include substitutions in the standard iterator, so that vanilla MC methods visit them (so they can get textures etc). The fml special one only visits the absolute set, used mostly for sanity checking and serialization.
		MinecraftForge/FML@24cb4a42c4e4bddde95c0e49d1f8b8bcc20c626d Enhance output of common FML errors in crash reports and server GUI.
		MinecraftForge/FML@12ccf9cf49b76140841cdc5a459422ae4781de1a Rather than try to fall back to the backup level.dat in case of weirdness in the ID map, just fail hard. There is probably a serious modder derp in this case and there's nothing FML can do to recover the situation except avoid making it worse.
		MinecraftForge/FML@e8cd368da30661ed2898fff232e2db787edcbdcc It's an IllegalState not an IllegalArgument *sigh*
		MinecraftForge/FML@2be9c743424c92f8799a6af1d59d60edd65e6bf0 And fix itemblocks being removed, leaving behind a residual block. This is a legitimate action - use the missing mapping event to let the mod tell us about it
		MinecraftForge/FML@7d8804cf656081d1570068f52e9bfc7140b21a65 You can't setAction to BLOCKONLY
		MinecraftForge/FML@13df640d9d4516219b07778edd76efd2643019f6 Pull in a lot of the FML tweaks from 1.7 to 1.8
		MinecraftForge/FML@447beaa99ec828fb83796185d07c72ea28b056c9 Merge remote-tracking branch 'origin/1.7.10'

Build 1.8-11.14.1.1349:
	cpw:
		MinecraftForge/FML@2afd55ab825fad3b07073c474cdb96b348701084 Fix scala mods, Closes #621
		MinecraftForge/FML@c541b08ef68161f437eeb7b22eabe27b20eebf55 Merge pull request #622 from diesieben07/scala-fix
		MinecraftForge/FML@d5021417dd10f36dc3d1b68e4975eb91f7f46e68 Forgot the register handling bit. Registration should work now..
		MinecraftForge/FML@5a65c6568699acaade8243040d8552b1f2e2e28f OK, this is finally actually working, I think...

Build 1.8-11.14.1.1348:
	fry: Fixed mipmapping not being enabled by expanding 1x1 texture

Build 1.7.10-10.13.2.1347-1.7.10:
	cpw:
		Comment on previous commit fix - it worked. Thanks to skyboy and tterrag for investigating and verifying.
		A chest as an acheivement icon will recreate the original problem, for note.

Build 1.7.10-10.13.2.1346-1.7.10:
	cpw: Experimental "fix" for the weird rendering in the Acheivements screen. Thanks skyboy for spotting this.

Build 1.8-11.14.1.1344:
	LexManos:
		Updated FML:
		MinecraftForge/FML@2a268cd5664b6562a4bf2a953a6a93fd8e111bd2 Improve mod list GUI, add sort and search
		MinecraftForge/FML@951fc2d9fd7e7970c86accb1be095a24f7bfaf18 First attempt at making FMLControlledRegistry something a bit more generic than just blocks/items.
		MinecraftForge/FML@410582222d9ba15d42dc47db0d3d6a84aeac2d22 Merge pull request #614 from tterrag1098/betterModList
		MinecraftForge/FML@ba0b176430cdbc3573643a6e21d47013cfd1f0e0 Fix ModDiscoverer ignoring inner classes.
		MinecraftForge/FML@9cc313eab9939724786f833f511a87c9957dbc72 Merge pull request #617 from diesieben07/innerclass-disc
		MinecraftForge/FML@01aaa7dc97480b381ca0d192ec65016d7baeb747 Fix mods defined via --mods or --modListFile launch args not being searched for coremods. #560
		MinecraftForge/FML@8cecc47b85db68e8e69f45641b1d843509dbe71d Merge pull request #620 from killjoy1221/extra-coremod-fix
		MinecraftForge/FML@38d9a5f444815810dec3607f5b3b7ff1ac513d4c Enhance output of common FML errors in crash reports and server
		
		Force load anonymous minecraft classes used in crash reports. This prevents some crashes being hiddedn behind class definiton exceptions.GUI.

Build 1.7.10-10.13.2.1343-1.7.10:
	LexManos:
		MinecraftForge/FML@24cb4a42c4e4bddde95c0e49d1f8b8bcc20c626d Enhance output of common FML errors in crash reports and server GUI.
		Force load anonymous minecraft classes used in crash reports. This prevents some crashes being hiddedn behind class definiton exceptions.

Build 1.7.10-10.13.2.1342-1.7.10:
	cpw:
		MinecraftForge/FML@4ca6f6e19f3c3147fcf48c58669f55478a9a1345 What a dumb oversight. One needs to copy the active substitution set to the active gamedata. Doesn't work well otherwise.
		MinecraftForge/FML@6f6cec96be73b4c94999cf60dc00741f3f3c2cc2 Substitutions need to be activated when they're registered, otherwise they won't appear in world, ever.
		MinecraftForge/FML@13ac015f0c36b8e2091ae332c556be315429f4c8 Change iterator behaviour for the registry - include substitutions in the standard iterator, so that vanilla MC methods visit them (so they can get textures etc). The fml special one only visits the absolute set, used mostly for sanity checking and serialization.

Build 1.8-11.14.1.1341:
	simonbarnes1:
		Add getTileData() to TileEntity
		
		- The same idea as Entity.getEntityData()

Build 1.7.10-10.13.2.1340-1.7.10:
	cpw:
		MinecraftForge/FML@6b0ae369eb9b8cf89eb9d53fe997a6e5ef222093 Try and improve performance of the registry by avoiding superType.cast.
		MinecraftForge/FML@dfebcafd49550b8c3f90c6c028ef0d7f3a13e607 Something I meant to add a long time ago, but it got overlooked. My apologies. Presend the (int) dimension ID in the serverhello packet. This should be 100% backward compatible with existing servers but bumping a server to this version will allow clients with this version as well to now login in dimensions outside the byte range. Probably fixes a bunch of mods that add dimensions.
		MinecraftForge/FML@6011419fa055c1375d05189f9bf0d86705c9c0ec Clean up my patch. Terrible person I am..
		MinecraftForge/FML@c6bbd0e82de3d8f7993d70aa7be3f883b3afbc47 Forgot that I need a noarg ctor. I'm so rusty.
		MinecraftForge/FML@6edc1635de163c41b6b5dfe02bee13d6a9c5aa4d Need to load the dimension from disk - do it without filling out the player so that the normal player loading (including events) works properly

Build 1.8-11.14.1.1339:
	erlend: Added newVolume and newPitch to PlaySoundAtEntityEvent. Deprecated ForgeEventFactory.onPlaySoundAt, added replacement ForgeEventFactory.onPlaySoundAtEntity.

Build 1.8-11.14.1.1338:
	Geforce132: -Added EntityMountEvent.

Build 1.8-11.14.1.1337:
	diesieben07: Fix jukebox message being too low with forge

Build 1.8-11.14.1.1336:
	LexManos:
		Updated FML:
		MinecraftForge/FML@3e7ae47f8f5d642b256adbe8b3395bb40daf85da Fix Event Bus Access Issues
		MinecraftForge/FML@c8e2a5f377ddf8a35cceda6a14697dbe8cad4ca8 Fixed WorldInfo properties not loaded
		MinecraftForge/FML@7f96b2c69ab8a2ed07b5b786b3d679ea4c509121 Fix Debug packet logger on local memory connections.

Build 1.8-11.14.1.1335:
	robin: remove translation and add a note for contributors

Build 1.8-11.14.1.1334:
	erju01: Fixed enchanting table applying secondary enchs.

Build 1.8-11.14.1.1333:
	mnmiller1: Add NeighborNotiftyEvent.

Build 1.8-11.14.1.1332:
	tmtravlrsmail:
		Added Nether Fortress chest to the ChestGenHooks
		
		I tried to follow the directions on
		
		https://github.com/MinecraftForge/MinecraftForge/wiki/If-you-want-to-contribute-to-Forge
		
		as best as I could. =)
		
		If anything is wrong, let me know and I'll change it!
	clienthax:
		Current spawner implementation checks the EntitySpawnPlacementRegistry hashmap to check where a entity should spawn
		as there is no way to modify this without the use of reflection or a AT, you can not specify where you want your entity to spawn
		adding this helper method will allow developers to specify where they want their entity to spawn.
		
		Signed-off-by: Clienthax <clienthax@gmail.com>
		
		Update EntitySpawnPlacementRegistry.java.patch
	LexManos: Fix compile error in ClientHax's PR.

Build 1.8-11.14.1.1329:
	fry: Hopefully fix NPE during baking of empty vanilla item models

Build 1.8-11.14.1.1328:
	LexManos: Fire WorldEvent.Load for Client worlds. Closes #1719

Build 1.8-11.14.1.1327:
	LexManos: Make Container.mergeItemStack respect Slot.isValidItem Closes #1630

Build 1.8-11.14.1.1326:
	LexManos: Fix JukeBoxes not storing the inserted record. All TE's in minecraft are in net.minecraft.tileentity EXCEPT JukeBoxes. Closes #1633 Closes #1714

Build 1.8-11.14.1.1325:
	LexManos: Fix NPEs in last commit.

Build 1.8-11.14.1.1324:
	LexManos:
		Updated FML:
		MinecraftForge/FML@c9cf3136c265b2e8e46eab102b2310a9312b8cfb New @Mod properties to define which environment to load the mod on.
		clientSideOnly will only be loaded in the Client environment.
		serverSideOnly will only be loaded in the Dedicated server environment.
		Combine with acceptedMinecraftVersions to prevent users from loading the mod in the incorrect environment.

Build 1.8-11.14.1.1323:
	LexManos:
		Updated FML:
		MinecraftForge/FML@5eff40897545c9e6f597a202bc9e86c3b07761ad Filter more known libraries from potential mod canidates.
		MinecraftForge/FML@feb4c436db27a249dd5190023edd38cb5884e90b Quiet ClassPatchManager debug spam by default. Reenable using -Dfml.debugClassPatchManager=true.
		MinecraftForge/FML@41e806fa950839bf901ebf9c18d0c632a7c5538c Fix double decoding of UTF8 characters in lang files.

Build 1.8-11.14.1.1322:
	LexManos: Fixed using items on the wrong block client side caused by iChuns eyeheight update.

Build 1.8-11.14.1.1321:
	ohai.iChun: Reimplement variable eyeHeight for players which was removed in the 1.7 to 1.8 port.

Build 1.8-11.14.1.1320:
	fry: Removed event bus call from the ModelLoader

Build 1.8-11.14.1.1319:
	matthewprenger: Add the ability to add prefixes and suffixes to the player's display name.
	LexManos: Add safty to URL detection in chat. Closes #1712

Build 1.8-11.14.1.1318:
	fry: Added a default white texture; Fixed B3DLoader crashing when the brush has empty texture specified
	fry: RenderItem can now use baked quad color

Build 1.8-11.14.1.1317:
	Parker Young:
		Added ATs for EnumFacing
		
		This publics the VALUES array and HORIZONTALS array in EnumFacing, thus giving modders access to these arrays, much like ForgeDirection had.

Build 1.8-11.14.1.1316:
	fry: Attributes.put (de)normalization now works as intended

Build 1.8-11.14.1.1315:
	LexManos: Hold a weak reference to the Minecraft fake player object. Closes #1705

Build 1.8-11.14.1.1314:
	matthewprenger: Minor tweak to UsernameCache to also cache usernames of offline players.

Build 1.8-11.14.1.1313:
	fry: Updated FML

Build 1.8-11.14.1.1312:
	fry: ModelRotation.getMatrix() now returns the correct matrix; fixed the application of custom transformations to vanilla models; fixed application of transformations to B3D models; fixed the culling of rotated vanilla models

Build 1.8-11.14.1.1311:
	fry: Alternative models work once again

Build 1.8-11.14.1.1310:
	fry: Updated FML

Build 1.8-11.14.1.1309:
	fry: fix ModelLoader.setCustomModelResourceLocation not storing same item with different metadata values

Build 1.8-11.14.1.1308:
	LexManos: Fixed debugging Dedicated server in Forge Dev workspace.
	LexManos: Fixed being kicked from the server while swimming.
	fry:
		fixed NPE during loading of B3D models without textures/brushes.
		changed default B3D color to have full opacity.
	fry: Reworked vanilla texture resolution, hopefully fixes NPE bug in FaceBakery
	fry: made renderLayer ThreadLocal, now it should hold correct value for use inside custom baked models
	LexManos: Try a maven mirrior to fix build issues.

Build 1.7.10-10.13.2.1307-1.7.10:
	LexManos: Fixed potential NPEs in Structure code caused by componenets not being able to load.

Build 1.8-11.14.1.1306:
	LexManos: Fixed potential NPEs in Structure code caused by componenets not being able to load. Closes #1686

Build 1.8-11.14.1.1305:
	LexManos: Fixed InitMapGenEvent's fire order so values are used. And added OCEAN_MONUMENT type. Closes #1681
	LexManos: Fixed BlockBush and BlockCrops not respecting custom soils. Closes #1683

Build 1.8-11.14.1.1303:
	fry: Restore binary backwards compatibility

Build 1.8-11.14.1.1302:
	fry: ModelBakeEvent now has ModelLoader as an argument instead of ModelBakery; Added various static hooks to ModelLoader to allow registering model-related information before it's needed (prevents file-not-found errors on first baking pass); ModelLoader waits until ModelBakeEvent is done before showing any missing model exceptions; It's now possible to define models completely in-code (as illustrated by ModelBakeEventDebug).

Build 1.8-11.14.1.1301:
	LexManos: Bump version to 11.14.1 for next development cycle.

Build 1.8-11.14.0.1299:
	fry: Fixed tracking of UV locking state. Closes #1679

Build 1.8-11.14.0.1298:
	LexManos: Fixed ItemFrames not having a model. Closes #1678
	LexManos: Updated FML: MinecraftForge/FML@22c9656196dbbea8ed983663d536c3ca272d7282 Reset S->C CustomPayload data after Write, allowing the same packet to be written multiple times.

Build 1.8-11.14.0.1297:
	LexManos: Fixed domain support in ArmorMaterial texture name. Closes #1675
	LexManos: Fixed Buttons not dropping anything when broken. Closes #1676

Build 1.8-11.14.0.1296:
	LexManos:
		Initial update to 1.8, Super beta. Most rendering related hooks are out due to major changes in 1.8.
		
		Some notes:
		Almost all int x, int y, int z parameters have been changed to BlockPos class
		ForgeDirection has been removed, replaced by net.minecraft.util.EnumFacing.
		All FML classes have moved from packet cpw.mods.fml to net.minecraftforge.fml
		Fluid Rendering has been disabled for the time being, to be re-evaulated and a test mod created for it.
		Minecraft now uses a Model based system for rendering blocks and Items. The intention is to expand the model format to better suit modder's needed once it is evaulated.
		As such, The model loaders from Forge have been removed, to be replaced by expanding vanilla's model format.
		Metadata has been extracted out in Minecraft to IBlockState, which holds a list of properties instead of magic number metadata. DO NOT listen to the fearmongering, you can do EVERYTHING with block states you could previously with metadata.
		Stencil Bits are disabled entirely by for the main Display, Modders must enable and recreate the FrameBuffer if they wish to use Stencil Bits.
	LexManos: Fix local variable conflict in Forge patch and latest MCP mappings.
	LexManos: Fix fog colors, Closes #1524
	LexManos: Fix acedential inversion causing some tress to not have leaves. Closes #1522
	LexManos: Fix creative picking a CommandBlock minecart returning wrong item. Closes #1523
	LexManos: Fixed crash with caomparators due to wrong position. Closes #1512
	LexManos: Fix inverted logic preventing blocks from breaking.
	LexManos: Fix Entityies not taking damage correctly. Closes #1511
	LexManos: Fix wrong state being passed to Block.getDrops
	LexManos: Fix potential NPE in Block.isToolEffective
	LexManos: Update RecipeSorter for new 1.8 recipies.
	LexManos: Fix destroy particles not being added. Closes #1528
	LexManos: Fix debug screen not showing grey background. Closes #1529
	LexManos: Fix not being able to place blocks in liquids, and related issues.
	LexManos:
		Updated FML:
		MinecraftForge/FML@36644e97714b46dbbb24416febdde1332a3e753c Finalize modded handshakes in the World tick thread. Prevents potential CMEs when login event takes to long to fire.
	LexManos: Fix interacting with entities.
	LexManos: Fixed Entity extended properties init order. Closes #1532
	LexManos: Fixed Entities not being able to climb ladders, Closes #1535
	LexManos: Fixed snow layers not being able to stack more then twice. Closes #1534
	LexManos: Fix BlockPane's connection detection.
	LexManos: Fixed vanilla bug where top part of double plants would flicker a tifferent texture before dissapearing.
	LexManos: Fix NPE with BlockSnapshots that caused items with TileEntities to be used up in creative mode.
	LexManos: Fixed vanilla issue where exceptions in World tasks would not be logged.
	LexManos: Fixed blocks not breaking properly when instantly destroied.
	LexManos: Fix stickey pistons not retracting properly.
	LexManos:
		Updated FML:
		MinecraftForge/FML@9c8ca4a4e3c4acc4980535e5c60da169b75a7810 Unlink banner block and item id. Mojang should of matched these up but they didn't -.-
		MinecraftForge/FML@84a101f344b8fc21de1201fde717fbcbcba2aa79 Update Dev mcp mappings to 11-30 snapshot.
	LexManos: Remove debug patch I left in.
	LexManos: Fix finding of spawn location for mobs. Closes #1546
	LexManos: Only call blockBreak when block itself changes, not just meta. Fixes bottles poping out of brewing stands.
	fry: Added model bake event (allows mods to insert custom baked models, much like TextureStitchEvent allows to load custom textures), ISmartBlock/ItemModel (ability form models to react to block/item states), Block.getExtendedState, support for unlisted properties in block states. Includes example implementation of http://imgur.com/a/FyyJX
	LexManos: Added Explosion Start and Detonate events to control explosion.
	LexManos: Fixed bug in ServerConfigurationManager.transferPlayerToDimension where it would send the old dimension's information.
	LexManos: Add "sand" to the OreDictionary
	LexManos: Cleanup deprecated code, and TODOs in OreDictionary. Down-typed things from ArrayList to List. Asking for the ores with a null stack will now throw an Exception.
	LexManos: Added CreateSpawnPosition event.
	LexManos: Add LivingHealEvent called from EntityLivingBase.heal()
	LexManos: Added PotionBrewEvent.Pre/Post. To allow for modification and cancelation of Brewing.
	LexManos: Add quartz_ore tool init, more mojang special casing -.-
	LexManos: Changed ToolMaterial's repair material to ItemStack version to allow metadata sensitive versions.
	LexManos: Improved Control of Enchantment.canApplyTogether() in Mod Enchantments, allowing both enchantments to determine if they can apply together.
	LexManos: Expand PlayerWakupEvent to expose the three parameters passed into EntityPlayer.wakeUp.
	LexManos: Unbind Shaped/Shapeless Ore Recipies from Array list to normal List.
	LexManos: Fixed NPE thrown when brewing event is fired and not all slots are filled. Closes #1564
	LexManos: Make daylight sensor recipe use ore dictionary wooden slabs Closes #1565
	LexManos: Fix missed patch causing Dispensed Armor to go into the wrong slot. Closes #1560
	LexManos: Fixed log spam when breaking DoublePlants. Closes #1555
	LexManos: Fix texture stitcher not using all avalible spaces.
	LexManos: Fix EnumHelper for new ArmorTexture argument.
	LexManos: Untie ItemModelMesher from using Item Ids internally by implementing our own simple mechanics using Trove.
	LexManos: Fix userdev for new BlockState change.
	LexManos: MinecraftForge/FML@e3785c28930a218cf9374458c67c34e7fba17922 Ensure that EntitySpawn and OpenGUI packets are handled in the world thread. Also log all errors that are thrown in FutureTasks.
	LexManos: Remove our changes to Stitcher slot allocation.
	LexManos: Fix incorrect logic in world change clumping.
	LexManos: MinecraftForge/FML@5a4d362293fe70e1421d1f22c4a195944731d6ba Finish removing marker in mapping entry names. FMLMissingMappingsEvent/FMLModIdMappingEvent should fire with correct names now.
	jadran.kotnik: Fixed messages not being added to the chat history and ClientCommandHandler not being called when sleeping.
	LexManos: Fix BlockSnapshots not firing correctly due to patch mixup in 1.8 update. Closes #1591
	palechip: Fix Scoreboard rendering for the sidebar.
	LexManos: Removed exclusion of white stained glass recipes in ore dictionary.
	LexManos: Added chests to the ore dictionary.
	LexManos: Fix crafting of non-oak fences/gates.
	LexManos: Fix MC-30864 (sending web links in chat)
	LexManos: Fix recipies for stone variants.
	Chicken-Bones: Allow blocks to render in multiple layers
	lumien231: Fixes #1603: Moving the start of the update thread to the pre init of the forge mod container
	LexManos: Fix potential NPE when loading a single player world where you were saved in a unloaded dimension. Closes #1575
	LexManos: Call World.init from DimensionManager.initDimension Closes #1551
	LexManos: Made Chunk.fillBlock respect TileEntity.shouldRefresh.
	LexManos: Fix value passed for Item.getModel useRemaining argument. Closes #1623
	LexManos: Silently eat exceptions when getting a TE's rendering bounding box, this 'fixes' Bukkit servers screwing up world data and causing clients to crash.
	jadran.kotnik: Fixed NPE when canceling ClientChatRecievedEvent. Fixes #1644
	Parker Young: Re-enabled Icon setting for Fluids
	LexManos:
		Updated FML:
		MinecraftForge/FML@a55e4124531119f1c9c023cff74cfa09b49ef0e0 Save the mod list of players in their NetworkDispatcher (Make it accessable for mods)
		MinecraftForge/FML@69d479d46ae658c5a5c2c00081be3df38e38c748 Fixed getEffectiveSide() for Netty Server threads
		MinecraftForge/FML@0f9a33cf14165ddd424a7d82c2178cf5854bf32f Exclude only log4j2 queue from class loader
	jadran.kotnik: Don't skip the first line when rendering (debug) text.
	fry:
		Added model loader registry
		
		Entry point: ModelLoaderRegistry
		loader interface: ICustomModelLoader
		custom model: IModel
		
		ModelLoader is responsible for splicing into vanilla model system.
		(you probably don't need to use it directly)
		
		Interop with vanilla models isn't great yet
		(vanilla models can't refer to custom ones as parents), will improve in
		the future.
		
		Includes loader for B3D models, with animation support
		(net.minecraftforge.client.model.b3d).
		Blender export plugin with compatible coordinate system:
		https://github.com/RainWarrior/B3DExport
		
		OBJ loader is being written, will be included at some point in the
		future. For now you can convert OBJ to B3D via blender, or wait.
	techStackLp:
		Closes #1552
		
		Set the destination block the to the fluid.
		In the previous code the destination block was still Air and would would
		cause a crash because air doesn't have a property for LEVEL
	fry: Removed leftover debug messages
	LexManos:
		Updated FML:
		MinecraftForge/FML@d00feb58c762b0bbc506d79faf1ce40bc96732e9 Remove debug code that was causing console spam in Forge.
		MinecraftForge/FML@1de3bf733aef754f15de55006b1750376871feb0 Fix FML's package for net.miencraftforge on maven. Fixes uploading of new builds. Note: 1.7.10 builds are bug fixes only while FML/Forge for 1.8 stabelizes.
		MinecraftForge/FML@05ecefb53857ecc1dc52d4a577ed593c26da9659 Update to ASM5 for Java 8 support
		MinecraftForge/FML@1112c455b9758c38eab385f48578bad17c0180f9 Merge pull request #595 from Grinch/master
		MinecraftForge/FML@9c3013e02af1bd2f724d34a30e0b880b6e131645 Merge remote-tracking branch 'origin/1.8'

Build 1.8-11.14.0.1295-1.8:
	fry: Removed leftover debug messages

Build 1.8-11.14.0.1294-1.8:
	techStackLp:
		Closes #1552
		
		Set the destination block the to the fluid.
		In the previous code the destination block was still Air and would would
		cause a crash because air doesn't have a property for LEVEL

Build 1.8-11.14.0.1293-1.8:
	jadran.kotnik: Don't skip the first line when rendering (debug) text.

Build 1.8-11.14.0.1292-1.8:
	fry:
		Added model loader registry
		
		Entry point: ModelLoaderRegistry
		loader interface: ICustomModelLoader
		custom model: IModel
		
		ModelLoader is responsible for splicing into vanilla model system.
		(you probably don't need to use it directly)
		
		Interop with vanilla models isn't great yet
		(vanilla models can't refer to custom ones as parents), will improve in
		the future.
		
		Includes loader for B3D models, with animation support
		(net.minecraftforge.client.model.b3d).
		Blender export plugin with compatible coordinate system:
		https://github.com/RainWarrior/B3DExport
		
		OBJ loader is being written, will be included at some point in the
		future. For now you can convert OBJ to B3D via blender, or wait.

Build 1.7.10-10.13.2.1291:
	lukastenbrink:
		Fix fluid tanks incorrectly reading NBT when empty
		
		If the Empty flag was set, the tank would not correctly read the data, keeping the outdated FluidStack instead. This is especially relevant with updatable TileFluidHandler TEs.

Build 1.8-11.14.0.1290-1.8:
	LexManos:
		Updated FML:
		MinecraftForge/FML@a55e4124531119f1c9c023cff74cfa09b49ef0e0 Save the mod list of players in their NetworkDispatcher (Make it accessable for mods)
		MinecraftForge/FML@69d479d46ae658c5a5c2c00081be3df38e38c748 Fixed getEffectiveSide() for Netty Server threads
		MinecraftForge/FML@0f9a33cf14165ddd424a7d82c2178cf5854bf32f Exclude only log4j2 queue from class loader

Build 1.8-11.14.0.1289-1.8:
	Parker Young: Re-enabled Icon setting for Fluids

Build 1.8-11.14.0.1288-1.8:
	jadran.kotnik: Fixed NPE when canceling ClientChatRecievedEvent. Fixes #1644

Build 1.8-11.14.0.1287-1.8:
	LexManos: Silently eat exceptions when getting a TE's rendering bounding box, this 'fixes' Bukkit servers screwing up world data and causing clients to crash.

Build 1.7.10-10.13.2.1286:
	asiekierka: fix shouldRefresh being too broad in tile entity update

Build 1.8-11.14.0.1285-1.8:
	Chicken-Bones: Allow blocks to render in multiple layers

Build 1.7.10-10.13.2.1284:
	lumien231: Fix versionCheck config option

Build 1.7.10-10.13.2.1283:
	CovertJaguar: Bulk Chunk Data packets should also check TileEntity.shouldRefresh().

Build 1.8-11.14.0.1282-1.8:
	LexManos: Fix potential NPE when loading a single player world where you were saved in a unloaded dimension. Closes #1575
	LexManos: Call World.init from DimensionManager.initDimension Closes #1551
	LexManos: Made Chunk.fillBlock respect TileEntity.shouldRefresh.
	LexManos: Fix value passed for Item.getModel useRemaining argument. Closes #1623

Build 1.8-11.14.0.1281-1.8:
	lumien231: Fixes #1603: Moving the start of the update thread to the pre init of the forge mod container

Build 1.8-11.14.0.1280-1.8:
	LexManos: Fix recipies for stone variants.

Build 1.8-11.14.0.1279-1.8:
	palechip: Fix Scoreboard rendering for the sidebar.

Build 1.8-11.14.0.1278-1.8:
	LexManos: Removed exclusion of white stained glass recipes in ore dictionary.
	LexManos: Added chests to the ore dictionary.
	LexManos: Fix crafting of non-oak fences/gates.
	LexManos: Fix MC-30864 (sending web links in chat)

Build 1.7.10-10.13.2.1277:
	mattmess1221: Fix MC-30864 (sending web links in chat)

Build 1.7.10-10.13.2.1276:
	clashsoft: Fix Stained Glass pane rendering issues

Build 1.7.10-10.13.2.1275:
	Kittychanley: Removed exclusion of white stained glass recipes in ore dictionary. Closes #1502 & #1481

Build 1.8-11.14.0.1274-1.8:
	LexManos: Fix BlockSnapshots not firing correctly due to patch mixup in 1.8 update. Closes #1591

Build 1.8-11.14.0.1273-1.8:
	jadran.kotnik: Fixed messages not being added to the chat history and ClientCommandHandler not being called when sleeping.

Build 1.7.10-10.13.2.1272:
	jadran.kotnik: Fixed messages not being added to the chat history and ClientCommandHandler not being called when sleeping.

Build 1.8-11.14.0.1271-1.8:
	LexManos: Fix incorrect logic in world change clumping.
	LexManos: MinecraftForge/FML@5a4d362293fe70e1421d1f22c4a195944731d6ba Finish removing marker in mapping entry names. FMLMissingMappingsEvent/FMLModIdMappingEvent should fire with correct names now.

Build 1.7.10-10.13.2.1270:
	LexManos: Remove our changes to Stitcher slot allocation.
	LexManos: Fix incorrect logic in world change clumping.

Build 1.8-11.14.0.1269-1.8:
	LexManos: MinecraftForge/FML@e3785c28930a218cf9374458c67c34e7fba17922 Ensure that EntitySpawn and OpenGUI packets are handled in the world thread. Also log all errors that are thrown in FutureTasks.
	LexManos: Remove our changes to Stitcher slot allocation.

Build 1.8-11.14.0.1268-1.8:
	LexManos: Fix userdev for new BlockState change.

Build 1.8-11.14.0.1267-1.8:
	fry: Added model bake event (allows mods to insert custom baked models, much like TextureStitchEvent allows to load custom textures), ISmartBlock/ItemModel (ability form models to react to block/item states), Block.getExtendedState, support for unlisted properties in block states. Includes example implementation of http://imgur.com/a/FyyJX

Build 1.8-11.14.0.1266-1.8:
	LexManos: Untie ItemModelMesher from using Item Ids internally by implementing our own simple mechanics using Trove.

Build 1.8-11.14.0.1265-1.8:
	LexManos: Fix texture stitcher not using all avalible spaces.
	LexManos: Fix EnumHelper for new ArmorTexture argument.

Build 1.7.10-10.13.2.1264:
	LexManos: Fix texture stitcher not using all avalible spaces. Closes #1557

Build 1.7.10-10.13.2.1263:
	LexManos: Fixed NPE thrown when brewing event is fired and not all slots are filled.

Build 1.8-11.14.0.1262-1.8:
	LexManos: Fixed NPE thrown when brewing event is fired and not all slots are filled. Closes #1564
	LexManos: Make daylight sensor recipe use ore dictionary wooden slabs Closes #1565
	LexManos: Fix missed patch causing Dispensed Armor to go into the wrong slot. Closes #1560
	LexManos: Fixed log spam when breaking DoublePlants. Closes #1555

Build 1.8-11.14.0.1261-1.8:
	LexManos: Unbind Shaped/Shapeless Ore Recipies from Array list to normal List.

Build 1.8-11.14.0.1259-1.8:
	LexManos: Add quartz_ore tool init, more mojang special casing -.-
	LexManos: Changed ToolMaterial's repair material to ItemStack version to allow metadata sensitive versions.
	LexManos: Improved Control of Enchantment.canApplyTogether() in Mod Enchantments, allowing both enchantments to determine if they can apply together.
	LexManos: Expand PlayerWakupEvent to expose the three parameters passed into EntityPlayer.wakeUp.

Build 1.7.10-10.13.2.1258:
	LexManos: Add quartz_ore tool init, more mojang special casing -.- Closes #1333 and Closes #1335
	LexManos: Fix invalid argument being passed to Block.isNormalCube from World.updateNeighbors. Closes #1339 and Closes #1346
	LexManos: Changed ToolMaterial's repair material to ItemStack version to allow metadata sensitive versions. Closes #1355
	LexManos: Improved Control of Enchantment.canApplyTogether() in Mod Enchantments, allowing both enchantments to determine if they can apply together. Closes #1434
	LexManos: Expand PlayerWakupEvent to expose the three parameters passed into EntityPlayer.wakeUp. Closes #1486

Build 1.8-11.14.0.1257-1.8:
	LexManos: Fixed bug in ServerConfigurationManager.transferPlayerToDimension where it would send the old dimension's information.
	LexManos: Add "sand" to the OreDictionary
	LexManos: Cleanup deprecated code, and TODOs in OreDictionary. Down-typed things from ArrayList to List. Asking for the ores with a null stack will now throw an Exception.
	LexManos: Added CreateSpawnPosition event.
	LexManos: Add LivingHealEvent called from EntityLivingBase.heal()
	LexManos: Added PotionBrewEvent.Pre/Post. To allow for modification and cancelation of Brewing.

Build 1.7.10-10.13.2.1256:
	LexManos: Fixed bug in ServerConfigurationManager.transferPlayerToDimension where it would send the old dimension's information. Closes #1548
	LexManos: Add "sand" to the OreDictionary Closes #1487
	LexManos: Added CreateSpawnPosition event Closes #1053
	LexManos: Add LivingHealEvent called from EntityLivingBase.heal() Closes #1282
	LexManos: Added PotionBrewEvent.Pre/Post. To allow for modification and cancelation of Brewing. Closes #1248

Build 1.8-11.14.0.1255-1.8:
	LexManos: Added Explosion Start and Detonate events to control explosion.

Build 1.7.10-10.13.2.1254:
	LexManos: Added Explosion Start and Detonate events to control explosion. Closes #1469

Build 1.7.10-10.13.2.1253:
	draco18s:
		Update RenderBlockFluid.java
		
		Added tessellator calls to render the block's back faces, so that the liquid properly renders when the player is immersed in the fluid.

Build 1.8-11.14.0.1252-1.8:
	LexManos: Fix finding of spawn location for mobs. Closes #1546
	LexManos: Only call blockBreak when block itself changes, not just meta. Fixes bottles poping out of brewing stands.

Build 1.8-11.14.0.1251-1.8:
	LexManos:
		Updated FML:
		MinecraftForge/FML@9c8ca4a4e3c4acc4980535e5c60da169b75a7810 Unlink banner block and item id. Mojang should of matched these up but they didn't -.-
		MinecraftForge/FML@84a101f344b8fc21de1201fde717fbcbcba2aa79 Update Dev mcp mappings to 11-30 snapshot.
	LexManos: Remove debug patch I left in.

Build 1.8-11.14.0.1249-1.8:
	LexManos: Fix stickey pistons not retracting properly.

Build 1.8-11.14.0.1248-1.8:
	LexManos: Fixed vanilla bug where top part of double plants would flicker a tifferent texture before dissapearing.
	LexManos: Fix NPE with BlockSnapshots that caused items with TileEntities to be used up in creative mode.
	LexManos: Fixed vanilla issue where exceptions in World tasks would not be logged.
	LexManos: Fixed blocks not breaking properly when instantly destroied.

Build 1.8-11.14.0.1247-1.8:
	LexManos: Fix BlockPane's connection detection.

Build 1.8-11.14.0.1246-1.8:
	LexManos: Fixed Entity extended properties init order. Closes #1532
	LexManos: Fixed Entities not being able to climb ladders, Closes #1535
	LexManos: Fixed snow layers not being able to stack more then twice. Closes #1534

Build 1.8-11.14.0.1245-1.8:
	LexManos: Fix interacting with entities.

Build 1.8-11.14.0.1244-1.8:
	LexManos: Fix debug screen not showing grey background. Closes #1529
	LexManos: Fix not being able to place blocks in liquids, and related issues.
	LexManos:
		Updated FML:
		MinecraftForge/FML@36644e97714b46dbbb24416febdde1332a3e753c Finalize modded handshakes in the World tick thread. Prevents potential CMEs when login event takes to long to fire.

Build 1.8-11.14.0.1243-1.8:
	LexManos: Fix potential NPE in Block.isToolEffective
	LexManos: Update RecipeSorter for new 1.8 recipies.
	LexManos: Fix destroy particles not being added. Closes #1528

Build 1.8-11.14.0.1242-1.8:
	LexManos: Fixed crash with caomparators due to wrong position. Closes #1512
	LexManos: Fix inverted logic preventing blocks from breaking.
	LexManos: Fix Entityies not taking damage correctly. Closes #1511
	LexManos: Fix wrong state being passed to Block.getDrops

Build 1.8-11.14.0.1241-1.8:
	LexManos: Fix fog colors, Closes #1524
	LexManos: Fix acedential inversion causing some tress to not have leaves. Closes #1522
	LexManos: Fix creative picking a CommandBlock minecart returning wrong item. Closes #1523

Build 1.7.10-10.13.2.1240:
	LexManos: Fix creative picking a CommandBlock minecart returning wrong item. Closes #1523

Build 1.8-11.14.0.1239-1.8:
	LexManos: Fix local variable conflict in Forge patch and latest MCP mappings.

Build 1.7.10-10.13.2.1236:
	xcompwiz:
		Fixes client-side fake rain
		
		Changes the updateWeather function in WorldServer to only send the
		weather info to players in the correct dimension, rather than all
		players on the server. This is what causes the client-side rain, as the
		client believes that it has started raining locally, rather than in
		another dimension.

Build 1.7.10-10.13.2.1235:
	oliver.kahrmann:
		Modify WavefrontObject to allow '.' in group object names
		
		Blender names objects with .001 ir .002 when separating vertices or duplicating objects and the importer would crash on them. This fixes the regex to allow dots in the name.

Build 1.7.10-10.13.2.1234:
	LexManos: Player sensitive version of Block.getPickBlock Closes #1348

Build 1.7.10-10.13.2.1233:
	LexManos: Fix slots being black due to vanilla blending leakage Forge fixes. Closes #1325 & #1242

Build 1.7.10-10.13.2.1232:
	luacs1998:
		Create CONTRIBUTING.md
		
		Simple file (which github will show for those making PRs) containing guidelines for making PRs.
		Feel free to comment if you want/need anything added. I can pull the same thing to FML too if you'd like, Lex.
	luacs1998:
		Update CONTRIBUTING.md
		
		Add link to wiki page on contributing

Build 1.7.10-10.13.2.1231:
	Adubbz: Fixed desert list initialization. Fixes #1447

Build 1.7.10-10.13.2.1230:
	LexManos: Fix logic error in Blodd's Snapshot capture that caused blocks to not be updated to the client. Closes #1451
	LexManos: Bump version for new RB.

Build 1.7.10-10.13.1.1229:
	Abrar Syed: implemented crowdin support
	matthewprenger: Add username cache for determining a player's last known username
	azanor1:
		Fix for biome weights under 10
		
		This solves the problem where custom mod biomes with weights under 10
		not being generated in the world.
		
		Cleaned up the code and made the patch smaller

Build 1.7.10-10.13.1.1226:
	LexManos: Compleetly disable stencil bits unless told not to by using the -Dforge.forceDisplayStencil=true flag. Should solve the 'menu in bottom corner' issue with Intel Integrated graphics cards.

Build 1.7.10-10.13.1.1225:
	Parker Young: Added PlayerWakeUpEvent

Build 1.7.10-10.13.1.1224:
	Adubbz: Fixed biome weights not working with non multiples of 10

Build 1.7.10-10.13.1.1223:
	LexManos: Fix vanilla lighting issue and blending issues in achievements gui. Closes #1445

Build 1.7.10-10.13.1.1222:
	LexManos: MinecraftForge/FML@d00feb58c762b0bbc506d79faf1ce40bc96732e9 Remove debug code that was causing console spam in Forge.

Build 1.7.10-10.13.1.1221:
	LexManos: Disable by default the Display Stencil bits. Keep FBO bits. Acording to Mumfery and ChickenBones, it should not be nessasary and should solve the 1/4 main menu issue. Use -Dforge.forceDisplayStencil=true to enable old behavior.

Build 1.7.10-10.13.1.1220:
	jadran.kotnik: Prevent client only commands from bleeding through to the server.

Build 1.7.10-10.13.1.1219:
	bloodshot:
		Added PlaceEvent and MultiPlaceEvent which fires before placing a block.
		
		Before calling "ItemStack.tryPlaceItemInWorld", a recording flag is turned on for
		setBlock to capture a blocksnapshot for each block that attempts to be placed.
		
		If 1 block is captured, a "BlockEvent.PlaceEvent" is fired to notify mods.
		If 2 or more blocks are captured, a "BlockEvent.PlaceEvent" is fired first with the first block
		captured followed by a "BlockEvent.MultiPlaceEvent" with all captured blocks. This extra event
		is required for items that have the ability to place 2 or more blocks such as a BlockBed.
		
		If either event is cancelled, the recorded block snapshot(s), item stacksize, and item meta will
		revert back to the captured snapshot(s).
		If the events are not cancelled, a notification will be sent to clients and block physics will be updated.
		
		What this means for mods is Forge will be able to capture all player block placement automatically and fire
		a PlaceEvent and/or MultiPlaceEvent.
		If for whatever reason your mod does not use the standard placement methods then you will need to fire the
		appropriate placement events in order to notify mods/servers.
		
		This commit also includes a new utility class called BlockSnapshot which is serializable. This new class is used in conjunction with
		both PlaceEvent and MultiPlaceEvent in order to record a snapshot of block space before it is altered. This
		allows us to restore the block(s) if an event is cancelled. The class also provides the ability to restore a snapshot
		to any location using the restoreToLocation method. This should be helpful to many mods that are looking to be able
		to capture block data then restore it to back to any location required.

Build 1.7.10-10.13.1.1217:
	cpw:
		GIANT FML UPDATE! Bump forge revision number, and fix patches for ItemStack changes. More to come on this branch I expect.
		
		MinecraftForge/FML@7c5cf219042581545b6073de4e947448ffa10879 Implement STDOUT/STDERR redirection.
		MinecraftForge/FML@bc78e31cb7ad4eda6e5faa173cd6b21e70a2c444 added support for \n in tooltip strings added \n test tooltip localization fixed int/double conversion error in slider entry added test slider scenario that highlighted conversion error
		MinecraftForge/FML@a2908e5c596bb5502bf455d468d2b1ead0520f55 Clean up a bunch of compiler warnings.
		MinecraftForge/FML@7f67523d870ae150071c67b002597542eb206725 Update realms to 1.3.2
		MinecraftForge/FML@73f23c24b85240458f352f248e885684aaff4743 Merge branch 'std-redir' of github.com:Emberwalker/FML
		MinecraftForge/FML@1c6b25df740a64c94d9ba05dd7e4412515abf5bb If an IO exception comes from the datawatcher, spew it all over the console don't discard it silently. Should stop pixelmon blaming forge for their mistakes.
		MinecraftForge/FML@e77da9eb2f5c58a494ed100dd4c1dd1a0c341dbf And fix the read side too, incase someone is trying to bitbang and failing.
		MinecraftForge/FML@305d8950c9332c7a7f290db05e6f18ef328016e2 Make LogContext optional. This can be useful for debugging mod issues, but Apache's implementation in log4j2 is responsible for a very significant % of the overall runtime. Quite frankly this is shockingly bad performance from what is supposed to be a high performance logging framework. Anyway, until we can figure out if we can fix it, we're turning it off by default.
		MinecraftForge/FML@bdfca1c8ed463a6053526c7a46a990007711e3d0 Make more noise when people screw up mod downloading and put .jar.zip in their mod folders.
		MinecraftForge/FML@21084941127fc882d9968316a8f0669531e484df Add a custom version range factory method. Should hush skyboy's complaints. Closes #486
		MinecraftForge/FML@7c1e6aaa40704001231e602ceaedfa21a5df1edf Add a delegate to every item and block. this should help with renaming fun stuffs. Also, fix all the tabs from my previous commits. *sigh*
		MinecraftForge/FML@61fcb4df06dc968fcc31d3e4e524e574acfdbb3b Tweak Itemstack patch to always delegate to the method call. Set the field, so it's in sync.
		MinecraftForge/FML@eb8c5ab146f2eb3ad3833d40607da97831278ffb Fix nested directory for language resources. Closes MinecraftForge#1264
		MinecraftForge/FML@7c05e5f70d5387512d0bee33ef99510ee5aac739 Default collections, so that we don't crash if useDependencyInfo is true. Closes #485
		MinecraftForge/FML@9729fe23326a3d4f6b03e60b5cdaf78a484b3657 Kill net.minecraft.src warning. It hasn't served a purpose in a long time now. Closes #313
		MinecraftForge/FML@21e875ef22eef6068ccd6df1bd71cf58cba48eed AllowPlayerLogins only after the server has completed the core init tasks. Closes #372
		MinecraftForge/FML@46cfeade80ae60ad2d8cdb40c5fdfdaeeaf16d00 Add a constructor to CustomModLoadingDisplayException. Closes #387
		MinecraftForge/FML@a6eab2683a15a0cceca7a0ded6095b746cdd017b Update README.txt
		MinecraftForge/FML@f75838461cf6d9c5010cbfd2d9ef5ceec03268d7 Last part is the itemstack transformer. Itemstacks should now only be loosely coupled with the items within.
		MinecraftForge/FML@51f24e9e6d1bee371cf23cdfd0071de7c5175417 First draft of add alias. It is probably not properly persistent atm.
		MinecraftForge/FML@2a4c6424709b20ce1e9bda0d85ce7fac47d157c2 Finally fix stupid NPE error caused by FML trying to parse the super of Object in IDEA envs.
		MinecraftForge/FML@c1b1417ee168523154a0edae68c3180814eab1c7 FML now supports passing a json formatted modlist as an argument, as well as a comma separated argument list. These facilitate modpacks mostly, by meaning you don't need to duplicate mods. The modlist is arranged in the maven style, with mods referenced maven-like.
		MinecraftForge/FML@3d42cda2a2cf5b24e7a25537d883260857b2107a Build.Gradle Patch
		MinecraftForge/FML@20c7add8455cd16a4551ed13336a9ad4f9770cd1 Merge pull request #484 from bspkrs/master
		MinecraftForge/FML@26ed4b992eb6341d52d12fb6735415ab8e3c501d Clear button list on FML fatal error screens. The hidden cancel button should not be there. Closes #497
		MinecraftForge/FML@ebe4f5c5e297d5d59ce57138810627a9c7a1b412 Merge pull request #494 from AntonBoch1244/patch-1
		MinecraftForge/FML@ad0da05f5c78d7f3c35a331e993dd6e679fc7ac9 Fix the ItemStack transformer to find the method and field so it works with srg and mcp naming.
		MinecraftForge/FML@65d380181a84d35a78791e1bc3c7712cd90506f6 Extend timeout for client to 5 seconds. Should fix Forge #1322
		MinecraftForge/FML@45486a0b6dfca65c4d1dd23176d4c9d13d46b6f5 Fix almost invisible NPE in TerminalTransformer when loading a non-existant class
		MinecraftForge/FML@13da3efce07653732971837709ccf4de7e4c5c8e Allow a clean way to exit the game without big ugly warnings, but with logging information available if needed. Closes #496
		MinecraftForge/FML@fda305edfea15ba2015cede72327703f273f74e3 Some more tidying up of the exit handling
		MinecraftForge/FML@b087f60c3379d0767247e51cbc3f7c631fe97a08 More cleanup of exit handling, also add a couple more noise classes to the list of things ignored.
		MinecraftForge/FML@d6358a466b4614cfc35b403d756fe3ef550ebf50 Cleanup override warnings
		MinecraftForge/FML@af7a58b9e50dbacf63cf4b5009abc52301609e1f Update to legacylauncher 1.10 and asm 5.0.3
		MinecraftForge/FML@e6d00440a612c235013f3f92f1756811139a6de0 ItemStack swapping
		MinecraftForge/FML@8597e45a0e417948db483006aa54e899f28b05ac Fix NPE from a boolean
		MinecraftForge/FML@b9b9daa8a9d1cac8550561f31f118589abc0c30a Fix ups from feedback.
		MinecraftForge/FML@d89165021f33fbffb4563d86b30bd261506c6ea6 Mark the promise a success in the outbound handler.
		MinecraftForge/FML@2e5ccf7988385d38b964c615776f23a1718f5c27 Update for launchwrapper 1.11. Fixes java 6 compatibility.
		MinecraftForge/FML@641250d8536bad3af5a036b70dae94097176b420 Fix java 8u20. Closes #501 and a bunch of other bugs too.
		MinecraftForge/FML@292be72639feded03ced26d9a06a98159f7a95b7 Allow client handshake to be reset by server to support BungeeCord.
		MinecraftForge/FML@092873fbe5baaee53bee67d26d2fc6d3d003f095 Merge branch 'bungeecord' of github.com:bloodmc/FML
		MinecraftForge/FML@134f2f8e8865a91292386a3738bb45bad0477a4b Fix bug with entityspawn - if the entity doesn't extend livingbase, it fails to write a headyaw byte, and everything will be derped for that packet.
		MinecraftForge/FML@4852de81e02e2b6c6d006abe20d8497499fdf51f Wrap the server description box a little bit shorter. Stops the overlapping. Closes #489
	cpw:
		MinecraftForge/FML@4ce3e73bfe36c02b10f504f93eff1bc94d640e32 Add overloaded version of SimpleNetworkWrapper#registerMessage that takes the MessageHandler instance directly, allowing to specify the same handler for multiple messages.
		MinecraftForge/FML@cbe2ccbda461ec0ecf4d776fcd19ab31930cc3f1 Add in ModType to the jar manifest. If it's present, and doesn't have value "FML" it will be skipped from the modloading cycle. This should let liteloader mods have a .jar extension.
		MinecraftForge/FML@37cf0174fc62a842d132b2c2cc31e477acfba205 OK, lets make that a csv list. It'll let you be liteloader and fml in one jar file!
		MinecraftForge/FML@0475b15eb1a7c35bf4959f1af40606e6ee8a9d03 Change the mods and modListFile argument handling a bit. Other tweakers will get a chance at looking at them now - they're only removed right before launch.
		MinecraftForge/FML@abeac06a2e9bf8825b058fa35291165b4d1f1fb3 Two new features. ModLists can have a "parent" mod list. Circularity will result in a crash, so be careful. Mods specified in a child will override ones from a parent (using the maven group:name:classifier triple to identify - ignoring the version component)
		MinecraftForge/FML@7fcfedcfef9b5fd85cd1c17aa2013fca1bacd871 Canonicalized file paths in modListFile handling with the minecraftDirectory.
		MinecraftForge/FML@633fce19d4b367aed56d79e916f17296842f675c Make Keyevent also fire for key releases
		MinecraftForge/FML@57ba2339b630afa22c0fdf060bf28edbf7b34d0f Merge branch 'keyup-event' of github.com:diesieben07/FML
		MinecraftForge/FML@1ff048062c7f122731619258a9e5a68a6111d5dd Merge branch 'simple-netw-improve' of github.com:diesieben07/FML
	cpw: MinecraftForge/FML@dc02d56195606d3ba2f1c5036fc8c0ddb67c843f Fix derp with ModType annotation. mods should load again now..
	diesieben07: Added Item#isBeaconpayment
	cpw:
		MinecraftForge/FML@7ab69aff2e19b349e457c1b5fcab8b3b01d22af2 Clean up import
		MinecraftForge/FML@c5a90bd456230b201522c268dd9bc5e80a0b57be Is vanilla possible with this mod load, side tests.
		MinecraftForge/FML@cad11f3165505e6d725411a9fc2c2ee8362f5827 Allow injecting alternative container types. This is the core support code for allowing sponge plugins!
	michafla:
		check for IFluidBlock (in addition to Material.liquid) when
		determining render height so that non-liquids (gases) render correctly
	kat.swales: Fixed Clientside GameProfile UUID being null on offline mode
	cpw:
		MinecraftForge/FML@63b64482e6dd4c3e2226ec002ceee549045c35ed Add jsr305 dev-time dependancy for Nullable/Nonnull annotations. Unneeded at runtime.
		MinecraftForge/FML@5365f5ea3e90ec85552bdb7f1f1237c51b4ea493 Add IEventExceptionHandler for EventBus to allow special handeling exceptions that are fired while running an event. Events now track what 'phase' they are in during the execution process. Each EventPriority is a 'phase'. An exception is thrown if the event attempts to set its phase to a previous one.

Build 1.7.10-10.13.1.1216-new:
	kat.swales: Fixed Clientside GameProfile UUID being null on offline mode

Build 1.7.10-10.13.1.1215-new:
	michafla:
		check for IFluidBlock (in addition to Material.liquid) when
		determining render height so that non-liquids (gases) render correctly

Build 1.7.10-10.13.1.1214-new:
	cpw:
		MinecraftForge/FML@7ab69aff2e19b349e457c1b5fcab8b3b01d22af2 Clean up import
		MinecraftForge/FML@c5a90bd456230b201522c268dd9bc5e80a0b57be Is vanilla possible with this mod load, side tests.
		MinecraftForge/FML@cad11f3165505e6d725411a9fc2c2ee8362f5827 Allow injecting alternative container types. This is the core support code for allowing sponge plugins!

Build 1.7.10-10.13.1.1213-new:
	diesieben07: Added Item#isBeaconpayment

Build 1.7.10-10.13.1.1212-new:
	cpw: MinecraftForge/FML@dc02d56195606d3ba2f1c5036fc8c0ddb67c843f Fix derp with ModType annotation. mods should load again now..

Build 1.7.10-10.13.1.1211-new:
	cpw:
		MinecraftForge/FML@4ce3e73bfe36c02b10f504f93eff1bc94d640e32 Add overloaded version of SimpleNetworkWrapper#registerMessage that takes the MessageHandler instance directly, allowing to specify the same handler for multiple messages.
		MinecraftForge/FML@cbe2ccbda461ec0ecf4d776fcd19ab31930cc3f1 Add in ModType to the jar manifest. If it's present, and doesn't have value "FML" it will be skipped from the modloading cycle. This should let liteloader mods have a .jar extension.
		MinecraftForge/FML@37cf0174fc62a842d132b2c2cc31e477acfba205 OK, lets make that a csv list. It'll let you be liteloader and fml in one jar file!
		MinecraftForge/FML@0475b15eb1a7c35bf4959f1af40606e6ee8a9d03 Change the mods and modListFile argument handling a bit. Other tweakers will get a chance at looking at them now - they're only removed right before launch.
		MinecraftForge/FML@abeac06a2e9bf8825b058fa35291165b4d1f1fb3 Two new features. ModLists can have a "parent" mod list. Circularity will result in a crash, so be careful. Mods specified in a child will override ones from a parent (using the maven group:name:classifier triple to identify - ignoring the version component)
		MinecraftForge/FML@7fcfedcfef9b5fd85cd1c17aa2013fca1bacd871 Canonicalized file paths in modListFile handling with the minecraftDirectory.
		MinecraftForge/FML@633fce19d4b367aed56d79e916f17296842f675c Make Keyevent also fire for key releases
		MinecraftForge/FML@57ba2339b630afa22c0fdf060bf28edbf7b34d0f Merge branch 'keyup-event' of github.com:diesieben07/FML
		MinecraftForge/FML@1ff048062c7f122731619258a9e5a68a6111d5dd Merge branch 'simple-netw-improve' of github.com:diesieben07/FML

Build 1.7.10-10.13.0.1208:
	zlyfire.martin:
		Update README.txt
		
		Add in reference to running setupDecompWorkspace to get decompiled classes

Build 1.7.10-10.13.0.1207:
	bernhard.bonigl: Write the correct default value for StringList comments in the config

Build 1.7.10-10.13.0.1206:
	LexManos: Fix AIOOB in BiomeDictionary. Closes #1326

Build 1.7.10-10.13.0.1205:
	cpw:
		Attempt to properly resolve this daft metadata and TE nonsense. This might be mod impacting, if you maintain a reference to a TE via neighbour update calls - you
		might see two TEs for a single setblock where previously you saw one. This is a phantom TE being created by badly written neighbour triggers - I'm looking at you
		redstone.
		
		Anyway, with luck, this'll close a slew of bugs across Forge, IC2, MFR, TE, RC. Yeah, fun times. Thanks to LexManos, skyboy and KingLemming for helping figure this
		issue out. Quite frankly, from now on, issues with phantom TEs will be mods behaving badly. Modders will need to adapt.

Build 1.7.10-10.13.0.1204:
	LexManos: Fix invalid math in GuiContainerCreative.

Build 1.7.10-10.13.0.1203:
	porcariadagata: Add ItemStack sensitive version of getItemEnchantability

Build 1.7.10-10.13.0.1202:
	LexManos: Add ability for creative tabs that have search bars to customize the text box's width, and prevent the default set of enchanted books from being displayed in those tabs. Closes #1303 Closes #1301

Build 1.7.10-10.13.0.1201:
	abab9579:
		Skylight Hooks for Minecraft Forge
		
		Mainly for solar/lunar eclipse.

Build 1.7.10-10.13.0.1200:
	JeanGlassmaker: Adds getLocalizedName and getUnlocalizedName to FluidStack

Build 1.7.10-10.13.0.1199:
	vazkii: Fixed items with more than 2 render passes rendering weird in first person
	LexManos: Fix patch screwup in Skyboy's Fishing PR -.-
	LexManos: Fix metadata for every permutation -.- Closes #1294
	t.tomkins:
		Legacy Liquid Load Fix
		
		nbt.getString("FluidName") no longer returns null, it returns an empty string.
		
		This patch allows legacy liquids to be resolved once again.

Build 1.7.10-10.13.0.1198:
	DemoXin:
		* Added AT for ContainerRepair.stackSizeToBeUsedInRepair (Now public)
		* Added ability to AnvilUpdateEvent to alter stackSizeToBeUsedInRepair (vanilla behavior is now reproducable)
		* Added AnvilRepairEvent, fired when the player removes an ItemStack from the output slot of ContainerRepair, and allows the chance to damage the anvil to be altered.

Build 1.7.10-10.13.0.1197:
	skyboy026: Add FishingHooks
	skyboy026: Update FishingHooks
	skyboy026: Add EntityFishHook AT

Build 1.7.10-10.13.0.1195:
	rwtema: Fixed ItemFluidContainer always draining the maximum amount, regardless of the amount remaining.

Build 1.7.10-10.13.0.1194:
	LexManos: Closes #1280

Build 1.7.10-10.13.0.1191:
	LexManos: Fixed bug that allowed duplication of Fluids with redstone dust. Closes #1279

Build 1.7.10-10.13.0.1190:
	idont: - Added drainFluidContainer() and getContainerCapacity() helper methods.

Build 1.7.10-10.13.0.1189:
	Adubbz: Added an event for fog rendering

Build 1.7.10-10.13.0.1188:
	cpw:
		Revert old light amortization patch. It seems to be breaking chunk sending pretty badly when more
		than a couple of people are online. Tests indicate it is not useful anymore.
	cpw: MinecraftForge/FML@3231db9376766d619f942b6a526718daa3c68038 Sorta revert 908491d5e7ac26becdac938f38cc90d6b9d73ce1 but merge assets into the map, rather than force overwriting. Fixes skyboy's comment.

Build 1.7.10-10.13.0.1187:
	LexManos:
		Updated FML:
		MinecraftForge/FML@53887ac59cec8f747e21fd251f94d5a438a69114 Hacky interm solution to #1207 to buy me time to re-write FML's network protocol.

Build 1.7.10-10.13.0.1186:
	LexManos: Fixed NPE that happens sometimes when exiting the game witout fully loading a world {main a dev-time thing}
	LexManos: Made skulls respect Block.isReplaceable when placing, also prevented them from deleting blocks when placed at certain angels. Closes #1233

Build 1.7.10-10.13.0.1185:
	LexManos:
		Updated FML:
		MinecraftForge/FML@9d40b761974f10ec2b5868a992260792f8a98e5d Don't scan ObjectHolders if there was an error already, derpitude will ensure.
		MinecraftForge/FML@76538c1781d6d6a1e4134fb317af99e6f13b46cc Add a terminal transformer and tweaker.
		MinecraftForge/FML@aec9228845e50107112bd1f8693f9b4729694c8b Add ExitVisitor to the TerminalTransformer that finds and intercepts any calls to Runtime.exit or System.exit.
		MinecraftForge/FML@908491d5e7ac26becdac938f38cc90d6b9d73ce1 Move LaunguageRegistry call above normal asset loading to allow resource packs to override mod's language systems.
		MinecraftForge/FML@d13295e28113a1c310d5bbb90ebfe241fefabe02 Fix FMLAT manifest AccessTransformers, class loader fun!

Build 1.7.10-10.13.0.1184:
	darklime:
		Changed exception message for duplicate enchantment ids to contain the
		class path for both enchantments along with the enchantmnet id that has
		been duplicated.

Build 1.7.10-10.13.0.1183:
	bspkrs:
		Fixed missing assignment of constructor arg (thanks @Lunatrius)
		
		I must have edited this out when I was cleaning up my formatting commit spam.

Build 1.7.10-10.13.0.1182:
	vincent_a_lee:
		Fix comment derp (+1 squashed commits)
		
		Squashed commits:
		
		[52c40bc] Fix experience orbs spawning at 32x coordinates clientside
		
		Add // FORGE comment
		
		Add // FORGE comment to clarify the purpose of the change

Build 1.7.10-10.13.0.1181:
	vincent_a_lee:
		Fix chat opacity
		
		Add // FORGE comment
		
		As per convention, add // FORGE comment to clarify the purpose of the change

Build 1.7.10-10.13.0.1180:
	LexManos:
		Updated FML:
		MinecraftForge/FML@ab52901b8b47a525e2719cf280327e97bad7f91e Force preferIPv4Stack to true early in the load chain to combat netty loopback issues.
		MinecraftForge/FML@11893fbbb76569417a415ae794494b8c1150a716 Add system property to skip doing world backups when game registry changes. This is SEVERLY ill-advised, if you do this DO NOT ask for any support.
		MinecraftForge/FML@fdb6b34b8fc3f1e0c6beb7bfb940a01a309f1603 Update authlib and realms to latest json data.
		MinecraftForge/FML@b3a74882b4d0d704d7061b9d896febb59ab0c269 added slider controls for numerics. default control is textbox, but slider can be used as a custom list entry class. fixed constructor javadocs in GuiConfig
		MinecraftForge/FML@7c6d1f7568885ff677e34692ff87b1f0826dfd48 Merge pull request #468 from bspkrs/master
		MinecraftForge/FML@692d955c1a5b6d0b8601ae88632ef42136d37393 Update tweaker login to use authlib.
		MinecraftForge/FML@c2119eb1c1246ba37304d9e565b4430ed7056db1 Update realms library to 1.3.1, and implement network latch when connecting to Realms. Tested and working.

Build 1.7.10-10.13.0.1179:
	cpw: Add a system property for the stencil, in case config is not available..

Build 1.7.10-10.13.0.1178:
	the.country.gamer:
		RenderBlockOverlayEvent patch
		
		Fixes skewed XYZ parameters

Build 1.7.10-10.13.0.1177:
	LexManos: Fixed Enchantment.addToBookList Closes #1160

Build 1.7.10-10.13.0.1176:
	LexManos: Add ability for modders to designate custom biome types. And remove note about automatically registering. Closes #1167

Build 1.7.10-10.13.0.1175:
	diesieben07: Added hook for custom PotionEffect rendering in the inventory

Build 1.7.10-10.13.0.1174:
	the.country.gamer:
		Added RenderBlockOverlayEvent.java
		
		Adds a Forge event which controls whether an overlay is rendered.
		Overlays include: First-person fire, Block (when inside a block)
			and water when a player is inside a water block.
		
		Patched for easier manipulation of event
		
		Fixed for Lex
		
		To be squashed
		
		Removed Contructor
		
		Added block XYZ parameters
		
		TODO, the second block overlay event’s XYZ might not be correct
	Adubbz: Enhanced the Biome Dictionary with tags based on temperature, vegetation, moisture, trees and others

Build 1.7.10-10.13.0.1172:
	LexManos: Made EmeraldOre respect isReplaceableOreGen. Closes #1157
	LexManos: Added World to ChunkProviderEvent.ReplaceBiomeBlocks, and exposed metadata to End and Nether generation events. Close #1201

Build 1.7.10-10.13.0.1171:
	tterrag1098:
		Add AchievementEvent
		
		Allows modders to react to players receiving achievements, and cancel
		them.
		
		Fix indentation
		
		More shortening
		
		Down to one line...
		
		Remove newline

Build 1.7.10-10.13.0.1170:
	LexManos: STENCIL buffer and DEPTH buffer, attempt a fix for GL errors.

Build 1.7.10-10.13.0.1169:
	Alexander Ibrahim: Added Javadoc comments for Forge Event documentation.

Build 1.7.10-10.13.0.1168:
	LexManos: MinecraftForge/FML@ac994e178a3533aa3c2ad8359aef9e5852c27a72 Scala people test your shit.

Build 1.7.10-10.13.0.1167:
	LexManos: Remove the BLEND enable in rendering damage bars. And exclicitly fix blend states in some GUI elements.

Build 1.7.10-10.13.0.1166:
	cpw:
		MinecraftForge/FML@3ee86d0f3e47249030ba2309386f9120025e95c1 updated gradle wrapper to gradle 2.0
		MinecraftForge/FML@627ae73ea655277617912df48b03288ecc79ffea Merge pull request #464 from AbrarSyed/upgradle
		MinecraftForge/FML@ee38c1b3f4642c567612f88070d7f9d651994aab Fix unneeded cast causing crash in new Config GUI system.
		MinecraftForge/FML@eb92c35a2fa49a0fbe35a33e31cfb58e0674f78e updated run configs for GradleStart/Server classes
		MinecraftForge/FML@70dcf80410a6d12c00300c00522582ee49ac4cc8 Merge pull request #465 from AbrarSyed/upgradle
		MinecraftForge/FML@0ebdbe77a2b3503db43d36aec50c98ffb8366e20 Updated Scala to latest stable
		MinecraftForge/FML@ddba18e6e33a9d9c5b113b1bfc0bfc82803b2607 Merge branch 'patch-1' of github.com:Soaryn/FML into scalaupdate
		MinecraftForge/FML@220a37660b2656136c634b435afee6a915fc88fe Update realms to 1.2.9
		MinecraftForge/FML@abd7d0969bed5ce3d766f52b921c2b44e8ba87d2 Merge branch 'scalaupdate'

Build 1.7.10-10.13.0.1162:
	foka_12:
		Added FluidStack sensitive version for Fluid's localised name
		
		Would be helpful for determining names for more complex FluidStacks (with tag compounds for example)

Build 1.7.2-10.12.2.1161-mc172:
	bspkrs: dupe quotes fix for category names

Build 1.7.10-10.13.0.1160:
	Gerard Bruwn: Add RenderItemInFrameEvent

Build 1.7.10-10.13.0.1159:
	LexManos: Fixed issue where Fire's 'fizz' would not play for the person who extinguished the fire.

Build 1.7.10-10.13.0.1158:
	ohai.iChun: Fixed inverted params in FogDensity use

Build 1.7.10-10.13.0.1157:
	LexManos: Add config option to disable attempting to creat screen with Stencil Bits.
	LexManos: Add config option to specify the default spawn fuzz factor for the overworld. Closes #1190

Build 1.7.10-10.13.0.1156:
	LexManos: Fix creative inventory tabs not blending base don items rendered. Closes #1179

Build 1.7.10-10.13.0.1153:
	bloodshot:
		Fixed wrong method call in ChunkIOProvider.
		
		When a chunk fails to load async, we fallback to the original sync method.
		In this case, it was calling the async method twice which ended up causing
		a stackoverflow.

Build 1.7.10-10.13.0.1152:
	cpw: MinecraftForge/FML@db219fb287b14fea5148ecdbf07d8ff08704c66a API is now able to "provide" and "own" itself. Useful for libraries without a Mod in them. To go along with this, you can now require an API, with a version, in your mod dependency string

Build 1.7.10-10.13.0.1151:
	bspkrs: fixed compounding quotes issue with category names that require quotes when save is called more than once

Build 1.7.10-10.13.0.1150:
	LexManos: Update to 1.7.10-pre4.
	LexManos: Fix flower pots not droping the items that are inside them.
	cpw: MinecraftForge/FML@06ab104c9ab798af6d2726e02a238211ff8124e1 Force the descriptors to the right type for the field they're referencing. Fixes the sand issue
	cpw: MinecraftForge/FML@e1529845384f4935b7c11d4d36d25db51c0b9a31 Add support for mod access transformers without a coremod requirement. Use the "FMLAT" manifest attribute, with a space separate list of files that live in the 'META-INF' directory. They should conform to standard AT formatting.
	cpw:
		MinecraftForge/FML@5d6dc5dce37e488188d6fc468c16e8a6183a3610 Fix up other exit points. Should stop process hangs for clean exits.
		MinecraftForge/FML@8a240ec3c7e4cf4c57beabdfe9bd408e57de1bdc Merge branch 'master' into mc179
		MinecraftForge/FML@0cd5ef6bb71cda1ef6add892d1247148bf1ecc15 Fix NPE when no FMLAT is defined
	cpw:
		MinecraftForge/FML@701d98eafa4d55144b166d26030818baa9b2f680 Added config GUI system
		MinecraftForge/FML@50164db5c13c85636c7fda0e13bae1fc0aedc745 Merge branch 'master' of github.com:bspkrs/FML into bspkrsgui
		MinecraftForge/FML@7eb36a1481aea9f68fa46bc199195769b27d904b Merge branch 'bspkrsgui'
		MinecraftForge/FML@96a7e14a45404449fb72af6d2d5e1efd30003318 Merge branch 'master' into mc179
		MinecraftForge/FML@f45f18b1d71e1c1d12582faa337a19e73ed5fb18 Fix accessing guava from transformers
		MinecraftForge/FML@8f7adced471951c798cfa6844b0abc176c93d19b Fix library issue. mojang auth requests newer libs, so we get them at dev time. But the mojang json doesn't refer them at runtime. So there's a lib mismatch. Fortunately all are available at mojang, so we can update the json.
	cpw: Fix new method with Side.CLIENT when it shouldn't have it. Closes a bunch of reports of problems.
	cpw: Clean patch cruft.
	cpw: Fix mcp release number
	luacs1998:
		Update mc version string
		
		Or was I not supposed to?
	cpw: Fix API incompatibilities. Should mean mods will work with new config changes.
	cpw:
		Update to MC 1.7.10, bump to 10.13.0
		
		MinecraftForge/FML@bc420dcb0b086899e2aaa218a6f5bd7e91091a90 Fix Eclipse launching attribute
		MinecraftForge/FML@1e0134a1ca97a1107ebbe604e5318e6f350fe9c4 Merge pull request #455 from rumickon/feature
		MinecraftForge/FML@1c5db211afc9962fedb7fd8450abc45d07807634 Update for release 1.7.10
		MinecraftForge/FML@79a0c5e55905f0f08471d026b744a563ea421236 Merge branch 'mc179'

Build 1.7.10_pre4-10.12.2.1149-prerelease:
	cpw: Fix API incompatibilities. Should mean mods will work with new config changes.

Build 1.7.10_pre4-10.12.2.1148-prerelease:
	luacs1998:
		Update mc version string
		
		Or was I not supposed to?

Build 1.7.2-10.12.2.1147:
	cpw: Fix API incompatibilities. Should mean mods will work with new config changes.

Build 1.7.10_pre4-10.12.2.1146-prerelease:
	bspkrs:
		Added support for new FML config GUI classes
		refactored lots of stuff based on comments
		
		added Configuration.load() exception handling and logging
	cpw: MinecraftForge/FML@5d6dc5dce37e488188d6fc468c16e8a6183a3610 Fix up other exit points. Should stop process hangs for clean exits.
	cpw:
		MinecraftForge/FML@701d98eafa4d55144b166d26030818baa9b2f680 Added config GUI system
		MinecraftForge/FML@50164db5c13c85636c7fda0e13bae1fc0aedc745 Merge branch 'master' of github.com:bspkrs/FML into bspkrsgui
		MinecraftForge/FML@7eb36a1481aea9f68fa46bc199195769b27d904b Merge branch 'bspkrsgui'
	cpw: Fix mcp release number

Build 1.7.2-10.12.2.1145:
	bspkrs:
		Added support for new FML config GUI classes
		refactored lots of stuff based on comments
		
		added Configuration.load() exception handling and logging
	cpw:
		MinecraftForge/FML@701d98eafa4d55144b166d26030818baa9b2f680 Added config GUI system
		MinecraftForge/FML@50164db5c13c85636c7fda0e13bae1fc0aedc745 Merge branch 'master' of github.com:bspkrs/FML into bspkrsgui
		MinecraftForge/FML@7eb36a1481aea9f68fa46bc199195769b27d904b Merge branch 'bspkrsgui'

Build 1.7.10_pre4-10.12.2.1144-prerelease:
	cpw: Clean patch cruft.

Build 1.7.10_pre4-10.12.2.1143-prerelease:
	cpw: Fix new method with Side.CLIENT when it shouldn't have it. Closes a bunch of reports of problems.

Build 1.7.10_pre4-10.12.2.1142-prerelease:
	cpw:
		MinecraftForge/FML@701d98eafa4d55144b166d26030818baa9b2f680 Added config GUI system
		MinecraftForge/FML@50164db5c13c85636c7fda0e13bae1fc0aedc745 Merge branch 'master' of github.com:bspkrs/FML into bspkrsgui
		MinecraftForge/FML@7eb36a1481aea9f68fa46bc199195769b27d904b Merge branch 'bspkrsgui'
		MinecraftForge/FML@96a7e14a45404449fb72af6d2d5e1efd30003318 Merge branch 'master' into mc179
		MinecraftForge/FML@f45f18b1d71e1c1d12582faa337a19e73ed5fb18 Fix accessing guava from transformers
		MinecraftForge/FML@8f7adced471951c798cfa6844b0abc176c93d19b Fix library issue. mojang auth requests newer libs, so we get them at dev time. But the mojang json doesn't refer them at runtime. So there's a lib mismatch. Fortunately all are available at mojang, so we can update the json.

Build 1.7.10_pre4-10.12.2.1141-prerelease:
	cpw:
		MinecraftForge/FML@5d6dc5dce37e488188d6fc468c16e8a6183a3610 Fix up other exit points. Should stop process hangs for clean exits.
		MinecraftForge/FML@8a240ec3c7e4cf4c57beabdfe9bd408e57de1bdc Merge branch 'master' into mc179
		MinecraftForge/FML@0cd5ef6bb71cda1ef6add892d1247148bf1ecc15 Fix NPE when no FMLAT is defined

Build 1.7.10_pre4-10.12.2.1139-prerelease:
	cpw: MinecraftForge/FML@e1529845384f4935b7c11d4d36d25db51c0b9a31 Add support for mod access transformers without a coremod requirement. Use the "FMLAT" manifest attribute, with a space separate list of files that live in the 'META-INF' directory. They should conform to standard AT formatting.

Build 1.7.10_pre4-10.12.2.1138-prerelease:
	cpw: MinecraftForge/FML@06ab104c9ab798af6d2726e02a238211ff8124e1 Force the descriptors to the right type for the field they're referencing. Fixes the sand issue

Build 1.7.10-pre4-10.12.2.1135-prerelease:
	LexManos: Fix flower pots not droping the items that are inside them.

Build 1.7.2-10.12.2.1133:
	Christian: Null check the Item in the supplied stack as well as the stack itself.

Build 1.7.2-10.12.2.1132:
	Christian: And fix firing for single player loading.

Build 1.7.2-10.12.2.1131:
	Christian: Fix derpity derp.

Build 1.7.2-10.12.2.1130:
	Christian:
		Fire an event when a player loads or saves from disk. Mods that want to load an additional
		player related file from the players dir can now do so in that event.

Build 1.7.2-10.12.2.1129:
	Christian:
		Some patch offsets
		MinecraftForge/FML@7219061b05db73d245405ef777b412d0787398b6 Also patch in warnings for Vec3Pool - similarly removed.
		MinecraftForge/FML@dff22045587b37282adeb2167486a572f51f1f16 FML now sets a security manager (FINALLY!). It's primary purpose at this point is to catch rogue calls to System.exit so that they can cause a proper crash report, rather than silently abandoning the game.

Build 1.7.2-10.12.2.1128:
	lumien231: Fixes a server crash caused by a player joining that is in a non existent dimension

Build 1.7.2-10.12.2.1127:
	thog92: Add missing 1.7 biomes to BiomeDictionary

Build 1.7.2-10.12.2.1126:
	nemesis:
		Fixed ArrayIndexOutOfBoundsException in getOreName
		
		Added sanity check to prevent ArrayIndexOutOfBoundsException in getOreName for negative ids.

Build 1.7.2-10.12.2.1125:
	LexManos: Fixed vines generation for hanging off of trees.

Build 1.7.2-10.12.2.1124:
	bloodshot:
		Don't call ChunkDataEvent.Load async
		
		ChunkDataEvent.Load must be called after TE's are loaded since this is
		what mods expect. The event is handled by ChunkIOProvider during
		callStage2.

Build 1.7.2-10.12.2.1123:
	bloodshot:
		Load chunks asynchronously for players.
		
		When a player triggers a chunk load via walking around or teleporting
		there is no need to stop everything and get this chunk on the main thread.
		The client is used to having to wait some time for this chunk and the
		server doesn't immediately do anything with it except send it to the
		player. At the same time chunk loading is the last major source of file IO
		that still runs on the main thread.
		
		These two facts make it possible to offload chunks loaded for this reason
		to another thread. However, not all parts of chunk loading can happen off
		the main thread. For this we use the new AsynchronousExecutor system to
		split chunk loading in to three pieces. The first is loading data from
		disk, decompressing it, and parsing it in to an NBT structure.  The second
		piece is creating entities and tile entities in the chunk and adding them
		to the world, this is still done on the main thread. The third piece is
		informing everyone who requested a chunk load that the load is finished.
		For this we register callbacks and then run them on the main thread once
		the previous two stages are finished.
		
		There are still cases where a chunk is needed immediately and these will
		still trigger chunk loading entirely on the main thread. The most obvious
		case is plugins using the API to request a chunk load. We also must load
		the chunk immediately when something in the world tries to access it. In
		these cases we ignore any possibly pending or in progress chunk loading
		that is happening asynchronously as we will have the chunk loaded by the
		time they are finished.
		
		The hope is that overall this system will result in less CPU time and
		pauses due to blocking file IO on the main thread thus giving more
		consistent performance. Testing so far has shown that this also speeds up
		chunk loading client side although some of this is likely to be because
		we are sending less chunks at once for the client to process.
		
		Thanks for ammaraskar for help with the implementation of this feature.
		
		This commit is based off the following :
		
		Bukkit/CraftBukkit@b8fc6ab2c12e9b4c8d7b5370e44f23cc838014b2
		Bukkit/CraftBukkit@85f5776df2a9c827565e799f150ae8a197086a98
		Bukkit/CraftBukkit@0714971ca2a31bc729bdd78ded8c69ffb2284813
		Bukkit/CraftBukkit@7f49722f457dcc31f8cac8e011871ff1b7fd3306
		Bukkit/CraftBukkit@53ad0cf1abe9c060ef411a86e9a16352f3e5197e

Build 1.7.2-10.12.2.1122:
	antoine.lucas.33: Add missing onLivingJump calls

Build 1.7.2-10.12.2.1121:
	LexManos: Pop version for new Recomended build.

Build 1.7.2-10.12.1.1120:
	Christian: Warn when chunks are being self-recursively loaded. This can cause serious issues. Modders should watch out.
	Christian: MinecraftForge/FML@1a99ec7db612f258983c6ac685da906bf7cde0a6 Deprecate getAABBPool so people can stop using it in mods. Failure to do so will result in 1.7.10 upgrade incompatibility. Use getBoundingBox instead.

Build 1.7.2-10.12.1.1119:
	LexManos: Changed dustLapis to gemLapis to make OM SHUT THE HELL UP.

Build 1.7.2-10.12.1.1118:
	LexManos: Fixed missed metadata offset, and now cache return values of getOres for speed.

Build 1.7.2-10.12.1.1117:
	cojomax99: World fog color and density can now be controlled through an event

Build 1.7.2-10.12.1.1116:
	diesieben07: Fix not being able to change target & attackDamage for EnderTeleportEvent.

Build 1.7.2-10.12.1.1115:
	LexManos: Fixed inverted player parameters in PlayerEvent.Clone, Closes #1142 Closes #1140

Build 1.7.2-10.12.1.1114:
	LexManos: Changed EntityWolf to EntityTameable in EntityLivingBase.attackEntityFrom, to allow for more custom pets. Closes #1141

Build 1.7.2-10.12.1.1113:
	LexManos: Rework OreDictionary's internals to be a bit more speedy to help combat modders using it inapropriatly. Closes #1022 Closes #1131

Build 1.7.2-10.12.1.1112:
	Christian:
		MinecraftForge/FML@e3ce211cc798f4d86ca6f974d9ba8b4e389b4dc9 Nullcheck the dispatchers on players. Should stop some crashes when spamming connectivity.
		MinecraftForge/FML@480bf2c1d078038bb59c4254a01a5af685c7cb22 Fix REPLY handling in SimpleNetworkWrapper. Closes  #440

Build 1.7.2-10.12.1.1111:
	LexManos:
		Fix inverted parameters in OreDictionary.getOreID Closes #1123
		-.- Closes #1120

Build 1.7.2-10.12.1.1110:
	Adubbz: Greatly simplified the addition of new biomes to the default world

Build 1.7.2-10.12.1.1109:
	LexManos: Added Noteblock change and play events. Closes #1027 #1025

Build 1.7.2-10.12.1.1108:
	LexManos: Add target world to PlayerInteractEvent for potential 'cross dimension' interaction such as LittleBlocks. Closes #1071

Build 1.7.2-10.12.1.1107:
	LexManos: Add a couple of localizations to Forge added strings. Closes #1068

Build 1.7.2-10.12.1.1106:
	rwtema: Fixed setBlock not using the location-specific version of getLightOpacity()

Build 1.7.2-10.12.1.1105:
	LexManos: Filter all vanilla blocks that we missed through Forge's getDrops and BlockDrops events. As well as implemented IShearable for DoublePlants and DeadBushes. Mojang really should generic out some of this stuff instead of repeating logic all over the place!

Build 1.7.2-10.12.1.1104:
	LexManos: Fix patch fuzz
	LexManos: Fixed GuiContainer calling button.mouseReleased. Closes #1116
	LexManos: Add comment to RotationHelper telling modders where to actually look, closes #1115

Build 1.7.2-10.12.1.1101:
	diesieben07:
		Add PlayerEvent.StartTracking and .StopTracking & make trackedEntityIDs visible
		& Update, as discussed on IRC (squash)

Build 1.7.2-10.12.1.1100:
	vilim.lendvaj: Make finite fluid blocks drainable

Build 1.7.2-10.12.1.1099:
	LexManos: Fix enum helpers for EnumRarity {moved to Commn and changed paramter} and EnumCreatureType {new parameter} and added junit test for them. Closes #1009

Build 1.7.2-10.12.1.1098:
	Christian: MinecraftForge/FML@1d41aa978d41267e4040ec449e10f49a20edd4fa Fix the side for the compatibility check. Should result in green ticks finally!

Build 1.7.2-10.12.1.1097:
	LexManos: Change IShearable JavaDoc by one line so Anti would shut up. Closes #1054

Build 1.7.2-10.12.1.1096:
	Christian: MinecraftForge/FML@4512f8e5e316ddaf6a4fe35470f1f88dcdddae1a Warn when the objectholder finds nothing in the registry. Helps debug mismatched names. Also, actually make the scoping thing work with objectholder

Build 1.7.2-10.12.1.1095:
	fry: Added world display list render events

Build 1.7.2-10.12.1.1094:
	foka_12:
		Fix getOreIDs not using the wildcard value correctly
		
		You can see it's not working by requesting the ore IDs from lapis, and you'll see the name "dye" is missing (and that's the one registered using the wildcard).
		
		Fixed it by inverting the order of the item stack parameters.

Build 1.7.2-10.12.1.1093:
	LexManos: Prevent duplciates in registered Ores in the OreDictionary and clean up some of the code, add new function to return all ores the specified ItemStack satisfies. Closes #1102

Build 1.7.2-10.12.1.1092:
	vilim.lendvaj:
		Fix fluid blocks
		For https://github.com/BuildCraft/BuildCraft/issues/1843 .

Build 1.7.2-10.12.1.1091:
	LexManos:
		Updated FML:
		MinecraftForge/FML@3aba56440aa7a95f6431efcdcb5c127ebafc8891 lastIndexOf, Note Don't code while sick.

Build 1.7.2-10.12.1.1090:
	LexManos:
		Updated FML:
		MinecraftForge/FML@c828bb63c57cb10c23d9b1c3a6934e9f9ddba37b Make AccessTransformer change INVOKESPECIAL to INVOKEVIRTUAL when making methods visible
		MinecraftForge/FML@a9aa468457a1eeed3366505b93e36da654610f05 Merge pull request #431 from diesieben07/at-invokevirtual
		MinecraftForge/FML@31d726abad0dec6d1b853e9adf6a01580aee2af4 Fix the null networkHandler in the MessageContext
		MinecraftForge/FML@725d988e36a7b104b9f5d8ae2daf993ac12af5bd Add in the objectholder, autopopulated by FML based on simple rules. Allows for reference driven substitution of mod blocks and items based on their server running state.
		MinecraftForge/FML@f07bf5cb30a20ca9f62337512e936cfefcfbf0c4 Fixed deobfusication of nested inner classes. And removed legacy ModLoader remaps.
	LexManos:
		Updated FML:
		MinecraftForge/FML@3a687f48b9606b4f9179d63ef0b831a25821ff8f -.- Save File First. My Bad.

Build 1.7.2-10.12.1.1088:
	LexManos: Add Glass, Colored glass, ore storage blocks, alines, and a few others to ore dicitonary. Closes #1011

Build 1.7.2-10.12.1.1087:
	clashsoft: Update GuiScreen.java.patch
	LexManos: Add new PlayerEvent.Clone called when an EntityPlayer is cloned via dimension travil or respawn.
	LexManos: Made WorldGenShrub respect Block.canSustainPlant, Closes #1096

Build 1.7.2-10.12.1.1085:
	delma:
		Fluid events now know how much fluid is moved
		
		Added amount that is being filled/drained to the FluidEvent
		
		Added constructors without amount to ensure backwards compability
		
		Added deprecation to amountless constructors

Build 1.7.2-10.12.1.1084:
	LexManos: Fixed Stems not droping a random number of seeds based on metadata, Closes #1087

Build 1.7.2-10.12.1.1083:
	xcompwiz:
		Bug Fixes to Biome Decoration and Chunk
		Fixes issue with biome decoration crashing on worlds with exposed void
		Fixes same issue in JungleBiome decoration
		Fixes forge bug in getting lighting from a block in chunk

Build 1.7.2-10.12.1.1082:
	LexManos: In Flower Forest biome a Poppy should spawn instead of Blue Orchid Closes #1078
	LexManos: Added Farmland to PLAINS type plants as that has changed in 1.7. Also made BlockTallGrass call it's super.canBlockStay to better support custom soils. Closes #1077
	LexManos: Added accessible instance to RenderBlocks and RenderItem for modders to use who don't wish to create there own instance. Warning: Other modders may influance the transient state of the instance, BE WEARY MODDERS.

Build 1.7.2-10.12.1.1081:
	Christian: MinecraftForge/FML@43e3ee1af1cab54db238dab4994076fdbe68bc6a Swap Listenerlist constructor around. Should fix parent resizing issue?

Build 1.7.2-10.12.1.1080:
	Christian: MinecraftForge/FML@70570a863ffa6a3ba7e2dd30b471bb47615b8bf8 Fix up possible CME

Build 1.7.2-10.12.1.1079:
	Christian: MinecraftForge/FML@503da3a2577a069b7847c158a27e8316c85ed852 Don't consider null NetworkDispatchers. This should fix a bunch of fakeplayer issues.

Build 1.7.2-10.12.1.1078:
	LexManos: Fully clear DimensionManager's DimensionID bitset when world is loaded. Closes #1074
	LexManos: Fixed No Blue Orchids spawn in swamp when using bone meal Closes #1072

Build 1.7.2-10.12.1.1077:
	Christian: Fix forge validating strict versions on remote connections.

Build 1.7.2-10.12.1.1076:
	Christian:
		MinecraftForge/FML@a8cbef2321a8e1bdfac56476bdfb5b306f71d38b Finally hopefully fully kills the race condition causing a classcast on slow machines.
		MinecraftForge/FML@8dbd1ae0a177a556d03630a059242a2ee7f45e55 Fix ObjectIntIdentityMap sporadically matching non-identical objects.
		MinecraftForge/FML@42713c66e565a26e963099baa838800f250089c3 Merge pull request #426 from sfPlayer1/master

Build 1.7.2-10.12.1.1075:
	Christian:
		MinecraftForge/FML@d8b6adb2598ce144568a0aaf26fa8b988c028b7c Add a helper for casting some common collection types into generic form
		MinecraftForge/FML@5275cea844a6afacc0deb41d153f01c1c25bb924 Try and see if there is anything to the identityHashCode collision hypothesis. If you see this in your error messages, kindly let us know!

Build 1.7.2-10.12.1.1074:
	LexManos:
		Updated FML:
		MinecraftForge/FML@a70308ef41f1e24074ea718f64caf75b8d6acba7 Update mcmod.info
		MinecraftForge/FML@8555344eb33e4f0cc676defdb7391a24ebd5677d updated wrapper to gradle 1.12
		MinecraftForge/FML@1d5fc60f82e911c1abfbebbe781316126c02c987 Merge pull request #411 from matthewprenger/master
		MinecraftForge/FML@3612ad0c25d103ba9bc81b32e8ecfef2dfc1cadc Attempt to fix another race condition related to reading NetClientHandler.
		MinecraftForge/FML@c73a2076e3dd5d1f60c2fe2f589109cefa2dc6ce Fix potential rance condition in connecting to vanilla servers as well. And move latch into client side only.
		MinecraftForge/FML@1436ac2f14fbdb48777c90b1b93378108c9cbf36 Fine use FMLCommonHandler.
		MinecraftForge/FML@542e9acec1016c950c6f80af0c9da3190691359b documented dependencies
		MinecraftForge/FML@ddc2cfbe864bd377232dbd1aa65df6e710d4639d Merge pull request #402 from AbrarSyed/patch-1
		MinecraftForge/FML@362ec8dee7ed2c291a8ed287c52eacdd80582eff Merge pull request #419 from Thog92/master
		MinecraftForge/FML@b9de9ebc960bbf26e7aee570701aa4c226252fee Revert "Fix refreshResources not happening if an error occurs."
		MinecraftForge/FML@738ce1d7cd5575269375066586d0a37881c536e2 Re-add removed genericiterable to clean a warning
		MinecraftForge/FML@b0eb1ef7c6f4a63689898bf28f28e84d2dbae6e7 Split loadmods into loadmods and preinitmods, to allow resource loading to occur *always* between the two phases. This should fix mods not being able to access resources during preinit.
		MinecraftForge/FML@de546bdf6cbeadb612cd6385bac8d54480073496 Clean up some missing generic info
		MinecraftForge/FML@cd43eacbb25bc9cc0e81138844fa3aa7fd133037 Ensure that the loadcontroller is ready to preinit.
		MinecraftForge/FML@f2fe80dc36972fe9db57e700380b6869abbc1832 Fixed default network mod checking to allow client side mods without the server side. Mods wishing to REQUIRE server side components must specify a custom check handler using @NetworkCheckHandler
		MinecraftForge/FML@0c36868f92a3516c83ae363e13e5cb1db81236d1 Fix network disconnect with message on the client side in NetworkDispatcher.

Build 1.7.2-10.12.1.1073:
	bspkrs: Fixed unforeseen NPE

Build 1.7.2-10.12.1.1072:
	LexManos:
		Revert "Implemented hashCode and equals in ItemStack, Closes #986"
		
		This reverts commit 0b01545a03942abca7b7ea28030be81e2ebeaa59.

Build 1.7.2-10.12.1.1071:
	LexManos: Implemented hashCode and equals in ItemStack, Closes #986

Build 1.7.2-10.12.1.1070:
	LexManos: Fix extended entity properties being lost when leaving the end, This introduces the concept of calling IExtendedEntityProperties.init when entites/worlds change. Lets see if mods explode.

Build 1.7.2-10.12.1.1069:
	bspkrs: New GuiScreen events and a new ElementType DEBUG for RenderGameOverlayEvent

Build 1.7.2-10.12.1.1068:
	LexManos: Added new hook to WeightedRandom.getItem that allows for use of custom rnadom generators, prevents redundant code in mods.

Build 1.7.2-10.12.1.1067:
	LexManos:
		Updated FML:
		MinecraftForge/FML@2c56c32c5aa8842cfadaf8c237396cdb75673909 Fix saving backups with the raw name. Fix air block not being assigned as the default.
		MinecraftForge/FML@d0f8073fa51db7426d5ded373f3404fa60d722f0 Merge pull request #413 from sfPlayer1/master
		MinecraftForge/FML@810b1f3075e6061ab189e1f6975bd77b20040d71 Clean some generic warnings up. Make a generic list handler. Helpful for others I think too.
		MinecraftForge/FML@fff86ee9d35874bdf77a1eaabe77615441644064 Fix refreshResources not happening if an error occurs.
		MinecraftForge/FML@76d8d0e870a4e389167634283984dc10abb08e84 Fix mod version checking
		MinecraftForge/FML@b84d0760ae47832e5b1e4d50237b582b2d50d520 Fix display of mod status at the server
		MinecraftForge/FML@251af1d09dfbf636e2fb3f323a5345c81cc07aea Fixed memory leak on the client caused by Netty holding references to the World.
	LexManos: Fixed hard references in WorldGenBigTree and ForgeCommand that caused worlds to leak in the client.

Build 1.7.2-10.12.1.1066:
	lhb:
		Fix for Block.getExplosionResistance getting passed the wrong parameters
		
		It is being sent the x, x, y coordinates instead of x, y, z

Build 1.7.2-10.12.1.1065:
	CovertJaguar:
		Fix issue with flexible rail return value
		
		Between 1.6 and 1.7 the return value to BlockRailBase.isFlexibleRail()
		was inverted. While this is not a huge deal and could be worked around
		by simply inverting your return value, it does mean its no longer
		consistent with the function name and javadocs.
	bioxx2007: Adds a new ReplaceBiomeBlocks Event constructor that supplies the metadata array if applicable and updates the ChunkProviderGenerate class to pass in the metadata array.

Build 1.7.2-10.12.1.1061:
	bspkrs: get a spelling checker :P

Build 1.7.2-10.12.1.1060:
	LexManos: Bump Forge version in prep for release.

Build 1.7.2-10.12.0.1059:
	LexManos: Try and fix invalid framebuffer depth/stencil setup, Thanks Ivoforce. Closes #1032

Build 1.7.2-10.12.0.1058:
	apricefrench2d:
		Fix infinite loop in RecipeSorter
		
		If recipe is multiple levels of inheritance from Object and not categorized, cls=cls.getSuperclass(); needs to be repeated more than once. It must therefore be moved to inside the while loop.

Build 1.7.2-10.12.0.1057:
	ohai.iChun: Fixes stencil buffers on platforms not supporting OpenGL 3.0 or higher.

Build 1.7.2-10.12.0.1056:
	LexManos:
		Small wording change in license to allow for specifc differnet licnense contributions.
		
		Updated FML:
		MinecraftForge/FML@e58562d3edfd1cd37fdc0a9e54181aed7433fdff Fix remaining issue with autoassigned Block and Item IDs overlapping.
		MinecraftForge/FML@a82195772e539437911c25508168cb607659bc71 Registry: Block IDs after failing to find a mapping for them
		MinecraftForge/FML@fd9389015fd5c6150155531bf1fffb38cfe9d551 Fix FMLMissingMappingsEvent.get
		MinecraftForge/FML@5eebd4df718d65ac8426deba61e1ebb6ae2fde18 Registry: Implement support for remapping blocks/items to a new name.
		MinecraftForge/FML@7325aa5033e7a5b5db79340777dd7a1c763315a0 Registry: cleanup, fix missing id error GUI formatting
		MinecraftForge/FML@eb29d651ebda7086fe6d1f716295b087e2c17e6f Fix old 1.7 worlds with broken ID mappings
		MinecraftForge/FML@6fd3c12a4a15a5cf38c421a94576a5cacd3fb7c1 Registry: allow handling missing blocks/items regardless of the mod id
		MinecraftForge/FML@038fa17ad33aeba276db84ab170504fce884c1e7 Merge branch 'master' of https://github.com/MinecraftForge/FML
		MinecraftForge/FML@49c623f59c440ba177adf2d76332ecee25e12236 initial attempt at a better way to ask the user in case of startup issues
		MinecraftForge/FML@9be92dcfcb1c737025397c92b18ed027a6c7f4fa Registry: Complain about bogus registrations
		MinecraftForge/FML@fd6d55afcc4f4c650c143ad43e09fbdc2cb9d850 Registry: Allow ignoring missing mods from the GUI, with confirm+backup
		  Registry: Add confirm+backup for automated corrupted id table fixup Require the user to confirm loading from a backup level.dat
		MinecraftForge/FML@c47fc3b382434d435050b4ee02a02550b81f5717 Enable custom gui rendering only as required
		MinecraftForge/FML@f77632df35dbf53fb31420fa86e6792f13257020 Remove unneeded entity spawn debug logging.
		MinecraftForge/FML@c7adb42199a0684d8748451d39deb8326c0a2194 Registry: Repair mismatched ItemBlocks as well Fix a few misc issues
		MinecraftForge/FML@c8a245a985779fd2545ee4b58a93270973aeb435 Registry: Fix debug info
		MinecraftForge/FML@c8a0b72eba9265be608670424e1bd835a9d2f1e2 Registry: Complain about missing mods when repairing broken worlds Registry: Reduce console spam
		MinecraftForge/FML@8e44006f432f1b36b826ff0469d99986a6051e4b Registry: Protect against putObject misuse, handle duplicate registrations better
		MinecraftForge/FML@294c93212cd9f30c50b9d1a3b048a6141c45cdea Registry: Add support for registering ItemBlocks before their Blocks
		MinecraftForge/FML@3b42b33b6ec4020b5032cae06760053ed135fae8 Merge pull request #400 from sfPlayer1/master

Build 1.7.2-10.12.0.1055:
	traincrazyb:
		Small Fix: Held Items & Multiple Render Passes
		
		Passes beyond 1 now have the correct icon.

Build 1.7.2-10.12.0.1054:
	LexManos: Fix line offset in Minecraft patch, and mix RenderPlayer looping once to many on multi-pass items.

Build 1.7.2-10.12.0.1053:
	t.tomkins: Update PlaySoundEvent17.java

Build 1.7.2-10.12.0.1052:
	LexManos: Update access transformer, Closes #951 and #1021
	LexManos: Add NPE protection to GuiingameMenu.actionPerformed, Closes #961
	LexManos: Finally do SoundSystem workup for 1.7, Closes #982

Build 1.7.2-10.12.0.1051:
	LexManos: Use BiomeGenBase's array size instead of hardcoding it in BiomeDictionary. Closes #871
	LexManos: Fix potential threading issue if FluidRegistry.loopupFluidForBlock is called from two threads at the same time before being setup. Closes #936

Build 1.7.2-10.12.0.1050:
	LexManos: New hook to truely seperate the display of the 'durability' bar from the current / max durability. Allowing modders to control that display easier.
	LexManos: ItemStack sensitive version of Item.getAttributeModifiers, Closes #816
	LexManos: Add ANIMALS tpe to PopulateChunkEvent.Populate Custom providers should call this function if they spawn animals curing population. Closes #790
	LexManos: Add AnvilUpdateEvent which is fired when a user places a item in both input slots of a Anvil and allows modders to control the output. Closes #838

Build 1.7.2-10.12.0.1049:
	LexManos: Add position to BreakSpeed event. Closes #621
	LexManos: Advanced Model Loader available server-side for data driven models. To be cleanuped and re-evaluated in 1.8. Closes #773

Build 1.7.2-10.12.0.1048:
	Abrar Syed: COnverted patches to SRG names
	Abrar Syed: updated for ForgeGradle 1.2
	Abrar Syed: added .exe file.. fixed a bunch of patches
	Abrar Syed: updated FML to latest master
	Abrar Syed: fixed remaining noop patches and exc derp
	LexManos: Update patches for new Fixed FernFlower used in FG 1.2.

Build 1.7.2-10.12.0.1047:
	reflex_ion:
		This correctly uses the world height less one block for placement of a
		Door.
		
		Required for placing doors inside a littleblocks area.

Build 1.7.2-10.12.0.1046:
	LexManos: MinecraftForge/FML@ef07de4f65ea16e1db1467845e316cb4c7d01a1f Fix hard link to DedicatedSerever when opening a LAN connection causing stalls on connecting.

Build 1.7.2-10.12.0.1045:
	LexManos: -.- Both null combinations.

Build 1.7.2-10.12.0.1044:
	LexManos: properly implement equals, sod off Player.

Build 1.7.2-10.12.0.1043:
	LexManos: Implement simple hash based equals in Fluid ContainerKey.

Build 1.7.2-10.12.0.1042:
	LexManos: Make StructureVillagePieces.Village public.

Build 1.7.2-10.12.0.1041:
	ohai.iChun: Fixes stencil bits not existing in Minecraft's framebuffer causing stencil test to not work.

Build 1.7.2-10.12.0.1040:
	LexManos:
		Updated FML:
		MinecraftForge/FML@e8b60441ccca8cccdc130560b4c8bf400aebc605 Reload game settings after mod loading is finished to capture mod keybindings. Closes #378
		MinecraftForge/FML@399770e572c9177babfb65a27280253023db2d9e Kill the modEventTypes list, register anything that extends FMLEvent, Fixes MissingMappingEvent handler, and any futureevents added.
		MinecraftForge/FML@b7ad532ab5eb3e00d77ffde946d25675c9f69cf7 Re-enable post initalize texture pack reloading to allow Icons to be registerd through any init phase.

Build 1.7.2-10.12.0.1039:
	t.tomkins:
		Small Fix: Held Items & Multiple Render Passes
		
		Passes beyond 1 now have the correct icon.
	DemoXin: * Added Ore Dictionary entries and recipe replacements for Diamond, Emerald, Crops, Redstone, and Glowstone
	DemoXin: * Fixed Items.glowstone to Items.glowstone_dust

Build 1.7.2-10.12.0.1034:
	LexManos: Fixed hashcode in FluidContainerRegistry, still needs a redesign. Closes #967

Build 1.7.2-10.12.0.1033:
	ohai.iChun: Add cancelable RenderHandEvent.

Build 1.7.2-10.12.0.1032:
	LexManos: Fix a typo in our tile entity fix causing it to be ineffective.

Build 1.7.2-10.12.0.1031:
	LexManos: Fix items with color rendering incorrectly.

Build 1.7.2-10.12.0.1030:
	Christian:
		Update Forge for patch changes
		
		MinecraftForge/FML@064b66af3d6c92b19821b88ec26cbb59577d68b4 Prevent players from logging in until server has finished starting.
		MinecraftForge/FML@2aa73afa15908dadb0a033c49deb0ffefad2f265 Fix ExampleMod.java for build #1024+
		MinecraftForge/FML@c890206268da3c594d97198f5426b52ff6b8460c Try and handle removal of mods a bit better. Currently no way to allow a world which has missing blocks to load - but i have the code in place to allow it i think.
		MinecraftForge/FML@995c204338cd601e118396d4b4ef8feb6e759037 Fix failing to load a world with missing mod blocks and items. There will be a way to force worlds to load when stuff is missing, but for right now, it will fail as this is "world safe".
		MinecraftForge/FML@fa5f4c884272f415933329a9e914e0b7d052e31a Some argumentation
		MinecraftForge/FML@45409bfa0c136078823a1aef1358396d92a269ee Prevent player dat files getting reset during disconnects.
		MinecraftForge/FML@33100d6bab654a4bd59701b1ec2bf91caa3399da Merge pull request #371 from bl4ckscor3/patch-1
		MinecraftForge/FML@572d32358ab11e5916d91c4c7b9c04a70cfed2f6 Merge pull request #373 from bloodmc/master
		MinecraftForge/FML@d0dd05a15c2eca9eabd308319c2ed85cb632922b FML expands S3F to support payloads up to 2 megs in size. Should be transparent

Build 1.7.2-10.12.0.1029:
	LexManos: Fixeed a missed -1 in SpawnerAnimals patch. Thanks Blood.

Build 1.7.2-10.12.0.1028:
	LexManos: Cull FakePlayers when worlds are unloaded.

Build 1.7.2-10.12.0.1027:
	LexManos: Use correct tag types when reading Forced Chunk data. Fixes ticket loading. Closes #964

Build 1.7.2-10.12.0.1026:
	LexManos: Fixed FluidContainerRegisry.contansFluid closes #845

Build 1.7.2-10.12.0.1025:
	LexManos: Fix AIOOB error with Endermen and blocks >256. Also better support for ID remapping. More to come later.

Build 1.7.2-10.12.0.1024:
	LexManos:
		Updated FML:
		MinecraftForge/FML@03fb1879d72fbd347badc140fed6c2c3191d2990 Fix obf error when right clicking a Empty Map.
		MinecraftForge/FML@6bb9b8b9532b276450d03a3419e0da016aecead8 Clean up FMLEventChannel. Closes #367.
		MinecraftForge/FML@b7b3450dcd123ab5df6b3693c9c2123bc3846b88 Update MCP mapping snapshot to latest crowdsourced names.
		MinecraftForge/FML@8c9e8b52708bd0630303f8b5dc184ab60e2553a1 Fix isRemote, this is integral to so many parts of the code, everyone knows it by this name, People should not change it.
	LexManos: Add the beginnings of a Constants class, to document/clean some of the magic numbers that are in the MC code base.

Build 1.7.2-10.12.0.1023:
	Christian:
		MinecraftForge/FML@d87822ad8519da1c808e48bcc0a1bf8eb15c0095 Bump gradle wrapper to 1.10
		MinecraftForge/FML@359ac3ca2a941d70709168fbbbc0725c861668dd Ensure we check both item and block registries when finding valid IDs. Should fix #365
		MinecraftForge/FML@cee0f0b81179d307059843f08401f8700fb3ddb2 Tweak so that writing to the context will automatically send a message back to the originator in handshakeestablished.
	Christian: Add a discriminator for fluididspacket. remove extraneous channel handler.
	Christian: Fix up the event handler so it knows it's owned by forge

Build 1.7.2-10.12.0.1022:
	LexManos: Uncomment aa few FluidRegistry entries.
	LexManos: Fixed issue where enchantment effects caused slight rendeirng issue.
	LexManos: Fixed missed parens causing trapdoors to fall off incorrectly.

Build 1.7.2-10.12.0.1021:
	LexManos: Inital Fluid system update, untested. Still in progress.

Build 1.7.2-10.12.0.1020:
	LexManos: Fix NPE when breaking ice.
	LexManos: Attempt a AIOOB error fix in tesselator when there are alot of transparent blocks in the rendering range.

Build 1.7.2-10.12.0.1019:
	Christian:
		MinecraftForge/FML@544320b8d239df4a5ee2b3a7ec331ce2ec0a2c09 Beginning of a saveinspectionhandler.
		MinecraftForge/FML@ab199c5811fe2d831592601d4f77691fbf82d1b8 Try harder to find a mod container.
		MinecraftForge/FML@8633d780c925ebb719c37ac52e2f3db5f9957895 And make a loud message if there isn't a modcontainer found, substitute Minecraft. In general, this can only happen for coremods not properly registering their code. Closes #363

Build 1.7.2-10.12.0.1018:
	LexManos: Fix imporerly efficient tools breaking blocks to fast.

Build 1.7.2-10.12.0.1017:
	LexManos: Fixed potential NPE in SlotCrafting, and added ItemStack sensitive version fo hasContainerItem. Closes #854
	LexManos: Adds a WeatherRender in the style of SkyRender, Closes #844

Build 1.7.2-10.12.0.1016:
	LexManos: Move change of metadata to immediatly after change of Block, should prevent any 'invalid' tile entities from breaking created. Reference: #897

Build 1.7.2-10.12.0.1015:
	LexManos: New PlayerUseItemEvents, Start, Stop, Tick and Finish. See PlayerUseItemEvent.java for more details. Closes #924

Build 1.7.2-10.12.0.1014:
	LexManos: Make ItemBlock.field_150939_a public, closes #945
	LexManos: Missing EntityAITasks.tasks and MapgGenStructreIO register ATs, Closes #949
	LexManos: Implement PlayerPickupXpEvent, fired when a player aquires XP from a EntityXPOrb. Closes #942
	LexManos: Exclude cobblestone slab recipe from ore dictification, closes #940
	LexManos: Add the ability for custom records to have finer control over there sound resource location. Closes #933
	LexManos: Don't short circuit item icons for multiple render passes while being used. Closes #929

Build 1.7.2-10.12.0.1013:
	LexManos: Fix Furnace stopping on 63rd Item, Closes #947

Build 1.7.2-10.12.0.1012:
	Christian:
		MinecraftForge/FML@b6d95d704b65dd8232ec8ddd333de378db8fe161 Name the log files properly. fml-junk is an early startup annoyance I can't kill because log4j2.
		MinecraftForge/FML@8692ca17d13eda036b5ef996ec8e8706e7707d80 Log4j2 logging context for things. This should help add context when things go wrong in mods.
		MinecraftForge/FML@a7ca131a337b5f0d4fc6f438626ac2d5b7771b3c And don't spam NONE everywhere
		MinecraftForge/FML@741e172ffe163f0dd3018e1474af46ef0696396a Log4j2 doesn't need debug level logging for itself anymore

Build 1.7.2-10.12.0.1011:
	Christian: MinecraftForge/FML@458b0620b43116c943549a0f060c7e8830c2d77a Log the bad packet in a prettier way. Also, don't show the authlib debug data in the log file.

Build 1.7.2-10.12.0.1010:
	LexManos: Add BookCloning to the recipe sorter.

Build 1.7.2-10.12.0.1009:
	Christian:
		MinecraftForge/FML@9a8d16b66e67691a4c83a9e1e236304e9f6d5139 Fix log4j2 config. Fix server gui to *show* logging. Fix log spamminess in the console. Fix bug in servergui that can cause deadlock.
		MinecraftForge/FML@a355eecb2c14123964c6ae2402a0933d57ae9736 Add in error logging for outbound messages. Fix bug with indexedcodec NPE
		MinecraftForge/FML@1c793abe0eef6846f681c9673019b0ebc49caaaf Fix derp with networkcheck
		MinecraftForge/FML@675b5a07788ada17bc26a9c4f26598e77d2098cf And turn down some more logging, now we have useful logging back again..

Build 1.7.2-10.12.0.1008:
	Christian:
		MinecraftForge/FML@4aa2416ce5dcd8e77761703c018d1e7d08464025 Propagate Optional method removal to trait implementation classes
		MinecraftForge/FML@fc025a7b73d9b3f46ecf2257227657592f5506b5 Logging Changes
		MinecraftForge/FML@f0132a6f3b47e746a1a7df3ef84f4be989f140dd changed fml log level to all
		MinecraftForge/FML@f23eba4352c38fd21e04e81f3db72c6cafe65a36 put max number of FML log files to 3
		MinecraftForge/FML@449ac98b77025eba38a75d0242113fffe26a8cf9 SSP Worlds updating from 1.6 will now pop a warning message before loading, and will capture a timestamped zip file in the minecraft dir before starting to load. Allows for people to test updates.
		MinecraftForge/FML@3557fe31c92ea8d76c90052f9b8b6da963300c4f Throw an exception when discriminator is not found
		MinecraftForge/FML@25240457283ba40c32022c97fc982c2ff4408e46 Make NetworkEventFiringHandler sharable
		MinecraftForge/FML@dfc0899ec66f87502b5727939ac2f0ad0fabf89f Merge pull request #357 from jk-5/sharable
		MinecraftForge/FML@79d42fca8d6b9d73204890ef0edb9d73cf075d87 Merge pull request #355 from jk-5/errorhandling
		MinecraftForge/FML@7907e16e96de21e8ba536906ae71adcf02bfa535 Add a type adapter for artifact version. Should fix #354
		MinecraftForge/FML@7ac5bddbc3c227e0ed9385904a2bd9621078e2de Allow indexed messages to validate themselves. Also, catch exceptions from an embedded channel, and cause them to close the connection. It's ugly, but it means that the client doesn't crash if it connects to a screwy bungycord that's trying a 1.6 handshake for some reason.
		MinecraftForge/FML@5adacc3b336bacbe30aa06175ef80c3aac08a62a Check the mod, not it's container, in the check handler. Closes #358
		MinecraftForge/FML@3d26f28bcf3e79e1f5fe20fcf056c604487dc35b Allow connection when server is apparently offline. Might allow :NOFML circumvention though. Hmmm. Closes #359
		MinecraftForge/FML@a62374d4aceac1c4ab39b3c0bae624ccbca65b6b findBlock should now return null, not the default block, if the thing being looked for is not found. Closes #352
		MinecraftForge/FML@6a695c4348d062af50b8cf5208530fc5036eba17 Try and stop the epic channel closed spam at close time. Closes #353
		MinecraftForge/FML@35a38d7840a5d0cd842005822c4ec6a9d3b65b6a Make sidedproxy support non-public fields. Closes #344
		MinecraftForge/FML@9d2e089df692655df04315a3822f43140015f3af Merge branch 'logging' of github.com:AbrarSyed/FML into abrar-borked
		MinecraftForge/FML@79b04898d43d354714e09ce7e66efb5357ebcf61 And restore suppressions. ABRAR, DON'T TIDY CODE!!!!
		MinecraftForge/FML@3dfb54e066ab91e44405706233f2dfffee9add72 Merge branch 'trait-optional' of github.com:RainWarrior/FML
		MinecraftForge/FML@32bb7315cc6beff84f186a33e73219cc5280821a Add in example assets dir. Closes #308
		MinecraftForge/FML@16d33d298953b41dbbe3e3b504e800f4f46a3e1b Clean up and document outbound handler a bit better. Add in dispatcher target. Closes #361
		MinecraftForge/FML@5719b9ec533b3e43213dbafcb448221884efd9e8 Fix reply handling. Make the proxy message available for subclasses of indexedcodec. Fire user events into the network event firing.

Build 1.7.2-10.12.0.1007:
	LexManos: Add support in Techne models for the TextureSize tag. Closes #856

Build 1.7.2-10.12.0.1006:
	LexManos: Updated FML: MinecraftForge/FML@444a7d7fa1cf7fad7dda67f581fa0e3be36069b7 Move placement of single player world load hook to fix NPEs.
	LexManos: Fixed RenderWorldLastEvent never being called, was missed in 1.7 update. Closes #932

Build 1.7.2-10.12.0.1005:
	LexManos: Fix flexible rails, Closes #944

Build 1.7.2-10.12.0.1004:
	LexManos: Fix warnings in Forge codebase.
	LexManos:
		Updated FML:
		MinecraftForge/FML@7c5d62704ac1d3e586f3bfe26265a534e5362c73 Make UniqueIdentifier final and add a hashCode. Closes #348
		MinecraftForge/FML@ff7b5845e7f6b300d413b917f57adc472a4ebcff Clean up some warnings about @Override
		MinecraftForge/FML@275ccac6f14bc66b88c76b1040aa7167f995967c Fix NPE at startup
		MinecraftForge/FML@2a5a8d0cd062d3feac9c4de234e3dab1ff4462e5 Fix memory leak?!

Build 1.7.2-10.12.0.1003:
	Christian:
		Add exception logging to forge channel handlers as well
		
		MinecraftForge/FML@53557dcd0582e09f7f35eb3bc2fd130fba3be4a0 Put logging exception handlers on all channel inbounds. Fix problem with failure to login. Closes #350

Build 1.7.2-10.12.0.1002:
	Christian: MinecraftForge/FML@9c96ca4402e4c231285f170281dd543bfffa191a Fire a custom packet channel registration/deregistration event, for any mods that care about that kind of thing

Build 1.7.2-10.12.0.1001:
	Christian:
		MinecraftForge/FML@e14efe786f6255a18e148c4137f560f5e2d2a38f Some fixes and tweaks
		MinecraftForge/FML@c013870b1df5e63bd84d92545ebdd434db74b5d1 Merge branch 'simplenet'
		MinecraftForge/FML@30882b0c1d2743afebbebc288d73f25696e0815c Clean up some warnings. Add in simple network impl
		MinecraftForge/FML@9cab2ab36e7981c847e3e9ae8c3fbbb36531ba6d Add in some tests and examples for the "simple" network stuff
		MinecraftForge/FML@a429e106dd00b34302ec5893e0a8fc97c8fc8019 Fix bug with SSP, and hook so we can do confirmation of world loading, as well as other things

Build 1.7.2-10.12.0.1000:
	Christian:
		MinecraftForge/FML@b362e8a2733eb3082975edfdf83c996f048b65d3 At the request of AbrarSyed.
		MinecraftForge/FML@e344303ec7a5ed27c4378ff072a036df7a350902 Merge pull request #346 from Jezzadabomb338/master
		MinecraftForge/FML@a4686b1261a9bad523b4efa8a36a4433a58897cc Added basic Mojang account authentication support for development time login.
		MinecraftForge/FML@dd17979a2f6f02ac4a9dda09b52c96365cc5fec9 Fix bukkit connectivity issue.

Build 1.7.2-10.12.0.999:
	Christian:
		Updated FML:
		MinecraftForge/FML@1db3daa0e82e67fc27ca3d535a09c806c1a54d67 added override toString method for getting full name.
		MinecraftForge/FML@acf74a34032224a73c4c03280cafa0042c35cf5a changed the readme to reflect new setup task.
		MinecraftForge/FML@96c19b35807fa078cb18b4ae50567d0360bcdb03 undid readme change
		MinecraftForge/FML@a89939e57e9ff061df3d53cf1cb075b31de5de1b Merge pull request #336 from jadar/master
		MinecraftForge/FML@717a8d694532bd9438eed8d9cf4b57318b2b4cfd Fix csv string vs list of strings. Thanks immibis. Closes #334
		MinecraftForge/FML@584c0f368bca1d5b0223b5b3611b366b9a00f7d7 Fix potential ordering issue, clean up some imports
		MinecraftForge/FML@28293b29ea65c30fe80c49e85e2ae15a4db68933 Add in a simple(ish) event driven network handling system. Register using newEventDrivenChannel and you'll get a simple network handler that will fire events at the subscriber(s) of your choice, whenever a packet is received. You'll also get some convenience methods for sending to things.
		MinecraftForge/FML@80b00dc7966d96111e2ce8643db8e0f544c2bc89 Fix openGui. Closes #342
		MinecraftForge/FML@fc69bcf2807dc2b85eb52681ba9531cb3e2f1945 Fix up privacy derp in TickEvent. Closes #343
		MinecraftForge/FML@10d056a494aac22137b644cff341a5958e8168fc Fix possible NPE derp
		MinecraftForge/FML@5da6dcc7e3607e5f107f6a7d39a4b4e1eb7fb306 Divert connection through FML, so we can deny connections to servers that don't want us

Build 1.7.2-10.12.0.998:
	ohai.iChun: Squash commits so Lex would stop whining. Fix erroneous position when getting player position with changed eye height.

Build 1.7.2-10.12.0.997:
	Christian:
		Updated FML:
		MinecraftForge/FML@d5bfd69e35b21f701390a8c4c4c58d7ec1fff1fc Fix problem with connecting to vanilla. SHOW what's modded and what's vanilla in the list. Hooks that make the blocking work to come
		MinecraftForge/FML@dd098854b0b65b8509b8788422e02d989a991b87 Fix the keybinding array to the right one
		MinecraftForge/FML@43068eb9862f280611f26f4107ff5ac2b42b08e4 Fix TargetPoint to be static

Build 1.7.2-10.12.0.996:
	LexManos: Attempt to prevent a NPE when MC renders a lot of things at once.

Build 1.7.2-10.12.0.995:
	minalien: Fixed MinecraftForgeClient for custom Item Renderer implementations. Removed check for forward-slashes (/) in texture asset locations (but left check for backslash in place).

Build 1.7.2-10.12.0.994:
	LexManos: MinecraftForge/FML@0d810c01fab99ac491c2277097a4198518fe6c75 Mark jopt needed on the server, herp derp, blame Abrar!

Build 1.7.2-10.12.0.993:
	LexManos: Deprecate BlockFire.func_149842_a, and throw exception if someone tries to set the burn properties for air. Should prevent 'The Air is on fire!' reports.
	LexManos: Fix DoublePlant placement, closes #921

Build 1.7.2-10.12.0.991:
	смирнов антон михайлович: Create ru_RU.lang

Build 1.7.2-10.12.0.990:
	Christian:
		Updated FML:
		MinecraftForge/FML@5317672631f30e1c9655f0bb28dd8b158deea2fb Add a utility method for finding the channel handler name based on type. Should fix naming weirdnesses.
		MinecraftForge/FML@9de9a1553086ebeeb5d5fc0f6d96da8680e52df0 Fix stupid hardcoding derp

Build 1.7.2-10.12.0.989:
	Vexatos: Create de_DE.lang
	Vexatos: Update de_DE.lang
	LexManos: Fixed pipeline naming issue in the ForgeNetworkHandler.

Build 1.7.2-10.12.0.987:
	LexManos: Fixing an infinite recursion case, Closes #916
	LexManos:
		Models now load from resource packs
		Models must now be loaded from resource packs using the standard resource pack reference. For example, to load a model named "assets/mymod/models/mymodel.obj", you would call AdvancedModelLoader.loadModel("mymod:models/mymodel.obj");
		Closes #670
	LexManos: Fix panes/iron bars not connecting correctly. Closes #904
	LexManos: Fixed the run config for dev time server, Cloases #913

Build 1.7.2-10.12.0.986:
	Adubbz: Made canBeReplacedByLeaves default to whether a block isn't opaque rather than if it is, also uninverted the checks for canBeReplacedByLeaves in WorldGenBigMushroom, WorldGenSwamp, WorldGenTaiga1 and WorldGenTaiga2

Build 1.7.2-10.12.0.985:
	Christian: Fix inversion

Build 1.7.2-10.12.0.984:
	Christian:
		Updated FML:
		MinecraftForge/FML@21b13d63512ce399c82cbb6b9042eefa6dcdaacd Lots of network cleanup. Gui packets now work too!
		MinecraftForge/FML@b3f98d1ee0416aa452f8611d458968afdf50775a Fix derpiness with Mods button when Realms is available
		MinecraftForge/FML@cdd9d92a4f8cd199e2d8a34bb398ef32e5f1e275 Starting work on the actual GUI. Still work to do. Needs an API.
		MinecraftForge/FML@ab5eb3ccfff7f9ccfd8720b23fcef3131e54d57d Fix button size for GuiModList
		MinecraftForge/FML@3113138bd1377d71afe3b8290e18511bfb6e5e97 Tweak button positions.
		MinecraftForge/FML@c5e29b574a315d48668ebc9189bcc497a0eae13e Avoiding redundant calls to LogManager
		MinecraftForge/FML@fbc1f8f6f9effa4a538880f9fec0ce5010226d09 Config GUIs in the modlist now work.
		MinecraftForge/FML@fa4f3015a0d7147cbde3edec7664e78e5bcacbb9 Added transparent background for GuiIngameModOptions as per cpw's request. May not compile due to manual de-mcp-fication.
		MinecraftForge/FML@7bf119e1e54cadff690ec31a4bab93c0d1d0aad1 Fix up readmes and credits. We no longer support modloader.
		MinecraftForge/FML@779cd05aa1ced720a63cc508b82e68cc6fc8daa9 Tweaks
		MinecraftForge/FML@b51fb913551a5116cc3b9bb7583b1666f280c650 Merge branch 'patch-1' of github.com:airbreather/FML
	Christian:
		Updated FML:
		MinecraftForge/FML@6f1da6550e10164bd6c678829f111bb5de9383b6 Fix up mcpname derp in GuiScrollingList.

Build 1.7.2-10.12.0.982:
	Adubbz: Fixed sky colour transitions on a render distance of 16, fixed the WorldGen of various things

Build 1.7.2-10.12.0.981:
	jk-5: Update ForgeMessage.java
	jk-5: Added a constructor and made the fields package-private
	jk-5: Added default constructor for reflection

Build 1.7.2-10.12.0.980:
	LexManos: Update patches for AT changes.
	LexManos: Fix inverted login in BlockPistonBase causing blocks to break incorrectly. Closes #910 #909

Build 1.7.2-10.12.0.979:
	Christian:
		Updated FML:
		MinecraftForge/FML@22ba6fda5ee2dbf29dc03ba93ff9c7707edeaeee Expose the nethandler in a few places, and pull out FMLEmbeddedChannel, exposing a utility method on it. More to come.
	LexManos: Update for the FMLEmbeddedChannel change.

Build 1.7.2-10.12.0.977:
	Christian:
		Fix build.gradle for tweakClass property
		
		Updated FML:
		MinecraftForge/FML@f36152398d1d287e7a55a31c77a2614cfb63e1b6 Add in the tweakclass, fix the json for lzma @ the server.

Build 1.7.2-10.12.0.976:
	Christian:
		Updated FML:
		MinecraftForge/FML@5d069629cf47cd04f2002b3b9a2c32b0ea73c26e Allow itemstacks for furnace recipe inputs. Allow passing extra arguments through registerblock into the itemblock constructor.

Build 1.7.2-10.12.0.975:
	Christian:
		Updated FML:
		MinecraftForge/FML@061288909de0f0452adf51a5a9935fd09992c801 Fire simple network connect/disconnect gameevents.

Build 1.7.2-10.12.0.974:
	Adubbz: Made BlockCrops.getDrops call its super method

Build 1.7.2-10.12.0.973:
	Christian: Fix the network handler for forge

Build 1.7.2-10.12.0.972:
	Christian:
		Updated FML:
		MinecraftForge/FML@34819c9303870f560232464a2d16eb46d152515c Make gradlew executable on linux
		MinecraftForge/FML@53a1f9841421b41d543d7d1d51319b44c86a527e Attempt to load old pre-1.7 worlds. ENSURE YOU HAVE A BACKUP!
		MinecraftForge/FML@6a5f9e135f88b662e4e01e8882f861448910ca90 Fix example mod code for 1.7

Build 1.7.2-10.12.0.971:
	Christian: Allow tools to override their material harvest levels.

Build 1.7.2-10.12.0.970:
	Christian: Tidier implementation of previous commit. Should fix for subclasses of individual tools too

Build 1.7.2-10.12.0.969:
	Christian: Add in harvesting abilities of the items, should fix effectiveness

Build 1.7.2-10.12.0.968:
	Christian:
		Updated FML:
		MinecraftForge/FML@f8d6213829d570501166d64d7c8bb4977567131f Update render registry
		MinecraftForge/FML@ec316f113fefef12f6defed9eb68de368d7f4420 AT for renderblocks

Build 1.7.2-10.12.0.967:
	LexManos:
		MinecraftForge/FML@3714426e19f8f0edaaeda8c787993f8f3615a44d fix derp in example builscript
		MinecraftForge/FML@01fb451b6918599de5e732d7ff30c761438ab930 Merge pull request #311 from AbrarSyed/patch-3
		MinecraftForge/FML@30d532f4fc6fc65ea7e79707a75ff4d6ea0ea031 Pass 1: Most patches are restored.
		MinecraftForge/FML@53127eec308d3929d68d3d9fafabcfef37e95c37 Merge branch 'master' of github.com:MinecraftForge/FML
		MinecraftForge/FML@7ab3c3a37ceb8ab945208206aec86739a2138329 Update gitignore
		MinecraftForge/FML@38cec7a11fae7cf12bda3a8d16a50bb6136d8886 The basic network handshaking for FML is done. All scenarios seem to work.
		MinecraftForge/FML@9f928963f20bc9bbfbe1391fb16c6f5ca5fd4344 A network design I like. It uses the netty embedded channel to allow mods to build channel pipelines on top of custom payload packets.
		MinecraftForge/FML@58f7487cfaf4a25a8349021b9cca5ef4ba0b541c Check in patches. Add in some network timeout tweaking values so you can debug the network.
		MinecraftForge/FML@e544adba5c7e9286f917342af2669e5888fa0a17 More cleanup. Bidirectional server <-> client network works for mods as well as FML|HS now.
		MinecraftForge/FML@f5c38e2359c2e6eca13cd6606465ee36086a7113 OK, network channels appear to be working well for both dedi and integrated servers. The beginnings of the new mod structure too.
		MinecraftForge/FML@9c96a0a10a5cbe34786be8fd41f9818b5ac929bc More network stuff, partially done id syncing.
		MinecraftForge/FML@2aaaeba15eabdec189daa8662e9ffdf0b5a09dbe ID loading from the server save now works.
	LexManos: Kill liquids finally.
	LexManos: Bump data for 1.7 start.
	LexManos: Some work on 1.7, waiting for Abrar to fix a few things.
	LexManos:
		Updated FML:
		MinecraftForge/FML@a30f17362764f3e4e594386e193f9e4368e6836e Add sonatype snapshots repo for SpecialSource snapshots.
		MinecraftForge/FML@b2550b8a693315ccc205f5315eac67c5283d7af9 Add mappings for Items/Blocks fields.
		MinecraftForge/FML@57f7f1d7abd304d3e9f42567f1d66c10122e4ec6 Update for fixed Enum cleaning and names.
		MinecraftForge/FML@99c681ad8736e4976053718c3d453b2fb30eefe0 Did it manually, forgot it needed the end comma
	LexManos:
		Updated FML:
		MinecraftForge/FML@1d71c017f45aa7ed9d7d7c5ed5250a8d22477980 ID syncing.
		MinecraftForge/FML@fd36f50d8210342f65cb0272bac56a3bcc42dd18 Cleanups
		MinecraftForge/FML@89e4e483c204c11b6fdfed34893fc223a7d6a899 Add in a remapping event for mods to consume.
		MinecraftForge/FML@cd417c6786256fa23f181ff0b76696bc6dfb0291 Fixed remote and local connections work with mods now.
		MinecraftForge/FML@ef492407ef812bb6bbc7f0bd8efbd16d07efcafb Entity spawning works.
		MinecraftForge/FML@d0d31d9575403eb2ec058898b86ffd99a9220f75 SpawnAdjustment packet. Clean up stuffs. No more compile errors.
		MinecraftForge/FML@3e278acb71e4e3d0406e80f0fad5071c9215ed33 Fix stupid possible compiler error.
		MinecraftForge/FML@009d4dee2328cc8d97b74177a2c5a3c359e6564a Fix the exc file. Fix the deobfremapper for handling inner classes.
		MinecraftForge/FML@49cb893d12bd4f82b5d1b50d1e6517a256525d32 Fix exc this time *sigh*
		MinecraftForge/FML@31efcfc3b2085f5d4e070ddab34a0be1481b4c6f Clean up patches for latest exc.
		MinecraftForge/FML@7a4ceebf5efe5b3650080cf912e371d92fc70a55 Kill old patches and add rejects to ignore file.
		MinecraftForge/FML@7ea571f593464ad4226ba845da27ff66161621b1 Fix AT, Fix exc. Almost works now!
		MinecraftForge/FML@b852e302851cfaf77e1db6f86408e8d049703656 First functional release under reobfuscation.
		MinecraftForge/FML@df870c1a3341d8e2e88d7fc3e2f3d9ed2507989f Update shiped ForgeGradle for 1.7
		MinecraftForge/FML@55aa337f952bc72c5a001a6ed661978b11822c63 Rename synthetic bridge methods, these methods are not decompiled, but need to reobf correctly cross the recompile boundary.
		MinecraftForge/FML@0098c57f94808751062ee45f2ee267324bb42089 Merge pull request #316 from AbrarSyed/patch-4
	LexManos: Comment out fluids until King gets his hands on it
	LexManos: Killed a few hundred compile errors.
	Christian:
		Moved the core event handler parts to FML. Implemented the Forge network handler based on the new
		netty strategy.
		
		Updated FML:
		MinecraftForge/FML@3b2994a3def35a2d3058960b71dc59dc48b802f9 Some patching touchups
		MinecraftForge/FML@557357fe179529e0b44aab2f3fcef0c5adf981d5 Update for log4j2
		MinecraftForge/FML@a2b324beb2ef6ec73000678c9305fd70d4ec1643 Copy eventhandler from Forge into FML. It is going to replace a lot of the runtime event systems.
		MinecraftForge/FML@4071ff38afe15fddf5db0be882f5627f503a37c6 Patch some GUIs. We're gonna add some basic mod gui config support.
		MinecraftForge/FML@0b419ac79c307579f162d47e0388a9d75bcd0a6e Fire a user event down the channels when a handshake has occured.
	Christian:
		Updated FML:
		MinecraftForge/FML@32561265fc935cd6639d5b2e086e879f375676fa Ticks, Player events, keybindings, all migrated to the new event driven system.
	LexManos: Inital patch update for 1.7.2, Doesn't compile, not done yet.
	LexManos:
		Updated FML:
		MinecraftForge/FML@a17489172cd54ca955548b15fa0669c9f95d7f45 Code to disable mods at runtime, or other times.
		MinecraftForge/FML@85516d9588ebfadbba25f21b2f973e4e81abbaa6 ICraftingHandler, IPickupHandler are now both events.
		MinecraftForge/FML@e4b63a1801b453797f5e820eb3f5bd42e6d43948 IWorldGenerator now has an ordering at registration time. This means the order of worldgen should be much more stable.
		MinecraftForge/FML@ef3856f9a34e82a05cb2b7715e3611f8fb1a9a6b Update patches for Gradle's rename rewrite: MinecraftForge/ForgeGradle@19e7acf2a27a6c6ae60f6e8ab38337defddc16d3
		MinecraftForge/FML@31ea100b29dfdb4fc907e212c3d49a5240ca72a9 Working on id missing handling
		MinecraftForge/FML@3e76dfba34aaba4397fc3fb2bd28e0d1f0abe3e4 More tweaking on id stuffs at worldload
		MinecraftForge/FML@f860c8ad3bc7537f885b27c7f045b5b1140c05f4 bump to legacy launcher 1.9 with logging unification stuffs.
	bloodshot:
		Refactored BiomeManager stronghold add/remove methods to support new
		
		MapGenStronghold dynamic biome changes.
		Changed InitNoiseGensEvent to pass a NoiseGenerator array instead of
		NoiseGeneratorOctaves due to new NoiseGeneratorPerlin in
		ChunkProviderGenerate.
		Fixed worldgen crash caused by wrong metadata in Chunk patch.
	LexManos: Get object based on identity not name.
	LexManos: Forge uses the FORGE channel for packets.
	LexManos: Fix MethodNotFound crash when shutting down internal server.
	LexManos:
		Fix:
		  Block placement/interaction
		  Tesselator crash due to wrong mapping
		  Missing isreplaceable check in world.canPlaceAt
		  Small foratting/logging cleanup
		  Temporarly commented out efficancy changes till I implement it.
	LexManos:
		Updated FML:
		MinecraftForge/FML@58132ccda3a575f10fc209c421fd5d80e01164cc Add new required --accessToken to launch specs.
	LexManos: Bump version to 10.12.0 to mark 1.7.
	LexManos: Fix debug HUD rendering semi-transparently.
	LexManos: Temporary fix for items rendering with effects on one layer. Restores default vanilla rendering, which is considered a bug in modded community.
	LexManos: Move Grass {Flower} registry to BiomeGenBase as 1.7 made flowers Biome specifc, this means modders who wish to add global base flowers need to add them to all the biomes indavidually.
	LexManos: Fixed accedential inverted logic that caused Potions to render incorrectly. Thanks iChun.
	LexManos: Fix items rendering on the GUI with invalid state due to glint rendering changing it. Thanks iChun.
	Christian:
		Updated FML:
		MinecraftForge/FML@156a9ae03a3c80bd1499a8e692c44a322ad9df62 Fix build script
		MinecraftForge/FML@7d3b1250e8368886bed0e0da350a94abaa4b6247 Fix handshaking properly. Also, fix ID syncup. It now will completely freeze the idmap after preinit. This frozen map is used to inject "new" stuff into existing serverside worlds. Interesting sideeffect: remote servers lacking things will change the client, to also LACK ids for those things. watch for -1 ids in your remap events. Note: idmaps should be considered temporary per server instance. SERVERSTOPPED will restore "startup" state, as will client logout.
	LexManos:
		MinecraftForge/FML@c180d9b15735ce89a38c497acd65fa3fab595f77 Add 1.7.2 base json, Gradle will automatically download updated versions of this. Keeping it in the repo allows us to se
		e what base json we have built our jsons off of. And if it changes update accordingly.
	LexManos: Added constructor to WorldType, and delegated the BiomeLayer management to it. Also updated the access transformer for Item/Block classes.
	LexManos: Forgot to regen patches...
	LexManos: Resize pending tile updates when it goes over the curent length. Fixed AIOOB error.
	LexManos: Add a version check mechanic to startup, it is done in a seperate thread and has a config option to compleetly disable it. This allows us to notify users of new recomended builds. Hopefully stemming the flow of outdated help request. Also adds a warning to the main screen if you are running a 'Beta' Forge. Which means a Forge for a new version of Minecraft that we have not promoted a recomended build for yet.
	LexManos: Fix dig speed on redstone ore and obsidian.
	ohai.iChun: Add render offset to event.
	Christian:
		Updated FML:
		MinecraftForge/FML@268bbabee6ae3fa1d596bd18e172298e26dc9ce4 Fix handling world reloads when new stuffs are added

Build 1.6.4-9.11.1.964:
	LexManos:
		Bump build for gradle fixes:
		  Now Builds for java 1.6
		  Include version,json in universal
		  Fixed classpath issues in eclipse task.

Build 1.6.4-9.11.1.963:
	luacs1998:
		Update readme for ForgeGradle
		
		Let me know if there's anything else to add or change.
	luacs1998: Updated
	luacs1998: Another update for eclipse users
	luacs1998: Update README.txt

Build 1.6.4-9.11.1.961:
	LexManos: Updated FML: MinecraftForge/FML@c2b919d339e5f63271cfb67a77235c21c5c3b80e Don't validate signatures in dev env.

Build 960:
	Abrar Syed: Step 1: The Purge
	Abrar Syed: update FML for gradle changes
	Abrar Syed: Step 2: The Reformation
	Abrar Syed: Step 3: The Rebirth
	Abrar Syed: fixed versioning and stuff
	Abrar Syed: added buildSrc to the gitIgnore
	LexManos: Fix for new FML, and publish to maven local
	LexManos: Update run configs.
	LexManos:
		Updated FML:
		MinecraftForge/FML@e9a7660cb8961660186c7c23e61ab35f9c2dfb81 updated samples
		MinecraftForge/FML@30894f7afadf5d3f3c3d5a54c3f904413d5f2309 Merge pull request #307 from AbrarSyed/master
		MinecraftForge/FML@c4b8a393f90b00ad7ee4992ea4341ffb6d676abb Make the working directory the root of the eclipse workspace.
	LexManos: Regenerate all patches, No functional change as added this is a formatting change only.
	Abrar Syed: update build.gradle
	porcariadagata: Make the gradle wrapper executable.
	LexManos: Proper configuratuion name for jenkins.
	LexManos: Fix build file pom closures.

Build 1.6.4-9.11.1.953:
	LexManos: Fix NPE on specific tile entities when the block break event is canceled. Closes #863
	LexManos: Fix NPE in FakePlayers when they are created in a purely client side environment. To remove in 1.7 as FakePlayers should be used for server side interaction with the world on a player's behalf, not for client rendering.

Build 1.6.4-9.11.1.952:
	Christian:
		Updated FML:
		    MinecraftForge/FML@23baf3a8ce58cb8306189401a60647957ccbb4c2 Actually fix the nethandler code
		
		Update patches

Build 1.6.4-9.11.1.951:
	Christian:
		Updated FML:
		MinecraftForge/FML@b7f34629c3c47b92ee89d72b0dc935b4997cb009 Don't try and open GUIs on the server.
	Christian:
		Updated FML:
		MinecraftForge/FML@da72640c7ef1f44c49f7f592fbdd193622a30b40 Way to go, missing import. *sigh*

Build 1.6.4-9.11.1.949:
	Christian:
		Updated FML:
		MinecraftForge/FML@6af42bc656dfb98972d034363352affc9e777805 Add in null protection for client/server sides of handleChat
	Christian: Don't send openGui commands from the fakeplayer. Fixes thaumcraft and probably others.

Build 1.6.4-9.11.1.948:
	CovertJaguar: Fix Water/Lava Fluid Localization

Build 1.6.4-9.11.1.947:
	LexManos: Noop out FakePlayer.addStat.

Build 1.6.4-9.11.1.946:
	Christian:
		Updated FML:
		MinecraftForge/FML@3d25b4e793c59a9131a441d6c7a2d80cac9cd701 Add in the ability to strip interface references for specific interfaces - this is probably mostly useful for scala scenarios where sythetic methods are generated and is not a substitute for using Optional.Method where appropriate. Closes #300

Build 1.6.4-9.11.1.945:
	onibait: Add block break events based on @bloodmc's initial 1.5.2 Pull Request
	onibait: Add block break events based on @bloodmc's initial 1.5.2 Pull Request
	onibait: Fixed formatting
	onibait:
		Cleaned up patches to BlockOre and BlockRedstoneOre
		Fixed trailing whitespace (it bugs me too)

Build 1.6.4-9.11.1.944:
	Christian:
		Updated FML:
		MinecraftForge/FML@f4532410ec1dbf43ce15dfa78d07e5f7be408b08 Change a couple of warnings, as a prelude to 1.7- preinit is now required for all GameRegistry activity, and every item and block REQUIRES registration.

Build 1.6.4-9.11.1.943:
	Christian:
		Updated FML:
		MinecraftForge/FML@8f87021b0f1ae5b277ad4d1891761b7a7ae1ab71 Fix derp with custom properties. They work now!

Build 1.6.4-9.11.1.942:
	Christian:
		Updated FML:
		MinecraftForge/FML@bc57ff9e83803d804e9d5374d76273fcd68611f4 Fix recursive API dependency resolution. Allows nested APIs, such as BuildCraft's

Build 1.6.4-9.11.1.941:
	Christian:
		Updated FML:
		MinecraftForge/FML@de8ab934d8ae960ebc0dede16218ca1e9e488ebc Fix up duplicate entries

Build 1.6.4-9.11.1.940:
	Christian:
		Updated FML:
		MinecraftForge/FML@81fe1c9682234297443402a54e4b852ef49d0ba8 Add in an API marker for API type packages. This does several things: 1. Packages marked as API will generate a new "modid" (the provides) that can be depended on. 2. Packages marked as API will be searched systemwide, and anything declaring that package (even without the API marker) will get an implicit dependency on the API package. 3. The API package itself will get a soft dependency on the "owner" package.

Build 1.6.4-9.11.1.939:
	LexManos: Add new recipe sorter that is called after all mods are initalized. This is disabled by default in 1.6 to not break current worlds as it may change machine's recipy outputs. Will enable by default in 1.7. Players may enable it in the forge config.

Build 1.6.4-9.11.1.938:
	xcompwiz:
		Adds a Check to prevent Biome Replacement
		
		Splits the BiomeGenBase constructor to create one which takes a flag
		that indicates whether to insert the biome object into the biomeList
		array.  The standard constructor calls the new one with the default of
		true.  This allows biome wrapper-objects to exist.

Build 1.6.4-9.11.1.937:
	Christian:
		Updated FML:
		MinecraftForge/FML@dac7f590eabb326c4467dbc829b4aae1e4be2779 Modify ordering of networkmod registration and mod instantiation. This fixes VersionCheckHandler logging an incorrect failure message due to NPE.
		MinecraftForge/FML@f0dc530b2833a1c89673208fe296dba5520671c1 Fix up documentation of VersionCheckHandler - it only ever accepted a String and only works on the NetworkMod annotated class
		MinecraftForge/FML@243a21a353e6b7717f64008776928c7132110ddf Wrapping coremods as tweakers. Part 1.
		MinecraftForge/FML@58a299aabcfadb4139f126a2d46b5247bede4185 Attempt to inject coremods as tweakers, so both can share a dependency ordering
	LexManos: Format strings properly in MC's internal logger. Fixes resource pack case warnings.

Build 1.6.4-9.11.1.935:
	LexManos: Updated FML: MinecraftForge/FML@bf54d4d66799f2e58944095826d0722ed0120b1f Make each mod's EventBus log a child of it's main logger.
	LexManos: Fix null pointer exception in BiomeDictionary causing the ChunkManager's config to not load/save.

Build 1.6.4-9.11.1.934:
	LexManos: Add wildcard versions of OreDict replacements, Closes #827

Build 1.6.4-9.11.1.933:
	Christian:
		Updated FML:
		MinecraftForge/FML@da4337efbfa07b35f5883107768f9ba2f1b24b9b Fix up handling the new method signature data for NetworkCheckHandlers

Build 1.6.4-9.11.1.931:
	Christian:
		Updated FML:
		MinecraftForge/FML@f92962bbbbb90c19788a5dc2eafdc2eeefdd77ce Use null to empty, so missing values work. *sigh*

Build 1.6.4-9.11.1.930:
	Christian: Add in an event for zombie summoning. Allows for mods to control summoning behaviour, as well as custom summoned mob.
	Christian: And remember to make the event class static *sigh*

Build 1.6.4-9.11.1.928:
	Christian: And allow for tweaking baby chance as well.
	Christian: And set the RIGHT variable *sigh*

Build 1.6.4-9.11.1.926:
	Christian: Allow configuration of the zombie additional summoning mechanic. The vanilla mechanic is a little borked at times.

Build 1.6.4-9.11.1.925:
	Christian:
		Updated FML:
		MinecraftForge/FML@58577775d277a4408bda510534eb36841b08ced4 Very minor style fixes
		MinecraftForge/FML@96be82343c25b83dd842ada8d6e8b66eb4e4ee00 Merge pull request #280 from mc10/patch-1
		MinecraftForge/FML@2714da10228020a6f2321f6c9a703f0d24fe1370 Primitive capability for tweakers to order. Add a "TweakOrder" integer property to your manifest, or accept the default of zero.

Build 1.6.4-9.11.1.924:
	LexManos: Prevent session from being printed to the console, also make sure the username is not empty. Causes a lot of bugs further down the line.

Build 1.6.4-9.11.1.923:
	Christian:
		Updated FML:
		MinecraftForge/FML@fc3e7647d2aff01146b1f5bd2ab6b57ef8e833e5 Support, and fix up, interface lists for Optional

Build 1.6.4-9.11.1.922:
	LexManos: Added some missing air checks to world gen features.

Build 1.6.4-9.11.1.921:
	LexManos: Fix repeated argument in CleintCommands.

Build 1.6.4-9.11.1.920:
	LexManos: MinecraftForge/FML@a381874bb9c3bdeeb508bb81719b4d210eb29696 Delay sound system backend initalization to speed up startup and prevent race condition on some computers.

Build 1.6.4-9.11.1.919:
	reflex_ion:
		Added PlayerOpenContainerEvent and added ForgeHooks.canInteractWith
		
		- Used to override the canInteractWith during player tick
		- setResult to ALLOW/DENY as required
		- Defaults to Vanilla behaviour in any other instance.
		
		Required for LittleBlocks Mod and to Assist Gullivers Mod

Build 1.6.4-9.11.1.918:
	Christian:
		Updated FML:
		MinecraftForge/FML@bc64ceabef76b1f4667b22ca8241b72351b44338 Optional shouldn't be constructable itself. It's purely a wrapper thing.
		MinecraftForge/FML@55525f6d2eb24f42c26a291b8ce98feb4d4498c9 ModLoader is officially deprecated. It will all cease to be with 1.7.

Build 1.6.4-9.11.1.917:
	Christian:
		Updated FML:
		MinecraftForge/FML@63ba3aa0099f43183315fb4e16f9e8e8007362f8 Add in support for Optional interfaces and methods. Be gone coremods!

Build 1.6.4-9.11.1.916:
	LexManos: Fix missing patch which caused per-world storage to not be saved.

Build 1.6.4-9.11.1.915:
	rhilenova: Added pre/post to player list rendering in GuiIngameForge.
	rhilenova: Moved PLAYER_LIST event inside display check.

Build 1.6.4-9.11.1.914:
	LexManos:
		Make isItemStackDamageable() pass the stack to getMaxDamage() to use the Forge version of getMaxDamage().
		Fixes display issues with mods using getMaxDamage(ItemStack) instead of the vanilla one. Closes #805
	LexManos: Bump version number for todays changes.

Build 1.6.4-9.11.0.913:
	ben.blank: allow blocks to choose how they handle indirect power
	ben.blank: move `shouldCheckWeakPower` to Forge section

Build 1.6.4-9.11.0.912:
	jrtc27: Pass arguments to install.sh and install.cmd to install.py

Build 1.6.4-9.11.0.911:
	LexManos: Add cancelable EntityStructByLightningEvent, Closes #789

Build 1.6.4-9.11.0.910:
	LexManos: Stack sensitive version of Item.getItemStackLimit. Closes #771

Build 1.6.4-9.11.0.909:
	Anthony Lomeli: Villager Trading GUI will not open if Player is sneaking.

Build 1.6.4-9.11.0.908:
	LexManos: Added all the vanilla records to the ore dictionary. Closes #731

Build 1.6.4-9.11.0.907:
	LexManos: Direct canApplyAtEnchantingTable through canApply Closes #740

Build 1.6.4-9.11.0.906:
	LexManos: Add pre and post event to rendering Chat, allowing for placement of the chat box. Closes #733

Build 1.6.4-9.11.0.905:
	LexManos: Set densityDir in BlockFluidBase's constructor, closes #737

Build 1.6.4-9.11.0.904:
	LexManos: Fix placement of snow cover over metadata 6. Closes #724

Build 1.6.4-9.11.0.903:
	LexManos:
		Add the ability to register chat commands that only execute on the client. Works with autocomplete.
		Client commands are gray when shown in the autocomplete list (when you press tab)
		Closes #640

Build 1.6.4-9.11.0.902:
	LexManos: Update workspace to point at launchwrapper 1.8
	LexManos: Vanilla hopper should obey the IInventory contract, TileEntityHopper now takes into account IInventory.getInventoryStackLimit() when inserting items Closes #597.

Build 1.6.4-9.11.0.901:
	hobos_taco:
		Added ItemTooltipEvent
		
		This event is fired at the end of ItemStack.getTooltip(EntityPlayer, boolean), which in turn is called from it's respective GUIContainer. It allows an itemstack's tooltip to be changed depending on the player, itemstack or whether the advanced information on item tooltips is being shown, toggled by F3+H.

Build 1.6.4-9.11.0.900:
	Christian:
		Updated FML:
		MinecraftForge/FML@5265e34a350adbb762264379f0134bfa40d33eaa Fix null killing the server

Build 1.6.4-9.11.0.899:
	LexManos: MinecraftForge/FML@35ab9f52b02d84592e4c7607feb6009710b2f7d9 Fix md5s for new checksums.sha1 in scala libraries.

Build 1.6.4-9.11.0.898:
	Christian:
		Updated FML:
		MinecraftForge/FML@e356f4d713b1269825839954fe86f5312ede0fc6 Cross-modsystem compatibility fix with thanks to Mumfrey @ liteloader
		MinecraftForge/FML@9b55f1f48f89a5348ac1d58622b71946f310316a Attempt at a shared modlist implementation - should allow visibility between liteloader and fml for "mod list display"

Build 1.6.4-9.11.0.897:
	Christian:
		Updated FML:
		MinecraftForge/FML@bfc25bc5da1ff0f6fd0faf817b32a8f6d35dedc2 Add to both the classloader and the parent

Build 1.6.4-9.11.0.896:
	Christian:
		Updated FML:
		MinecraftForge/FML@9f0f9e7288afc6cce9a425ad770a208af9e28648 Fix deobf tweaker

Build 1.6.4-9.11.0.895:
	Christian:
		Updated FML:
		MinecraftForge/FML@ce6404fd5bb5e8e425af3bcafeaa285575bf39a3 TYPOS!!!

Build 1.6.4-9.11.0.894:
	Christian:
		Updated FML:
		MinecraftForge/FML@8f18a3de9a02b003762dace891829ef64dfedf49 Separate deobf tweaker so it runs last. Should fix problems with cascaded tweakers expecting an obf environment.

Build 1.6.4-9.11.0.893:
	Christian:
		Updated FML:
		MinecraftForge/FML@8e26c99de3b44d272d2fdc398e0687db17bce3b7 Add debugging for deobfuscation
		MinecraftForge/FML@1d902df5814b815959165e4aa69272003f002d25 Use the negative cache in latest legacylauncher.
		MinecraftForge/FML@9815d8c3793182a08fcdbd29376a3f70bff464d0 Update for launchwrapper 1.8

Build 1.6.4-9.11.0.892:
	LexManos: Add wrapper exception to the new Structure ID system to point to the correct Structure.

Build 1.6.4-9.11.0.891:
	LexManos: Update dev workspace for 1.6.4 ..
	LexManos: Remove some side onlys on BiomeEvents that don't need them.
	LexManos: Fixed typo in bounding box based ladder checks that caused potential infinite loops with entities in certian positions. Thanks Overmind for reporting it.
	LexManos:
		Updated FML:
		MinecraftForge/FML@fc8c3bef0380d59c0842a252e4f0bd29127ee78b Update to new installer that uses xz compression and better support for non-standard jvms

Build 1.6.4-9.11.0.886:
	Christian:
		Updated FML:
		MinecraftForge/FML@a4de22c1addf0a6b95d38e467a96f2af417c86d5 And use the parent that's actually going to be valid. *sigh*

Build 1.6.4-9.11.0.885:
	CovertJaguar:
		Fluid Rarity should have a default
		
		Oops.
	Christian:
		Updated FML:
		MinecraftForge/FML@70cffe6982b27df0ea7d8d4d8851a0c0043bb2cb Herpaderp. Make addURL accessible. *sigh*

Build 1.6.4-9.11.0.884:
	Christian:
		Updated FML:
		MinecraftForge/FML@4a94c2c71bb4cc9644caeb06011a189989b22f87 Fix NPE when loading second single-player world
		MinecraftForge/FML@0e80fcb8f716cfef5b016a73ca32ff0e2f3c3c05 Merge pull request #284 from smcv/uninit
		MinecraftForge/FML@39620f1e41464f53482277dc3bcb0b9eed8ca25c Fix injection of tweaker into system

Build 1.6.4-9.11.0.883:
	Christian:
		Updated FML:
		MinecraftForge/FML@79c39f8b7c711377f7919abd1ee6a56a339d1062 Fix classpath for launchwrapper 1.7

Build 1.6.4-9.11.0.882:
	traincrazyb: Correcting SoundManager Transformer

Build 1.6.4-9.11.0.881:
	Christian: Clean patch fuzz

Build 1.6.4-9.11.0.880:
	Christian:
		Updated FML:
		MinecraftForge/FML@f6190e8752013c0d6857090ffd42559cf83809ae Update workspaces for 1.6.4

Build 1.6.4-9.11.0.879:
	Christian:
		Updated FML:
		MinecraftForge/FML@25981706ef12654b6c2baccc80fa2298bb5afb4a Update for MC 1.6.4
		MinecraftForge/FML@0950b9fc8441a2d3b022ed876f17ee5ac0c47b9c Fix up a deep crash in the early server init hanging the client

Build 1.6.3-9.11.0.878:
	LexManos: Remove duplicate access transformer
	LexManos: Move have handler creation up, to prevent NPE.

Build 1.6.3-9.11.0.877:
	LexManos:
		Updated FML:
		MinecraftForge/FML@e7dd728f955aa4713fef45fea770b1f91246d712 Format the log messages through MessageFormat. Thanks CovertJaguar for the pointer.
		MinecraftForge/FML@82d896a35e08be5712bdc15bdb93e5d4fc0ddd46 Make final transformers actually work on methods as well.

Build 1.6.3-9.11.0.876:
	LexManos: Move the Structure data save files to per-world data folders. Vanilla saves them to the global folder which will potentially cause conflicts if two worlds generate 'Villages'. Which in the modded world is highly likely. Refer back to the long standing vanilla issue where nether 'villages' would override the overworlds villages, it's the same situation.

Build 1.6.3-9.11.0.875:
	LexManos: Make MapGenStructureIO name registration functions public, Any mod that has anything extending StructureStart or StructureComponent must register there classes and create a default (no parameter) constructor.

Build 1.6.3-9.11.0.874:
	LexManos: Unfinalized Item.getIconIndex(ItemStack)

Build 1.6.3-9.11.0.873:
	LexManos:
		Updated FML:
		MinecraftForge/FML@da70cdd35a378d02db47d2aa31fb9aac87beaedc Update tweaker for new Launcher API
		MinecraftForge/FML@352117fd78eec745da6c80b8d354947c4dbbbb48 Update for new installer and thank you.
		MinecraftForge/FML@40a34af43105ebcb5a63ce2351ca119da5a8158e Merge branch 'master' into newtweak
		MinecraftForge/FML@e77d2547ad447025729ae7f3cccaaf343c4c86f9 Update for pre-ninja 1.6.3 update
		MinecraftForge/FML@34493b0d99e2cf2bdca080ff226f2dfeedb1cf51 Update for real 1.6.3 update
		MinecraftForge/FML@95afc95b248ecc69bc6ffcc5a95912820d8f4066 Update mcp mod info
		MinecraftForge/FML@ff75416a325717770a5cf457c859bfb0abcbe281 Update mc_versions data and commands patch and eclipse workspace
		MinecraftForge/FML@8f2e67558127f16d92399ea97cbcb0df46d52e19 Update the src distro's eclipse workspace.
	LexManos: Bump version for new MC version.
	LexManos: Actually push the submodule update -.-

Build 1.6.2-9.10.1.871:
	Christian:
		Updated FML:
		MinecraftForge/FML@81328b6684c5127427153807b5e498c2efefb96b Add in support for using a mirror list and provide checksums for packed download of libs

Build 1.6.2-9.10.1.870:
	Christian:
		Revert "Added a RenderType that allows Map-style rendering w/o inheriting from"
		
		This reverts commit eb4688bf5ea132cd8ddc802a7dad6d423ad50543.
		
		Conflicts:
			patches/minecraft/net/minecraft/client/renderer/ItemRenderer.java.patch

Build 1.6.2-9.10.1.869:
	vilim.lendvaj: Prevent NPE in fluid lookup for block
	Christian: Fix broken PR from vilml. TEST!

Build 1.6.2-9.10.1.867:
	CovertJaguar:
		Allow Fluids to have Rarities
		
		Used for tool tips.

Build 1.6.2-9.10.1.866:
	Christian: Fix the divider

Build 1.6.2-9.10.1.865:
	Adubbz:
		Sky colours now smoothly transition
		
		Made transitions even smoother
		
		Sky colours now smoothly transition
	Christian: Move stuff around a bit- also tie range and enabled to options.

Build 1.6.2-9.10.1.864:
	ml:
		Added a RenderType that allows Map-style rendering w/o inheriting from
		ItemMap.
	Christian: Tweak patch comment

Build 1.6.2-9.10.1.863:
	mitchpetrie29: Check if block is air instead of just ID zero when growing from stem block.

Build 1.6.2-9.10.1.862:
	Christian: Allows proper raytracing from actual player eye position rather than hardcoded eye heights.

Build 1.6.2-9.10.1.861:
	claire.alexandria: Added fov hook
	claire.alexandria: fixed merge
	claire.alexandria: Small formatting changes (opening braces on new line)

Build 1.6.2-9.10.1.860:
	Christian:
		Updated FML:
		MinecraftForge/FML@b5af446d7111730c7973c9f0d6b76e62b78b9131 Fix sidedness derp in LanguageRegistry.

Build 1.6.2-9.10.1.859:
	Christian: The partial tick should be available for all render player events. Weird it wasn't.

Build 1.6.2-9.10.1.858:
	Christian: Reverting HarvestEvent, for new implementation
	Christian: Redo harvest event. This time with simpler logic, that should be less liable to weird "missing" stuff.

Build 1.6.2-9.10.1.857:
	LexManos: Fix bug where guis were not closed properly, resulting in signs not having there text set.

Build 1.6.2-9.10.1.856:
	Christian: Change trigger calculation so entities get some time to age before refiring the event.

Build 1.6.2-9.10.1.855:
	LexManos: Create helper apply_patches script and add paramter to change patch output folder.

Build 1.6.2-9.10.1.854:
	Christian:
		Change from Cancelable to using a Result. This means you can force despawn mobs you
		don't want around anymore. Also, deferred check to once every 20 ticks. May tune it
		down further or make it a config if this event is a lag issue.

Build 1.6.2-9.10.1.853:
	Christian:
		Add a cancellable despawn event- allows mods to decide to prevent the despawning
		of certain otherwise normally despawnable mobs.
	Christian:
		Added fov hook
		
		Small formatting changes (opening braces on new line)
	Christian: Create es_ES.lang

Build 1.6.2-9.10.1.852:
	Christian: Add some javadoc to the HarvestBlock event.

Build 1.6.2-9.10.1.851:
	Christian: Use the dropchance from the event.
	Christian: Clean up some formatting.

Build 1.6.2-9.10.1.850:
	claire.alexandria: Added tessellation methods to obj model, for ISBRH-friendliness
	claire.alexandria: Fixed both RenderAllExcept behaviours
	claire.alexandria: Added more render methods to IModelCustom interface.
	jk-5:
		Added GuiOpenEvent
		
		You can use this for a clean way to override guis, without needing an
		TickHandler to check if the gui you want to override is open and show
		your own gui
		
		Proper close check
	mhahn:
		capacity was not respected
		
		Updated to properly calculate the amount of free space in the tank
		before checking that against the amount of the resource.
	robin: create french localization
	claire.alexandria: Added display name hook
	claire.alexandria: Memoization of display name result
	claire.alexandria: Added mouse event
	claire.alexandria: inserted hook into Minecraft.java
	claire.alexandria: fixed logic error
	ohai.iChun:
		Fix player push out of blocks clientside being hardcoded and not based on entity size.
		Added player eyeHeight field to allow changeable eye heights of players rather than being hardcoded per player class as well as add a getDefaultEyeHeight function.
	Christian: Reduce patch size significantly
	Christian: Fix patch for new MCP naming.
	Christian: Add a bit of javadoc
	Christian: MachineMuse, remember, there's TWO model formats supported!
	Christian: Defer firing CreateDecorator until it's likely mods have had a chance to register their listener. Should close #759
	Christian:
		Add a harvestblock event, to allow mods to intercept and change the drops for blocks. Don't abuse this, or we'll have to take safety measures.
		Fires for both silktouch and non-silktouch harvesting, and provides the player. Note, you may need to
		change your break overrides to pass on the player for best results.
	Christian: Add in a block reverse lookup for fluids. Closes #749

Build 1.6.2-9.10.1.849:
	Christian:
		Update forge for MCP naming updates
		
		Updated FML:
		MinecraftForge/FML@d0c6e92900590f578b80d9a6c00fa28fd333d3bf Update MCP data
	Christian: Update version to 9.10.1 for mcp naming changes.

Build 1.6.2-9.10.0.848:
	Christian: Fix possible NPE in searching code.

Build 1.6.2-9.10.0.847:
	Christian:
		Updated FML:
		MinecraftForge/FML@2a9c485edc4cf3382154d5b3b9b600386f2ab8ae Remove @SideOnly from 70318 (getDistance) it makes no sense that it's not on the server.

Build 1.6.2-9.10.0.846:
	Christian:
		Updated FML:
		MinecraftForge/FML@a13598b17ea9637c054d867a76298d6c080c5e32 Use java 1.6 compatible method of closing the zip file. Stops stupid compile error.

Build 1.6.2-9.10.0.845:
	Christian: Small fix to container registry. emptyContainer is not null, it's "NULL_EMPTYCONTAINER" now and won't match any valid container.

Build 1.6.2-9.10.0.844:
	Christian: Tweak the release to add in assets to the distributable. *sigh*

Build 1.6.2-9.10.0.843:
	Christian:
		Updated FML:
		MinecraftForge/FML@1c9a853868f7df0daa5f67b99401dfab44ae18e6 Allow coremods to properly inject asset readers.
		MinecraftForge/FML@40b54013b4c9b01686411cd47a7866eeb650ea2b Allow server side lang file injection, hopefully
	Christian: Add some starting work for a forge tps command. Also update coremod for new FML behaviour

Build 1.6.2-9.10.0.842:
	Christian:
		Updated FML:
		MinecraftForge/FML@b993cf4a9825865b3a8a0c7b083c23d56dbd1d6f More exception handling for less derpiness.

Build 1.6.2-9.10.0.841:
	Christian:
		In the time honoured tradition of trying to fix vanilla, we today attempt to patch the pathfinding AI so that it doesn't lag when
		there's a lot of entities. Basically, if the zombie can't reach the villager, backoff subsequent pathfinding attempts. Hopefully
		should really help with lag caused by zombie swarms.

Build 1.6.2-9.10.0.840:
	Christian: Allow multipass RenderItem rendering for terrain icons too. Should fix sengir's saplings.

Build 1.6.2-9.10.0.839:
	Christian:
		Updated FML:
		MinecraftForge/FML@913f6f6d36bd179db7c147db0485e99dee693933 Try and use the relaunch log, which should be classloaded..
		MinecraftForge/FML@ac065ff5f76b6c512b346366107efde66e9e1c88 Reset the IWorldGenerator seed for each mod, before calling. That should mean worldgen is consistent and not dependent on mod ordering, or mod sideeffects.

Build 1.6.2-9.10.0.838:
	LexManos: Cache world on all render passes in case some mod disables the first pass.
	LexManos: Skipp toss event for null entity items. Closes #732

Build 1.6.2-9.10.0.837:
	LexManos: Fix bug with custom Fluids. You can now drown in them!

Build 1.6.2-9.10.0.836:
	Christian:
		Updated FML:
		MinecraftForge/FML@9468e41bbf3ea425c50daa710cf3ada11c82b238 Fix up scala refs, for better results

Build 1.6.2-9.10.0.835:
	Nick:
		Adds Temperature to Lava
		
		Missing lava temperature. Feel free to change it to any value.
		1300K is the typical max for Magma so wasn't sure what was desired. Regardless, better than the same temp as water at 295K :smile:

Build 1.6.2-9.10.0.834:
	Christian:
		Updated FML:
		MinecraftForge/FML@4a9d0f9bd522e543b76daaf9c49b6214443c595f Add in some log information
	Christian:
		Updated FML:
		MinecraftForge/FML@f157e7a6ecdeac2758fc0eaf547d3e8a763fb15b And more coremod logging
	Christian:
		Updated FML:
		MinecraftForge/FML@ffdd056a18eddb8f28b74435d40e69c956b9dd48 Check keys, not values *sigh*

Build 1.6.2-9.10.0.833:
	Christian:
		Updated FML:
		MinecraftForge/FML@03989166665956df03aa85472eb13dca2d74a38d And actually instantiate the collection *sigh*

Build 1.6.2-9.10.0.832:
	Christian:
		Updated FML:
		MinecraftForge/FML@dec9a3924d361bc016cb7f6b3e95764158cf5ae1 Add in "FMLCorePluginContainsMod" in the manifest. If this value is present, FML will attempt to parse your mod jar file as a normal mod file as well, instantiating mod containers there.

Build 1.6.2-9.10.0.831:
	Christian:
		Updated FML:
		MinecraftForge/FML@24701206808a43b9c7b10d7130c47b5d1e841bb6 Clean up a couple of resources. Also, don't parse jars just because they're in the mods dir

Build 1.6.2-9.10.0.830:
	Christian:
		Updated FML:
		MinecraftForge/FML@9a5e24e338c6172531efb086a4b584c26d4f1435 Fix stupid derp is stupid. Closes #275 and means sp614x can do his thing
		MinecraftForge/FML@ba90b616070ce15793eb05e5afaed62a6f07c6e7 Make sure we only add args to the argument list if a tweaker hasn't already. Should fix LiteLoader compatibility issue.

Build 1.6.2-9.10.0.829:
	LexManos: Fix NPE in enchangint books.

Build 1.6.2-9.10.0.828:
	LexManos: Fix inverted case, search works now.

Build 1.6.2-9.10.0.826:
	ross.swartz: Add stone and cobblestone to Ore Dictionary
	ross.swartz: Update OreDictionary.java
	LexManos: Addition: Added isAllowedOnBooks hook to Enchantments Closes #589

Build 1.6.2-9.10.0.825:
	LexManos: Deprecate Block.addCreativeItems, Kill in 1.6.3+ Closes #655

Build 1.6.2-9.10.0.824:
	mehvids: Add onNeighborTileChange callback to block by generalizing func_96440_m to all blocks rather than just comparators.

Build 1.6.2-9.10.0.822:
	malc.geddes: Added a new function to allow control over whether an entity is dismounted when the entity it is riding goes under water
	LexManos: Allow creative tabs to have a search box if they want to Closes #592

Build 1.6.2-9.10.0.821:
	tommy.stanley96: Fixed Fluid Non-Solid Block Duplication
	tommy.stanley96: Fixed Double Item Drop
	tommy.stanley96: Fixed Classic Checking

Build 1.6.2-9.10.0.820:
	LexManos: Add optional feature to check entire bounding box for ladders. Closes #709

Build 1.6.2-9.10.0.819:
	LexManos: Only refresh vanilla tile entities when IDs change.

Build 1.6.2-9.10.0.818:
	LexManos:
		Updated FML:
		MinecraftForge/FML@f275a24b43559cfdced243ff77e9848c9d458362 Add in some reverse lookup methods for game registry data
		MinecraftForge/FML@cb05c8c4aa60a131de92f0a21c06697c8f8896a8 Add missing SideOnly in BaseMod
		MinecraftForge/FML@1857064afa9ace796440c19f3275637a6e659375 Merge pull request #266 from grompe/patch-1
		MinecraftForge/FML@182aa9c0cbe61ac69b0d428ead1dc817dd2a2e71 Fixed install.sh not passing arguments to install.py
		MinecraftForge/FML@f46a538b41157081c840f647f123513ac4c5a071 Merge pull request #268 from Bo98/sh-args-fix
		MinecraftForge/FML@29ef3d5ab412dcabbd67695558880c45011ace82 Update installer.

Build 1.6.2-9.10.0.817:
	tommy.stanley96:
		Fluid Render Fix
		
		Formatting
	ohai.iChun: Add Pre and Post events for RenderLivingEvent
	ohai.iChun: Add Pre and Post events firing for RendererLivingEntity
	ohai.iChun: if statement added
	ohai.iChun: Update RendererLivingEntity.java.patch
	tommy.stanley96:
		Fixed fluids eating each other
		
		Fluids check for other fluids density before flowing, if their density
		is higher they can flow into the other fluid, if not they can't.
	CovertJaguar: Add SneakClick bypass to client
	cpw: Fix names for water/lava fluids. Closes #689
	cpw:
		Add support for loading legacy liquid stacks as new fluid stacks.
		Requires having been written with the "liquidname" code from forge 1.5.x
	cpw:
		Add a translation map for looking up legacy liquid names to convert
		to new fluid names.
	tommy.stanley96: Fluid Rendering Fixes
	cpw: Fix formatting error in PR
	cpw:
		Tweak setBlock in update tick - it should only send serverside updates for
		source blocks. Experimental attempt to fix worldgen issues for fluid blocks
	cpw:
		Updated FML:
		MinecraftForge/FML@57befa89bbbf2bc2fcc4a97b78e07b3f9e23ef9d Fix keybindings being derped
		MinecraftForge/FML@1d84e8063e9d0dc73928dba006e6001201285cad Temporarily add a version of 'reobfuscate.py' that will resolve complex reobfuscation graph issues with specialsource. Copy it over 'reobfuscate.py' in the mcp runtime dir. Hopefully will have an MCP/specialsource fix in the coming days.
	ohai.iChun: Fix RenderLivingEvent.Pre/Post not being fired by most Renders.
	tonkamatt98:
		added temperature to fluids
		
		it could be useful for blocks that are affected by temperature
	mitchel.pyl: Fix render colour on bottom of fluids
	mitchel.pyl: Fix small derp

Build 1.6.2-9.10.0.816:
	purpleposeidon:
		Add an InputStream constructor to WavefrontObject
		
		It is said that Resource Packs will return InputStreams. And I like putting my models into texture packs which, obviously, give InputStreams rather than URLs.
	7of9: Add cloud height to WorldType

Build 1.6.2-9.10.0.815-miscchanges:
	mitchel.pyl: Fix render colour on bottom of fluids
	mitchel.pyl: Fix small derp

Build 1.6.2-9.10.0.812-miscchanges:
	tonkamatt98:
		added temperature to fluids
		
		it could be useful for blocks that are affected by temperature

Build 1.6.2-9.10.0.811-miscchanges:
	ohai.iChun: Fix RenderLivingEvent.Pre/Post not being fired by most Renders.

Build 1.6.2-9.10.0.810-miscchanges:
	cpw:
		Updated FML:
		MinecraftForge/FML@57befa89bbbf2bc2fcc4a97b78e07b3f9e23ef9d Fix keybindings being derped
		MinecraftForge/FML@1d84e8063e9d0dc73928dba006e6001201285cad Temporarily add a version of 'reobfuscate.py' that will resolve complex reobfuscation graph issues with specialsource. Copy it over 'reobfuscate.py' in the mcp runtime dir. Hopefully will have an MCP/specialsource fix in the coming days.

Build 1.6.2-9.10.0.809-miscchanges:
	cpw: Fix formatting error in PR
	cpw:
		Tweak setBlock in update tick - it should only send serverside updates for
		source blocks. Experimental attempt to fix worldgen issues for fluid blocks

Build 1.6.2-9.10.0.808-miscchanges:
	tommy.stanley96: Fluid Rendering Fixes

Build 1.6.2-9.10.0.807-miscchanges:
	cpw:
		Add a translation map for looking up legacy liquid names to convert
		to new fluid names.

Build 1.6.2-9.10.0.806-miscchanges:
	cpw:
		Add support for loading legacy liquid stacks as new fluid stacks.
		Requires having been written with the "liquidname" code from forge 1.5.x

Build 1.6.2-9.10.0.804:
	copyboy: Fix getArmorTexture by passing it the subtype

Build 1.6.2-9.10.0.802:
	LexManos:
		Re-added deprecated liquids system. To be removed next major MC versions after issues with Fluids are fixed. (reverse-merged from commit 9b5208fa308f22c24e295ce3be38dcafea2857ea)
		This WILL be removed and should not be developed against aside for a temporary 1.6 release.

Build 1.6.2-9.10.0.801:
	LexManos: Remove SideOnly(Client) in IBlockAccess.isAirBlock

Build 1.6.2-9.10.0.800:
	LexManos: MinecraftForge/FML@10b16d32da4b7c32b15e69cf1c636505ebbe2540 Use json 2.9.1 nightly for OSX in release json like vanilla does.

Build 1.6.2-9.10.0.799:
	LexManos: General code cleanup of Fluid system. Made Fluid icons and associated functions non-sided.

Build 1.6.2-9.10.0.798:
	LexManos: MinecraftForge/FML@3f21a2c1b413e591f61f2906c3adbadd9c5b09e3 Stupid spaces and windows escaping -.-

Build 1.6.2-9.10.0.797:
	LexManos: MinecraftForge/FML@b2958c9066db8c95bb4260893fbfe00103fc4ba1 Add quotes for paths with spaces -.-
	LexManos: Package 'version.json' with universal jar for maunchers to use. It's the json used by the vanilla Minecraft launcher for Forge.

Build 1.6.2-9.10.0.796:
	LexManos: MinecraftForge/FML@9520978b81d4cba5d8b0af0d5f155bd115023795 Use a temporary file for recompile's command line to combat command length to long issues.

Build 1.6.2-9.10.0.795:
	LexManos: Updated FML: MinecraftForge/FML@4981aa3421262c3c1c4705468fe202df8198b9f0 Fix potential NPE in villager skin registry. Closes #678

Build 1.6.2-9.10.0.794:
	Nick:
		Fixes Vanilla Fluid Still Icon Setters
		
		Fixes null icons from being set for both the still water/lava icons, and sets the correct Icon.

Build 1.6.2-9.10.0.793:
	LexManos: Updated FML: MinecraftForge/FML@c48b48ee15f38d3e794b6eb3499c536226ca5a79 Fix server launching.

Build 1.6.2-9.10.0.792:
	Christian: Fix for new location of mcp logo.

Build 1.6.2-9.10.0.791:
	Christian:
		Updated FML:
		MinecraftForge/FML@0378355c3720d587652b7792665a8b70bf104eb3 The server.classpath generates the runtime manifest, so it needs the non-debug asm jars.
		MinecraftForge/FML@a3f48734ffbbb2eccffdafcd3cbe73824bd1afd6 Fix up jar sanity check code. FML validation of the jar works now and doesn't derp classloading.
		MinecraftForge/FML@9947ba85036542a3231e25328d3300f2a5337370 Fix logo handling. no more NPE if the logo can't be found. Also, fix location of mcp logo now.

Build 1.6.2-9.10.0.790:
	Adubbz:
		Made eating particles compatible with metadata
		
		Removed extra spaces
		
		Made eating particles compatible with metadata
	Christian:
		Updated FML:
		MinecraftForge/FML@e44e8b3112bd56c716a00c19d0be2f15d9128b70 Force a global asset scan prior to mod construction : you should be able to reference assets anywhere in your mod now.
		MinecraftForge/FML@20e93a412ee13498babef02d404f57bf5e0fd919 Fix up logos in the mod screen. Clean up some unnecessary casts and suppressions, use the -debug asm library at dev time, since it contains full symbols and code in compiled form.
	LexManos: MinecraftForge/FML@b9f4b02cb0b041594656f05de70225df702a8ddd Kill mcp's truncate method, for more useful logs.
	LexManos:
		Updated FML:
		MinecraftForge/FML@7348929819b0ae8ad35419ef5dbf66e66b442858 Kill release time scala libraries, to be re-evaluated after all movement is done and shit is fixed. May require manual instalation for mods that use scala.
		MinecraftForge/FML@6de36d78f57f6f08ec586b67b684d0e5406cd436 Coremods now have a primitive dependency capability. Also, we search mods dir for special "TweakClass" manifests. These are using the vanilla tweak mechanism to inject into Minecraft. Helpful for other "platform" systems, when you don't want to have to deal with json changes!
		MinecraftForge/FML@d4b30422b64a62a2f8a8c2cccd94cb0fd06154e0 Update build and eclipse workspaces for debug asm.
	LexManos: MinecraftForge/FML@c625ef30093abb0755985c74d1f31e2c4cf6cfdd Update Forge signature for new private key
	LexManos: Update changelog generator to point to new jenkins.
	LexManos: Monkey patch to try and make print flush properly.

Build 1.6.2-9.10.0.789:
	LexManos: Re-add reverted patch AGAIN cpw check your commits -.-

Build 1.6.2-9.10.0.787:
	Christian:
		Updated FML:
		MinecraftForge/FML@bab4d87ce76baa40200939cc46780b1d3b2ff466 Update FML for new stealth update for 1.6.2

Build 1.6.2-9.10.0.786:
	Christian: Remove forge ISidedInventory, deprecated since 1.5.

Build 1.6.2-9.10.0.785:
	Christian:
		Allow optional rider interaction for entities, thanks for the suggestion Vswe.
		
		Updated FML:
		MinecraftForge/FML@7af5c21d74679d1a53550f9719bba22b2f28dd13 @InstanceFactory was set to look for Fields instead of methods
		MinecraftForge/FML@bc9d1fe657c7a0953adc7d4c5ed81c575bdfb0f1 Merge pull request #254 from CaptainShadows/patch-1

Build 1.6.2-9.10.0.784:
	LexManos: MinecraftForge/FML@c913258ca38e662264bdf4aafbfbef86881c9290 Disable signature check of client for now, it's broken.
	Christian:
		Updated FML:
		MinecraftForge/FML@97269a5e3dc0a0e2e1a79183f9f5f2ee120e90bd Decode the file URL. Hopefully will make things work more..
		MinecraftForge/FML@d4d522c5978ecd7a9195977b3327b441901bb5b4 And don't forget to remove the test code

Build 1.6.2-9.10.0.781:
	LexManos:
		Updated FML:
		MinecraftForge/FML@dfa3a2665d6782b87713cea26dda558ac990a72a Add MC Version to installed version name.
		MinecraftForge/FML@e91431fb707ce3e7e4296ccb8f3b2e5208b4dfac Don't validate signatures on servers, they are not signed.
		MinecraftForge/FML@c7ab872c85dd057a4e44e12e34089dfd1a1184b6 Temporarily disable GuiModList's Mod logos.

Build 1.6.2-9.10.0.780:
	LexManos:
		Updated FML:
		MinecraftForge/FML@c997f2adbc4c11cd8c2abe5f82ccd00b0e954b68 FML now verifies that the minecraft jar is correct and intact. This is intended to discourage those who think that modifying the minecraft jar is still acceptable.
		MinecraftForge/FML@0db4624b27a5ecf59ed506ccfc26459ca26ee408 Don't initialize the server.
		MinecraftForge/FML@4fa375683fdb7edff67c951fb371ab4a23435308 Fix NPE in new debug line when patch targets don't exist.

Build 1.6.2-9.10.0.779:
	LexManos: Fix accedential reverted patch.
	LexManos: Proper return for getRegisteredFluidContainerData thanks Soaryn. Ref issue #634

Build 1.6.2-9.10.0.778:
	Christian: Make resourcelocation the class available on the server.

Build 1.6.2-9.10.0.777:
	Christian:
		Drop two domain related fixes that have been applied in vanilla.
		
		Updated FML:
		MinecraftForge/FML@c47d08c89dfcacb96e36c427593174e08dcb4224 Tweak debug data on patched classes
		MinecraftForge/FML@dbf5fe38cee04288e92d57f8782114b452245bce We now generate an adler32 checksum for each patched file and verify at load time that they match. Mismatch won't crash, but will emit a big warning..
		MinecraftForge/FML@e88a0cd13f63904f7317e1a73880611f58820389 Update for stealth update. Thanks mojang!
		MinecraftForge/FML@2336002f20e9412a7663781b23c51de0eff6a692 The game is going to exit in face of patch mismatch, unless you force it to run with fml.ignorePatchDiscrepancies in the system properties.

Build 1.6.2-9.10.0.776:
	LexManos:
		Updated FML:
		MinecraftForge/FML@1d0384f8f664d7002019b865675a5fddf2963b3d Update for 1.6.2 and MCP 8.04
		MinecraftForge/FML@111b0216fdc55f56a8361a584141bca7c9c3f070 Add the jsons for 1.6.2
		MinecraftForge/FML@6f96d89e2bf9313b26eeb4c334a208bf3e1c9ad4 Update eclipse workspaces for 1.6.2
	LexManos: Remove deprecated Liquids API, Use new Fluids system as replacement.
	LexManos: Bump version to 9.10 for new MC version and removal of Fluids.

Build 1.6.1-8.9.0.775:
	Christian:
		Updated FML:
		MinecraftForge/FML@c97ac284a5e7dbdbccbad2f7ccc95252c4aef239 Update ModLoaderFuelHelper.java
		MinecraftForge/FML@3a200e901e34ade679e4485307f57bee725bbe94 Fix coremod injection into main system. Should stop double-dipping coremods.
		MinecraftForge/FML@2676c8999cbede05b5475ba68bfc25467a67d4fc Update mcp data. fixes #248
		MinecraftForge/FML@5990e29af7b70e343dfd9cf38bb3e033e71a4489 Merge pull request #247 from jk-5/patch-1
		MinecraftForge/FML@adc89722770b7319884619cadc6f10cc9050df24 Add cascadedTweaks. This will allow simple coexistence for any other mod framework using the tweaker system as well. Hi Voxel and LiteLoader!

Build 1.6.1-8.9.0.774:
	xcompwiz:
		Makes player-specific spawnpoints dimension aware
		
		Makes ServerConfigurationManager correctly get player-specific spawn
		point for the target dimension
		Changes EntityPlayer to store and save a (bed) spawn point for every
		dimension, as well as transfer them to respawn "clones"

Build 1.6.1-8.9.0.773:
	LexManos: Re-gather list of Icons when atlas textures are stitched, allows for addition/removal of blocks/items after the atlas's inital constrction.

Build 1.6.1-8.9.0.772:
	LexManos: Fix enchantment effect on single pass items. Closes #644

Build 1.6.1-8.9.0.771:
	kinglemming:
		Forge Fluid System!
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	LexManos: Mark old liquid system as deperated to be removed next Minecraft release.

Build 1.6.1-8.9.0.770-newliquid:
	LexManos: Mark old liquid system as deperated to be removed next Minecraft release.

Build 1.6.1-8.9.0.769-newliquid:
	richard: Techne model loader (incomplete for debugging)
	richard: Complete it, got the bug figured out
	Christian:
		Updated FML:
		MinecraftForge/FML@24c405665105a789a0708a7e30c8bcb96899da6b Add in an optional modid identifier for @SidedProxy. It's main use is when both scala and java @Mods reside in the same package, and you want the @SidedProxy behaviour for a specific @Mod language type. In general it should not be needed otherwise.
		MinecraftForge/FML@cd0466395a8f1af3ec44f124bf4088df2d318603 Fix sysout with trailing messages after a newline
	LexManos: Disable ImageIO's File based cache, should speed up texturepack loading/stitching.
	jadran.kotnik: Added rotation support for all vanilla blocks that can be rotated.
	LexManos:
		Add NPE protection to ItemStack delegates. Closes #601
		Also cleaned up the names of said delegates, we do not have to follow MCP's crowdsourced names as they are very bad.
		Redirected damage through setItemDamage to allow items to have finder control of breaking.
	LexManos: Fix Air block check in BlockPortal.
	LexManos: Fix hoes being able to till dirt under other blocks, and made it look for air type blocks.
	LexManos: Add NPE protection to refernce to MinecraftServer.worldServer
	LexManos: Fix AIOOB exception in crash reporting if exception does not have a stack. Possible, but odd.
	LexManos: Fixed changelog generation.
	LexManos: Forgot most important side, release script.
	Christian: Make glass panes and iron fences connect to block sides based on solidity. This does change IBlockAccess, so anything with a custom IBlockAccess may need to implement the new method.
	Christian:
		Fix server patch FML update
		
		Updated FML:
		MinecraftForge/FML@22738de028a9ba51d43d73857dfb8969985566f0 Attempt to properly fix deadlock if the internal server derps. It should never hang now. Damn you fast computer..
		MinecraftForge/FML@05a854cd2af53ca822ee8b249b0b3bbe44f94675 Small tweaks to the mcp data. Nothing major..
	mitchel.pyl: Fix tripwire patches for solid sides
	LexManos: Added EntityLiving to Block.isLadder arguments, deperacating older version. New parameter has the possibility of being null, so modders must take care. Closes #608
	LexManos: Add air checks to BlockSand falling and Piston pushing. Please report any other issues with custom 'Air' blocks in issue #602
	LexManos: Bump Forge revision and mark recomended.
	LexManos: Fic Chest content gneeration delegate call. Cloases #609
	LexManos: Add air check to Flint and Steel Ref: #602
	LexManos: Update workspace for new library structure.
	LexManos: Update FML to 16launch branch
	LexManos: Initial patch update to 1.6, Does not compile, need to update references to the old TexturePack system.
	LexManos: Small fixup, need to Update GuiIngameForge for new HUD changes.
	LexManos:
		Updated FML:
		MinecraftForge/FML@6a318ddb784ca8b2bef0f6718089f7beb4d404e0 Fix typo in new packages.
		MinecraftForge/FML@3711da9c456d20865a965734cc5aeaf7f5cb5e5d Another typo
		MinecraftForge/FML@e35e4b16ff3d6dea547c41f02f2ca31ebe1f74aa More fixups
		MinecraftForge/FML@18371bd8c9bd107f774289da35519f593ccc8ee7 Some fixes for updated mcp code
		MinecraftForge/FML@ef646d3146e1f285d2cb8e79a74373beffa84774 Merge branch '16launch'
		MinecraftForge/FML@7406b38d8ad1bc5c2c641c74f1614b946f246588 1.6.1
		MinecraftForge/FML@12c928c538c1c04d3a21255c747d15468328ace9 Tweak commands patch
		MinecraftForge/FML@3f15cd54c2d776ea161aaedbecad9e188d66578f Functional client @ 1.6.1
		MinecraftForge/FML@71a92de5d95fccc4fe17cc39d0836891c6622f4d Client launch for eclipse
	LexManos:
		Updated FML:
		MinecraftForge/FML@8960f6869fbe30d358a40997c47999025c3eae68 Add windows lzma executable http://tukaani.org/xz/ He states that most things are under public domai
		n, But I couldn't find an exact reference to this executable. I'm going to assume it under public domain and distribuiting it here is fine. If not someone pleas
		e direct me to the apropriate license and I will act accordingly.
		MinecraftForge/FML@70cfe24e67adf6872ef1501599e2115e420c2539 Fix wrong project name in distro eclipse launch.
		MinecraftForge/FML@7a004087f79b94bc92f29d50eb71288b6c1c968c Add deobf data to src dist. Dont create deobf jar as we ship the lzma Added *.lzma to .gitignore
	LexManos:
		Updated FML:
		MinecraftForge/FML@110cf372eb5aa85df20b248976f1acdefa85e102 Add deobf data to merge-common, workspace is now actually runnable!
	LexManos: Support dirty submodules in changelog script.
	LexManos: 1.6.1 Update
	LexManos: Add new launch configs to dev workspace.
	LexManos: Update GuiIngameForge to reflect Mojang changes in 1.6.1
	LexManos:
		Updated FML:
		MinecraftForge/FML@c418da353f6a8420b095fa737e8b0eae270d31ae Cleanup coremod code, server side working now.
	LexManos: Update release script to generate binary patches and include deobf data.
	LexManos: Deprecation sweep and update version to 8.9 to reflect 1.6.1 update.
	LexManos: MinecraftForge/FML@7fecf2ad6bdd918149a3c43453f6a78bd11e5404 Update mcp URL.
	LexManos: Try absolute path, to not confuse jenkins.
	LexManos:
		Updated FML:
		MinecraftForge/FML@1229c4c4ea888f4f69272eed94ef5a53ce79ccda Fix src distrabution, and got rid of pesky common folder in eclipse workspace. src is now installable.
		MinecraftForge/FML@902772ed0cb6c22c4cd7ad9b0ec7a02961b5e016 Revert common folder fix, Common folder does nothing, feel free to delete it after first load.
	LexManos: Update src distro installer script. Source distro works now!
	LexManos: Update ToolMaterial enum helper.
	LexManos: Release will now build a installer jar and use the standard 'target' output folder.
	LexManos:
		Updated FML:
		MinecraftForge/FML@29d6c875d0675ffa14428c511bd6ebe9232a486c Add FML Installer logo crated by @ZaverSLO https://twitter.com/ZaverSLO/status/349947190300508162
		MinecraftForge/FML@3d17434510e890574b68c8a181b80c830b5d043a Build installer package for the new client launcher.
		MinecraftForge/FML@bf38d947569911dab03319a8b0f1964f36b195b2 Update json samples
		MinecraftForge/FML@7037184a4e724300001dfc1f8df2e76a0ec30368 Fix up release JSON
		MinecraftForge/FML@dc7d02ebf6c9fc5965344a9aeca79f230a40afb4 Fix json syntax error.
	LexManos:
		Fix installer unintended replace.
		
		Updated FML:
		MinecraftForge/FML@9b6525e80504ff72a1798cf5797bf148295db776 Point scala downloads to our servers, Launcher doesn't like standard maven repos.
	LexManos:
		Updated FML:
		MinecraftForge/FML@91ecf711092e1610dd10e77cdd517c3324e62d8d Fix -rel json
		MinecraftForge/FML@efc369ee83a7b62f605c13e16efad66b63b4bd8c Fix EventHandler annotation.
		MinecraftForge/FML@fbd57b32641b540d609314d91fd64350d50b9013 Mods are now loaded as resource packs. Vanilla will scan for valid prefixes based on subdirs of 'ass
		ets' which can then be referenced as ResourceLocations with the "<prefix>:path" notation.
	LexManos:
		Updated FML:
		MinecraftForge/FML@5a97d183dfb13b0f831172a1afef7407347ea7bc Remember to update your patches!!!!
		MinecraftForge/FML@f1b533ad87ea08d6e62259c59779bcec1636e2fe Keep these on our servers until the launcher is actually fixed -.-
	LexManos: Fix bound texture in Controls screen, Closes #631 and #629
	LexManos: Make Block.setIconName public
	LexManos: Update filler block to prevent useless console warning.
	LexManos: Fix resource domain when loading icon. Textures should be located in /assets/{domain}/textures/{block|item}/{name}.png Same strcutre as before except 'assets' instead of 'mods'.
	LexManos: Update ChestGenHooks for new Dungeon chest strcture.
	Christian:
		Start: f1b533ad87ea08d6e62259c59779bcec1636e2fe
		End: f21cd286ca8e974b75536224a38cc0dacaca8454
		Updated FML:
		MinecraftForge/FML@f21cd286ca8e974b75536224a38cc0dacaca8454 Resource packs, part two. FML mods are now resource packs. Vanilla will scan anything under 'assets' and turn it into a resource prefix. Use resourcelocations to look stuff up.
	LexManos: Move resource location resolution down to TextureAtlasSprite and allow for sprites that are not stitched.
	LexManos: Attempt to gather lastBuild information to fix ChangeLog's off-by-one issue.
	LexManos:
		Updated FML:
		MinecraftForge/FML@6f0eedc9a64e4e246c40335e91b4868ad7f5a9e2 Fixed ClassCastException when loading ModLoader mods
		MinecraftForge/FML@8844554da6d5d15756d7b0a9da2f5924006b3190 Merge pull request #243 from jrtc27/modclassloader
		MinecraftForge/FML@7aa7221756d62ea1fbc750d7cf7acfdb28d75f2e Fix transformer search
		MinecraftForge/FML@5f7df5e742cbc21565cee0d25709b5cb5462127c Revert "Keep these on our servers until the launcher is actually fixed -.-"
		MinecraftForge/FML@ad79b9ed86eaf8c2702d79505d78a931c1774560 Fix up some deprecation warnings, and clean up coremod code that's going away.
		MinecraftForge/FML@ba3707af22376f8f18103f63db56e4614a9c37db More javadoc cleanup
	LexManos: Update dev worksapce: Proper natives location and new server launch profile.
	LexManos: TEMPORARY fix for MCP mapping issue.
	LexManos: Include MANIFEST file from FML's universal.jar, makes the jar runnable now!
	LexManos:
		Updated FML:
		MinecraftForge/FML@155e8468180c93f1886a64028628764b1b22dd58 Add in support for mods/<mcversion> as a mod location. Also drop coremods as a location. They go in mods too now.
		MinecraftForge/FML@3f4bf61ae6757605b27078c7321de9f640876836 Update key
		MinecraftForge/FML@4545beb49d5348d8632e42965627b9837115525b Add deobf-data to setup env.
		MinecraftForge/FML@e24f94951741709329208f738000b72933302a24 Fix eclipse workspaces and launch configurations.
		MinecraftForge/FML@532bee7ce1c4392ee11f0389d98f0c2be6240aa0 Update to new MCP bugfix version, Fixes: Missing Armor/Item rendering, and Boss health mapping issues.
	LexManos:
		Updated FML:
		MinecraftForge/FML@7ce84491d1d4eada442944e02fc0e50c51f8045c Fix missing argument and startclient/startserver support.
	LexManos: Fix domain issue with SoundPool entries.
	LexManos: Add hook for EntityWither trying to destroy a block.
	LexManos: Fix lether item rendering colors.
	LexManos: Render pass sensitive version of Item.hasEffect, Closes #517
	LexManos: Fix compile errors temporarily, dont use till updated to new system.
	LexManos: Add missing air checks to WorldGenTrees and ChunkCache Closes #593
	LexManos: Updated FML: MinecraftForge/FML@54e06e841d1c8df24fc30e1ec3a51def67f58858 Move Resource refreshing until affter postInit.

Build 1.6.1-8.9.0.768:
	LexManos: Add missing air checks to WorldGenTrees and ChunkCache Closes #593
	LexManos: Updated FML: MinecraftForge/FML@54e06e841d1c8df24fc30e1ec3a51def67f58858 Move Resource refreshing until affter postInit.

Build 1.6.1-8.9.0.767:
	richard: Techne model loader (incomplete for debugging)
	richard: Complete it, got the bug figured out
	LexManos: Fix compile errors temporarily, dont use till updated to new system.

Build 1.6.1-8.9.0.766:
	LexManos: Add hook for EntityWither trying to destroy a block.
	LexManos: Fix lether item rendering colors.
	LexManos: Render pass sensitive version of Item.hasEffect, Closes #517

Build 1.6.1-8.9.0.765:
	jadran.kotnik: Added rotation support for all vanilla blocks that can be rotated.

Build 1.6.1-8.9.0.764:
	LexManos:
		Updated FML:
		MinecraftForge/FML@7ce84491d1d4eada442944e02fc0e50c51f8045c Fix missing argument and startclient/startserver support.
	LexManos: Fix domain issue with SoundPool entries.

Build 1.6.1-8.9.0.763:
	LexManos:
		Updated FML:
		MinecraftForge/FML@155e8468180c93f1886a64028628764b1b22dd58 Add in support for mods/<mcversion> as a mod location. Also drop coremods as a location. They go in mods too now.
		MinecraftForge/FML@3f4bf61ae6757605b27078c7321de9f640876836 Update key
		MinecraftForge/FML@4545beb49d5348d8632e42965627b9837115525b Add deobf-data to setup env.
		MinecraftForge/FML@e24f94951741709329208f738000b72933302a24 Fix eclipse workspaces and launch configurations.
		MinecraftForge/FML@532bee7ce1c4392ee11f0389d98f0c2be6240aa0 Update to new MCP bugfix version, Fixes: Missing Armor/Item rendering, and Boss health mapping issues.

Build 1.6.1-8.9.0.762:
	LexManos: Update dev worksapce: Proper natives location and new server launch profile.
	LexManos: TEMPORARY fix for MCP mapping issue.
	LexManos: Include MANIFEST file from FML's universal.jar, makes the jar runnable now!

Build 1.6.1-8.9.0.761:
	LexManos:
		Updated FML:
		MinecraftForge/FML@6f0eedc9a64e4e246c40335e91b4868ad7f5a9e2 Fixed ClassCastException when loading ModLoader mods
		MinecraftForge/FML@8844554da6d5d15756d7b0a9da2f5924006b3190 Merge pull request #243 from jrtc27/modclassloader
		MinecraftForge/FML@7aa7221756d62ea1fbc750d7cf7acfdb28d75f2e Fix transformer search
		MinecraftForge/FML@5f7df5e742cbc21565cee0d25709b5cb5462127c Revert "Keep these on our servers until the launcher is actually fixed -.-"
		MinecraftForge/FML@ad79b9ed86eaf8c2702d79505d78a931c1774560 Fix up some deprecation warnings, and clean up coremod code that's going away.
		MinecraftForge/FML@ba3707af22376f8f18103f63db56e4614a9c37db More javadoc cleanup

Build 1.6.1-8.9.0.760:
	LexManos: Attempt to gather lastBuild information to fix ChangeLog's off-by-one issue.

Build 1.6.1-8.9.0.759:
	LexManos: Move resource location resolution down to TextureAtlasSprite and allow for sprites that are not stitched.

Build 1.6.1-8.9.0.758:
	Christian:
		Start: f1b533ad87ea08d6e62259c59779bcec1636e2fe
		End: f21cd286ca8e974b75536224a38cc0dacaca8454
		Updated FML:
		MinecraftForge/FML@f21cd286ca8e974b75536224a38cc0dacaca8454 Resource packs, part two. FML mods are now resource packs. Vanilla will scan anything under 'assets' and turn it into a resource prefix. Use resourcelocations to look stuff up.

Build 1.6.1-8.9.0.757:
	LexManos: Update ChestGenHooks for new Dungeon chest strcture.

Build 1.6.1-8.9.0.756:
	LexManos: Make Block.setIconName public
	LexManos: Update filler block to prevent useless console warning.
	LexManos: Fix resource domain when loading icon. Textures should be located in /assets/{domain}/textures/{block|item}/{name}.png Same strcutre as before except 'assets' instead of 'mods'.

Build 1.6.1-8.9.0.755:
	LexManos: Update ToolMaterial enum helper.
	LexManos: Release will now build a installer jar and use the standard 'target' output folder.
	LexManos:
		Updated FML:
		MinecraftForge/FML@29d6c875d0675ffa14428c511bd6ebe9232a486c Add FML Installer logo crated by @ZaverSLO https://twitter.com/ZaverSLO/status/349947190300508162
		MinecraftForge/FML@3d17434510e890574b68c8a181b80c830b5d043a Build installer package for the new client launcher.
		MinecraftForge/FML@bf38d947569911dab03319a8b0f1964f36b195b2 Update json samples
		MinecraftForge/FML@7037184a4e724300001dfc1f8df2e76a0ec30368 Fix up release JSON
		MinecraftForge/FML@dc7d02ebf6c9fc5965344a9aeca79f230a40afb4 Fix json syntax error.
	LexManos:
		Fix installer unintended replace.
		
		Updated FML:
		MinecraftForge/FML@9b6525e80504ff72a1798cf5797bf148295db776 Point scala downloads to our servers, Launcher doesn't like standard maven repos.
	LexManos:
		Updated FML:
		MinecraftForge/FML@91ecf711092e1610dd10e77cdd517c3324e62d8d Fix -rel json
		MinecraftForge/FML@efc369ee83a7b62f605c13e16efad66b63b4bd8c Fix EventHandler annotation.
		MinecraftForge/FML@fbd57b32641b540d609314d91fd64350d50b9013 Mods are now loaded as resource packs. Vanilla will scan for valid prefixes based on subdirs of 'ass
		ets' which can then be referenced as ResourceLocations with the "<prefix>:path" notation.
	LexManos:
		Updated FML:
		MinecraftForge/FML@5a97d183dfb13b0f831172a1afef7407347ea7bc Remember to update your patches!!!!
		MinecraftForge/FML@f1b533ad87ea08d6e62259c59779bcec1636e2fe Keep these on our servers until the launcher is actually fixed -.-
	LexManos: Fix bound texture in Controls screen, Closes #631 and #629

Build 1.6.1-8.9.0.751:
	LexManos:
		Updated FML:
		MinecraftForge/FML@1229c4c4ea888f4f69272eed94ef5a53ce79ccda Fix src distrabution, and got rid of pesky common folder in eclipse workspace. src is now installable.
		MinecraftForge/FML@902772ed0cb6c22c4cd7ad9b0ec7a02961b5e016 Revert common folder fix, Common folder does nothing, feel free to delete it after first load.
	LexManos: Update src distro installer script. Source distro works now!

Build 1.6.1-8.9.0.750-1.6:
	LexManos:
		Updated FML:
		MinecraftForge/FML@1229c4c4ea888f4f69272eed94ef5a53ce79ccda Fix src distrabution, and got rid of pesky common folder in eclipse workspace. src is now installable.
		MinecraftForge/FML@902772ed0cb6c22c4cd7ad9b0ec7a02961b5e016 Revert common folder fix, Common folder does nothing, feel free to delete it after first load.
	LexManos: Update src distro installer script. Source distro works now!

Build 1.6.1-8.9.0.749:
	LexManos: Update workspace for new library structure.
	LexManos: Update FML to 16launch branch
	LexManos: Initial patch update to 1.6, Does not compile, need to update references to the old TexturePack system.
	LexManos: Small fixup, need to Update GuiIngameForge for new HUD changes.
	LexManos:
		Updated FML:
		MinecraftForge/FML@6a318ddb784ca8b2bef0f6718089f7beb4d404e0 Fix typo in new packages.
		MinecraftForge/FML@3711da9c456d20865a965734cc5aeaf7f5cb5e5d Another typo
		MinecraftForge/FML@e35e4b16ff3d6dea547c41f02f2ca31ebe1f74aa More fixups
		MinecraftForge/FML@18371bd8c9bd107f774289da35519f593ccc8ee7 Some fixes for updated mcp code
		MinecraftForge/FML@ef646d3146e1f285d2cb8e79a74373beffa84774 Merge branch '16launch'
		MinecraftForge/FML@7406b38d8ad1bc5c2c641c74f1614b946f246588 1.6.1
		MinecraftForge/FML@12c928c538c1c04d3a21255c747d15468328ace9 Tweak commands patch
		MinecraftForge/FML@3f15cd54c2d776ea161aaedbecad9e188d66578f Functional client @ 1.6.1
		MinecraftForge/FML@71a92de5d95fccc4fe17cc39d0836891c6622f4d Client launch for eclipse
	LexManos:
		Updated FML:
		MinecraftForge/FML@8960f6869fbe30d358a40997c47999025c3eae68 Add windows lzma executable http://tukaani.org/xz/ He states that most things are under public domai
		n, But I couldn't find an exact reference to this executable. I'm going to assume it under public domain and distribuiting it here is fine. If not someone pleas
		e direct me to the apropriate license and I will act accordingly.
		MinecraftForge/FML@70cfe24e67adf6872ef1501599e2115e420c2539 Fix wrong project name in distro eclipse launch.
		MinecraftForge/FML@7a004087f79b94bc92f29d50eb71288b6c1c968c Add deobf data to src dist. Dont create deobf jar as we ship the lzma Added *.lzma to .gitignore
	LexManos:
		Updated FML:
		MinecraftForge/FML@110cf372eb5aa85df20b248976f1acdefa85e102 Add deobf data to merge-common, workspace is now actually runnable!
	LexManos: Support dirty submodules in changelog script.
	LexManos: 1.6.1 Update
	LexManos: Add new launch configs to dev workspace.
	LexManos: Update GuiIngameForge to reflect Mojang changes in 1.6.1
	LexManos:
		Updated FML:
		MinecraftForge/FML@c418da353f6a8420b095fa737e8b0eae270d31ae Cleanup coremod code, server side working now.
	LexManos: Update release script to generate binary patches and include deobf data.
	LexManos: Deprecation sweep and update version to 8.9 to reflect 1.6.1 update.
	LexManos: MinecraftForge/FML@7fecf2ad6bdd918149a3c43453f6a78bd11e5404 Update mcp URL.
	LexManos: Try absolute path, to not confuse jenkins.

Build 1.6.1-8.9.0.748-1.6:
	LexManos: Try absolute path, to not confuse jenkins.

Build 1.5.2-7.8.1.738:
	LexManos: Fic Chest content gneeration delegate call. Cloases #609
	LexManos: Add air check to Flint and Steel Ref: #602

Build 1.5.2-7.8.1.737:
	LexManos: Bump Forge revision and mark recomended.

Build 1.5.2-7.8.0.736:
	LexManos: Added EntityLiving to Block.isLadder arguments, deperacating older version. New parameter has the possibility of being null, so modders must take care. Closes #608
	LexManos: Add air checks to BlockSand falling and Piston pushing. Please report any other issues with custom 'Air' blocks in issue #602

Build 1.5.2-7.8.0.735:
	mitchel.pyl: Fix tripwire patches for solid sides

Build 1.5.2-7.8.0.734:
	Christian:
		Fix server patch FML update
		
		Updated FML:
		MinecraftForge/FML@22738de028a9ba51d43d73857dfb8969985566f0 Attempt to properly fix deadlock if the internal server derps. It should never hang now. Damn you fast computer..
		MinecraftForge/FML@05a854cd2af53ca822ee8b249b0b3bbe44f94675 Small tweaks to the mcp data. Nothing major..

Build 1.5.2-7.8.0.733:
	Christian: Make glass panes and iron fences connect to block sides based on solidity. This does change IBlockAccess, so anything with a custom IBlockAccess may need to implement the new method.

Build 1.5.2-7.8.0.732:
	LexManos: Forgot most important side, release script.

Build 1.5.2-7.8.0.731:
	LexManos: Fixed changelog generation.

Build 1.5.2-7.8.0.730:
	LexManos: Fix AIOOB exception in crash reporting if exception does not have a stack. Possible, but odd.

Build 1.5.2-7.8.0.729:
	LexManos: Fix hoes being able to till dirt under other blocks, and made it look for air type blocks.
	LexManos: Add NPE protection to refernce to MinecraftServer.worldServer

Build 1.5.2-7.8.0.728:
	LexManos: Fix Air block check in BlockPortal.

Build 1.5.2-7.8.0.727:
	LexManos:
		Add NPE protection to ItemStack delegates. Closes #601
		Also cleaned up the names of said delegates, we do not have to follow MCP's crowdsourced names as they are very bad.
		Redirected damage through setItemDamage to allow items to have finder control of breaking.

Build 1.5.2-7.8.0.726:
	LexManos: Disable ImageIO's File based cache, should speed up texturepack loading/stitching.

Build 1.5.2-7.8.0.725:
	Christian:
		Updated FML:
		MinecraftForge/FML@24c405665105a789a0708a7e30c8bcb96899da6b Add in an optional modid identifier for @SidedProxy. It's main use is when both scala and java @Mods reside in the same package, and you want the @SidedProxy behaviour for a specific @Mod language type. In general it should not be needed otherwise.
		MinecraftForge/FML@cd0466395a8f1af3ec44f124bf4088df2d318603 Fix sysout with trailing messages after a newline

Build 1.5.2-7.8.0.724-newliquid:
	jeffreykog: RenderGameOverlayEvent.Post(ALL) is now called in GuiIngameForge
	LexManos: Fix arbitrary GUIContainer text coloring by forcing lighting to be disabled. Closes #594
	Christian: Patch village distance checking to use floats instead of ints, to avoid int wrapping
	Christian: Fix isAir check to see if a portal can light. Should fix w/Railcraft and others
	LexManos: Make changelog generation non-fatal untill we get jenkins issue figured out.
	LexManos: Add cache for ASM Event Handler bridge classes, should not need to redefine a class to invoke the same method on different instances.
	LexManos: Ignore registration of a object that is already registered. Preventing duplicate callback invocations. Thanks King_Lemming for pointing this out.
	Christian:
		Updated FML:
		MinecraftForge/FML@6f3da9736531153629fb4213e3b2cae776bfb50a Don't throw an exception if the scala adapter find a java proxy. I may add some distinguishers to @SidedProxy so you know which mod it's for.
		MinecraftForge/FML@59fe905695421a5be9370b0009ef794abaaf75bb Don't continue trying to send events to mods that depend on errored mods.

Build 1.5.2-7.8.0.723:
	Christian:
		Updated FML:
		MinecraftForge/FML@6f3da9736531153629fb4213e3b2cae776bfb50a Don't throw an exception if the scala adapter find a java proxy. I may add some distinguishers to @SidedProxy so you know which mod it's for.
		MinecraftForge/FML@59fe905695421a5be9370b0009ef794abaaf75bb Don't continue trying to send events to mods that depend on errored mods.

Build 1.5.2-7.8.0.722:
	jeffreykog: RenderGameOverlayEvent.Post(ALL) is now called in GuiIngameForge

Build 1.5.2-7.8.0.721:
	LexManos: Ignore registration of a object that is already registered. Preventing duplicate callback invocations. Thanks King_Lemming for pointing this out.

Build 1.5.2-7.8.0.720:
	LexManos: Add cache for ASM Event Handler bridge classes, should not need to redefine a class to invoke the same method on different instances.

Build 1.5.2-7.8.0.719:
	Christian: Fix isAir check to see if a portal can light. Should fix w/Railcraft and others
	LexManos: Make changelog generation non-fatal untill we get jenkins issue figured out.

Build 1.5.2-7.8.0.716:
	Christian: Patch village distance checking to use floats instead of ints, to avoid int wrapping

Build 1.5.2-7.8.0.715:
	LexManos: Fix arbitrary GUIContainer text coloring by forcing lighting to be disabled. Closes #594

Build 1.5.2-7.8.0.713:
	Christian:
		Updated FML:
		MinecraftForge/FML@843a13c1ab1e3901160082fa63c557243fb64675 Try and clean up cycle detection output a bit
		MinecraftForge/FML@82e9de8641c6a559eec711ea6d1e940d99cbc98f More tweaks to the mod sorting code
		MinecraftForge/FML@ac97370f94d10beee5f021795cddda827c4411d4 Add in a pretty sorting error screen
		MinecraftForge/FML@f1d68ed4c82cd28e50ec6a0befc55ff0165bfe08 Throw the sorting exception
		MinecraftForge/FML@edc1fb24e2cad9badd2dd18ccccd590d77156e18 Send the "suspect list", and print the suspect versions

Build 1.5.2-7.8.0.711:
	bloodshot:
		Add support for servers to register dimensions on client.
		
		In order to support multi-worlds such as MultiVerse, the server needs the
		ability to register dimensions on client or many forge mods such as IC2
		will not function correctly. This has been an issue for MCPC which
		provides both Forge and Bukkit support to players. By adding the
		DimensionRegisterPacket class, MCPC now has the ability to send the
		required packet to client to register a dimension with DimensionManager.
	LexManos: Cleanup Dimension Registration packet, generate takes no arguments, and added fix to world to prevent providers from overwriting the dimension ID.
	LexManos: Fix potential GL issue when atlas animations bind textures without informating RenderEngine.

Build 1.5.2-7.8.0.710:
	LexManos:
		Introduced the framework for Forge's packet handler system. Heavily based off FMLPacket.
		Packet splitting and reconstruction is handled.

Build 1.5.2-7.8.0.708:
	Christian:
		Updated FML:
		MinecraftForge/FML@3bf50c4bbe82f0cc317dafcf2a569cb5210bc738 Fix server side derp with Forge network packet handler

Build 1.5.2-7.8.0.707:
	LexManos: Fix type in biome list.
	LexManos: Fixed creative tab rendering with invalid color closes #588

Build 1.5.2-7.8.0.706:
	Christian:
		Add forge network handling support
		
		Updated FML:
		MinecraftForge/FML@4922e90d81d8b8b9374c4d04858a06c5bf03965c Separate network mod config from setup. Allows for Forge Packet Handler nicety

Build 1.5.2-7.8.0.705:
	mehvids: Add hitInfo field to MovingObjectPosition for when an int doesn't suffice

Build 1.5.2-7.8.0.704:
	LexManos: Fix another NPE when Items are in Block range with custom renderers, Modders keep your items out of the block range! Closes #581
	LexManos: Fixed render count for stacks of blocks 40+ and distrabution of items based on scale. Closes #579

Build 1.5.2-7.8.0.703:
	Christian: Remember x & z passed to getTopSolidOrLiquidBlock and use it for foliage tests. Fixes #575

Build 1.5.2-7.8.0.702:
	Christian: Fix blending on the hotbar. Closes #574

Build 1.5.2-7.8.0.701:
	Christian:
		Updated FML:
		MinecraftForge/FML@23b070c7d02a8da44bf04c2f9ba2b485a44ad967 Alternative @SidedProxy setter for Scala.
		MinecraftForge/FML@2cca7aa759b4b6c3a128ce43bbd924e4762c43c2 Some more Scala @SidedProxy adjustments. Now properly supporting pure singletons, i.e. object C {   @SidedProxy(...)   var proxy: P = null } Removed fallback, as all such singletons are properly handled by the new code now, and class implementations fall back to the code also used for plain Java mods.
		MinecraftForge/FML@8517a824e5251c409e05999d42fc6d70497609f5 Merge declaration and initialization of a variable.
		MinecraftForge/FML@a3a920437f3ede6841ae2c449a38975b02b28088 Merge pull request #230 from fnuecke/master
	Christian: Add in a very simple stencil bit registry to try and arbitrate between mods wanting to use stencil bits in rendering

Build 1.5.2-7.8.0.700:
	hbiede:
		Added oreQuartz
		
		Gives a default quartz Ore Dictionary (I know of at least 3 used by different mods that use Nether Quartz as an equivalent).
	gholdampf: updated FurnaceRecipes.java.patch
	mike.stengel: Created an ItemStack sensitive version of canHarvestBlock.

Build 1.5.2-7.8.0.699:
	CovertJaguar:
		Possible NPE if the liquid isn't in the LD
		
		https://github.com/BuildCraft/BuildCraft/issues/787

Build 1.5.2-7.8.0.698:
	LexManos: Fix NPE when rendering EntityItems that are not blocks but int he block range.

Build 1.5.2-7.8.0.697:
	LexManos: Prevent water from dropping snowballs.

Build 1.5.2-7.8.0.696:
	LexManos: Fire EntityJoinWorled event for forced entities {Players and there mounts} as well, just ignore the cancelled value.

Build 1.5.2-7.8.0.695:
	LexManos:
		MinecraftForge/FML@787c0c4a6af3af60928b3a90f383a305a17a4347 Don't spit error on LWJGL not supporting 4.3 just warning.
		Make custom item renderers attempt to use EQUIPPED type when running first person. For backwards compatiblity, will be removed in 1.6.
		And a small change to make the 1.6 check not print it's stack trace.

Build 1.5.2-7.8.0.693:
	purpleposeidon: Fix render bounding box of trapped double chests
	jholcroft:
		Make getStencilBits static
		
		Made getStencilBits static so it can be called.

Build 1.5.2-7.8.0.692:
	LexManos: Move Partical rendering down in the order, after everything else. Should fix particals rendering behind water, digging process, and selection.

Build 1.5.2-7.8.0.691:
	LexManos: Fixed NPE in rendering dragged items.

Build 1.5.2-7.8.0.690:
	LexManos:
		Attempt to allocate a 8-bit stencil buffer when creating Minecraft's display context. If that throws an error it will revert back to it's default values.
		Also contains a method for modders to rereive how many bits the context was created with. Closes #552

Build 1.5.2-7.8.0.689:
	LexManos: EntityPlayer sensitive version of Item.isValidArmor, deprecated older version. Closes #551
	LexManos: Changed to just plane entity for flexability.
	LexManos: New RenderPlayer and RenderLiving events. Closes #493

Build 1.5.2-7.8.0.688:
	pahimar: Update forge_at.cfg

Build 1.5.2-7.8.0.687:
	mitchpetrie29: Separate EQUIPPED and EQUIPPED_FIRST_PERSON Item Render Types

Build 1.5.2-7.8.0.686:
	LexManos: Capture and fire the PlaySoundAtEntity event for The client entity. Minecraft does some odd bypasses for no good reason. Thanks iPixile for reporting this.

Build 1.5.2-7.8.0.685:
	LexManos:
		Updated FML:
		MinecraftForge/FML@99bb50d8f8d27217ba58a41c802a504213e99461 Improved Entity Spawn Error
		MinecraftForge/FML@c0cca7f41d5b080e39dd8d3d6cfc329295c822e6 Merge pull request #227 from CovertJaguar/patch-1
		MinecraftForge/FML@49111e9c5cffab49ec35f965801c3f0496f6def6 Add version detection to astyle and print error if it doesnt detect version 2.0+
		 Also fixed astyle's config for max-instatement-indent that sometimes caused crashes with certian versions of astyle.

Build 1.5.2-7.8.0.684:
	LexManos:
		Update to 1.5.2 PR.
		MinecraftForge/FML@f0bba74a4748935ef3a715ae2f45feb75cc20376 Update for minecraft 1.5.2
		MinecraftForge/FML@62fdbad74c2507d147ecab56f56029135d88c6f5 Update MCP's md5 for the fixed srg files.
	LexManos:
		Updated FML:
		MinecraftForge/FML@00f00b17bf0da262e6fe3e327ca2deedf7146305 Fix scalac detection to actually use the located command instead of defaulting to 'scalac'
	LexManos: Fixed hardcoding of MC version in debug text.
	LexManos: Bump version number for 1.5.2

Build 1.5.2-7.8.0.683-1.5.2:
	LexManos: Bump version number for 1.5.2

Build 1.5.1-7.7.2.682:
	cadyyan: Fixed build error handling using invalid Python syntax.

Build 1.5.2-7.7.1.681-1.5.2:
	LexManos: Fixed hardcoding of MC version in debug text.

Build 1.5.2-7.7.1.680-1.5.2:
	LexManos:
		Updated FML:
		MinecraftForge/FML@00f00b17bf0da262e6fe3e327ca2deedf7146305 Fix scalac detection to actually use the located command instead of defaulting to 'scalac'

Build 1.5.1-7.7.2.679:
	LexManos: Changelog generator will now bundle failed builds with the next successful build. Should make it look better and prevent the version numbers from being confusing.

Build 1.5.1-7.7.2.678:
	LexManos: Bump version to 7.7.2 so I can make a release.

Build 1.5.1-7.7.1.676:
	tobias: Fixed ListenerListInst not being rebuild after unregistering a listener, causing calls to unregistered event listeners.
	tobias: Replaced derpy tabs with spaces

Build 1.5.1-7.7.1.675:
	kinglemming:
		-Add vanilla Ores to the Ore Dictionary. No recipe replacement required.
		-Add NBT-sensitive getMaxDamage() for ItemStack.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>

Build 1.5.1-7.7.1.674:
	LexManos: Attempted a fix for the changelog generation, should print all builds back to 1 now.

Build 1.5.1-7.7.1.673:
	Christian:
		Updated FML:
		MinecraftForge/FML@cf9b5b445ba284d389c7e32a03d9c8ef43469042 Don't leave scala running in interactive mode.

Build 1.5.1-7.7.1.672:
	Christian:
		Updated FML:
		MinecraftForge/FML@cfda7fc738ce6079f625a3822ebff5e7e0db5669 Fix URL for MCP
		MinecraftForge/FML@781c68121626321e0efddaf4c4db9f1b8b5911db Some fixups for scala compilation in MCP. Scala should now be compilable and reobfuscatable with srgnames in MCP.
	Christian: Try and be less noisy about world leaks
	Christian: ItemStack delegation to Item for damage values.
	LexManos: Fix rotation issue with non-block items.
	Christian:
		Updated FML:
		MinecraftForge/FML@ddadf93ca1d648d88fdb61c9625cd675c3650ccd Fix when an old scalac is present on the system to not fail the build
	Christian:
		Updated FML:
		MinecraftForge/FML@aa200923f0fe0c548faa4f103d803ade2e49d19d Fix patch derp.

Build 1.5.1-7.7.1.667:
	Christian:
		Updated FML:
		MinecraftForge/FML@dcf069ca52738a7bb7bde01f1c7ebd2e06cd0ac6 Attempt to reduce lines on the screen for id mismatch. Hopefully prevents game crashes.
		MinecraftForge/FML@58ba24add2a96bf4c079d5919f2d90dcc2f380e4 Fix possible NPEs in GameData

Build 1.5.1-7.7.1.666:
	Christian:
		Updated FML:
		MinecraftForge/FML@a3b5eaacfdd9218ef68d3dc064bba729b797cb3d Fix a small modloader compatibility derp: closes #222
		MinecraftForge/FML@677a6e578e84109702365da4a784f9a57d8c9957 Fix scala supporting SidedProxy. It should work now.
		MinecraftForge/FML@334a76de75f2b417f04c23526c7e66ceb48e0de2 Update FMLDeobfuscatingRemapper.java
		MinecraftForge/FML@42f1d8795599e0d1a516a1fdd7488a09b77e4565 Merge pull request #224 from Glought/master
		MinecraftForge/FML@2dcabe01232b48009acbca6724565598761f561b Add a to string to fmlmodcontainer: should mean less derpy cyclic dependency data
		MinecraftForge/FML@11ac46daebe901a6012a09ba5f6fe44af5b1be06 Fixing the GameRegistry. Now it is possible to register a Block with a BlockItem using following code: MyBlock myBlock = new MyBlock(); GameRegistry.registerBlock(myBlock, MyBlockItem.class, "myBlock"); where MyBlockItem class has one constructor with signature: public MyBlockItem(int id, Block block)
		MinecraftForge/FML@c3fda11d100f9db7c32ef212ac37eade3e35d701 Merge pull request #225 from MarcinSc/master
	Christian: Add forge/FML data to the f3 screen.

Build 1.5.1-7.7.1.665:
	LexManos:
		Forge now takes control of GuiIngame's renderGameOverlay, and spits out a ton of events to give modders control of how the screen is rendered.
		Inital draft for community feedback.

Build 1.5.1-7.7.1.664:
	LexManos: Allow spawning of Bonemeal particles even if block is not set.

Build 1.5.1-7.7.1.663:
	LexManos: Fix the BLOCK_3D render helper for items that aren't an instance of ItemBlock Closes #533
	LexManos: Fix replaceable checks to work on blocks with a non-replacable material, Closes #532
	LexManos: Restore world unload event for client worlds Closes #531

Build 1.5.1-7.7.1.662:
	LexManos: Fix logic issue in CrashReportCategory patch, blame Jadedcat for sloppy quick patch.

Build 1.5.1-7.7.1.661:
	lhb:
		Fix for ClassCastException when attempting to fetch Biome types from BiomeDictionary
		
		Attempting to fetch the BiomeDictionary types linked to a biome throws a ClassCastException. This fixes that
	lhb: getBiomesForType will cause the same problem

Build 1.5.1-7.7.1.660:
	Christian:
		Updated FML:
		MinecraftForge/FML@b3d4ea05ec633fb1898e97febf786f1a3e420986 Fix possible NPE in findItemStack, closes #218
	Christian:
		Simple block recolouring API: closes #525
		Fix up documentation on "rotation" API: it is up to the mod to decide interpretation of "rotation" for the mod/block.

Build 1.5.1-7.7.1.659:
	LexManos: Fix return value of EnchantPower hook, closes #518
	LexManos: Adds a field to the player for maximum health. Player.dat additions are present, getMaxHealth() needs a magic number for spawning. Closes #527

Build 1.5.1-7.7.1.657:
	LexManos: New hook to allow Items to render Helmet overlays like pumpkins do.

Build 1.5.1-7.7.1.656:
	Christian:
		Updated FML:
		MinecraftForge/FML@394f424185a044afcd6b31f400e731478171dd18 Fix to output versions in crash logs
		MinecraftForge/FML@8f35adca7a41c280a4b63d4787f042f615966cac Use more expressive language when a version specifier is a simple unbounded above condition

Build 1.5.1-7.7.1.655:
	Christian:
		Updated FML:
		MinecraftForge/FML@5673c1dd2966536000c2b3f17f85131204c4a291 Add srgname to registerTileEntityWithAlternatives
		MinecraftForge/FML@7aea09f4ca2f087d59ff6cb0de1c8e3e8b9ea4df Add type info to properly deobfuscate overloaded fields. Fixes #210.
		MinecraftForge/FML@edffd04ed2e89ece75189f76b92ae47643ec92f8 Add in some caching of the read field descriptions for efficiency
		MinecraftForge/FML@0daf1a6df4203d97be65a76a46550f6ad22ccc79 Merge branch 'agaricusb-fix-deobf-field'
		MinecraftForge/FML@ada52078c75fdfa506a4287c112d01d9af961d5a Merge pull request #216 from agaricusb/add-srgname

Build 1.5.1-7.7.1.654:
	jmacwilliams: fixed a bug that prevented proper lava generation near bedrock

Build 1.5.1-7.7.1.653:
	LexManos: Fix AIOOB in crash report stack trimming.

Build 1.5.1-7.7.1.652:
	pahimar: Fix a derp in that we provision the various arrays for a face, even if we are not going to parse data into it. Solves NPEs for when obj models that don't have texture coordinates attempt to render.
	pahimar: Missed a bit

Build 1.5.1-7.7.1.651:
	LexManos: Cave and Ravine gen will now take into account the Biomes top and foller block, allowing them to break the surface in modded biomes. Beaches, MushroomIslands and Deserts are exempt from this check to preserve vanilla world gen functionality. Closes #491

Build 1.5.1-7.7.1.650:
	Christian: Fix offset in AdvancedModelLoader. *doh*

Build 1.5.1-7.7.1.649:
	LexManos: Added NBT data to liquid stacks. Closes #501
	LexManos: Added a small method in the Block.java to specify the amount of enchanting power it can supply to an enchanting table. Closes #508

Build 1.5.1-7.7.1.648:
	LexManos: Item callback for EntityItem update tick. Closes #426
	LexManos: Add Item 'swing' callback for use when playing the arm swing animation. Closes #505

Build 1.5.1-7.7.1.647:
	Christian: Delete sneaky extra file

Build 1.5.1-7.7.1.645:
	LexManos: Re-add and mark deprecated the old signature for ForgeHooksClient.getArmorTexture.

Build 1.5.1-7.7.1.644:
	Christian:
		Deprecate preloadTexture, make it a no-op. Should stop derpiness with new
		texturing system performance tweaks.

Build 1.5.1-7.7.1.643:
	LexManos:
		Updated FML: MinecraftForge/FML@4836b3272a9b292c62816c1d1f9e845486753839 Re-worked the Texture patches, optifine helper function, and re-added support fo
		r dynamically rotating the texture for mod authors who do things horribly wrong.

Build 1.5.1-7.7.1.642:
	Christian:
		Fix performance of texture uploads
		
		Updated FML:
		MinecraftForge/FML@00c788308881a07a683e17e2e9382313f3719b45 Very significant improvement in performance by using glSubImage to upload data. Inspired by frequent complaints about performance of hires texture packs. They probably still need a beefy system but should work. Hopefully I can figure out why the subImage GL side copy isn't working properly for an even more significant speed boost. But this gets things started.
		MinecraftForge/FML@57ad221cc6d9605b9d521f86620c2a31f922ac24 And add the patches *sigh*
	Christian:
		Updated FML:
		MinecraftForge/FML@a31607ae7d0214101679a1ecf1ae8032a5257eda Fix compilation derp, and clean up rotation helper.

Build 1.5.1-7.7.1.640:
	LexManos: Small optimization for usages of Minecraft.getGLMaximumTextureSize(), only need to calculate it once.
	LexManos: Small bugfix in Stitcher that was preventing ti from fully filling the possible texture space. Should lower the amount of empty space in textures.
	LexManos:
		Optimize Texture loops a bit for non-rotated textures. Should help the FPS loss on higher resolution texture packs. If it becomes a major issue we may have to look into a more  optimized animation system.
		
		https://mojang.atlassian.net/browse/MC-13206

Build 1.5.1-7.7.1.639:
	LexManos: Fix scoreboard saving bug caused by our fix of vanilla map saves.

Build 1.5.1-7.7.1.638:
	LexManos: Updated FML: MinecraftForge/FML@1de89525cc2265bdce8704d9bd0d31c57bca4d97 Fixed issue with instalation when java/javac commands had quotes.
	LexManos: Deprecate long dead interface that moved to FML. remvoe next MC version.

Build 1.5.1-7.7.1.637:
	LexManos: Updated FML: MinecraftForge/FML@704a70902fca3de620375116a33dccd3d6d576d0 Sanitize input to isRemappedClass to use '/' as a package seperator like the srg files.

Build 1.5.1-7.7.1.636:
	froggytheturtle:
		This allows the result of the explosion to take into account metadata,
		tile entities, or even to cancel it altogether.
		
		Allowed block exploding to take into account tile entity and metadata
	LexManos: New hook to allow Items to provide there own armor models. Closes #487

Build 1.5.1-7.7.1.635:
	LexManos: Fix item deletion in creative menu for items that are the same id/meta but differnet NBT's. Closes #479
	LexManos: Untag NBTTagList.removeTag as client side only, allowing simple removal ont he server side. Closes #477

Build 1.5.1-7.7.1.634:
	LexManos: Allow items to provide there own FontRenderer for there tooltips. Added for #463

Build 1.5.1-7.7.1.633:
	ProjectZulu: Added maxCanSpawnInChunk event to allow overriding of creature chunk spawn cap
	ProjectZulu: Clarify Factory call and Event Functionality
	LexManos: Add function to remove categories from a configuration, indavidual properties can be removed using ConfigCategory.remove() Closes #462

Build 1.5.1-7.7.1.632:
	LexManos:
		Pulled Biome Tag System by Emasher, Closes #433
		An issue with biome adding mods which is becoming increasingly annoying for players, is that many mod authors that add biome specific world generation or mobs in their mods, for the most part, hard code them to work with vanilla biomes only. This becomes a huge problem when it's difficult to even find a vanilla biome, let alone a specific one, when biome mods are installed.
		
		A simple solution to this problem is a tag system for biomes that allows mod authors to set up their world generators, or mobs to generate or spawn in biomes that have been registered with a specific tag such as "FOREST", or "FROZEN". I wrote such a system a few months ago, which I've been using with my own mods, and have made available to anyone who wants to use it. Since then, I've had requests from mod authors and players alike to try and get it, or at least similar functionality, into Forge, where other mod authors will be more comfortable using it.
		
		Aside from the tags, it also includes a rule based system to classify biomes that have not already been registered with it when information is requested on them (You can opt out of this by registering a biome as type "NULL"). And additionally, the ability to register IWorldGenerators for specific biomes, or biome types (tags) to speed up chunk generation a little bit.

Build 1.5.1-7.7.1.631:
	LexManos: Deprecate IArmorTextureProvider, moved to Item. And exposed more information to the function. Closes #365

Build 1.5.1-7.7.1.630:
	LexManos: Updated FML: MinecraftForge/FML@570faeb790745c35403c67fabab57651b71da576 Added the ability to save transformed classes to disc for debugging.
	LexManos: Add checking for 'ENUM$VALUES' in EnumHelper. Eclipse uses it's own internal compiler which does not follow the java standard of making the values field names $VALUES and private. Instead its public and ENUM$VALUES. Closes #502

Build 1.5.1-7.7.1.629:
	LexManos: Revert MinecraftForge/MinecraftForge@f594109b30c87f5a0996eee9e8c4513380733cee If concurancy issues arise we will reassess. The provided solution caused entities to be removed incorrectly and cause 'invisible' entities client side.

Build 1.5.1-7.7.1.628:
	LexManos: Fix EntityPlayer passed to Bonemeal event.

Build 1.5.1-7.7.1.627:
	LexManos: Fix off-by-one in rotated textures.
	LexManos: Removed index bounds checking in some chunk functions, if you error blame Grum.

Build 1.5.1-7.7.1.625:
	LexManos: Fix vanilla texture bug causing rotated textures to be placed wrong.

Build 1.5.1-7.7.1.624:
	Christian:
		Updated FML:
		MinecraftForge/FML@8b8837c9ff635d4988e0a1504fca38667825daf0 Fix NPE when branding isn't present

Build 1.5.1-7.7.1.623:
	kraphteu: Remove unneeded SideOnly. ref: Buildcraft/Buildcraft#710

Build 1.5.1-7.7.1.622:
	Christian:
		Removed obsolete patches
		Updated FML:
		MinecraftForge/FML@26ccb9106e443e664b0fdc1b95c3600b90ab2bc5 Change snooper/crash report brand handling. fmlbranding now loads another string!
		MinecraftForge/FML@eff464cf0e656d92dfedf16e79e5cd6c36b9fc76 And the core patches for that

Build 1.5.1-7.7.1.621:
	Christian: Sanity check the item ID for loaded liquid stacks better.

Build 1.5.1-7.7.1.620:
	Christian: Make liquidstacks immutable in their type data. Sorry about this, but it makes things a lot easier.
	Christian: Add in persistence code for LiquidTank. Using it should protect against liquids that get removed f.e. Closes #395

Build 1.5.1-7.7.1.618:
	Christian: Fix up liquidstack so it knows about the texture sheet for it's icon

Build 1.5.1-7.7.1.617:
	Christian: Fix AT file

Build 1.5.1-7.7.1.616:
	Christian: Fix possible NPE in ChunkManager. Closes #478 in reality

Build 1.5.1-7.7.1.615:
	Christian: made BlockFluid.theIcon protected
	Christian: fix bug #489 from #429
	Christian: Fix up some liquid logic

Build 1.5.1-7.7.1.614:
	Christian:
		Updated FML:
		MinecraftForge/FML@2bc6a0666f8a54f6b1fbc3398c6e3a385ecd35b5 Attempt to make any "default package" class public. This might fix problems with certain modloader mods that ship changes to vanilla classes.
	Christian: Use the liquid name in liquid stack persistence. Closes #429
	Christian: Fix hashCode
	Christian:
		Updated FML:
		MinecraftForge/FML@0d844874124649099dbcbb9ae2b36719e1dda25f Fix up derp in access transformer

Build 1.5.1-7.7.1.611:
	LexManos: Bump version number for 1.5.1 Note: We really need to do this more...

Build 1.5.1-7.7.0.610:
	LexManos: Fix NPEs when modders stupidly register null texture names.

Build 1.5.1-7.7.0.609:
	LexManos: Fixed issue with Event.hasAnnotation ignoring it's parameter. And cached its values for potential performance gain. Closes #482

Build 1.5.1-7.7.0.608:
	jesse:
		Entity Extended Properties Changes
		
		Adds IExtendedEntityProperties interface, which specifies three methods
		that are needed:  Init, Save, and Load.
		
		Adds the EntityConstructing event, which is called during the
		constructor of Entity.  It is needed there so that the reference is in
		place during the ReadNBT call.
		
		Adds hooks into Entity that allow registration of
		IExtendedEntityProperties classes, as well as saving and loading to NBT.
	jesse:
		Brewing Stand Changes
		
		Added an event on potion ingredient applied.  Event contains the item
		stacks of each of the potions being brewed as well as any remaining
		ingredients.
		
		Changed TileEntityBrewingStand and SlotBrewingStandPotion to look for
		instanceof ItemPotion rather than potion.itemID
	jesse:
		Player Flyable Fall Event
		
		Adds an event to EntityPlayer that is posted on player fall when the
		player has flight capabilities.
	Christian: Fix itemframe render bug
	Christian: Add in block rotation support. It supports most vanilla blocks (hopefully), logs should be added soon.
	jesse:
		Access Transformer Changes
		
		AT changes and corresponding class changes.
		Additions (all made public):
		EntityLiving.targetTasks
		PotionHelper.potionRequirements
		PotionHelper.potionAmplifiers
		PotionEffect.duration
		Potion.setIconIndex
		Item.setPotionEffect
		Block.blockHardness
		Block.blockResistance
	jesse:
		Enderman Teleport Event
		
		New event when an enderman teleports that allows the teleport location
		to either be modified or completely cancelled.
	jesse:
		Enderman attackEntityFrom changed
		
		Changed so that if the teleport fails upon being attacked, Endermen will
		take damage as normal.
	jesse:
		Ender Teleport Changes
		
		Renamed Ender Teleport Event and added it in to ender pearls.
	jesse:
		quick bugfix in entityenderman
		
		reversed boolean check on event result
	Christian:
		Updated FML:
		MinecraftForge/FML@2d368c4c2eb6b4e0bb60757b6e1679c23aaad9db Itemstacks in the GameRegistry (manual registration by mods)
	Christian:
		Updated FML:
		MinecraftForge/FML@5e1949eb0e3a43d3ec6c710289532d93f6819934 Clone the itemstack, and allow for passing in a stacksize
	Christian:
		Updated FML:
		MinecraftForge/FML@ede93d438f2b5fab92cd6a459247ca158354e430 Validate supplied stack size
		MinecraftForge/FML@d73ac867df775174dafdd2da193fabd7c3e7407e Add a mechanism to dump the registry- useful for mod developers.
	Christian:
		Updated FML:
		MinecraftForge/FML@82bc9f1b35f5d51a722d294dd252e6bab4d54fa4 Add some information, and a log message letting you know it worked
	Christian: Update patches!
	Christian: Re-enable changelog? Hopefully...
	Christian: Changelog fixup
	Christian: Damn you python and your tab obsession!

Build 1.5.1-7.7.0.605:
	Christian: Fix AT config for texturemap

Build 1.5.1-7.7.0.604:
	Christian:
		Allow itemstack sensitive damage computation for attacks. Should allow
		storing data in the nbt :)

Build 1.5.1-7.7.0.603:
	Christian:
		Updated FML:
		MinecraftForge/FML@d9db27275ea06d37ae75e201140019ca152314b0 Fix mismatch screen a bit. Should render more correctly now and at least not be blank in a lot of circumstances..
	Christian: Allow items to decide if they can or cannot have book enchantments applied

Build 1.5.1-7.7.0.602:
	Christian:
		Updated FML:
		MinecraftForge/FML@d1ff1967b50f2ff2edf0b60acdb6508c0a3eeb06 Fixed FMLRelaunchLog's Newline Handling
		MinecraftForge/FML@591a25722b36d2d1b200a31278cb8da117363f6b Merge pull request #208 from jrtc27/patch-1

Build 1.5.1-7.7.0.601:
	Christian:
		Updated FML:
		MinecraftForge/FML@f709ce757984b13acb7208d6d8fbdeaa83d2928d Fix missing block world rendering
		MinecraftForge/FML@748eece456e079a21112a77047d004d4f410b170 Merge pull request #206 from mDiyo/patch-1
		MinecraftForge/FML@012a755bb9ce9737c843b0dfd86473d143b637be Fix up patch properly. Also, fix md5s for the jars.

Build 1.5.1-7.7.0.600:
	LexManos:
		Update to 1.5.1 Pre-Release:
		MinecraftForge/FML@9565529baf77de27ed8b75be2065da3ba08d16c8 Updated to latest MCP and Minecraft 1.5.1 Pre-release.
		MinecraftForge/FML@a573faf92def5dd01af380b3ca86de877c1178a2 Someone derped up this function bad, revert name.
	LexManos: MinecraftForge/FML@aaf02ea2ac938d8cbaafdd2f59985c0604d648d7 Updated for new PR client jar.

Build 1.5-7.7.0.598:
	LexManos:
		Updated FML:
		MinecraftForge/FML@3c346247e1c5de12d4548f6a99349157057e2de6 Fix NPE with CoreMods who do not have the new MCVersion annotation.
	LexManos:
		Updated FML:
		MinecraftForge/FML@625da6492dddcaca8133718aeee97f9981ced623 Fix install.py --mcp-dir option. Fixes #204.
		MinecraftForge/FML@687d3c059d054c338c25a489be206a9f3dc63d81 Merge pull request #204 from agaricusb/fix-mcpdir

Build 1.5.1-7.7.0.597-1.5.1:
	LexManos: MinecraftForge/FML@aaf02ea2ac938d8cbaafdd2f59985c0604d648d7 Updated for new PR client jar.

Build 1.5-7.7.0.595:
	LexManos: Change placement of ChunkDataEvent.Save call to apply before sending to worker thread.

Build 1.5-7.7.0.594:
	Christian:
		Updated FML:
		MinecraftForge/FML@5cc90f060caace93c0bf041d3cc37208f425f623 Fix the logger to treat newlines better, hopefully. Closes #199
		MinecraftForge/FML@5e3af8ac0e18cfa3a92f9ba726ec1a6b55e87d97 Use the relaunch log, for class circularity safety.
		MinecraftForge/FML@ce949e6099fe2a63ee6774acd6e55aa55d3b3673 Support simple mc version test in coremods, only effective through jar loading. Also, log some more data about the environment.

Build 1.5-7.7.0.593:
	LexManos:
		New TextureStitchEvents called before and after a TextureMap gathers and stitches textures together.
		Also added a config option to diable the writing of resulting stitched textures to disc. Default disables the writing.

Build 1.5-7.7.0.592:
	LexManos:
		Updated FML:
		MinecraftForge/FML@24022ab6ba79e4babb57fc0db893c23d4aec85bc Added comments to note FML-only methods
		MinecraftForge/FML@8905237306230a33e2a3bab7a2b6f7a8b42d94e4 Merge pull request #200 from bspkrs/patch-2
		MinecraftForge/FML@577b19c1cf12a354112e829fb5704c32fd6cd0a5 Fix potential NPE in class loading and add extra debug information.

Build 1.5-7.7.0.591:
	LexManos: Fix placing of certian items on Redstone Blocks.

Build 1.5-7.7.0.590:
	LexManos: Fix equipment slots for items when right clicked, and dispensed using a dispensor.

Build 1.5-7.7.0.589:
	LexManos: Prevent pistons from generating snowballs.
	LexManos: Fix logic inversion that allowed SnowMen to create snow on hoppers.

Build 1.5-7.7.0.588:
	lepko.san: Fix ShapedOreRecipe checking mirrored recipes

Build 1.5-7.7.0.587:
	Christian: Fix multipass item rendering so that it uses the right spritesheet for the item.

Build 1.5-7.7.0.586:
	froggytheturtle:
		Made WorldServer.allPlayersSleeping public
		
		Made EntityPlayer.sleepTimer public
		
		Sleep changes

Build 1.5-7.7.0.585:
	LexManos: Fix Activator rails activating TNT carts, closes #458

Build 1.5-7.7.0.584:
	github: Update ForgeDummyContainer.java

Build 1.5-7.7.0.583:
	Christian:
		Updated FML:
		MinecraftForge/FML@c5d5f4e5164111c5ae63e8de7ce97cc583d73e6e Fix AllPublic access transformer not affecting methods. Should fix modloader compatibility

Build 1.5-7.7.0.582:
	LexManos:
		Updated FML:
		MinecraftForge/FML@4762d4d8ef00bd789ffb6bccbd12f7478b07da62 Allocate more ram {typically 256 is defailt} to fermflower, should fix decomplication issues on OSX
		MinecraftForge/FML@6370c242f0e1cb8ec80c7dccc1133cb0d0607bae OS X's python 2.6.1 has a bug in zipfile.extractall that makes it unzip directories as regular files. So switch to extract

Build 1.5-7.7.0.581:
	LexManos: Remove the block if TE errors.

Build 1.5-7.7.0.580:
	LexManos: Add config toggle to atempt to remove TileEntities and Entities that error during there update without fully crashing the server, use at your own risk. Closes #424

Build 1.5-7.7.0.579:
	Christian:
		Updated FML:
		MinecraftForge/FML@8f2dbf7046f52d836993edb946d7d310b399bf9d Fix up stupid derp in IMC code: actually reset the IMC list after each delivery. Fixes a bunch of mods. Sorry everyone.

Build 1.5-7.7.0.578:
	ohai.iChun:
		[Bugfix] One should not assume an item would use the item spritesheet.
		
		Item class has a func to return an int to use terrain.png or items.png. This makes forge take account of it.

Build 1.5-7.7.0.577:
	LexManos: Fix bug with rendering one too many passes for ItemEntities Closes #450
	LexManos: Fix RedstoneBlock power issues, Closes #452
	LexManos: Fix for nether quartz not generating in the nether, Closes #454

Build 1.5-7.7.0.576:
	LexManos: Deprecation Sweep in DungeonHooks and fixed wildcard in ChestGenHooks remove function.

Build 1.5-7.7.0.575:
	LexManos: Fix RenderItem to work with items that use the terrain texture map that aren't in the block ID range. Close #443
	LexManos: Move the RenderWorldLastEvent back to before renderHand like it was in 1.4 Closes #444
	LexManos: Add call to EntityLiving when counting entities for Spawning Cap. Closes #447
	LexManos: Fix missed wildcard change in OreDictionary closes #448

Build 1.5-7.7.0.574:
	LexManos: Fix crash when EnumHelper can't find $VALUES field, log info, and return gracefully.

Build 1.5-7.7.0.573:
	Christian:
		Updated FML:
		MinecraftForge/FML@23ea835fa7bc0cdb466d058814b5a0e0c67e8c9a Pass obfuscation status to coremods

Build 1.5-7.7.0.572:
	Christian: Some tweaks to the liquid dictionary, to allow for canonical liquid stacks for things like rendering
	Christian:
		Updated FML:
		MinecraftForge/FML@d88db6c0cfd5484428b574889eae02d34535beae Fix up deep tree deobfuscation

Build 1.5-7.7.0.571:
	LexManos: Removed get/setTextureFile from Block, nolonger used.
	LexManos:
		Updated FML:
		MinecraftForge/FML@7b722bfcd6d4c6867d15492c293a455dfd50d272 Update MCP for latest PR silent update.
		MinecraftForge/FML@c6dab815f4e036e25b8f56bef7b8ee63f838adb4 Missed joined.exc, must fix scripts.

Build 1.5-7.7.0.569:
	LexManos:
		Updated FML:
		MinecraftForge/FML@a90504315e928915345c7b04972d912cdaa0bfdb Readjust size of mods button when Minecraft Realms button is enabled.

Build 1.5-7.7.0.568:
	Christian: Fix the oredictionary for the new recipe wildcard value of Short.MAX_VALUE.

Build 1.5-7.7.0.567:
	Christian:
		Updated FML:
		MinecraftForge/FML@3765ceb02d783ae5156976f3165bafdb6a3ddbb3 Update MCP, fixes the "broken texture packs" problem.

Build 1.5-7.7.0.566:
	Christian:
		Updated FML:
		MinecraftForge/FML@179c504746910d4196eef3ee2d56f63cf585c983 Simplify logic in tick start/end
		MinecraftForge/FML@29edd242cd7a1fadedf4fb874ea8bbd4e643bffa Fix coremods without a manifest crashing the game. Closes #181
		MinecraftForge/FML@ac16845fc4661fa046a252eda7f9a9a847940189 Fix demo mode crash. Closes #187
		MinecraftForge/FML@984291cee91f585a6f4300eedfed882c814843f8 Fix supertype parsing to handle null superclass (Hi Object!). Closes #160
		MinecraftForge/FML@f6479299936f0f94cfc43210dd9dd44b8b5350ef Merge branch 'master' of github.com:Uristqwerty/FML
		MinecraftForge/FML@b301e8e4c1877be246fd4f0b45085b70773d8f2b Change type of connection queue to a concurrent linked queue. Much more efficient, hopefully. Closes #189
	Christian:
		Updated FML:
		MinecraftForge/FML@dab22f5b74f3f2a410e20583f811605dc8e3c05f Fix "0 mods" display when installed in forge.

Build 1.5-7.7.0.565:
	Christian:
		Updated FML:
		MinecraftForge/FML@485db6be2e6b54a9a523a2b06e0d886792b0826a Use the reobfuscation maps in the reflection helper for field lookups: should help some reflection cases with the deobf.
	Christian:
		Updated FML:
		MinecraftForge/FML@591e65fa1aa52d2a72dc527ad1c2ac53c8eb94c4 Revert "Use the reobfuscation maps in the reflection helper for field lookups: should help some reflection cases with the deobf."
		MinecraftForge/FML@2a779ec3289f695b477ec6b0822a27801e2deba1 Try a different way of remapping the fields. Should work because it's userspace, not relauncher space
		MinecraftForge/FML@ca2d8bd83475f37946b86cf6fabd8ff810f9c2bf Fix reflection helper: it needs to unmap the classname to find the field maps.

Build 1.5-7.7.0.563:
	Christian:
		Updated FML:
		MinecraftForge/FML@25f3fcad4654d19637878bdfb2b70a9586fb3fc9 Fix up some relauncher stuff: the vanilla applet works now, as do other applets. Deobf data is resolveable for them too.

Build 1.5-7.7.0.562:
	LexManos:
		Updated FML:
		MinecraftForge/FML@6bf7c9878cc959d5f5fa8ec0bf9d0d75037df882 Fixed srg name of minecraftDir for runtime deobf.

Build 1.5-7.7.0.561:
	Christian: Refresh patch
	Christian:
		Updated FML:
		MinecraftForge/FML@95d0ff18cdca3b5a91b648c847c00f559f8ce6f2 Fix runtime deobfuscation for remapped inner classes

Build 1.5-7.7.0.560:
	LexManos:
		Updated FML:
		MinecraftForge/FML@86a9c7d35953296f7c8bd3a2b1b43115ef0f9308 Fixup reobfusication of server code if present.
		MinecraftForge/FML@8e7956397dd80902f7ca69c466e833047dfa5010 Just enable server side compile, and warn not to complain tous.
		MinecraftForge/FML@889efc1c0a9216b55f6de275e4f4a279d977e60c Fixes GameRegistry.registerBlock
		MinecraftForge/FML@fe1623a36a1bb8b0a046d833e896fd46d88898ef Merge pull request #195 from RainWarrior/snapshot15
		MinecraftForge/FML@62f5adf8e21d59408af409a88b2c81757fd3c587 Revert "Fix modlist to use the new texture binding functions, i think"
		MinecraftForge/FML@58ee06ea8edf508daa4ab3920790c0153cf6660d Some fixes for the snapshot
		MinecraftForge/FML@368a2245ef0071b0b7a35d3bd78ab1ae379f8faf Merge branch 'snapshot15'
		MinecraftForge/FML@1eba1dfdc00edf12ca3d8586dc342563218fc717 Fix accidental commands.patch overwrite
		MinecraftForge/FML@ebdb166ec87e63503f0071e557cdb44629a0e0c2 Merge branch 'snapshot15'
		MinecraftForge/FML@450dd8313c2e9e46d173bbd242f84d48266af7c8 Fix up some small things, merging into mainline
		MinecraftForge/FML@1642bad402efe819f4e763bf4b460d8c04194849 Fix Multi-part entity children ID issue, mobs with custom spawning must deal with child ids themselves.

Build 1.5-7.7.0.559:
	LexManos: Update patche for jad-style names.
	LexManos: Updated FML and at config for 1.5 snapshot
	LexManos: First patches updae to 1.5, Many rendeirng related changes, most notibly removed Item/Block's getTextureFile() functions.
	LexManos: Removed some dead code, We don't bind custom tessellators
	CovertJaguar: MCL Update
	LexManos: Bump major and minor version numbers to mark 1.5, it's gunna break everything. Should be a compileable 1.5 build.
	Christian:
		Fix a couple of forge patches
		
		Update FML: d075daf
		d075daf Merge branch 'master' into snapshot15 Fix up compilation and patching errors
		1bd6847 Fix up packages.csv ordering for easier diffing
		dd832f2 Update for MCP7.30c - fixes redstone rendering issues
		aebf6eb Add in a registry method to allow for alternative TileEntity names- they will be used to support loading maps containing the older definiti
		8921cfe Remember to add the new patches!
		cd67596 The "ServerStarting" event should now properly crash the server if it fails, so the client will properly exit. Also, added in a "pre-server
		e1c6630 Javadoc cleanup
		5ce4e31 Fix breaking change
		a99c488 Merge branch 'patch-1' of https://github.com/bspkrs/FML into gh-updates
		94282c5 Merge branch 'FMLLogFormatter' of https://github.com/donington/FML into gh-updates
		7ad8529 Update MCP to MCP7.26a and refresh MCP names
		15534ed Update address of the FML repository to the new location in all the files
		aa822e3 Fix logical error in comment text
		a14ab91 Update license text to make clear that FML is not a way to sidestep MCP licensing.
		0165742 Fix mcp conf md5 signatures for the snapshot
		26a5b31 FMLLogFormatter: dynamic log level name
	LexManos:
		Merge commit '695b080197bd577cc34fe6dbc72b74f4a74b2d5c' into snapshot15
		Testing cherry picking.
	LexManos:
		Sync up with FML, Will not run nativly as you need deobfusication_data.zip in your libs folder.
		We have not setup the download for that yet, to make it yourself just zip joined.srg name it deobfusication_data.zip and put it in lib
	LexManos: Not supposed to have debug stuff...
	LexManos: Updated Forge to s13w09c
	Christian: Fix up patches for FML, also, add in FML as a submodule rather than a zip
	Christian:
		Add in simple texture management for mods using the stitcher. Scope with "{domain}:{texture}" to
		get textures that are not at /textures/<item|block>/{texture}.png but /mods/{domain}/textures/<item|block>/{texture}.png
		instead
	LexManos: Testing selective commit of submodule.
	LexManos:
		Added submodule changelog ganerator:
		
		Updated FML:
		MinecraftForge/FML@e74087ee430633475c3ca058e54e3ef242a9d6aa Ignore again, testing submodule.
	LexManos: Removed GNUWin32 files and uneeded files seince FML is now a submodule.
	LexManos: Remove window helper batch files.
	LexManos: Update python scripts to reflect that FML is now a submodule. Delete updateasmdata as it's in /fml/ now. Build should work once again.
	LexManos: Change FML module to read-only connection.
	Christian: Update submodule
	LexManos: Copy over some needed files for debugging.
	LexManos: Rework configuration, configs should now use Config.hasChanged to deterne if thehould call save(), also re-worked the saving to not use String.format as much.
	LexManos: Fixed new python changes.
	LexManos:
		Updated FML:
		MinecraftForge/FML@aed2cc446ad8d5882890c5f218eb894ea7bd2577 Force file name encoding to UTF-8, caused different zips on different systems.
	LexManos: Fix animation location for textures with domains
	LexManos: Add helper functions for deling with custom TextureStitched
	LexManos: Add callback on TextureStitched to control texture loading.
	LexManos: New world event for controlling potential entity spawnlists. For #430
	LexManos: Removed erroring imports and update build function to die on errors.
	LexManos: Fix ItemSeedFood respecting custom soils.
	LexManos:
		Updated FML:
		MinecraftForge/FML@debbdc00be8ea1a261cdff83785ddc7100419a74 Capture Minecraft logs into FML logging
		MinecraftForge/FML@74fffc6fdc2eda8caa9a7feb0826d7babb84751a Update next render to 40
	Christian:
		Call stitcher for non-existent textures as well. Probably allows
		for generated textures. Hmmm
	Christian: let's do it right this time. Hmmm
	Christian:
		Updated FML:
		MinecraftForge/FML@abe4f73a9a3158f6f9d1ea2334798f54a25817bf FIX massive performance issue with FML. Thanks to @sfPlayer1 for finding this epic derp on my part!
	Christian: Add an Icon to the LiquidStack, for rendering the liquid in various ways
	LexManos: Readd second render pass to TileEntities and Entities, patches were missed when merging in master branch. As note, CB can DIAF.
	LexManos: Fix compile error, forget to flush to disc.
	LexManos: Make release quit on compile error.
	Christian: Clean up Access Transformer mapping data
	Christian:
		Updated FML:
		MinecraftForge/FML@e9ff699c2dcd787a3e0ebaa427c625a48de4c9fb Refresh the renderengine after modloading is complete. Should fix issues with out-of-place texture registration by mods.
		MinecraftForge/FML@a723aa68606d57b0ee5bac8b1d1905abef440b54 Refresh copyright notices on everything
		MinecraftForge/FML@c42a2101408b21799728c88e2d02c718c3b0dd36 Strip deprecated code
		MinecraftForge/FML@6eeae8c49ff4359dc21c44eb73e4e043285cd8bf Fix up state transition derp when the server crashes with an error- it shouldn't double-derp
		MinecraftForge/FML@81c6421f84c1bff359dfe927974e8730b348806a Tweak license text- any osi licensed project can use the asm transformer code
	LexManos:
		Updated to 1.5 Pre-release
		Updated FML:
		MinecraftForge/FML@2d98835db8c6a7665ef55117d60ab4318876836b Scala support! It's still primitive, I hope that people will like it. I do :)
		MinecraftForge/FML@5bfaf7c1700191b6ed8f4752c9a95bf8c25323ef Global object registry, also, support the new itemblockwithmetadata constructor
		MinecraftForge/FML@80a40c03e644840d827eb7d67ff97f6558eaa2e4 Update to MCP 1.5 and minecraft 1.5.
		MinecraftForge/FML@b3e854a15d7c50b4967be8237df5fdace95a15ee Update for new MCP with srg reobf.
	LexManos: Fix typos.
	LexManos: Deprecated Forge's ISidedInventroy, there is a vanilla solution. Added temporary config option to legacy furnace slot orientation.
	LexManos:
		Updated FML:
		MinecraftForge/FML@f1c6bdd57d41a938cb3326d509042f6842e42396 Support the MCP format of partial reobfuscation for portability. Ensure modloader-like compatibility
		MinecraftForge/FML@0419b9d9751ade4497343aefaf2ca43703eb479a Update MCP info for latest
	LexManos: Early define CrashReport classes to combat invalid crash details.
	LexManos: Fix reobf call.

Build 1.5-7.7.0.558-snapshot15:
	Christian: Clean up Access Transformer mapping data
	Christian:
		Updated FML:
		MinecraftForge/FML@e9ff699c2dcd787a3e0ebaa427c625a48de4c9fb Refresh the renderengine after modloading is complete. Should fix issues with out-of-place texture registration by mods.
		MinecraftForge/FML@a723aa68606d57b0ee5bac8b1d1905abef440b54 Refresh copyright notices on everything
		MinecraftForge/FML@c42a2101408b21799728c88e2d02c718c3b0dd36 Strip deprecated code
		MinecraftForge/FML@6eeae8c49ff4359dc21c44eb73e4e043285cd8bf Fix up state transition derp when the server crashes with an error- it shouldn't double-derp
		MinecraftForge/FML@81c6421f84c1bff359dfe927974e8730b348806a Tweak license text- any osi licensed project can use the asm transformer code
	LexManos:
		Updated to 1.5 Pre-release
		Updated FML:
		MinecraftForge/FML@2d98835db8c6a7665ef55117d60ab4318876836b Scala support! It's still primitive, I hope that people will like it. I do :)
		MinecraftForge/FML@5bfaf7c1700191b6ed8f4752c9a95bf8c25323ef Global object registry, also, support the new itemblockwithmetadata constructor
		MinecraftForge/FML@80a40c03e644840d827eb7d67ff97f6558eaa2e4 Update to MCP 1.5 and minecraft 1.5.
		MinecraftForge/FML@b3e854a15d7c50b4967be8237df5fdace95a15ee Update for new MCP with srg reobf.
	LexManos: Fix typos.
	LexManos: Deprecated Forge's ISidedInventroy, there is a vanilla solution. Added temporary config option to legacy furnace slot orientation.
	LexManos:
		Updated FML:
		MinecraftForge/FML@f1c6bdd57d41a938cb3326d509042f6842e42396 Support the MCP format of partial reobfuscation for portability. Ensure modloader-like compatibility
		MinecraftForge/FML@0419b9d9751ade4497343aefaf2ca43703eb479a Update MCP info for latest
	LexManos: Early define CrashReport classes to combat invalid crash details.
	LexManos: Fix reobf call.

Build 13w09c-7.7.0.556-snapshot15:
	LexManos: Make release quit on compile error.

Build 13w09c-7.7.0.555-snapshot15:
	LexManos: Readd second render pass to TileEntities and Entities, patches were missed when merging in master branch. As note, CB can DIAF.
	LexManos: Fix compile error, forget to flush to disc.

Build 13w09c-7.7.0.553-snapshot15:
	Christian: Add an Icon to the LiquidStack, for rendering the liquid in various ways

Build 13w09c-7.7.0.552-snapshot15:
	Christian:
		Updated FML:
		MinecraftForge/FML@abe4f73a9a3158f6f9d1ea2334798f54a25817bf FIX massive performance issue with FML. Thanks to @sfPlayer1 for finding this epic derp on my part!

Build 13w09c-7.7.0.551-snapshot15:
	Christian: let's do it right this time. Hmmm

Build 13w09c-7.7.0.550-snapshot15:
	Christian:
		Call stitcher for non-existent textures as well. Probably allows
		for generated textures. Hmmm

Build 13w09c-7.7.0.549-snapshot15:
	LexManos: Fix ItemSeedFood respecting custom soils.
	LexManos:
		Updated FML:
		MinecraftForge/FML@debbdc00be8ea1a261cdff83785ddc7100419a74 Capture Minecraft logs into FML logging
		MinecraftForge/FML@74fffc6fdc2eda8caa9a7feb0826d7babb84751a Update next render to 40

Build 13w09c-7.7.0.548-snapshot15:
	LexManos: Removed erroring imports and update build function to die on errors.

Build 13w09c-7.7.0.547-snapshot15:
	LexManos: New world event for controlling potential entity spawnlists. For #430

Build 13w09c-7.7.0.546-snapshot15:
	LexManos: Add callback on TextureStitched to control texture loading.

Build 13w09c-7.7.0.545-snapshot15:
	LexManos: Fix animation location for textures with domains
	LexManos: Add helper functions for deling with custom TextureStitched

Build 13w09c-7.7.0.544-snapshot15:
	LexManos: Copy over some needed files for debugging.
	LexManos: Rework configuration, configs should now use Config.hasChanged to deterne if thehould call save(), also re-worked the saving to not use String.format as much.
	LexManos: Fixed new python changes.
	LexManos:
		Updated FML:
		MinecraftForge/FML@aed2cc446ad8d5882890c5f218eb894ea7bd2577 Force file name encoding to UTF-8, caused different zips on different systems.

Build 13w09c-7.7.0.543-snapshot15:
	Christian: Update submodule

Build 13w09c-7.7.0.542-snapshot15:
	Christian: Fix up patches for FML, also, add in FML as a submodule rather than a zip
	Christian:
		Add in simple texture management for mods using the stitcher. Scope with "{domain}:{texture}" to
		get textures that are not at /textures/<item|block>/{texture}.png but /mods/{domain}/textures/<item|block>/{texture}.png
		instead
	LexManos: Testing selective commit of submodule.
	LexManos:
		Added submodule changelog ganerator:
		
		Updated FML:
		MinecraftForge/FML@e74087ee430633475c3ca058e54e3ef242a9d6aa Ignore again, testing submodule.
	LexManos: Removed GNUWin32 files and uneeded files seince FML is now a submodule.
	LexManos: Remove window helper batch files.
	LexManos: Update python scripts to reflect that FML is now a submodule. Delete updateasmdata as it's in /fml/ now. Build should work once again.
	LexManos: Change FML module to read-only connection.

Build 13w09c-7.7.0.539-snapshot15:
	LexManos: Updated Forge to s13w09c

Build 13w05b-7.7.0.538-snapshot15:
	LexManos: Not supposed to have debug stuff...

Build 13w05b-7.7.0.537-snapshot15:
	LexManos:
		Sync up with FML, Will not run nativly as you need deobfusication_data.zip in your libs folder.
		We have not setup the download for that yet, to make it yourself just zip joined.srg name it deobfusication_data.zip and put it in lib

Build 13w02b-7.7.0.536-snapshot15:
	mehvids: Gave entities and tile entities access to the second render pass for translucency.
	Christian: Attempt to fix a possible NPE in the face of ChickenBones' hackery. ChickenBones. stop it!
	Christian:
		Fix a potential problem with "Entity already added" when using the dormant
		chunk cache capability. The entities in the dormant chunk cache will get new
		IDs prior to the cached chunk returning.
	Christian: Fix NPE causing issue with the cache. Derpy derp.
	Christian:
		Add in TESR culling, and a new TileEntity method to allow for differential sizing of the
		TESR view culling vs the TE collision bounding box (the former defaults to the latter)
		Checked into a branch because it's likely to break expanded TileEntities.
	Christian: Bump the revision number for the TESR and renderpass changes
	Christian:
		Add in a mechanism for explicit subclassing of WeightedRandomChestItem to allow for
		generational style chest content generation rather than static. Cleans up some old code nicely
	Christian:
		We try and log a message if we detect a world leak: it's probably not infallible, but it should
		help mod developers- if you see this when testing your mod with, say, mystcraft, you're probably
		keeping a hold of an invalid handle to the World (either directly, or indirectly via Entity or TileEntity)
		and you should look to refactor to wrap those handles in WeakReferences
	LexManos: Moved warning logic down, so that no more tickets are isues if the mod is over it's alotment. Fixes #378
	LexManos: Forge Additions: Exposed ChunkCache.worldObj to public PR #383
	LexManos: Fixup a resource leak warning.
	LexManos: Add DimensionManager.unregisterProviderType for PR #388
	LexManos: Added input getters for Ore recipies, and javadoc warning for modders, #390
	LexManos: Rework canSilkHarvest hook to try and honor vanilla overrides, should close #391
	LexManos: Added catch to TileEntityChestRenderer for potential crash when modders do bad things -.- Closes #389
	LexManos: Change access of upper and lower chest fields of InventoryLargeChest to public. Closes #387
	LexManos: Change WorldServer.allPlayersSleeping to public, and remove the SideOnly annotation on EntityPlayer.getSleepTimer() Closes #393
	LexManos: Fix initalization issue with the clamping threshold config value.  And remove vanilla console spam related to it.
	Christian: Fix small derp in TE
	Christian:
		Update FML:549b6fd
		549b6fd IMC tweaks: runtimeMessages now work (thanks for all that testing for this much requested feature!) and IMCEvent will no longer rem
		9fafdc1 More logging tweaks. You can probably configure individual mod log files if you wish now
		f169f7c A log of logging cleanup. FML will now read logging.properties to configure logging channels a couple of times during startup. You
		3ac891f Try and handle "death on startup" a bit cleaner
		2dc0189 Deprecate the old GUI ticktype. They're dead and have been for some time.
		dd98784 Tweak a method signature
		1c9a510 Add parameters to FML install to enable/disable certian aspects. Applying patches, running transformer/merger, and decompiling serv
		1bd6847 Fix up packages.csv ordering for easier diffing
	Christian:
		Add in "armor ticking"- implement the interface and the armor piece will tick.
		
		Update FML:22dbe41
		22dbe41 Fix up mistake that broke all modloading. Nice.
	Christian: Fix TESR rendering for double chests
	Christian: Fix possible null case for collision bounding box.
	Christian: Remove the single use interface ITickingArmor, and apply to Item directly.
	Christian:
		Fix ServerBrand retriever- forge is now forge,fml!
		
		Update FML: cd96718
		cd96718 Fix HD mob skins, FINALLY!!! Stupid eyes are stupid.
	LexManos: Kill generated timestamp in config files, if you want to retreive this information, usethe file's modified time. Closes #404
	LexManos: Actually use the line parameter in ServerChatEvent, closes #401
	LexManos: Kill .sh wrappers until someone writes more robust versions, closes #392 and closes #402
	LexManos: Made LiquidStack.isLiquidEqual(ItemStack) properly check the contained liquid, in addition to obvious id/meta closes #399 and closes #403
	LexManos: Add item frame transformations to the EntityItem render helper Closes #407
	LexManos: Added a hook into SlotArmor so Items can control if they are classified as a Armor type. Closes #408
	LexManos: Fixes comparison for items in creative inventory, closes #411
	LexManos: Fix fortune modifier always passed as 0 to idDropped closes #412
	LexManos: Fix EventTransformer throwing an NPE when transforming a class that doesn't exist. Closes #413
	LexManos: Fix profiler issue with RenderGlobal patch. Closes #414
	LexManos: Jenkins needs this script, *pokes Overmind* -.-
	LexManos:
		Update FML to 556:
		b6d6f235 Fix sprite map issue.
		1158aa46 Fix Language Registry, closes #FML 163
		50ce6fb3 Option to disable renaming for srgnames.
	LexManos: Disable automatic equiti of pcke dup items for players, and fixed index issues in Player.setCurrentItemOrArmor.
	LexManos: Fixed entity colision above max world height, and below 0. Closes #400
	LexManos: Change usage of ketSet/get to entrySet in OreDictionary, closes #422
	LexManos: Fix movement speed check, closes #420
	LexManos: clarify what the size is measured in for the dormant chunk cache. -.-
	LexManos: ItemStack sensitive versions of Item.getPotionEffect and Item.isPotionIngredient Closes #321
	LexManos: WorldGen*Trees shoud not respect custom soils. Closes #355
	LexManos: Added unload event for client worlds Closes #405
	LexManos: Store the glMultiTexCoord lightmap for later use with glDrawArrays closes #406
	LexManos: Add water and lava to liquid dictionary by default, closes #419
	LexManos: Bump version to 6.6.2, declaring Forge for MC 1.4.7 feature complete, as 1.5 is on the horizon, only bug fixes from this point on. Unless something major happens on Mojang's end.
	LexManos: Fix TESR culling for beacons, and implement a good enough measure for Chests.

Build 13w02b-7.7.0.535-snapshot15:
	LexManos:
		Merge commit '695b080197bd577cc34fe6dbc72b74f4a74b2d5c' into snapshot15
		Testing cherry picking.

Build 1.4.7-6.6.2.534:
	LexManos: Fix TESR culling for beacons, and implement a good enough measure for Chests.

Build 1.4.7-6.6.2.533:
	LexManos: Bump version to 6.6.2, declaring Forge for MC 1.4.7 feature complete, as 1.5 is on the horizon, only bug fixes from this point on. Unless something major happens on Mojang's end.

Build 1.4.7-6.6.1.532:
	LexManos: Added unload event for client worlds Closes #405
	LexManos: Store the glMultiTexCoord lightmap for later use with glDrawArrays closes #406
	LexManos: Add water and lava to liquid dictionary by default, closes #419

Build 1.4.7-6.6.1.531:
	LexManos: WorldGen*Trees shoud not respect custom soils. Closes #355

Build 1.4.7-6.6.1.530:
	LexManos: Fix movement speed check, closes #420
	LexManos: clarify what the size is measured in for the dormant chunk cache. -.-
	LexManos: ItemStack sensitive versions of Item.getPotionEffect and Item.isPotionIngredient Closes #321

Build 1.4.7-6.6.1.529:
	LexManos: Disable automatic equiti of pcke dup items for players, and fixed index issues in Player.setCurrentItemOrArmor.
	LexManos: Fixed entity colision above max world height, and below 0. Closes #400
	LexManos: Change usage of ketSet/get to entrySet in OreDictionary, closes #422

Build 1.4.7-6.6.1.528:
	LexManos:
		Update FML to 556:
		b6d6f235 Fix sprite map issue.
		1158aa46 Fix Language Registry, closes #FML 163
		50ce6fb3 Option to disable renaming for srgnames.

Build 1.4.7-6.6.1.527:
	LexManos: Kill generated timestamp in config files, if you want to retreive this information, usethe file's modified time. Closes #404
	LexManos: Actually use the line parameter in ServerChatEvent, closes #401
	LexManos: Kill .sh wrappers until someone writes more robust versions, closes #392 and closes #402
	LexManos: Made LiquidStack.isLiquidEqual(ItemStack) properly check the contained liquid, in addition to obvious id/meta closes #399 and closes #403
	LexManos: Add item frame transformations to the EntityItem render helper Closes #407
	LexManos: Added a hook into SlotArmor so Items can control if they are classified as a Armor type. Closes #408
	LexManos: Fixes comparison for items in creative inventory, closes #411
	LexManos: Fix fortune modifier always passed as 0 to idDropped closes #412
	LexManos: Fix EventTransformer throwing an NPE when transforming a class that doesn't exist. Closes #413
	LexManos: Fix profiler issue with RenderGlobal patch. Closes #414
	LexManos: Jenkins needs this script, *pokes Overmind* -.-

Build 1.4.7-6.6.1.524:
	Christian:
		Fix ServerBrand retriever- forge is now forge,fml!
		
		Update FML: cd96718
		cd96718 Fix HD mob skins, FINALLY!!! Stupid eyes are stupid.

Build 1.4.7-6.6.1.523:
	Christian: Remove the single use interface ITickingArmor, and apply to Item directly.

Build 1.4.7-6.6.1.522:
	Christian: Fix possible null case for collision bounding box.

Build 1.4.7-6.6.1.521:
	mehvids: Gave entities and tile entities access to the second render pass for translucency.
	Christian:
		Add in TESR culling, and a new TileEntity method to allow for differential sizing of the
		TESR view culling vs the TE collision bounding box (the former defaults to the latter)
		Checked into a branch because it's likely to break expanded TileEntities.
	Christian: Bump the revision number for the TESR and renderpass changes
	Christian: Fix small derp in TE
	Christian:
		Update FML:549b6fd
		549b6fd IMC tweaks: runtimeMessages now work (thanks for all that testing for this much requested feature!) and IMCEvent will no longer rem
		9fafdc1 More logging tweaks. You can probably configure individual mod log files if you wish now
		f169f7c A log of logging cleanup. FML will now read logging.properties to configure logging channels a couple of times during startup. You
		3ac891f Try and handle "death on startup" a bit cleaner
		2dc0189 Deprecate the old GUI ticktype. They're dead and have been for some time.
		dd98784 Tweak a method signature
		1c9a510 Add parameters to FML install to enable/disable certian aspects. Applying patches, running transformer/merger, and decompiling serv
		1bd6847 Fix up packages.csv ordering for easier diffing
	Christian:
		Add in "armor ticking"- implement the interface and the armor piece will tick.
		
		Update FML:22dbe41
		22dbe41 Fix up mistake that broke all modloading. Nice.
	Christian: Fix TESR rendering for double chests

Build 1.4.7-6.6.1.520-TESRculling:
	Christian: Fix small derp in TE

Build 1.4.7-6.6.1.519-TESRculling:
	Christian:
		Add in a mechanism for explicit subclassing of WeightedRandomChestItem to allow for
		generational style chest content generation rather than static. Cleans up some old code nicely
	Christian:
		We try and log a message if we detect a world leak: it's probably not infallible, but it should
		help mod developers- if you see this when testing your mod with, say, mystcraft, you're probably
		keeping a hold of an invalid handle to the World (either directly, or indirectly via Entity or TileEntity)
		and you should look to refactor to wrap those handles in WeakReferences
	LexManos: Moved warning logic down, so that no more tickets are isues if the mod is over it's alotment. Fixes #378
	LexManos: Forge Additions: Exposed ChunkCache.worldObj to public PR #383
	LexManos: Fixup a resource leak warning.
	LexManos: Add DimensionManager.unregisterProviderType for PR #388
	LexManos: Added input getters for Ore recipies, and javadoc warning for modders, #390
	LexManos: Rework canSilkHarvest hook to try and honor vanilla overrides, should close #391
	LexManos: Added catch to TileEntityChestRenderer for potential crash when modders do bad things -.- Closes #389
	LexManos: Change access of upper and lower chest fields of InventoryLargeChest to public. Closes #387
	LexManos: Change WorldServer.allPlayersSleeping to public, and remove the SideOnly annotation on EntityPlayer.getSleepTimer() Closes #393
	LexManos: Fix initalization issue with the clamping threshold config value.  And remove vanilla console spam related to it.

Build 1.4.7-6.6.0.518:
	LexManos: Fix initalization issue with the clamping threshold config value.  And remove vanilla console spam related to it.

Build 1.4.7-6.6.0.517:
	LexManos: Moved warning logic down, so that no more tickets are isues if the mod is over it's alotment. Fixes #378
	LexManos: Forge Additions: Exposed ChunkCache.worldObj to public PR #383
	LexManos: Fixup a resource leak warning.
	LexManos: Add DimensionManager.unregisterProviderType for PR #388
	LexManos: Added input getters for Ore recipies, and javadoc warning for modders, #390
	LexManos: Rework canSilkHarvest hook to try and honor vanilla overrides, should close #391
	LexManos: Added catch to TileEntityChestRenderer for potential crash when modders do bad things -.- Closes #389
	LexManos: Change access of upper and lower chest fields of InventoryLargeChest to public. Closes #387
	LexManos: Change WorldServer.allPlayersSleeping to public, and remove the SideOnly annotation on EntityPlayer.getSleepTimer() Closes #393

Build 1.4.7-6.6.0.516:
	Christian:
		We try and log a message if we detect a world leak: it's probably not infallible, but it should
		help mod developers- if you see this when testing your mod with, say, mystcraft, you're probably
		keeping a hold of an invalid handle to the World (either directly, or indirectly via Entity or TileEntity)
		and you should look to refactor to wrap those handles in WeakReferences

Build 1.4.7-6.6.0.515:
	Christian:
		Add in a mechanism for explicit subclassing of WeightedRandomChestItem to allow for
		generational style chest content generation rather than static. Cleans up some old code nicely

Build 1.4.7-6.6.1.514-TESRculling:
	Christian: Bump the revision number for the TESR and renderpass changes

Build 1.4.7-6.6.0.513-TESRculling:
	mehvids: Gave entities and tile entities access to the second render pass for translucency.

Build 1.4.7-6.6.0.511:
	Christian: Fix NPE causing issue with the cache. Derpy derp.

Build 1.4.7-6.6.0.510:
	Christian:
		Fix a potential problem with "Entity already added" when using the dormant
		chunk cache capability. The entities in the dormant chunk cache will get new
		IDs prior to the cached chunk returning.

Build 1.4.7-6.6.0.509:
	Christian: Attempt to fix a possible NPE in the face of ChickenBones' hackery. ChickenBones. stop it!

Build 13w02b-7.7.0.508-snapshot15:
	scott: Add ability to WorldTypes to display the 'Customize' button and react to it
	LexManos:
		Update FML:
		New scripts for signing jars, and repackging source folders.
		Fix LanguageRegistry loading files in UTF-8 format. loadLocalization should work for non-xml in all languages now (assumes UTF-8)
		Fix incorrect end length calculation. Closes #161 Thanks BStramke!
	LexManos: Fix check in getItem() to allow lowest item ID #361
	CovertJaguar:
		Fixed render passes for EntityItems
		
		Should be < instead of <=
	Christian:
		Update licencing information to make clear that forge is allowed to redistribute and automatically
		download parts of MCP, but this permission is not transitive to people distributing MinecraftForge
		source independently of the MinecraftForge project.
		
		Update MCP to 7.26a and FML: 7ad8529
		7ad8529 Update MCP to MCP7.26a and refresh MCP names
		15534ed Update address of the FML repository to the new location in all the files
		a14ab91 Update license text to make clear that FML is not a way to sidestep MCP licensing.
	Christian:
		Update FML: a99c488
		a99c488 Merge branch 'patch-1' of https://github.com/bspkrs/FML into gh-updates
		94282c5 Merge branch 'FMLLogFormatter' of https://github.com/donington/FML into gh-updates
		aa822e3 Fix logical error in comment text
		26a5b31 FMLLogFormatter: dynamic log level name
	Christian: Merge part of PR #375 related to ChunkEvent.Load for the client side
	Christian:
		Update FML: 5ce4e31
		5ce4e31 Fix breaking change
	Christian:
		Add in patch to change how playerinstance sends TE chunk updates. It should always send just the TEs
		that changed now, and not "ALL" TEs. Also, added configuration value to change the 64 threshold to a
		configurable number
	Christian: Some javadoc fixes
	Christian:
		Change DimensionManager.getCurrentSaveRootDirectory() to try and work even for the new server about to start event
		
		Update FML:8921cfe
		8921cfe Remember to add the new patches!
		cd67596 The "ServerStarting" event should now properly crash the server if it fails, so the client will properly exit. A
	Christian:
		Update FML:aebf6eb
		aebf6eb Add in a registry method to allow for alternative TileEntity names- they will be used to support loading maps containing the older definiti
	Christian:
		Fix a couple of forge patches
		
		Update FML: d075daf
		d075daf Merge branch 'master' into snapshot15 Fix up compilation and patching errors
		1bd6847 Fix up packages.csv ordering for easier diffing
		dd832f2 Update for MCP7.30c - fixes redstone rendering issues
		aebf6eb Add in a registry method to allow for alternative TileEntity names- they will be used to support loading maps containing the older definiti
		8921cfe Remember to add the new patches!
		cd67596 The "ServerStarting" event should now properly crash the server if it fails, so the client will properly exit. Also, added in a "pre-server
		e1c6630 Javadoc cleanup
		5ce4e31 Fix breaking change
		a99c488 Merge branch 'patch-1' of https://github.com/bspkrs/FML into gh-updates
		94282c5 Merge branch 'FMLLogFormatter' of https://github.com/donington/FML into gh-updates
		7ad8529 Update MCP to MCP7.26a and refresh MCP names
		15534ed Update address of the FML repository to the new location in all the files
		aa822e3 Fix logical error in comment text
		a14ab91 Update license text to make clear that FML is not a way to sidestep MCP licensing.
		0165742 Fix mcp conf md5 signatures for the snapshot
		26a5b31 FMLLogFormatter: dynamic log level name

Build 1.4.7-6.6.0.507:
	Christian:
		Update FML:aebf6eb
		aebf6eb Add in a registry method to allow for alternative TileEntity names- they will be used to support loading maps containing the older definiti

Build 1.4.7-6.6.0.506:
	Christian:
		Change DimensionManager.getCurrentSaveRootDirectory() to try and work even for the new server about to start event
		
		Update FML:8921cfe
		8921cfe Remember to add the new patches!
		cd67596 The "ServerStarting" event should now properly crash the server if it fails, so the client will properly exit. A

Build 1.4.7-6.6.0.505:
	Christian: Some javadoc fixes

Build 1.4.7-6.6.0.504:
	Christian:
		Update FML: 5ce4e31
		5ce4e31 Fix breaking change
	Christian:
		Add in patch to change how playerinstance sends TE chunk updates. It should always send just the TEs
		that changed now, and not "ALL" TEs. Also, added configuration value to change the 64 threshold to a
		configurable number

Build 1.4.7-6.6.0.503:
	scott: Add ability to WorldTypes to display the 'Customize' button and react to it
	CovertJaguar:
		Fixed render passes for EntityItems
		
		Should be < instead of <=
	Christian: Merge part of PR #375 related to ChunkEvent.Load for the client side

Build 1.4.7-6.6.0.502:
	Christian:
		Update FML: a99c488
		a99c488 Merge branch 'patch-1' of https://github.com/bspkrs/FML into gh-updates
		94282c5 Merge branch 'FMLLogFormatter' of https://github.com/donington/FML into gh-updates
		aa822e3 Fix logical error in comment text
		26a5b31 FMLLogFormatter: dynamic log level name

Build 1.4.7-6.6.0.501:
	Christian:
		Update licencing information to make clear that forge is allowed to redistribute and automatically
		download parts of MCP, but this permission is not transitive to people distributing MinecraftForge
		source independently of the MinecraftForge project.
		
		Update MCP to 7.26a and FML: 7ad8529
		7ad8529 Update MCP to MCP7.26a and refresh MCP names
		15534ed Update address of the FML repository to the new location in all the files
		a14ab91 Update license text to make clear that FML is not a way to sidestep MCP licensing.

Build 13w02b-7.7.0.500-snapshot15:
	LexManos: Bump major and minor version numbers to mark 1.5, it's gunna break everything. Should be a compileable 1.5 build.

Build 1.4.7-6.6.0.499:
	LexManos:
		Update FML:
		New scripts for signing jars, and repackging source folders.
		Fix LanguageRegistry loading files in UTF-8 format. loadLocalization should work for non-xml in all languages now (assumes UTF-8)
		Fix incorrect end length calculation. Closes #161 Thanks BStramke!
	LexManos: Fix check in getItem() to allow lowest item ID #361

Build 1.4.7-6.6.0.497:
	LexManos: Added getter for Metadata smelting list, because, why not.. PR: #352
	LexManos: Fixed incorrect lighting in some cases. Closes issue #349
	LexManos:
		Added event hooks to control to allow mod control of mob spawning. PR: #337
		Deprecated LivingSpecialSpawnEvent in favor of new LivingSpawnEvent.SpecialSpawn

Build 1.4.7-6.6.0.496:
	LexManos: Fix issue where dungeon loot table had wrong values.
	LexManos: Fixed issue where ChunkPriderEvent.InitNoiseField used the wrong sizeY value.
	LexManos: Some small code cleanups.

Build 1.4.7-6.6.0.495:
	Christian:
		Update FML:6f1b762
		6f1b762 Move server stopped *after* the server has actually stopped. *sigh*

Build 1.4.7-6.6.0.494:
	Christian:
		Update FML:d9bfb29
		d9bfb29 Add in a "server stopped" event

Build 1.4.7-6.6.0.493:
	Christian:
		Attempt to resolve the entity concurrency issue, by simply deferring unload
		to the next tick

Build 1.4.7-6.6.0.492:
	Christian: Fix noisy exception logging
	Christian:
		Update FML:6fc7bc4
		6fc7bc4 Add in some classloader debugging information: use fml.debugClassLoading=true as a system property to track down prob

Build 1.4.7-6.6.0.491:
	Christian:
		Fix a missed patch and cleaned up other patches
		Rollback a method name change that breaks a lot of mods
		Update FML: fb701cd
		fb701cd Revert MCP name change for canConnectRedstone - it conflicts with a forge method of the same name and breaks 1

Build 1.4.7-6.6.0.490:
	Christian:
		Update for MC 1.4.7
		Update FML: f7cc50b

Build 1.4.6-6.5.0.489:
	LexManos: Attempt a fix for the new chunk compression changes.

Build 1.4.6-6.5.0.488:
	Christian:
		Update FML:1a232cf
		1a232cf Fix multiple GUI containers for ML containers. Sorry ultimatechest that this fix took so long, a bug report at
		853f54b Log if there's a problem reading the class bytes

Build 1.4.6-6.5.0.487:
	LexManos: Fix mobs spawning on inverted slabs/stairs.

Build 1.4.6-6.5.0.486:
	LexManos: Use nanoTime instead of currentTimeMillis for potential performance increase.
	LexManos: Fixed order <.< you saw nothing.

Build 1.4.6-6.5.0.484:
	LexManos: Fixed issue with Efficancy enchatment when connected to vanilla servers.
	LexManos: Fixed EntityMinecard missed patch, Issue #338
	LexManos: Fixed typo in dungeon loot

Build 1.4.6-6.5.0.483:
	Uristqwerty:
		Force parent ListenerListInsts to rebuild.
		
		Without this change, it is possible (and, in fact, nearly guaranteed) for lists to rebuild endlessly if a parent list is marked as needing a rebuild but never actually read. This change forces the parent list(s) to rebuild as well, resulting in a significant performance increase and smoother framerate due to greatly reduced GC activity.
	Christian: Protect deflation with a simple semaphore. Should close #336

Build 1.4.6-6.5.0.482:
	LexManos: Update FML: Fix NPE in fingerprint loading, and pass expectged fingerprint to FMLFingerprintViolationEvent

Build 1.4.6-6.5.0.481:
	Christian:
		Update FML: 7e6456d
		7e6456d Fix a message delivery issue in IMC
		664ebda Some tweaks for signing and ID matching

Build 1.4.6-6.5.0.480:
	LexManos:
		Fixes a vanilla bug where the player view would dip when stepping between certain blocks
		https://mojang.atlassian.net/browse/MC-1594
		Issue #318, let me know if you notice any issue.

Build 1.4.6-6.5.0.479:
	LexManos: Fixed parameter ordering u.u

Build 1.4.6-6.5.0.478:
	LexManos:
		Re-write/Deprecated DungeonHooks loot tables, now uses ChestGenHooks like the rest of the world gen. Also fixes issue #330 by adding in enchanted books.
		
		Should be API compatible.

Build 1.4.6-6.5.0.477:
	LexManos:
		Move chunk compression to the network thread in Packet 51 and 56
		
		This will reduce the server load considerably by doing the chunk data compression in writePacketData, which will be run from the network thread.
		
		The chunk compression can easily use 1/4th of the overall server thread CPU time if someone is exploring much, especially when moving quickly (e.g. with quantum leggings).
		
		Player, this is how it's properly done.

Build 1.4.6-6.5.0.476:
	LexManos: Fix missed patch in EntityMinecart, #334
	LexManos: Explicitly check if useItem is not denied, allows for denying the item without denying the block

Build 1.4.6-6.5.0.475:
	LexManos: Delete unneeded patch.

Build 1.4.6-6.5.0.474:
	Christian: Some access transformations to allow mystcraft to work again. Closes #331

Build 1.4.6-6.5.0.473:
	Christian: Fix Fireworks to always work in SMP

Build 1.4.6-6.5.0.472:
	Christian:
		Fix up enchantment at the enchanting table vs via a book. Adds in a method
		that previously exists under a new name: canApplyAtEnchantingTable()
		to determine enchantments that can apply at the enchanting table (a smaller
		subset of all possible enchantments for an item, now). Also, add your
		enchantments to the anvil book application list, if neccessary.

Build 1.4.6-6.5.0.471:
	Christian: Tweak packet56 to see if this resolves the apparent worldgen derpiness

Build 1.4.6-6.5.0.470:
	Christian:
		Server side only item callback: allow a held item to decide if it wants to pass sneak-clicks through
		to a block, or not. Defaults false- the same as the new vanilla behaviour (sneak clicks with an item
		in hand don't activateBlock anymore).

Build 1.4.6-6.5.0.469:
	Christian: Move another patch up a bit - should actually close #329

Build 1.4.6-6.5.0.468:
	Christian: Add IPlantable to itemseedfood. Potato and carrot support!

Build 1.4.6-6.5.0.467:
	LexManos:
		Update FML:
		Fixed issue with users who don't have the JDK installed in there path
		MCP will now output bfusicated files with windows reserved names to _name.class and FML will prioritize those names.
		Fixed placement of onConnectionClosed callback
	LexManos: Updated NetClientHandler for onConnectionClosed placement fix.
	LexManos: Fixed cpw's derp in the PlayerInteractEvent logic.

Build 1.4.6-6.5.0.466:
	Christian: Fix ItemInWorldManager so that itemUseFirst works, and the playerinteractevent works. Minor patching mis hit. Apologies.

Build 1.4.6-6.5.0.465:
	Christian: OK. AT the right thing, and add in a call to always get the right thing. Clean up patch fuzz too.

Build 1.4.6-6.5.0.464:
	Christian: Access Transform a couple of methods

Build 1.4.6-6.5.0.463:
	LexManos: Fixe BiomeDecorator AT entry.

Build 1.4.6-6.5.0.462:
	Christian: Drop the item in onBlockHarvested, not breakBlock

Build 1.4.6-6.5.0.461:
	Christian: Fix up block drops for skulls and cocoa

Build 1.4.6-6.5.0.460:
	Christian: And fix up the other equals

Build 1.4.6-6.5.0.459:
	Christian: Fix comparing ItemStack tags for equality

Build 1.4.6-6.5.0.458:
	Christian:
		Update FML: 40e57a2
		40e57a2 Update MCP to newer version Fix fingerprint fire

Build 1.4.6-6.5.0.457:
	Christian:
		Fix accidentally removed not-deprecated methods.
		
		Update FML: d604e44
		d604e44 InterModComms now supports a runtime polling based model for inter-mod comms at runtime. Deprecate method that shouldn't be used. COPY it's content to your mod. Don't CALL it.
		8b7778c Don't be as alarming about item overwrites.

Build 1.4.6-6.5.0.456:
	Christian: Fix binding the texture for multiple render passes. Thanks mdiyo! Closes #320

Build 1.4.6-6.5.0.455:
	Christian: Allow RenderItem to be easily overridden for things that need to render entityitems. IronChest, BuildCraft, RP2, whatever...

Build 1.4.6-6.5.0.454:
	LexManos: Fixed items dieing improperly due to new EntityItem sync changes, also made items render offset when rendered in 3d.

Build 1.4.6-6.5.0.453:
	Christian: Fix RenderItem so that forge textures load for it

Build 1.4.6-6.5.0.452:
	LexManos: Removed all functions marked as deperacted for the new MC version
	LexManos:
		Updated FML:
		Fixes startclient/startserver
		
		Added configuration file which allows modids to ignore ID validation checking. IT WILL CRASH YOUR GAME in 99.999% of cases.
		
		Immibis is a whingy ass. And TinyTimRob too. Now STFU and GTFO. closes fml/#510 for ever.

Build 1.4.6-6.5.0.451:
	LexManos: Inital update to 1.4.6, Version bumped to 6.5
	LexManos: Added jar signing to forge, we sign cpw/* and net/minecraftforge/*
	LexManos: Try and print error while signing jar

Build 1.4.5-6.4.2.448:
	Christian:
		Update FML: e98c311
		e98c311 Fix up handling null names. *sigh*

Build 1.4.5-6.4.2.447:
	Christian:
		Update FML: 293edb3
		293edb3 Some tweaks to item identification. The GameRegistry methods are deprecated to encourage you to use the new named ones instead. These will force a name on the item/block, allowing for stronger matching t
		9266ff3 Updated MCP download mirriors upon Searge's request.
		31695d5 Fix var name messup
		bfb3020 Update released eclipse project to link BouncyCastle
		22a88ea Change ID management slightly. IDs are tracked by block type for itemblock items now. This means servers will need to update. Also, ordinal rearrangements within a mod will no longer trigger server disco

Build 1.4.5-6.4.2.446:
	LexManos: Make PlaySoundAtEntityEvent fire for players as well
	LexManos: Remove erronious double call to PlayerDestroyItemEvent

Build 1.4.5-6.4.2.445:
	LexManos: Update FML to fix a typo

Build 1.4.5-6.4.2.444:
	LexManos: Automatically resolved imports.
	LexManos: Fixup workspace for BC replacement
	LexManos: Manual import fixes
	LexManos:
		Update FML:
		Minecraft is now decompiled into sane package names.
		Got rid of the src/common folder as the only folder that exists is src/mincraft, because the client and server codebase is merged.
		ID Map generation/validation fixes
	LexManos: Updated python scripts for removal of common folder
	LexManos: Update patches for repackage.
	LexManos: Update AT for repackage
	LexManos: Update FML: Fixed the eclipse workspace to reference BouncyCastle library.

Build 1.4.5-6.4.2.443:
	LexManos: Bump version to 6.4.2 to mark the merge of TerrainGen branch.

Build 1.4.5-6.4.1.442:
	Christian:
		Added terrain gen events
		Added biome color events for @XCompWiz
	Christian: Removed unchanged file
	Christian: Readded unchanged version
	Christian: For @XCompWiz, added a hook to allow mods to dynamically change the color that water is rendered.
	Christian: Fix RenderBlocks patch, touch branch

Build 1.4.5-6.4.1.441:
	LexManos:
		Update FML:
		2f34290e: Fix possible escape leakage..
		83deece6: Change ID management slightly. IDs are tracked by block type for ItemBlock items now. This means servers will need to update.
		
		Also, ordinal rearrangements within a mod will no longer trigger server disconnection, though a warning will still be logged.
	LexManos: Derp, imported the repackaged names not old names.

Build 1.4.5-6.4.1.439:
	LexManos: Update readme to reflect the fact that we now download MCP.

Build 1.4.5-6.4.1.438:
	LexManos: Fix ForgeDirection.ROTATION_MATRIX for issue #313
	LexManos: Made GuiContainer.drawSlotInventory overrideable for issue #312
	LexManos: Made BlockButton.func_82535_o overrideable for issue #311
	LexManos: Moved check if map cursor should 'spin' and which world a player respawns in to WorldProvider for PR #308
	LexManos: Add .DS_Store to the gitignore for mac users
	LexManos: Add CloudRenderer for PR #304
	LexManos: New TileEntity function to determine if the TE should be destroied when Block/Meta changes, For Issue #300
	LexManos: Pistons now respect world height a little better, for PR #286, will review Rotation event later.
	LexManos: Creative GUI will now remember what tab page you were on, thanks Matchlighter PR #290
	LexManos: Fix type in ForgeChunkManager.ticketCountAvaILableFor, thanks iChun PR: #285
	LexManos: Fixes crash when mods add TreeMaps to the Configuration map, thanks AtomicStryker, PR: #282
	LexManos: Fix shouldRiderSit() to properly determine if rider is sitting.
	LexManos: Expose BiomeDecorator fields for custom Biome information, Issue: #239
	LexManos: Make BlockButton.sensible protected and non-final

Build 1.4.5-6.4.1.437:
	LexManos: Fix for FML Fixes eclipse workspace, now sets execution bits on astyle-osx, and mcp .sh files. Also now kills install if astyle is not found.

Build 1.4.5-6.4.1.436:
	LexManos: Fixed release -skipchangelog
	LexManos: Fixed install --mcp-dir
	LexManos:
		Updated FML to 486:
		02b54ca8: Add a modid on the mods list, should make it easier to do things like forge chunkloading config
		70670f2f: Fix build eclipse extractor task
		b9fa3fc9: Add in storage, detection and validation of the ItemID array between client and server
		5e5d8206: Fixing id map generation - should validate correctly now
		f9fc06a8: Remade python dist as 32-bit.
		93d47a1c: Reenabled replacement of the eclipse folder.

Build 1.4.5-6.4.1.435:
	LexManos: And finally, fix up the release install script to have a parameter to specity the MCP directory.

Build 1.4.5-6.4.1.434:
	LexManos: Fix Forge install script to use python shipped with FML.

Build 1.4.5-6.4.1.433:
	LexManos: Push didn't get all of eclipse....

Build 1.4.5-6.4.1.432:
	LexManos:
		Cleaned up eclipse workspace and moved it to a zip file.
		Setup will extract it if it doesn't already exist.

Build 430:
	Christian: Fix release script for new forge job name. Add in skip changelog option for local builds

Build 1.4.5-6.4.1.426:
	LexManos: Remove MCP from released src distro.. whops.

Build 1.4.5-6.4.1.425:
	Christian:
		Fix static method, closes #271
		Don't spam the log if a mod requests a ticket beyond their maximum. A single message is fine.

Build 1.4.5-6.4.1.424:
	GuntherDW: Fix typo in chunkmanager config
	Christian: fix List configs
	Christian: Add Chunk Watch and UnWatch events.

Build 1.4.5-6.4.1.414:
	Christian:
		Tweak release.py script: HEAD==master in general
		
		Update FML: 26a2ef5
		26a2ef5 Add a modid on the mods list, should make it easier to do things like fo
		b4e3490 Fix build eclipse extractor task
		828341f Fix typo
		7a8dae5 Try and make branch non-derpy
		d3c0e1f Try defaulting branch differently
		9c77d3f Remove old eclipse workspace and ship/extract as a zip file (use ant set
		6371e9b Assume Forge is the parent directory when checking for AT configs.
		516954e Name both zips the same format
		1151d5c Last part of branch name only please
		25f1dda Try and get a valid branch name on jenkins
		39a146f Clean up build.xml script- support outputting a branched jar file
		037dcae Small derp in install.py
		01d6da3 Try marking python as binary.
		8b26659 FML will now attempt to download MCP as part of the install process Now
		42b3e6a Windows Python distrabution created using py2exe, thanks Fesh0r for the
		e709ab8 Marked more spots in gui/items bitmask as being free.

Build 1.4.5-6.4.1.413:
	LexManos: Add wget and unzip from GnuWin32 for use in the setup scripts.
	LexManos: Update FML, now includes python, and will download MCP for you
	LexManos: Update python files to add support for specifying MCP directory and FML downloading MCP on the fly.
	LexManos: Fix issue with DimensionManager.shouldLoadSpawn

Build 1.4.5-6.4.1.411:
	Christian: Fix #289

Build 1.4.5-6.4.1.410:
	Christian:
		Add in some additional ticket loading callbacks for ChickenBones. Closes #284
		Add in a call to determine if there are possible chunktickets for a world. This should let
		Mystcraft and other dynamic world generating mods check if they should immediately load
		a world based on existing chunk tickets.

Build 1.4.5-6.4.1.409:
	LexManos: Fix issue where non-BlockContainer TEs would not be removed properly.

Build 1.4.5-6.4.1.408:
	LexManos: Fix logic issue in ForgeChunkManager.ticketCountAvaliableFor(username) PR
	LexManos: Fix issue where worlds were potentially unloaded improperly on server shutdown.

Build 1.4.5-6.4.1.407:
	LexManos: Small change to fix loading configs.

Build 1.4.5-6.4.1.406:
	LexManos: Added section of the EntityData NBT that will be persisted for players across respawning.

Build 1.4.5-6.4.1.405:
	LexManos: Exposed some ChunkLoader information for PR #278
	LexManos: Fix potential NPE in EntityJoin handler and print warning.

Build 1.4.5-6.4.1.404:
	LexManos: Small tweak to config to use Treemap

Build 1.4.5-6.4.1.403:
	xcompwiz:
		Adds a more intelligent chunk constructor
		
		Adds a chunk constructor with full block id range, that's metadata
		sensitive, has intelligent coord ordering, and which allows for
		generation at greater heights than 127.
	xcompwiz: Fixes some weird formatting
	zach:
		Fixes ordering for z & x loops (proper array increment order)
		
		The ordering before would skip about in the ids and metadata arrays.  This runs linearly and should improve performance.
		Done live on github

Build 1.4.5-6.4.1.402:
	LexManos: Fixed AIOOB issue with new sanity check in getBlock

Build 1.4.5-6.4.1.401:
	LexManos: Fix potential NPE in saving a property that didn't define a type.

Build 1.4.5-6.4.1.400:
	LexManos:
		Added new functions to the Config class to allow for specification of comments when getting properties.
		Added new getTerrainBlock whihc will limit the resuling ID to < 256, useful for world gen.
		Calls to getBlock with IDs less then 256 will be assigned values above 256 {Thus freeing up terrain gen slots}
		Made ConfigCategory implement Map<String, Propertery> should fix compatibility with most mods that broke two builds ago.

Build 1.4.5-6.4.0.399:
	xhamolk.class11:
		OreDictionary addition: getOreID(ItemStack)
		
		Allow getting the oreID from a ItemStack, as an alternative from getOreID(String).
		
		Now is easier to exchange items for their equivalencies through the OreDictionary.

Build 1.4.5-6.4.0.398:
	LexManos: New nested configuration category support, for PR #258

Build 1.4.5-6.4.0.397:
	LexManos: Fixed issue with abandoned chunks.
	LexManos: Fixed random chest items not generating to there max stack sizes.

Build 1.4.5-6.4.0.396:
	ohai.iChun:
		Add check that Entity saves to disk before saving entity to saved chunkloading data.
		
		Returning false to addEntityID prevents the entity from being saved (cred to LexManos)
		Entities which do not save to disk but are chunkloaders causes errors the next time the world loads. This ought to fix it.

Build 1.4.5-6.4.0.395:
	LexManos: Updated FML, proper free-sprite list for /gui/items.png, and fixed MCP version.

Build 1.4.5-6.4.0.394:
	Christian:
		Move server specific patch back to common from minecraft.
		
		Update FML: 1f5c58b
		1f5c58b Fix up MCP version
		61e4db2 Merge joined.exc add update howto
		5efc1eb Revert "Fix MC-2497 - derpy torch flames. Moved from forge. Everyone sho
		3b3600d Modified merger to just consider all server classes as common. And moved
		edcc5ca Forgot mcp.cfg
		ca79dfe Updated to 1.4.5b
		5945279 Fix python error
		57bf643 Modified decompile so that we do not have to decompile the server, saves
		d9d0a46 Cleaned up some tabs
		2fac644 Change usage of ZipFile, fixes issues with Mac's default instation of py

Build 1.4.5-6.4.0.393:
	LexManos: Fix TE Issue

Build 1.4.5-6.4.0.390:
	LexManos: Removed GnuWin32 programs, should no longer be needed as we've moved to python.
	LexManos: Updated to MC 1.4.5b

Build 1.4.5-6.4.0.388:
	Christian: Stupid eclipse resetting preferences. Spaces, not tabs!!!
	Christian:
		Update FML: 570592b
		570592b Attempt to fix a possible comodification risk

Build 1.4.5-6.4.0.387:
	Christian: Add in events when forcing and unforcing chunks. Hope this works for you ChickenBones!

Build 1.4.5-6.4.0.386:
	Christian:
		Update FML: fde9414
		fde9414 Change texturebinding to use the textureId directly rather than iconInde

Build 1.4.5-6.4.0.385:
	LexManos: Fixed issue with default implementation of Beach plant type check
	LexManos: Fixed custom soil checks for NetherStalk and Reeds

Build 1.4.5-6.4.0.384:
	LexManos: Release script will now include the Minecraft version in the arcive names.

Build 6.4.0.383:
	Christian:
		Update FML: f348496
		f348496 Fix mod display list. Shouldn't be derpy anymore.
		a5c31b5 Fix World patch- workaround no longer required and leftovers are bad.
		2dc3f0d Cleaned up the AT config updater, should work for any setup of the MCP w

Build 6.4.0.382:
	LexManos: Fixed beds not working properly when respawning.

Build 6.4.0.381:
	Christian:
		Remove EntityFX patch - moved to FML. Patch SuspiciousClasses to add "forge"
		
		Update FML: fa56701
		fa56701 Fix MC-2497 - derpy torch flames. Moved from forge. Everyone should benefit.
		96935bb Fix an NPE in TileEntity trying to generate a crash report. Make suspicious classes just return the obvious. Fix NPE for FML crash report on server. Clean up dead pa

Build 6.4.0.380:
	Christian: Fix the derpy torch flames properly. Closes MC-2497 properly ;)

Build 6.4.0.379:
	Christian:
		Update to MC 1.4.5
		Update FML: 43d3042
		43d3042 Clean up a patch
		fec221f Update FML for MC 1.4.5
		b0f0635 Fix for ModLoader static overrides not displaying.
		23a2513 Fix up derpy file name handling: closes #127 Fix up duping childmods: cl
		a6eaa2b Fix spelling issue.
		c6a0741 FML setup should now download and verify all the minecraft files needed
		5a1930e Small fix to some MCP metadata for pre2
		418deba Update to MC 1.4.4
		4ff2cff Fix bug when a modloader mod is run on a dedicated server and has a conn

Build 6.3.0.378:
	Christian:
		Some liquid events. Non-API breaking. Add them at your leisure. This helps liquids know
		what's happening to them. In case they're volatile or something ;)

Build 6.3.0.377:
	Christian: Another difference

Build 6.3.0.376:
	Christian:
		Fix fillLiquidContainer - return null, not the empty container for
		previous API compatibility

Build 6.3.0.375:
	LexManos: Update FML to fix ModLoader/addOverride functionality.

Build 6.3.0.374:
	kinglemming:
		Fixed oversights in liquid registry, added functionality for instant checks as requested by CJ.
		Liquid list return is now secure.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	Christian: Change name to LiquidContainerRegistry. Fix up missing API. This better be it now!

Build 6.3.0.373:
	kinglemming:
		Liquid Manager Rewrite - slightly more memory usage, loads more efficient at runtime.
		Added default Lava and Water registrations to Liquid Manager.
		Removed method which relied on flawed assumption that a given liquid only had a single type of container.
		
		Signed-off-by: King Lemming <kinglemming@gmail.com>
	Christian: Rename some liquid stuff for more sensible naming. Tweak API slightly.

Build 6.3.0.372:
	Christian:
		Add in the basic IBlockLiquid interface. The actual block implementation
		will follow.

Build 6.3.0.371:
	Christian:
		Add an ItemStack sensitive version of getIconForRenderPass, defers to
		existing by default. Should allow NBT data to affect multipass icon rendering.

Build 6.3.0.370:
	Christian: Change getLeft to getRotation, around any axis.

Build 6.3.0.369:
	Christian: Some new stuff on the liquid API for better RP2 interaction. Coming soon: blocks!

Build 6.3.0.367:
	Christian: Tweak liquidcontainer API for sidedness capability

Build 6.3.0.366:
	LexManos: Updated FML, Fixed spelling issues in logs, and file name issues.
	LexManos: Added saplings and leaves to the ore dict. PR: #242
	LexManos: Mods can use custom textures for Slot background overlay, instead of only items.png PR #245 and #246
	LexManos: Fix issue where players would spawn in the ground.
	LexManos: Allow for modders to decide whether or not players are positioned on ridingEntities similarly to pigs PR #244
	LexManos: Fix breaking despite cancel in creative mode for PlayerInteractEvent OR #247

Build 6.3.0.364:
	Christian:
		As agreed, liquid API from BuildCraft has been migrated to minecraft forge. There will be cleanups to follow,
		including sided handling and client rendering tweaks. Stay tuned!
		Tweak forgedirection for a couple of naming constants

Build 6.3.0.363:
	Christian: Add toLeft rotational data to ForgeDirection

Build 6.3.0.362:
	LexManos: New field in ForgeDirection to hold just the valid directions. And made getOrientation a bit more efficient.

Build 6.3.0.361:
	LexManos: Fix entity items rendering on the ground.
	LexManos: Fix crops not droping seeds properly.

Build 6.3.0.360:
	LexManos: Update to 1.4.4
	LexManos: Bumped version number for 1.4.4

Build 6.2.1.358:
	LexManos: Ore Dictionary Improvements, replaces vanilla recipes with OreDict recipes for some vanilla items. Thanks Covert.

Build 6.2.1.357:
	LexManos: Made Item constructor public, and made setTextureFile chainable, requires mods to recompile, but as this is for 1.4.3 i'm not concerned.

Build 6.2.1.356:
	Christian:
		Temporary update for 1.4.3
		Update FML: bd2123c
		bd2123c Clean up some patch fuzz
		c2a603c Update joined.exc file from latest conf
		db12af4 Update to 1.4.3
	LexManos:
		Readdaed teleporter sensitive versions of the teleport function
		Added per-world list of custom teleporters, Modders, use World.Load to populate this list.
		Changed the definition of our version schemes.

Build 6.0.1.355:
	Christian:
		Update FML: 8356fe9
		8356fe9 FUUUUUU! Stupid ticking. STOP REGISTERING TICK HANDLERS IN YOUR CONSTRUC
		6edce8b Patch a file handle leak in RegionFileCache handling when under memory p
		ca2bbe0 Update MCP mapings again, yay bad syncs.
		c8941a7 Updated MCP mapings.
		5e20c03 StartServer is now useable in merged code base.

Build 6.0.1.354:
	LexManos: Update FML: Updated MCP mapings, and fixed StartServer

Build 6.0.1.353:
	Christian:
		Update FML: b19e882
		b19e882 Remove some debug, closes #123
		9d7d32a Fix up tick management outside of mod loading phases for ModLoader mods.
		d512539 Negatively cache failed class lookups, should help with @SideOnly performance issues.

Build 6.0.1.351:
	Christian:
		This update fixes some world corrupting vanilla error handling, mostly caused by
		mods doing something derpy. Hopefully, your world saves will thank me.
		Note that if the mod does derp, it's data is lost. It's not FML or Minecraft Forge's
		responsibility if "DirtChest 2000 Mk5" can't write their TileEntity method correctly
		and you lose your 100000 diamonds.
		
		Update FML: a3a93f3
		a3a93f3 Fix some whitespace issues, handle possibly bugged entities as well
		a7eb5dc Vanilla/mod bug fixes: CME on entity processing, TileEntity resetting chunk on save/load.

Build 6.0.1.350:
	LexManos: Fix cast issue when mods attempt to make fake worlds.
	LexManos: Fix a vanilla bug related to certian seeds and stronholds.
	LexManos: Cleanup some debug in the script, and fix version number for the current build.

Build 6.0.1.349:
	LexManos: Change logs should now be bundled with downloads, as well as avalible on files.minecraftforge.net

Build 6.0.1.348:
	Christian:
		Update FML:b23081d
		b23081d Support for ModLoader 1.4.2. Good job Risu!
		66db4ec Add in an exclusion list tag for @Mod. The backend code isn't yet implemented, but shows the basic idea.

Build 6.0.1.345:
	LexManos: EntityLiving.experianceValue private->public for Issue #225
	LexManos: Changeable name tag render distance for PR: 174
	LexManos: Remove some debug code
	LexManos: New hook to allow items to be on multiple creative tabs PR 176
	LexManos: Fix issue where scroll bar would not render when switching tab pages.
	LexManos: Added metadata sensitve experience to furnace recipies and added Item callback to determine experience gain.
	LexManos: Exposed functions for adding superflat presets.
	LexManos: New hook to allow for custom beacon support blocks.
	CovertJaguar:
		Added vanilla wood + dye to the Ore Dict
		
		Should help simplify interaction between mods that add similar items.
	LexManos: Added Stonghold, Village, and Spawn biome management helpers for PR 207
	LexManos: Fix compile issue.

Build 6.0.1.343:
	csendek: Add event to cancel or change chat messages sent from server
	csendek: Add event to cancel or change chat messages sent from server

Build 6.0.1.342:
	LexManos: Pickblock will new compare NBT data, should allow mods to refine there result better.
	LexManos: Added system to place all configs that use Forge's Configuration function into a single file on disc. Optional config to enable this. Blame MattaBase for this idea..

Build 6.0.1.341:
	LexManos: Fix ItemSeed placement to take into account the IPlantable interface.

Build 6.0.1.339:
	LexManos: Added a per-world MapStorage feature that provides a method to store data files associated with a specific world, as well as fixes the issue with villagers loosing there village. {Where villagers wouldn't go inside at night}

Build 6.0.1.338:
	pahimar: Update patches/common/net/minecraft/src/SlotCrafting.java.patch
	Christian:
		Fix the accessor and type on World.getPersistentChunksFor()
		Update FML: 8bd98c3
		8bd98c3 Fix a small problem with the new MCP container- it can cause NPEs. Nice.
		34cc42d Fix up some javadoc complaints

Build 6.0.1.337:
	Christian:
		MCP information is now included in Minecraft Forge. They deserve the credit :)
		
		Update FML: 09eade4
		09eade4 Update build - include MCP information in the source pack
		9bfe7df MCP deserves lots of credit. So here it is.

Build 6.0.1.332:
	Christian:
		Update FML: 8006b77
		8006b77 Fix instantiation bug
		7cc91cf Simple InterMod comms. Send a message using FMLInterModComms.sendMessage(). Receive messages through an @IMCCallback
		24d7285 Update for MC 1.4.2
		cedf3d5 Duplicate Mod display screen.

Build 6.0.1.331:
	LexManos: Downgrade to FML 415, issue with new IMC system.

Build 6.0.1.330:
	LexManos: Update to 1.4.2, obf stayed the same, so only small revision.

Build 6.0.0.329:
	LexManos: Update World patch to fix map provider issue.

Build 6.0.0.328:
	Christian:
		Add an access transform for Block.setBlockBounds - should help a lot of code that uses this.
		
		Update FML: d915f39
		d915f39 Fix typo in access transformer
		346691c Fix the merge for forge
		6dadc1d Fix up references to minecraftDir in obf code
		8a55f68 Update FML for Minecraft 1.4.1
		5645fa5 First update to 1.4.1, patches need updating.
		ff0f00f Add some null checks, and throw descriptive exception when SideTransformer prevents a class from loading.

Build 6.0.0.327:
	LexManos: Update to MC 1.4.1 and Forge 6.0.0

Build 5.0.0.326:
	LexManos: Fix color issues with Dyed Leather armor.

Build 5.0.0.325:
	LexManos: Remove deprecated code.
	LexManos: Cleanup mirrored things in ShapedOreRecipe to address issue 208 and issue 210
	LexManos: Fix up the setHandeled/setHandled for events, it is now a generalized setResult, the meaning of which is defined by each event.

Build 5.0.0.324:
	LexManos: Fix NPE issue when mods add null EntityFX's to be rendererd.

Build 5.0.0.323:
	Christian:
		Update FML: 7a34246
		7a34246 Ship a client only class so the merge works both sides.

Build 5.0.0.322:
	Christian: Fix install.py so it can be installed properly from src distribution

Build 5.0.0.321:
	Christian:
		Update FML (entire change log since last by me): 62a6b52
		62a6b52 Fix RenderRegistry render ID - now at 36 Fix SpriteMaps - they're running out fast! Switch to forge if you can! RenderBiped now has an armo
		b845cde Fix up FML python script for forge
		2c36dfb Update to MCP pre 3. Fixes some weirdnesses with explosions.
		acd880d Merge branch '1.4'
		e6f57e5 Update for MCP release
		b1de0fc Remove fuzz from patches for INetworkManager change
		ad44619 Fix for new names INetworkManager and ITexturePack. I also provide refactoring scripts for both, for your use...
		3a94211 Add a script to ignore git complaining about the eclipse workspace changing - run when you first open the eclipse workspace
		9386e23 Update gitignore - ignore the files that will change or be deleted
		10b318c Add in "starter" image for eclipse workspace
		995d5b7 Eclipse workspace fixup 2?
		bbb12c8 Clean up eclipse workspace- part 1
		b50058e Clean up a bit of patch fuzz
		4a0bfa9 Fix CommonHandler for rename of the server thread class
		4d1ec66 Update with RC2 MCP. Use the joined.exc file directly since MCP now provides it.
		b52e3d0 Fix exception for CodecMus
		a1011c9 Fix some compilation issues. Requires resolving the worldclient abstract method
		0ebd4f3 Inital patch update to 1.4
		89c68c4 Moved into EntityVillager
		e4702cb Fix line ending detection during checkout.
		6e64fd7 We don't need logging here...
		014b3f4 remove useless -Server projects
		7628c67 Updated the AT config and Marker config for 1.4 obf
		54a322c Updae build to copy files that may decompile differently but are actually the same, and updated for 1.4 values.
		aadf396 Update MCP Merge config.
		81e1855 Pull in MCP's 1.4 conf files.
		5686fd4 Fix error in merging of exec's

Build 5.0.0.320:
	LexManos: FML Update for 1.4
	LexManos: Fix recompile call for 1.4 MCP change
	LexManos: Update Forge's AT for 1.4 names.
	LexManos: Update for new names in 1.4
	LexManos: Remove final from 'villageCollectionObj' to allow for delayed setup of Map source objects.
	LexManos: Moved to common where it should be
	LexManos: No longer needed, getRenderDistance removed because Vanilla has it now, TileEntity.func_82115_m
	LexManos: Forge spawn protection removed, now a vanilla feature.
	LexManos: Patches that applied with little to no functional changes.
	LexManos: Updated Render patches, Bipeds now have the ability to have helmets, of either blocks, or the new 'heads'
	LexManos: BlockSnow now pretty much just passes harvestBlock to it's super.
	LexManos: Entities have a new function to determine explosion strength that they create, and implemented Item frame pickblock.
	LexManos: Patches removing forge spawn protection, now a vanilla feature.
	LexManos: BlockCrops is now the parent class of multiple types of crops, Wheat, Potatoes, and Carrots, updated getBlockDropped patch to reflect.
	LexManos: Removed Forge's TileEntity.getRenderDistance, now a vanilla feature:  TileEntity.func_82115_m
	LexManos: Teleporting has a new function (func_82448_a), made it so that you can supply your own teleporter to that function, and so it works with dimension movement factors.
	LexManos: Updated World patch, there are a lot of new things happening int he constructor, xcomp should probably vet this.
	LexManos: Updated Forge version to 5.0.0, for 1.4
	LexManos: Update release script for mcp changes, releases now build.

Build 4.3.5.318:
	LexManos: Remove some test code.
	LexManos: Bump version to 4.3, final for 1.3.2

Build 4.2.5.317:
	LexManos: Added ability for mods to cleanly define and display new creative tabs.

Build 4.2.5.316:
	Christian: Fix classloading issue preventing JRockit from running forge

Build 4.2.5.315:
	Christian:
		Forge build change: the universal jar, if installed alongside a server jar file, can be executed to load forge. No server side merging required!
		Update FML: 989ab3e
		989ab3e Update build.xml - add a classpath to the manifest. This means the universal jar is now a server side launche
		88f1dc9 Typos!

Build 4.2.5.314:
	Christian:
		Update FML: 470a185
		470a185 Try and avoid an NPE in crash reports
		0029518 Fix logging problems- log death messages and re-route the server through FML logs properly.
		fe7a832 Fix the test mod
		a2bc30b Coremods can be specified via the command line: fml.coreMod.load=<listofcommaseparatedclasses> This will help with developing coremods
		bae1f74 Fix classpath for server
		887aa27 Add in the ability for a client to throw a custom exception that displays a custom gui instead of the default error message.
		e17f267 Update FML internal classpath. Helpful for coremod devs
		3b9972a Don't use File to separate the last element of the path. It's a URL, they're always separated by '/'
		5c96afe Changed RelauchLibraryManager so that files with different paths on the same baseURL can be implemented in one ILibrarySet.
		1bca393 FML as a whole is now subject to transformers.
		27cf731 Bonus extra character. thanks randomitter!
		94c84cd Merge pull request #116 from Vazkii/patch-1
		c2d3195 Add Null check to FMLClientHandler.sendPacket

Build 4.2.5.313:
	LexManos: Make Item.createEntity only call when its specifically a EntityItem, not a subclass of it.

Build 4.2.5.312:
	LexManos: New Block hook to determine if it can be destroied by the ender dragon, for PR 199
	LexManos: Ship forgeversion.properties with release zips. Same format as fmlversion.properties.
	LexManos: Dll files are binary as well.

Build 4.2.5.311:
	LexManos: Fill out the .gitattributes to help with line endings how they should be.
	LexManos: Change the Crafting damage check to be the same as the usage damage check. (>= -> >)
	LexManos: Allow hook into GuiSlot for background rendering for PR #203

Build 4.2.5.310:
	Christian: Reorganize the forced chunks a bit- offload the cost of immutable map building to the mods, rather than the chunk tick

Build 4.2.5.307:
	Christian: Remove @SideOnly from removePotionEffect. Hi RichardG!

Build 4.2.5.306:
	LexManos: Add some accessors to teh ChunkLoader tickets.

Build 4.2.5.305:
	ohai.iChun: Fix not passing right render pass to Item class.

Build 4.2.5.303:
	Christian: Fix bounds checking on chunkcache. Should fix a bunch of rp2 and maybe other extended tile entity code

Build 4.2.5.302:
	Christian:
		Use weak references to the worlds in our maps. WorldClient would otherwise
		leak all over the show.

Build 4.2.5.299:
	mehvids: Add some of the model subsystem to the server. The part that doesn't require openGL. This allows for systems that dual models as collision/selection boxes etc.
	xcompwiz:
		Improves DimensionManager
		
		Adds handling for unloading and hotloading of worlds, fixes some typos,
		allows for dimensions to be unregistered (allowing save specific
		dimension registrations), general changes to match these features.
	xcompwiz:
		Adds world unloading and hotloading calls
		
		Adds world unloaded message to MinecraftServer on save.
		Adds world unloading calls to chunk provider/manager when all chunks are
		unloaded.
		Adds call in MinecraftServer getWorld to hotload world if it isn't
		loaded.
	xcompwiz:
		MapStorage Fix
		
		Fixes setting and timing of map storage object to allow for the
		WorldProvider to use it during initialization
		Forces single instance of map storage object (per side)
		Moves setting of spawn to after provider setup
	xcompwiz:
		Lighting Time fix
		
		score_under's lighting fix that limits and fairly distributes the amount
		of time spent on recalculating lighting
	xcompwiz:
		Server player concurrency fix
		
		Fixes an issue where the server can move a player while the player is
		moving, process the player's last move (putting the player back where
		they were before the teleport), and then complain about the player
		moving too fast when the client catches up to it's new position.  Also
		fixes this issue while riding an entity.  Only affects player
		client/server movement sync.
	Christian:
		Remove dead WorldInfo patch. Tweak dimension code a bit for better naming, and use the new FML world loading facilities
		Update FML: d0e7c9e
		d0e7c9e Update patches *sigh*
		f3e1cac Add in a savehandler strategy for reading and writing data to the world save. This service is only available to coremods via the WorldAccessConta
		51fb513 Add in some bukkit supporting code. Most of this is unimplemented until the bukkit coremod is complete.
		65c9fdd New stuff on the ModLoader! Risu has been busy. Closes #114
		c1d4458 Mods can now declare a range of minecraft versions they will run against
	Christian: Update forge to 4.2

Build 4.1.4.298:
	LexManos: Fix issue where light would not properly recalculate.
	LexManos: Fix issue where mushrooms would not check the proper soil block.

Build 4.1.4.297:
	LexManos: Expanded DungeonHooks to allow for adding of custom DungeonLoot values directly, allowing for better control over the generated items.

Build 4.1.4.296:
	LexManos: Made PlayerEvent.BreakSpeed fire when a player cannot harvest the block. Issues #191 and #188

Build 4.1.4.295:
	Christian: Dormant chunk cache might actually work now, and not mix chunks across worlds
	Christian:
		Update FML: ca1ca4f
		ca1ca4f Fix maps supporting greater than byte() dimension sizing
		15ee8bf Fix language registry additions, closes #113
		a08b5b1 Merge pull request #112 from pahimar/master
		8dac58f Added ability to query the Language Registry by key and language for specific localized text, as well as loading in localization text f

Build 4.1.4.294:
	LexManos: Fix buckets, need to rethink for bukkit compatibility.
	LexManos: Fix vanilla bug where the player would load chunks outside its range that would be 'abandoned' and never unloaded.
	LexManos: Forgot comment, you see nothing...

Build 4.1.4.292:
	Christian:
		A few requested features of ForgeChunkManager. Mods can specify a
		chunkloading config directly in the config file, including chunk
		loading overrides if they wish (and the config allows them).
		Also added "player" tied tickets that bind to the player and not the
		mod's quota.

Build 4.1.4.291:
	LexManos: Missing updates from last commit
	LexManos: Location aware version og Block.lightOpacity for PR #169

Build 4.1.4.290:
	LexManos: Fix bug in last commit that caused block to not break.
	LexManos: Added preliminarty Player Interact event heavily based on the bukkit event.

Build 4.1.4.289:
	LexManos: Add PlayerEvent.HarvestCheck and PlayerEvent.BreakSpeed for dealing with things related to a player harvesting a block.

Build 4.1.4.288:
	LexManos: Fix bug where breaking texture would not apply to top/bottom of beds.

Build 4.1.4.287:
	Christian: Add in an "EntityEvent.EnteringChunk" event. Useful for your entity chunkloading stuff.

Build 4.1.4.286:
	LexManos: Support for no BOM.

Build 4.1.4.285:
	Christian:
		Update FML: f083707
		f083707 Extreme headless mode is back!

Build 4.1.4.284:
	Christian:
		Update FML: dd39ae5
		dd7502a Fix parent child counts showing properly. Closes #107 thanks scott!
		b36d447 It's useMetadata, not usesMetadata. thanks myrathi and psx. closes #110
		efb1066 Fix random shuffling when manipulating biomes by using a LinkedHashSet to preserve iteration order. Closes #111
	Christian:
		Some more tweaks to the chunkloading code. The world.load event fires slightly later- once the entity watcher is
		set up, so entities can actually load into the server world. Also, tickets actually save and load properly
		and null entities don't break the server

Build 4.1.4.282:
	LexManos: > != >=

Build 4.1.4.281:
	LexManos: Fix Configuration.getItem to return pre-shifted values suitible to pass into Item constructors.

Build 4.1.4.280:
	LexManos: Fire off PlayerDestroyItemEvent for crafting contianer items that get damaged to much. PR #183

Build 4.1.4.279:
	LexManos: Configuration will now attempt to detect the encoding of the file using the Byte Order Mark.
	LexManos:
		Changed Configuration to use overloaded methods, and changed the order of arguments to be Category, Key, Value instead of Key, Category, Value to hopefully help cleanup some peopels code.
		Added function to get a free Item id. Will only accept values that are not in the block space. Needs testing.
		Marked all the old getOrCreate* functions as deprecated.

Build 4.1.4.278:
	Christian: Fix some errors if the config is unparseable. It should log an exception and carry on with defaults.
	Christian: Support quoting in property and category names for almost all possible characters allowed
	Christian: Fix up some config file handling to be even more resilient.

Build 4.1.4.277:
	Christian:
		More modifications to the ticket callback handling system. There are up to two callbacks during world loading now. One to allow
		selective preference for ticket types. The other to actually allow the mod to force chunks.

Build 4.1.4.276:
	Christian:
		Update FML: dd39ae5
		dd39ae5 Try and fix the newline capture so consoles show on the server on windows again
		b39f808 Readd ancient searge name so dan200 and computercraft can run again. REMOVE THAT CODE DAN.
	Christian:
		Some changes to the ForgeChunkManager.
		Null modData is allowed now.
		The entity id is actually properly persisted in the ticket now.
		There is a new "orderedLoadingCallback" that allows you to provide a preferred ticket loading order in case of "excess tickets". Also, tickets
		that are not in the returned list are now unregistered.
		There is a way to resort the chunks in the forced chunklist on a ticket now.
		Log the dormant cache configuration

Build 4.1.4.275:
	Christian: Simple chunkloading implementation
	Christian: Working cross dimensional implementation of chunkloading for Forge.
	Christian:
		A lot of tweaks to the chunkloading for entity behaviour. Entities are now bound by a new
		persistent id they *all* have, on the server side.
	Christian: Remove @SideOnly flag for function now required on the server
	Christian: Fix NPE in ForgeChunkManager
	Christian: And a concurrentmodificationexception in the same code
	Christian:
		Simple chunk caching capability for the chunkloader. This will store "dormant" chunks in a
		configurable cache, potentially saving the cost of reloading them from disk.
	Christian: Delete some debug code
	Christian: Some more fixes for chunkloading code. Works very reliably now.
	Christian:
		Update FML: a2c059e
		a2c059e Fix missing import. Thanks ichun :(
		19316a0 Version file searching should work for directories too
		fbc7a5c Fix bug causing NPE if non-whitelisted player joins an FML server without FML installed
		e9cfd10 Merge pull request #103 from iChun/patch-2
		1424883 Fixed ModTextureAnimation not updating and not binding to correct image.

Build 4.1.4.274:
	mitchpetrie29:
		Update patches/common/net/minecraft/src/WorldProvider.java.patch
		
		Fixed WorldProvider.setDimension() setting the wrong variable.
	LexManos: Fix patch errors in merge of last PR -.-

Build 4.1.4.272:
	LexManos: Fix accedental doubling of shift, Fixes saplings/flowers planting a space above where they should

Build 4.1.4.271:
	LexManos: New Plant API that allows for custom plants/soils.

Build 4.1.3.270:
	LexManos: Added new hooks for modifying the items generated in chests during world gen.

Build 4.1.2.269:
	LexManos: Redirect a lot of functions through WorldProvider for Mystcraft, allowing them to be overriden by the provider.

Build 4.1.2.268:
	CovertJaguar: Fixed Entity Item render helper

Build 4.1.2.267:
	ohai.iChun: Fix pick block key giving invalid spawn eggs
	ohai.iChun: Logic derped
	ohai.iChun: Logic derp (again)

Build 4.1.2.266:
	LexManos: Added side sensitivity to standard EntityDiggingFX, added Block functions to override spawning of digging and breaking effects.

Build 4.1.2.265:
	LexManos: Fix potential NPE in Custom item entity span code caused by item id misconfigurations.

Build 4.1.2.264:
	LexManos: Fix recursion issue with new special item entity code.

Build 4.1.2.263:
	Christian:
		Update FML: 6c746ec
		6c746ec Tidy code
		aacbfeb Change version.properties search slightly, allow access to found file from the preinit event
		1513b36 Add in the capability to read an internal version as <modid>.version from a file in the zip call versi
		35852a6 Fix up reversed assignment for version fallback

Build 4.1.2.261:
	pahimar: Changes to how PotionEffects are removed, now each PotionEffect can specify which ItemStacks can remove it's effect
	pahimar: Inverted logic derp

Build 4.1.2.260:
	LexManos: Package all of paulscode/ with the universal jar to help mac users who cant understand how to merge folders -.-

Build 4.1.2.259:
	LexManos: Bump version to 4.1.2 to mark the end of todays changes.

Build 4.1.1.258:
	LexManos: Fix potential issue with custom events where the constructor is not visible from the EventBus class, Should never arise but meh.
	LexManos: Read/Write config files as UTF-8 instead of ANSII, should fix issue with Turkish people.
	LexManos: Allow for respawning in different dimensions.
	LexManos: Move spawn fuzz to WorldProvider/WorldType, useful for VoidWorld types.

Build 4.1.1.257:
	LexManos: Make EntityJoinWorldEvent Cancelable properly
	LexManos: Move Forge init message to MinecraftForge.initalize
	LexManos: Add ability for Items to create custom Entities for themselves when added to the world, PR: #151

Build 4.1.1.256:
	admin: Allow flight,player sensitive

Build 4.1.1.255:
	LexManos: Fix a few patch fuzzes
	LexManos: Implemented isBlockFoliage for pull #141

Build 4.1.1.254:
	LexManos: Clean up some javadoc warnings.
	LexManos:
		New EntityItem related events
		Fixed player death event in SMP
		Added Player specific drops event
		Added generic EntityJoinWorldEvent

Build 4.1.1.253:
	LexManos: Fix FillBucketEvent to work with stacked buckets. New change in 1.3
	LexManos: EntityLiving variation of drawBlockDamageTexture to allow for Non-player viewports.

Build 4.1.1.252:
	Christian: Remove all references to ModLoader
	Christian:
		Update FML: 89b8236
		89b8236 Fix onConnectionClosed not being called on the client side of a connection

Build 4.1.1.251:
	LexManos: Bump version to 4.1.1

Build 4.0.0.250:
	Christian:
		Update FML: 290a3c9
		290a3c9 Merge pull request #94 from iChun/patch-1
		9485dc5 Fix handleTinyPacket using short instead of int.
	Christian:
		Update FML: 70f55c5
		70f55c5 Add in exclusion list for IFMLLoadingPlugin.
		1c1716d Remove debug cruft
		d567f79 To properly align with packet9respawn, make packet1login's dimension an int as well
		ecd4e46 Attempt to build some protocol negotiation, and fix packet1login so that the dimension is a short, matching packet9respawn
		16fe495 Compatibility level is now passed from server to client - and the client tracks it. This means certain packet changes can be made without b
		4f70d23 Fix dependency checking: you can depend on specific versions of FML

Build 4.0.0.249:
	Christian:
		Update FML: e6abb69
		e6abb69 Fix up tiny packet handler to actually work
		e862052 Allow javax to be shipped by mods. Should allow some more modloader mods to work unaltered
		4071ad1 Add in a little bit of protocol cleanup. Start work on allowing multiple protocol versions
		6061964 Give a way to build the packet131mapdata packet correctly populated
		b818769 Capture and leverage Packet131MapData

Build 4.0.0.248:
	LexManos: Fix placing torches and the like on inverted woden slabs.

Build 4.0.0.247:
	Christian:
		Update FML: 12bc4ba
		12bc4ba Make console logging pass through a single logging thread to avoid concurrency problems with launchers and stuff
		8fccfa2 Overlooked chat message support *sigh*. Fixes wierd mods that communicate through custom chat messages rather than
		a697d04 Rescan mod packages where there was a possible mod identified to try and make sure we load it. Fixes Matmos r16

Build 4.0.0.246:
	Christian:
		Update FML: 9d812f1
		9d812f1 And handle the other way to globally register an entity
		869cf78 Fix up mods trying to register entities outside of modloading. Now you'll get a big fat warning for doing such a de
		186680c Fix CJB mod compatibilty for real. Gui container registration can now happen in the constructor. YUK!
		5aed6d9 Fix compatibility with ModLoader dispenser hook. Fixes a bug with IDispenseHandler too - though it means that inter
		3d7a665 Fix headless operation, hopefully

Build 4.0.0.245:
	Christian:
		Update FML: 10a7169
		
		10a7169 Fix up trying to re-add stuff to the classpath when it's already there
		0eb7180 Fix out of range entity id handling for ModLoader mods a bit more. Thanks Herobrine mod!
		b1b4c61 Expose GuiMerchantButton
		359cfb5 Log a big fat warning for the developer in the case the network version is not acceptable to the mod itself. (This can happen because of a bad range specifier for example)

Build 4.0.0.243:
	Christian:
		Update FML: 8656fd5
		8656fd5 Also, make missing entity not blow things up
		25a4dcb Fix entity tracker "update" packet not computing correctly. Should work now..

Build 4.0.0.242:
	Christian:
		Update FML: c90a853
		c90a853 Fix up addRenderer to catch exceptions from the basemod, also, addrenderer now supplies a list of the default renderers from MC for editing and will note the
		18069d8 Change download location for FML libraries to files.minecraftforge.net, add an encoding param to the javac command line to force utf 8
		a40f4a7 Add in random jar/zip files to the classpath. UGH this is so fucking ugly it's not funny.
		5b6460b Use a null socket and try to prefer the result of getLocalHost in the broadcast data.

Build 4.0.0.240:
	Christian:
		Update FML: c0d1348
		c0d1348 Add in an ItemRenderer null check so FML can run render adding mods
		482c163 Inverted boolean logic. Grrr.
		221d113 ModLoader mob spawns use packet 24- build a bypass system so that they can still use it
		f19f426 Remove debug statements

Build 4.0.0.239:
	Christian:
		Update FML: 9dd9b6e
		9dd9b6e Fix keybindings not loading properly from gamesettings file after restart

Build 4.0.0.238:
	LexManos: Fix silk touch on Ender Chests.

Build 4.0.0.237:
	t.tomkins:
		Update patches/common/net/minecraft/src/NetServerHandler.java.patch
		
		 Update patches/common/net/minecraft/src/NetServerHandler.java.patch
		
		Server mods can now use noClip to push players through solid blocks without is being an invalid move and resetting the players position.
		
		Useful for creating semi-solid blocks like quicksand.

Build 4.0.0.236:
	LexManos: Fix Issue #140: Custom items not properly having texture applied for partical effects.

Build 4.0.0.235:
	Christian:
		Update FML: acb0b21
		acb0b21 Fix so we always send received packets to handlers. Renders 250 filtering useless unless i can figure a way to intercept

Build 4.0.0.234:
	Christian:
		Update FML: b17dd3c
		b17dd3c Some tests
		fa66ffa Fix trying to load the client side packet handler, when on the server, hopefully?
		b106420 Fix up network negotiation - now it will disconnect with a nice error screen if there are missing mods on the client vs se

Build 4.0.0.233:
	Christian:
		Update FML: c971adb
		c971adb Fix missing addCommand call: thanks "spawnwolf test command"
		d6326de Fix a couple of modloader mods. Thanks!
		483667c Some functionality fixes for @Instance injection.
		8bef512 Versions now have two flavours: the @Mod(version) which is the "programmatic version" and is used for all version relationship calculatio
		501009c Always for ML mods into "public" class accessibility - we don't call from the default package like ML does.
		d3d4308 Add in a convenience method for getting a class instance based on existence of another Mod. Useful for soft dependencies.

Build 4.0.0.232:
	Christian:
		Update FML: 2d9b88b
		2d9b88b And more mod sorting fixes.
		93d5934 Actually *use* the sorted mod list

Build 4.0.0.231:
	LexManos: Fix FillBucketEvent to actually fire.

Build 4.0.0.230:
	LexManos: Fix call to createTileEntity on blocks that extend BlockContainer.

Build 4.0.0.229:
	Christian:
		Update FML: 180a279
		180a279 Merge pull request #82 from Chicken-Bones/master
		cf38461 The access transformer will now handle classes in packages.
		2c85539 Reverse the meaning of state in fml.modStates system property and fmlModState.properties - it was very derpy before. Now: true is enabled, false is disabled, as you would expect
		d651189 Actually fix the corrupt JSON problem
		f6a8cd5 Fix isModLoaded for "disabled" mods, and the toposort as well
		3bde961 A bit more information for dependency handling
		6396bea Fix up handing corrupt mcmod.info
		6bc6def Fix a problem with network ids
		7328610 Fix up version handling properly. Hopefully, and the error screen.
		9fcc452 Only active mods should have dependencies checked, and be sorted
		26302a6 Fix oddity with Screen, print a version out in the sorted list!

Build 4.0.0.228:
	Christian:
		Update FML: 62dbfb3
		62dbfb3 Fix metadata

Build 4.0.0.227:
	Christian:
		Update FML: b91cbe9
		b91cbe9 Fix up versioned dependencies so they work a lot better, also add in a missing mods screen

Build 4.0.0.226:
	Christian:
		Update FML: 93b8ba9
		93b8ba9 Fix missing serverSendPacket
		23fdbbd Trading support for ModLoader - thanks Herblore!
		d7a74d8 Close the jar, for cleanliness sake
		58e6dd9 Fix authors - it'll read both "authors" and "authorList" from the json now
		907cf2d More ML compatibility - fix up dragon mounts, thanks!
		ee48a36 Fix up loading mods that are grandchildren of BaseMod
		c6f362b Fix entity handling for ModLoader mods, thanks parachute mod!

Build 4.0.0.225:
	LexManos: Fix lighting issue for air related to 4096 fix.

Build 4.0.0.224:
	LexManos: Made helper hooks for EntityLiving and EntityRenderer hooks for Optifine
	LexManos: Removed deprecated ISpawnHandler, that never worked in 1.3.2 so noone should be using it. See FML's replacement.

Build 4.0.0.223:
	Christian:
		Update FML: 6e01c59
		6e01c59 Merge ChickenBones pull into FML - adds player trackers
		a0cbd37 More precise error handling when an invalid class is present
		12323e2 Fix textures not applying properly
		789a4a3 Fix up entity spawning - hopefully they won't warp anymore.
		a87d045 Add in a helper on the server start event for adding commands to the server.
		82e9309 Move villager trading hook up a bit. thanks sengir.
		8deaa37 Fix LAN to try hard to find a real network interface, not just localhost most of the time
		b5363e3 Update build to not bother building client jar. Universal is everything now.

Build 4.0.0.222:
	LexManos: Pickblock now replaces the currently selected item if it could not find a empty space.

Build 4.0.0.221:
	dvrabel:
		Use original minecart drag co-efficients for regular carts.
		
		Since the amount of speed lost is 1 - co-eff, rounding 0.997 to 0.99
		makes a big difference to the distance a minecart will travel (less
		than half of the distance in vanilla 1.25).

Build 4.0.0.220:
	LexManos:
		Update FML to 304:
		Client side only classes are properly annotated, and denied loading on server side
		Added missing client side only ModLoader.getContainerGUI function
		Guis work for FML mods now.
		Fixed MLProp handeling of null info
		Fix up dispenser handling, add in new params for the dispenser: breaks IDispenseHandler, sorry
	Christian:
		Update FML: 28a10ac
		28a10ac Null protection for ticks() -- probably should uses EnumSet.noneOf() but you can also use null now to stop ticking. closes #77
		c349d51 Automatic mod entity registration into the global entity list. This might break entity code out there, sorry, but this way for most entities you no longer need to manage the global mod entity stuff at all. just remove it. FML will take care of the rest (note, worlds won't load the old entities)
		ef01745 Add in a utility function that *might* tell you the context you're running in on either client or server: FMLCommonHandler.getEffectiveSide
		c97d6a6 Try and stop sendPacketToAllAround from being crashy
		2062273 Mods can add mod specific crash information to the crash report now Forge needs to implement MinecraftForge.getCrashCallable
		6e6436e Fix up dispenser handling, add in new params for the dispenser: breaks IDispenseHandler, sorry
		38f4a22 Fix up MLProp handling for null info
		3a8b047 GUIs working in FML for ML mods
		52483ee Support gui opening for Shelf mod
		dce1cbc Updated MCPMerger to annotate unique classes with there sides, and SideTransformer to null out any class that is loaded on the wrong side.

Build 4.0.0.217:
	LexManos: Updated onItemUseFirst call to include the new hit vector information, and updated readme.

Build 4.0.0.216:
	LexManos: Added missing server side onBlockStartBreak hook, fixes Sheers.

Build 4.0.0.215:
	LexManos: Fixed Forge's 4096 block filler initalization.

Build 4.0.0.214:
	LexManos: Fix IndexOutOfBounds exception, Major derp.

Build 4.0.0.213:
	Christian:
		Update FML: 46c563a
		
		46c563a Expose more of the village construction parts for building village piece
		1380c2e Allow access to the type "ComponentVillage"
		71a3818 Documentation and registration for villager stuff
		e3a343c Fix javadoc derp
		195b1a0 Villager trading, manipulation and village enhancement. Still WIP but sh
		69e66c3 Fix exception based logging to actually log the exception!

Build 4.0.0.212:
	Christian:
		Update FML:
		885637c Fix up keyboard events for modloader
		90a7c8f Pickup notification

Build 4.0.0.211:
	LexManos: Changed order in which EntityItemPickupEvent is called, it will no longer be called if the 'delay' on the item is still active. Also EntityItems that are in the world with invalid item stacks will now kill themselves.

Build 4.0.0.210:
	mitchel.pyl: Adds a SkyProvider class that can handle the rendering of the sky

Build 4.0.0.209:
	Christian:
		Move and add a few AT for forge: rail and leaves stuff mostly
		Update FML (reorg some AT for FML vs forge):
		2171c0c Update fml_at with new transforms
		924a6f9 Fix derp where client sided packet handler would be created on a dedi server env
		ad4cffb Add in support for "dummy" keybindings- ones that are added to the list but never do anything so the mod can handle it all themselves.
		cf77ffb Don't complain about minecraft source code being in "net.minecraft.src". Derp.
		b2fdcd7 Fix ModLoader add XP Smelting
		094ce2a Actually register client/server packetspecs as their correct sides! fixes #71

Build 4.0.0.208:
	LexManos: Fix MC packet bugs for remote servers that use blocks with ids > 256

Build 4.0.0.207:
	LexManos: Fixed bug in EntityMinecart that would cause them to fall through the ground at the bottom of slopes.

Build 4.0.0.206:
	Christian:
		Update FML:
		
		e8cb2c1 Error if channel name is invalid - either too short, or too long
		9c6c56c Add a connect and read timeout for downloading libraries. This should really stop the "waiting forever" at startup screen.
		0d5affe GIANT FAT WARNINGS if you use any code in net.minecraft.src or any subpackage thereof. Get it out of there, now!
		13f210f Fix up ML GUI ticking. Thanks sharose!

Build 4.0.0.205:
	LexManos: Fixed EntityEvent.CanUpdate
	LexManos: Fix EntityItemPickupEvent 'pop' sound spamming.
	LexManos: Added timeout to MC's download of sound resouces.
	LexManos: Update WorldProvider.path diff.

Build 4.0.0.204:
	Christian:
		Update fml:
		c61ad51 Organize ALL the imports
		c0842b0 Expose the server in serverstart event
		2851079 Fix up directory injection of log file locations
		5197524 Refer to FMLLog, not FMLRelaunchLog
		78efd1a Tidy up server launch - reflection not required anymore
		eee0a99 Also, log what the directory discoverer finds for mcmod.info
		10c96c3 And log the exception if it has a problem reading the jar file
		07cc3fb Fix jar loader failing to inject any metadata at all if mcmod.info is not found.
		e31f143 Change install.cmd to install.bat, why, cuz people are .... Updated readme to mention needing server and client.

Build 4.0.0.200:
	LexManos: Allow white space in the property name.
	Christian:
		Update FML to include some ML compatibility fixes. Minimap should run, assuming he
		recompiles against standard ML interfaces.
		This updates to official MCP 7.2, so you'll need to rebuild your workspace (some
		small but important patches to MCP went in)

Build 4.0.0.199:
	Christian: Update FML, make the .sh scripts executable

Build 4.0.0.196:
	LexManos: Update FML to 285

Build 4.0.0.194:
	draake: Added additional sound events to allow manipulation of a sound source at its creation.
	draake: Removed SoundSetListenerEvent implementation.

Build 4.0.0.193:
	LexManos: Fix potential index exception in ForgeDirection
	LexManos: Whops

Build 4.0.0.192:
	LexManos: Rename Orientation to ForgeDirection {Damn MCP naming a class Direction already}

Build 4.0.0.191:
	LexManos: Update FML again for mod screen blending fix.

Build 4.0.0.190:
	LexManos: Updated Orientation with new helper functionality.
	LexManos: Fix ItemBlock placement, should fix RP Deployers placing blocks 1 tile down.
	LexManos: Seperated block placmenet logic in ItemBlock as immibis requested: https://github.com/MinecraftForge/MinecraftForge/pull/110
	LexManos: New Command event.
	LexManos: Fix issue with default getContainerItemStack
	LexManos: Add render distance property to TileEntity.

Build 4.0.0.189:
	LexManos: Updated FML, should fix the new included eclipse workspace.

Build 4.0.0.188:
	LexManos: Cleanup repo, delete old code
	LexManos: Update FML to 278, MC 1.3.2
	LexManos: Cleaned up forge scripts, and updated AT config for 1.3.2, deleted any reference to server specific code.
	LexManos: Updated patches to 1.3.2
	LexManos: Fixed bug in DimensionManager that would cause Index error for custom dimensions, also made WorldProviders aware of what dimension they are.

Build 4.0.0.187:
	LexManos: Readded patch to allow for use of custom teleporter for transfering dimensions.

Build 4.0.0.186:
	LexManos: Update FML with entity spawning fixes

Build 4.0.0.185:
	LexManos: Updated FML, should fix 'derp?' RuntimeError

Build 4.0.0.184:
	LexManos: Fix PickBlock 'ghost item' bug when picking with a item selected.

Build 4.0.0.183:
	LexManos: Update FML, Tons of bug fixes and proper merging of client and server.
	LexManos: Delete Forge server projects
	LexManos: Update debug settings to use Client's internal MinecraftServer.main to debug dedi-server env.
	LexManos: Update release script to create universal binary distro.

Build 4.0.0.182:
	j.marini: Fix bug where default bonemeal behavior wouldn't trigger. Only return if the event was canceled.

Build 4.0.0.181:
	LexManos: Update FML, new AT features, and error info.

Build 4.0.0.180:
	LexManos: Fixed ItemRenderer not grabbing custom texture files properly for block items
	LexManos: Updated FML
	LexManos: Delete dead IGuiHandler
	LexManos: Update AT config to expose some block functions and a few extras.

Build 4.0.0.179:
	LexManos: Should fix commands.py patching not working properly first run.

Build 4.0.0.178:
	LexManos:
		Updated FML, Should fix a lot of installing issues for MCP.
		Made patches error and not apply if the target file is not found.
		Updated Event Transformer to add a default constructor...
		Fixed 4096 setup code in MinecraftForge.initalize()

Build 4.0.0.177:
	LexManos: Fix issue in install script for users with spaces in there paths.

Build 4.0.0.176:
	LexManos: Update FML, server should run now. Still issue with NPE with no mods installed.
	LexManos: Updated FML, fixed custom tool hooks, and spawn protection/player reach hooks.

Build 4.0.0.173:
	LexManos: Fixed Diemsnion API related NPEs, and updated FML to 231.

Build 4.0.0.172:
	LexManos: Get rid of all old patches
	LexManos: Added a better eclipse workspace for deving Forge
	LexManos: inital push of updated setup script and cleaned up forge.py
	LexManos: Dump old mcp config
	LexManos: New Start.java which allows the user to login using a legit account for testing on servers.
	LexManos: Committing inital work on generating sanitized MCP conf data.
	LexManos: Add the direct copied files from MCP conf
	LexManos: Add newids to that list
	LexManos: Helper function grab all unique searge names that are shared client and server
	LexManos: Added merging fields/methods/param csv files. And updated FML to 197
	LexManos: Remove eclipse files from old eclipse projects
	LexManos: Updated build.py
	LexManos: Update FML
	LexManos:
		Moved logo to new client folder
		Added blank Access Transformer config for Forge
		Implemented version storage
		Added basic dummy FML mod container to remove the need for mod metadata file
		Added beggining work on Forge event system
		Updated and moved EnumHelper
	LexManos: Updated update_patches.py, and made first patch!
	LexManos: Moved paulscode to new client folder
	LexManos: First push of some small patches and introduction of basic events. As well as the first cases for Forge's Access Transformer
	LexManos: Missed a file
	LexManos: Moved in OreDictionary stuff to new system. IOreHandler is replaced by OreDictionary.OreRegisterEvent
	LexManos: Renamed MinecraftForge.eventBus to EVENT_BUS as it's constant.
	LexManos: Implemented BonemealEvent (IBonemealHandler replacement), and bonemeal making grass.
	LexManos: Implemeneted adding grass seeds, as well as IShearable for BlockTallGrass
	LexManos: More progress on converting patches from 1.2.5
	LexManos: Some more patch migration before bed.
	LexManos:
		More patches converted.
		Refactored some of the events to be a better hiarachy.
	LexManos: A bulk of more patches converted, updated fml
	LexManos: Moved some files.
	LexManos: More work, moved over packet stuff, need to change everything to use new NetworkMod system
	LexManos: More conversions, added all the entity living events.
	LexManos: Finished World and EntityMinecart patches.
	LexManos: Removed a lot of old files
	LexManos: Updated Client side patches for the new Merged MCP workspace.
	LexManos: Nope, unneeded patch
	LexManos: Cleaned up some more, fixed infinite loop with cancelable annotation, Client now compiles and enters world just fine.
	LexManos: Delete conf, server compile, update fml, and fix install script.
	LexManos: Copy forge files over in install.
	LexManos: Update fml
	LexManos: Moved over Configuration
	LexManos: Fix oreientation bug causing levers not being able to place.
	LexManos: Added new pick block hook for blocks and entites to allow for better grained control of the result.
	LexManos: Include Forge's AT config into redist zips.
	LexManos: Update fml, impelemnted Diemsnion API stuff.
	LexManos: Updated FML, updated patches

Build 3.4.9.171:
	Christian: Normalize the repo
	LexManos: Rebase
	LexManos: Bumped version to 3.4.9, final commit for 1.2.5.

Build 3.3.8.170:
	someh4x0r: Fix BlockTrapDoor.disableValidation on server

Build 3.3.8.164:
	LexManos: Should fix NPE on older ISoundHandlers EXA: http://minecraftforge.net/forum/index.php/topic,759.html

Build 3.3.8.163:
	Christian: Update fml with recent tick fix

Build 3.3.8.162:
	truebrain:
		-Add: sync serverPos[XYZ] on spawning of entity
		
		This fixes the issue that, up to 400 ticks from getting in range,
		entities have a wrong offset (because server and client don't agree on
		the position to calculate relative updates from)
	truebrain: -Fix: check for null where needed
	truebrain: -Codechange: applied LexManos' request

Build 3.3.8.161:
	LexManos: Fixed a improper rounding in EntityMinecart
	LexManos: Made WorldGenMinable metadata sensitive.

Build 3.3.8.160:
	Christian: Update fml to 175- fixes some weird ticking behaviours for ML mods, adds in new ticking behaviours for smart mods

Build 3.3.8.159:
	LexManos: Moved licenses and credits into install folder.
	LexManos: Removed symlink files, shouldn't be in the repo.
	LexManos: Updated some remaining scripts to call there python versions.

Build 3.3.8.158:
	LexManos: Fix furnaces not smelting the proper number of results after the first one. Damn you tahg, fix this! Keeps falling through my cracks.

Build 3.3.8.157:
	Christian:
		Fix server check "blockHasTileEntity" used to determine if getDescriptionPacket
		is sent for the block to be metadata sensitive. Thanks iChun!

Build 3.3.8.156:
	Christian: Fix ghost players who appear if they don't have the 4096 fix installed

Build 3.3.8.155:
	LexManos: Fix container creative to not add Blocks above 256 unless it's told to.

Build 3.3.8.154:
	Christian:
		Fix world provider behaviour: WorldProvider.byDimension should always return
		a new instance- otherwise you can end up with worlds overwriting one another

Build 3.3.8.153:
	LexManos: Fixed isBlockReplaceable and placing ItemBlocks'

Build 3.3.8.152:
	LexManos: Fucking spelling nazis

Build 3.3.8.151:
	LexManos: Fix bitmask bug related to 4096 in multi-block change.
	LexManos: Updated FML to build 153

Build 3.3.8.150:
	LexManos: Fix NPE related to server/client not having block ids synced properly.
	LexManos: Add option to randomize potential spawn locations to have a more randomly dispersed spawn patern, useful for games like FTB vs.
	LexManos: Added configuration option to disable the darkroom mechanic. For servers who wish to not risk destruction at one broken pipe.

Build 3.3.8.148:
	LexManos: FML 150, more tick related work.

Build 3.3.8.147:
	LexManos: Close inputstream

Build 3.3.8.146:
	LexManos: More bugfixes related to portal generation. Should be all now.

Build 3.3.8.145:
	LexManos: Some 4096 I missed in custom renderers.
	LexManos: Updated to FML 149, should fix all ticking issues with ModLoader mods
	LexManos: Fix Vanilla bug where nether portals would not work above 127

Build 3.3.8.144:
	LexManos: Updated to FML build #142, fixed FML compilation issue causing missing files when reobfing.

Build 3.3.8.143:
	LexManos: Updated release script to automatically inject version info into .info file.

Build 3.3.8.142:
	LexManos: Updated to FML 141, should fix ticking issues with certian mods, and crash issue with TropiCraft

Build 3.3.8.141:
	LexManos: Bumped version number for new IEntityLiving interface.

Build 3.3.7.140:
	pahimar: Typo in the new EntityLivingHandler code

Build 3.3.7.139:
	LexManos: Made setFailsafeFieldValue public for Rob
	LexManos: Implemented enchanced EntityLiving events. Thanks Atomic for parts of it.

Build 3.3.7.138:
	LexManos: Few more cases for 4096, thanks TrueBrain

Build 3.3.7.137:
	LexManos: Forgot Configuration in 4096 change.

Build 3.3.7.136:
	LexManos: Configurable kick message when you don't have forge.
	LexManos: Initial 4096 fix based of mDiyo's work.

Build 3.3.7.135:
	LexManos: Fixed bug in new entity sound hook.

Build 3.3.7.134:
	LexManos: Updated to FML #135 {Fixed ModList rendering issue, and incorrect arument on crafting hook}
	LexManos: Added new ISoundHandler.onPlaySoundAtEntity hook. Should be backwards compatible with any older ISoundHandler implementations.
	LexManos: New onChunkUnload event for TileEntities, for psxlover.
	LexManos: Bumped version number to 3.3.7 for full release.

Build 3.2.6.132:
	LexManos: Fixed concurent modification exception in the ore registry.

Build 3.2.6.131:
	LexManos: Fix for potential concurancy modification exceptions

Build 3.2.6.130:
	LexManos: Fixed possible NPE when blocks havent fully initalized yet.

Build 3.2.6.129:
	LexManos: Updated FML to 132, TextureFX fix, and bumped revision to 6.

Build 3.2.5.128:
	LexManos: Added bouncer functions for functions we removed. Makes MagicLauncher shut up about missing functions {not actually missing}, and therefor makes users stop thinking its a life or death error.

Build 3.2.5.127:
	LexManos: New Ore Dictionary recipies. Allows for simpler Ore Dictionary integration with recipies. IOreHandler should no longer be used.

Build 3.2.5.126:
	LexManos: Updated to FML 130
	LexManos: Added hackish workaround for Tessellator.textureID to provent crashing while we wait for Optifine to update.

Build 3.2.5.125:
	LexManos: Server side of ITextureProvider for Block/Item for compilations sake.

Build 3.2.5.124:
	LexManos: Backwards compatibility fix for ITextureProvider

Build 3.2.5.123:
	LexManos: Updated FML to 121 to fix world tick issues.

Build 3.2.5.122:
	LexManos: Updated MCP mapings. Moved the bulk of custom logic from RenderItem to ForgeHooksClient.
	LexManos: All Items and Blocks now implement ITextureProvider, and have a setTextureFile(String) function, to support cleaner code in Mods and in Forge.
	LexManos: Tag each Tessellator with it's associated texture ID.

Build 3.2.5.121:
	LexManos: Added kick info to disconnect event, updated to FML 120, keybindings, better image rendering in ModList ui.

Build 3.2.5.120:
	LexManos: Fix bug in cart functions where would always return null.

Build 3.2.5.119:
	LexManos: Fixed some inverted logic causing tress to not gen correctly.

Build 3.2.5.118:
	LexManos: Update FML to 117

Build 3.2.5.117:
	LexManos: New Hooks addedf for custom tree/leaves. And better interaction with trees growing and rerplacing certain blocks. Should allow for ExtraBiomes to behave nicer, and RedPower to make there blocks un-breakable by trees.
	LexManos: Also, new hook in last commit for blocks to determine if they are able to be replaced by ores, for any mod that adds new world gen. Bumped revision up.

Build 3.2.4.116:
	LexManos: We now bundle CodexIBXM from PaulsCode. See http://paulscode.com http://www.paulscode.com/forum/index.php?topic=4.0 and the included license files for more info.
	LexManos: Updated to FML 115, added Forge Logo to the client dist, and in-game ModInfo page.

Build 3.2.4.115:
	LexManos: Updated to FML build 114

Build 3.2.4.114:
	LexManos: Included fmlversion.properties in the release zips.

Build 3.2.4.111:
	LexManos: Added FML ReadMe, Credits, and License to release zips

Build 3.2.4.110:
	LexManos: Update FML to 92, this include full client side support, ModLoader nolonger needed.
	LexManos: Added new source clean step to fix linux vs windows astyle issues.
	LexManos: Cleaned up names for Minecraft Forge's text files so they dont clash with other mods. Fixed up the release script to include the license text, and executable permissions for install.sh.
	LexManos: Added FML mod info file
	LexManos: Updated MCP Mapings and patches.
	LexManos: Updated patches for FML, moved some extranious code to Forge classes instead of patches.
	LexManos: Updated to FML Build 95

Build 3.2.3.108:
	LexManos: Bump version number for official release.

Build 3.1.3.107:
	LexManos: Fixed AudioMod compatibility with MultiMC style launchers.

Build 3.1.3.106:
	LexManos: Bit masked the entity ID to change the range from -127-127 to 0-255

Build 3.1.3.105:
	LexManos: Updated MCP Mapings

Build 3.1.3.104:
	LexManos: Added forge identifier to statistics collection.

Build 3.1.3.103:
	LexManos: Fix for furnaces not smelting the final item in full stacks.

Build 3.1.3.102:
	CovertJaguar: static final vars are inlined during the compile step, making the version variables useless at runtime.
	LexManos: Fixed Levers droping off the backs of stairs client side.

Build 3.1.3.101:
	LexManos: New block hooks for creating custom beds.

Build 3.1.3.100:
	cpw: Update to FML 74: fixes an important issue with MLProp

Build 3.1.3.99:
	LexManos: Bumped revision to 3

Build 3.1.2.98:
	LexManos: Fixed Vinella mob spawning bug that prevented mobs from spawning on the top most chunk. Added new Block function to determine if a Mob can naturally spawn on the block. Add new hook to allow for special case handeling on natural entity spawn.

Build 3.1.2.97:
	LexManos: Fix for loading Minecart Entities in worlds that were last accessed before Forge was installed.

Build 3.1.2.96:
	LexManos: Moved MLMP compatibility functions to ModCompatibilityClient, and fixed issue where no vehicles would be spawned.

Build 3.1.2.95:
	LexManos:
		New ISoundHandler interface, useful for adding custom sounds and dealign with sound based events.
		Includes basuic AudioMod compatibility.

Build 3.1.2.94:
	LexManos: Fixed vinella bugs when trying to access chunk information with a y < 0

Build 3.1.2.93:
	LexManos: Updated to FML build #73
	LexManos: Added MLMP hook invocation for vehicle spawn and opening GUI's to provide compatibility for clients that have both ModLoaderMP and forge installed.

Build 3.1.2.92:
	LexManos: Exposed TileEntityData packet to TileEntities. And added helper sender function.

Build 3.1.2.91:
	LexManos: Added metadata sensitive Chunk constructor for Bioxx

Build 3.1.2.90:
	LexManos: Added MinecraftApplet.clas to the force output list because users cant understand the concept of only replacing files they are told to. And bumped version to 3.1.2

Build 3.0.1.89:
	LexManos: made the ID in PacketEntitySpawn unsigned.
	LexManos: Added generic packet sending function to MinecraftForge class.
	LexManos: Fixed shift-clicking issue with items that utilized the new ItemStack sensitive smelting system.
	LexManos: Implemented a 'small' packet system for those mods that need to send rapid, small data packets and who are concered about the overhead of the 250 payload packet. It uses packet 131.

Build 3.0.1.88:
	LexManos: Implemented  RichardG's Paged Achivement list GUI modifications.

Build 3.0.1.87:
	t.tomkins: Edits enable use of EntityPlayer.canHarvestBlock (for PlayerAPI) when the ToolClass has no rules for the block.

Build 3.0.1.86:
	LexManos: MAX_ENTITY_RADIUS Now works on the Y axis
	LexManos: Respawning in dimensions should now properly set the dimension ID for the new player instance.

Build 3.0.1.85:
	LexManos: Fix for vanilla crash for chunk generation with block ID's above 127.

Build 3.0.1.84:
	cpw: Update fml to build 68: fixes a ticking issue and soft vs hard dependencies

Build 3.0.1.83:
	LexManos:
		Changed entity Forge spawning code works to be more in line with normal spawning:
		(World, double, double double) constructor is nolonger called, normal (World) constructor, and setPositionAndRotation is called afterwords.
		yaw, pitch, and yawHead is sent (if the entity isn't a EntityLiving yawHead isn't used)
		The datawatcher data is also sent like a normal Entity.

Build 3.0.1.82:
	LexManos: Fixed bug in BlockFire's old fields.
	LexManos: Added variable entity radius to World, to be used if a mod make really large entities.

Build 3.0.1.81:
	LexManos: Fixed TileEntity bug that was causing Ghost tile entities.

Build 3.0.1.80:
	LexManos: Multi-pass item rendering now uese proper render pass number.

Build 3.0.1.79:
	LexManos: Added slope velocity hook for Covert

Build 3.0.1.78:
	LexManos: Fixed bugs in the Dimension transfer code, Now displays proper join message, and respawning in dimensions other then 0 works.

Build 3.0.1.77:
	CovertJaguar: Added a function for checking block harvest levels without having to resort to reflection.
	LexManos: Try to fix jenkins build.

Build 3.0.1.75:
	LexManos: Added ItemStack sensitive burn time hook.

Build 3.0.1.74:
	LexManos:
		Added new Item function to allow for multiple rendering passes.
		Fixed a vinella bug where item layters would not line up for EntityItem's
		Added new IItemRendere helper flag for 3d block translations.

Build 3.0.1.73:
	cpw: Update fml to 62- provision a server console command and fix mod loading order
	cpw: Update FML for new hooks: onPlayerLogout and onPlayerDimensionChanged
	LexManos:
		Rewrote IItemRenderer to be a more generic and expandable version, Breaks previous interfaces, but this should be the last time the interface changes.
		Implemented the MapRender hook ChickenBones requested.

Build 3.0.0.72:
	cpw: Fix separated login/announce handler
	cpw: FML 59: don't send a zero length register packet, add mod channels

Build 3.0.0.71:
	cpw: Update to FML 57: fixes FML not calling it's login handler code

Build 3.0.0.70:
	LexManos: MCP Conf update for 1.2.5
	LexManos: Initial patch update to FML and MC 1.2.5
	LexManos: Deleted patches
	LexManos: Fixed update_patches.py to now delete old patch files that have no working src relation
	LexManos: Updated repo scripts to python, allowing more flexability and less code duplication.
	LexManos: Finished up converting the source dist install scripts to python. Fixed a couple issues with the other scripts.
	cpw: Update patches for FML fix.
	cpw: Fix release script to import "inject_version"
	cpw: Add in recent fml with fixes
	cpw: Delete the old one too
	LexManos: Rewrote the login code to delay full login untill forge fnishes negotiating network IDs. Should fix entities not having proper ID mapings.
	LexManos: Added ChickenBones's request ITextureLoadHandler hook
	LexManos: Updated patch for mapings
	LexManos: Implemented ISaveEventHandler as ChickenBones's requested.
	LexManos: Add server spawn protection config option as per someh4x0r's request.
	LexManos: Couple of output fixups and added script to be executed by Jenkins during the build. First test build.
	LexManos: Changed IGuiHandler's signature to be compatible with both sides. Took out ModLoaderMp reference in README.

Build 2.0.0.68:
	LexManos: Fix some shadowing warnings.
	LexManos: Some cleanups to update_patches, should run properly on any system now.
	LexManos: Add IChunkLoadHandler.canEntityUpdate() function to allow entities to update while in custom loaded chunks.
	LexManos: Implemented a chat event handler system to allow for manipulating and handeling the various chat/command events.

Build 2.0.0.67:
	LexManos: Changed update_patches script to use python for the bulk, Prevents making 1800 temporary useless files.
	LexManos: Fixed camelcasing in IConnectionHandler, ment to do during first upgrade.

Build 2.0.0.66:
	LexManos: Fixed typo bug in MinecraftForge.getEntityTrackerInfo

Build 2.0.0.65:
	LexManos:
		Updated to MC: 1.2.4 MLMP: 1.2.4 v1
		Removed all code that was marked as deprecated, IE: ICustomItemRenderer, and the functions in Configuration

Build 1.4.1.64:
	LexManos: Reworked EntityPlayerMP.openGui to hopefully be more compatible with PlayerAPI

Build 1.4.1.63:
	LexManos: Cleanup the EffectRenderer patches, Allows custom food items to have the proper particals. Cleaned up special case class in favor of basic java generics.

Build 1.4.1.62:
	CovertJaguar: Added the ability to define custom categories for config files.
	CovertJaguar: Removed createCategory() function and changed it to create categories as they are encountered.
	LexManos: Updated MCP mapings
	LexManos:
		Fixed a couple of bugs in the Configuration categories pull request.
		Added helper functions to Property for standard int/boolean usage.
	LexManos: Added rider sit pull request.

Build 1.4.1.61:
	LexManos: Fixed NPE on CustomPayload packets with 0 data
	LexManos: Changed logic in Configuration to allow for extended block ID mods easier access to change that. Just use reflection to change Configuration.configBlocks to whatever length you want.
	LexManos: Implemented Pheenixm pull request allowing for more control over the camera.
	LexManos:
		Added MinecraftForge.isClient() function that returns true if you are in the Minecraft Client,  (As defined as net.minecraft.client.Minecraft existing) false otherwise.
		Fixed a typo on PacketEntitySpawn that caused speed to be assigned improperly.
		A little code cleanup.

Build 1.4.1.60:
	LexManos: Fixed a few typos that CovertJaguire found in The Forge entity handeling code. And re-wrote the connection sequance so that clients get a list of mod ids before anything else.

Build 1.4.1.59:
	LexManos: Readded the deprecated interface ICustomItemRenderer. Added method to enforce deprecation cross Minecraft versions.

Build 1.4.1.58:
	newthead: Added new item render interfaces to Forge client
	newthead: Added hook for rendering equipped items
	newthead: Clarified render option for inventory items
	newthead: Added remaining item render hooks, and fixed a static method access
	newthead: Added render code for inventory items and entity items.
	newthead: Cleanup/fix item render hooks
	newthead: Added additional flag for rendering entity item bobbing
	newthead: Merged item rendering interfaces into a single IItemRenderer
	newthead: Updated render hooks and registration to use the IItemRenderer interface
	newthead: Modified patches to use new item render hooks
	newthead: Merged item rendering interfaces into a single IItemRenderer
	CovertJaguar: Fix for network code.
	newthead: Changed render hook checks to all use ItemStack instead of itemID
	newthead: Reverted vanilla texture binding to an explicit if() statement based on item ID
	LexManos: Fixed dyes showing twice in creative list
	LexManos: Bumped version number to 1.4.1

Build 1.4.0.57:
	LexManos: Fixed tile entities not properly being removed for blocks that do not extend BlockContainer, or override BlockContainer.onBlockRemoval

Build 1.4.0.56:
	LexManos: Fixed excessive need for user interaction in the install script.
	LexManos: Fixed a class to a deprecated method to fix tool effectiveness.

Build 1.4.0.55:
	LexManos: Reworked the workspace scripts so the build should fail on compile errors. This build should fail as a test.
	LexManos: Fixed IOException not found error in CovertJaguires pull request. Updated scripts so that build should now be fixed

Build 1.4.0.53:
	CovertJaguar: Added throws clause to ISpawnHandler functions to keep the functions consistent with similar functions and increase ease of use. Exceptions are already being caught everywhere these functions are called, so no further changes required.
	LexManos: Fixed onTakenFromCrafting hooks to be called once per stack taken. Sadly due to how shift-click is handled, the passed in item stack is not garenteed to be the stack that the result was added to.

Build 1.4.0.52:
	LexManos: Fixed forgotten type identifier in clean_src
	LexManos: New EntityInteract hook for handeling player vs entity interaction on the global level vs the item level.
	LexManos: Fixed sides of grass not getting biome colors
	LexManos: Fixed type on patch conversion messing up tile entities
	LexManos: Proper fix for SDK's invalid bit shifts of parameters for chunk population
	LexManos: Made BlockStairs, BlockFarmland, and BlockStep have proper sided-solidity. Can now place torches on any solid side of those blocks.

Build 1.4.0.51:
	cpw:
		Fix worldgen doubleshifting in ModLoaderMP until SDK fixes it.
		
		This means mods can generate surface and nether in SMP again.

Build 1.4.0.50:
	eloraam: Fixed a merge error.
	LexManos:
		New script to fix decompile differences between windows and linux/osx.
		Removed the MLProp special case, no longer needed as MLProp decompiles fine.
		Updated patches to work on all systems.
		Added warning and exit if the user does not say yes to the cleanup.

Build 1.4.0.49:
	eloraam: MCP Update.  Fixed a few small bugs in the linux scripts.

Build 1.4.0.48:
	LexManos: Fixed the inverted logic in the missing mod check.
	LexManos: Fixed a wrong argument for dimensions, should fix entity tracking.
	LexManos: Custom dimensions should now honor the canRespawnHere function for respawning.

Build 1.4.0.47:
	LexManos: Fix up Configuration ids to only work for 256 ids until Jeb finishes the 4096 conversion.

Build 1.4.0.46:
	LexManos: Fixed a bug where vines were not shearable.

Build 1.4.0.45:
	CovertJaguar: Fixed a minor bug with the Minecart Dictionary.

Build 1.4.0.44:
	LexManos: 1.4.0 official release.

Build 1.3.4.42:
	LexManos: Updated to MLMPv3

Build 1.3.4.41:
	LexManos: Hack-fix for players getting stuck during logins. Detailed fix when bug is actually tracked down.
	LexManos: Implemented ChickenBone's Chunk handler

Build 1.3.4.39:
	LexManos: Fixed client side bonemeal on grass only making flowers
	LexManos: Updated to latest MCP

Build 1.3.4.38:
	LexManos: Fixed MLMP thinking Network mods need a client side when they dont.
	LexManos: Fixed a generic tile entity line i missed on the server side.
	LexManos: Removed improper tile entity negation

Build 1.3.4.37:
	LexManos: Updated to SDK MLMP v2

Build 1.3.4.36:
	LexManos: Fixed missing double array in MLMP's packet server side. Also, fixed the creative code again, brain failed.

Build 1.3.4.35:
	LexManos: Got my comparitor turned around
	LexManos: Updated to SDK's 1.2.3 MLMP, Mush cleaner, no longer supporting Flan's.

Build 1.3.4.34:
	LexManos: Updated gitignore, fixed digging particles, fixed creative container showing to many blocks, fixed wrong argument for custom renderers.

Build 1.3.4.33:
	LexManos: Updated MCP's patch files. Fixes hangs on running MC as applet.
	LexManos: ItemBlock now implements ITextureProvider so that blocks with custom textures will showup properly when being held.

Build 1.3.4.32:
	LexManos: Fixed NPE in the login handler
	LexManos: Fixed directory issues in the setup script
	LexManos: Cleanup of ModLoaderMP and proper update to the latest version of ModLoader

Build 1.3.4.31:
	LexManos: Fixed missing space in linux scripts
	LexManos: No longer mark forge packets as chunk packets.
	LexManos: Updated MCP mapings files

Build 1.3.4.30:
	LexManos: Updated scripts so that we use Fernflower now. Added a small python script to download fernflower for the user. And the scripts exit out if it fails.
	LexManos: Deleted modLoaderMP.patch, unneeded now that we use Fernflower
	LexManos: Updated eclipse project for MCP 1.2.3's inclusion of the Start folder in the src folder.
	LexManos: Updated The Json enum helper to point to the new packaged names. And fixed a casing change in ModLoader
	LexManos: Made mod_MinecraftForge extend NetworkMod, and changed NetworkMod to extend BaseModMP server side.
	LexManos: Fixed unneeded imports in ForgePacket
	LexManos: removed unneeded import, and fixed casing of args in IShearable
	LexManos: Deleted EntityPigZombie patches, Who needed these? Why could you not do this via reflection?
	LexManos: Conf for 1.2.3
	LexManos: Same patch diff, files.
	LexManos: No longer needed, bug was fixed
	LexManos: Client side initial patch update to Fernflower and MC 1.2.3
	LexManos: Bit of a cleanup of the client patches
	LexManos: Couple of things I missed client side
	LexManos: Deleted unneeded server side patches, Packet250 bug was fixed. And the others got moved to AnvilSaveHandler
	LexManos: First push of server side patch updates for 1.2.3. MLMP is still not updated so it does not include those changes, and will not compile.
	LexManos: Small imports cleanup
	LexManos: Missed damageCarryover on the server
	LexManos: Made the scripts forge updating md5s/mcp/names
	LexManos: Updated for MLMP 1.2.3 v1

Build 1.3.4.29:
	LexManos: Bumped version to 1.3.4, final commit for Minecraft v1.1

Build 1.3.3.28:
	LexManos: Fixed bug in build script that caused the Minecraft/MinecraftServer classes to not be included.

Build 1.3.3.27:
	LexManos: Client side of the new Dimension support.

Build 1.3.3.26:
	thedeveducer: Fixed spelling mistake ('Frequancy')
	LexManos: Fixed ITextureprovider for multi-textured items when rendering on the GUI.
	LexManos: Fixed compile error for the spelling pull request.

Build 1.3.3.24:
	LexManos: Fixed up Shearable blocks to play nicer with sub-classes.
	LexManos: Fixed line endings in windows update_patches
	LexManos: Deleted Deprecated interfaces.
	LexManos: Ran AStyle over forge code for uniform code formatting, and refactored old code a bit to have cleaner names.

Build 1.3.3.23:
	connor: People may think the server needs the mods to continue and not the client.

Build 1.3.3.22:
	LexManos: Fixed a bug in update_patches that caused apostrphies to be removed. Causing the last patch to be generated incorrectly.

Build 1.3.3.21:
	LexManos:
		Initial attempt at server side extra dimensions support.
		Mods must register there dimensions on load, by calling DimensionManager.registerDimension(uniqueID, WorldProvier, boolean)
		Mods are resposible for writing there own transporter blocks.
		Initial commit, needs some more testing and design thoughts.

Build 1.3.3.20:
	LexManos: Added new Item.getIconIndex context sensitive version.
	LexManos: Implemented a response to Methuselah96's Arrow hook request. See IArrowNockHandler and IArrowLooseHandler

Build 1.3.3.19:
	LexManos: Changed the layout of the missing mods gui a little. Still needs a lot of work to look good.
	LexManos: Marked forge packets as 'chunk' packets. Giving them a higher priority making the initial mod list check more reliable.
	LexManos: Introduced some debugging info into Forge packets. And a debug flag in the client and server packet handlers.
	LexManos: Moved Client side EntityPlayer.openGui work code to EntityPlayer for compatibility between player API.

Build 1.3.3.16:
	eloraam: Linux scripts fixed, TE bug fix.
	eloraam: Fixed linux scripts, fixed TE bug.

Build 1.3.3.15:
	LexManos: Exposed getters for NetServerHandler.playerEntity and NetworkManager.netHandler
	LexManos:
		Introuduced NetworkMod, a BaseMod extension and replacement for BaseModMP. All mods that are designed to work in the server environment should extend this.
		NetworkMods will be assigned unique ModIDs by the server, and those IDs will be sent to the client upon connection.
		Refactored Forge packets to the net.minecraft.src.forge.packets package. And introduced the base ForgePacket class.
		Added initial ModList request/response.
	LexManos:
		Expanded the Mod check to test for missing mods and display a GUI screen for the client if it is missing any.
		The client now downloads NetworkMod ID's from the server upon connecting.
	LexManos: Implemented a generic EntityPlayer.openGui system, and the network backend for it to work on server and client.

Build 1.3.3.14:
	LexManos:
		Fixed up the install scripts. The linux script no longer needs sed. Should fix some issues on OSX's without gsed.
		Also forge sources will only be copied to sides that were downloaded.
		Also, install scripts now prompt for input to cleanup.

Build 1.3.3.13:
	LexManos: Split mod_MinecraftForge so that Clients arnt required to have MLMP installed if they don't use a MP mod.

Build 1.3.3.12:
	LexManos: Update MCP Mapings
	LexManos: Small update to update_patches.bat, to skip patch reject files.
	LexManos: Bumped version to 1.3.3

Build 1.3.2.10:
	LexManos:
		Refactored so that ISpecialArmor items do not see the factor of 25 on the damage.
		The value returned form ISpecialArmor.getProperties is now copied, so mod items are free to re-use there return values.

Build 1.3.2.9:
	LexManos:
		Reworked ISpecialArmor to provide better functionality as requested by IC2 devs.
		Armor can now be prioritized over other armor.
		It can deal with damaging it's own itemstacks.
		Also impkemented the ISpecialArmor.getArmorDisplay

Build 1.3.2.8:
	LexManos: Lowered the amount of build log spam, and fixed the inject_version script for use on other systems.
	LexManos: Fixed ITextureProvider support for items that have multiple colored overlays.
	LexManos: Added Item.onLeftClickEntity hook. Used to intercept and cancel the 'attack' action within items.
	LexManos: Implemented item.onBlockStartBreak call for creative single player.
	LexManos: Implimented a new IShearable system. This allows mods to create both new shear-like items/blocks. As well as new Entities/Blocks that work with other mod's shear-like items.

Build 1.3.2.7:
	LexManos: Missed a caluse, ISpecialArmor should work as intended now. And not destroy Armor instanatly.

Build 1.3.2.6:
	LexManos:
		Implmented Sengir's IPickupHandler.
		http://www.mod-buildcraft.com/forums/topic/hook-intercept-item-pickups-by-player-entities/?view=all

Build 1.3.2.5:
	LexManos:
		Merged in the change to ISpecialArmor to introduce the DamageSource argument.
		As well as the concept of damage absorption vs reduction.

Build 1.3.2.4:
	LexManos:
		Created a Entity tracking ans spawning system.
		Mod creators should call MinecraftForge.registerEntity to register a entity.
		All entity ID numbers are Mod Unique. Meaning two mods can have Entity #1.
		Added client and server side packet handlers for the 'Forge' channel. For use in internal packets such as the new Spawn packet.
		Updated the build scripts to copy over unique server source files now that there actually are some.
		For modders:
		  If you have a entity that used MLMP's 'owner' system, you should have your entity implement IThrowableEntity
		  If you have a entity that implments MLMLP's ISpawnable, you should implement ISpawnHandler.
		They provide the same functionality, just in a cleaner, more orginized way and will be the method used when we eventually drop MLMP.

Build 1.3.2.3:
	LexManos: Fixed return value for un/registerChannel. Now returns properly indicate when un/register commands should be sent.

Build 1.3.2.2:
	LexManos:
		Setup .gitignore for eclipse bin dirs.
		Fixed line endings in install.sh
		Added mod_MinecraftForge for simpler logging of minecraft version in crash reports
		Added new hooks for connection events, See IConnectionHandler for more details.
		Added Packet250CustomPayload handeling and channel registraction management, see MessageManager and IPacketHandler for more details.
		Forge now uses unsed fields in C->S Packet1Login to identify itself. None Forge clients will get a graceful disconnect message instead of the 'Unknown packet 230'
#!/bin/sh

#
# Copyright � 2015-2021 the original authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      https://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

##############################################################################
#
#   Gradle start up script for POSIX generated by Gradle.
#
#   Important for running:
#
#   (1) You need a POSIX-compliant shell to run this script. If your /bin/sh is
#       noncompliant, but you have some other compliant shell such as ksh or
#       bash, then to run this script, type that shell name before the whole
#       command line, like:
#
#           ksh Gradle
#
#       Busybox and similar reduced shells will NOT work, because this script
#       requires all of these POSIX shell features:
#         * functions;
#         * expansions �$var�, �${var}�, �${var:-default}�, �${var+SET}�,
#           �${var#prefix}�, �${var%suffix}�, and �$( cmd )�;
#         * compound commands having a testable exit status, especially �case�;
#         * various built-in commands including �command�, �set�, and �ulimit�.
#
#   Important for patching:
#
#   (2) This script targets any POSIX shell, so it avoids extensions provided
#       by Bash, Ksh, etc; in particular arrays are avoided.
#
#       The "traditional" practice of packing multiple parameters into a
#       space-separated string is a well documented source of bugs and security
#       problems, so this is (mostly) avoided, by progressively accumulating
#       options in "$@", and eventually passing that to Java.
#
#       Where the inherited environment variables (DEFAULT_JVM_OPTS, JAVA_OPTS,
#       and GRADLE_OPTS) rely on word-splitting, this is performed explicitly;
#       see the in-line comments for details.
#
#       There are tweaks for specific operating systems such as AIX, CygWin,
#       Darwin, MinGW, and NonStop.
#
#   (3) This script is generated from the Groovy template
#       https://github.com/gradle/gradle/blob/master/subprojects/plugins/src/main/resources/org/gradle/api/internal/plugins/unixStartScript.txt
#       within the Gradle project.
#
#       You can find Gradle at https://github.com/gradle/gradle/.
#
##############################################################################

# Attempt to set APP_HOME

# Resolve links: $0 may be a link
app_path=$0

# Need this for daisy-chained symlinks.
while
    APP_HOME=${app_path%"${app_path##*/}"}  # leaves a trailing /; empty if no leading path
    [ -h "$app_path" ]
do
    ls=$( ls -ld "$app_path" )
    link=${ls#*' -> '}
    case $link in             #(
      /*)   app_path=$link ;; #(
      *)    app_path=$APP_HOME$link ;;
    esac
done

APP_HOME=$( cd "${APP_HOME:-./}" && pwd -P ) || exit

APP_NAME="Gradle"
APP_BASE_NAME=${0##*/}

# Add default JVM options here. You can also use JAVA_OPTS and GRADLE_OPTS to pass JVM options to this script.
DEFAULT_JVM_OPTS='"-Xmx64m" "-Xms64m"'

# Use the maximum available, or set MAX_FD != -1 to use that value.
MAX_FD=maximum

warn () {
    echo "$*"
} >&2

die () {
    echo
    echo "$*"
    echo
    exit 1
} >&2

# OS specific support (must be 'true' or 'false').
cygwin=false
msys=false
darwin=false
nonstop=false
case "$( uname )" in                #(
  CYGWIN* )         cygwin=true  ;; #(
  Darwin* )         darwin=true  ;; #(
  MSYS* | MINGW* )  msys=true    ;; #(
  NONSTOP* )        nonstop=true ;;
esac

CLASSPATH=$APP_HOME/gradle/wrapper/gradle-wrapper.jar


# Determine the Java command to use to start the JVM.
if [ -n "$JAVA_HOME" ] ; then
    if [ -x "$JAVA_HOME/jre/sh/java" ] ; then
        # IBM's JDK on AIX uses strange locations for the executables
        JAVACMD=$JAVA_HOME/jre/sh/java
    else
        JAVACMD=$JAVA_HOME/bin/java
    fi
    if [ ! -x "$JAVACMD" ] ; then
        die "ERROR: JAVA_HOME is set to an invalid directory: $JAVA_HOME

Please set the JAVA_HOME variable in your environment to match the
location of your Java installation."
    fi
else
    JAVACMD=java
    which java >/dev/null 2>&1 || die "ERROR: JAVA_HOME is not set and no 'java' command could be found in your PATH.

Please set the JAVA_HOME variable in your environment to match the
location of your Java installation."
fi

# Increase the maximum file descriptors if we can.
if ! "$cygwin" && ! "$darwin" && ! "$nonstop" ; then
    case $MAX_FD in #(
      max*)
        MAX_FD=$( ulimit -H -n ) ||
            warn "Could not query maximum file descriptor limit"
    esac
    case $MAX_FD in  #(
      '' | soft) :;; #(
      *)
        ulimit -n "$MAX_FD" ||
            warn "Could not set maximum file descriptor limit to $MAX_FD"
    esac
fi

# Collect all arguments for the java command, stacking in reverse order:
#   * args from the command line
#   * the main class name
#   * -classpath
#   * -D...appname settings
#   * --module-path (only if needed)
#   * DEFAULT_JVM_OPTS, JAVA_OPTS, and GRADLE_OPTS environment variables.

# For Cygwin or MSYS, switch paths to Windows format before running java
if "$cygwin" || "$msys" ; then
    APP_HOME=$( cygpath --path --mixed "$APP_HOME" )
    CLASSPATH=$( cygpath --path --mixed "$CLASSPATH" )

    JAVACMD=$( cygpath --unix "$JAVACMD" )

    # Now convert the arguments - kludge to limit ourselves to /bin/sh
    for arg do
        if
            case $arg in                                #(
              -*)   false ;;                            # don't mess with options #(
              /?*)  t=${arg#/} t=/${t%%/*}              # looks like a POSIX filepath
                    [ -e "$t" ] ;;                      #(
              *)    false ;;
            esac
        then
            arg=$( cygpath --path --ignore --mixed "$arg" )
        fi
        # Roll the args list around exactly as many times as the number of
        # args, so each arg winds up back in the position where it started, but
        # possibly modified.
        #
        # NB: a `for` loop captures its iteration list before it begins, so
        # changing the positional parameters here affects neither the number of
        # iterations, nor the values presented in `arg`.
        shift                   # remove old arg
        set -- "$@" "$arg"      # push replacement arg
    done
fi

# Collect all arguments for the java command;
#   * $DEFAULT_JVM_OPTS, $JAVA_OPTS, and $GRADLE_OPTS can contain fragments of
#     shell script including quotes and variable substitutions, so put them in
#     double quotes to make sure that they get re-expanded; and
#   * put everything else in single quotes, so that it's not re-expanded.

set -- \
        "-Dorg.gradle.appname=$APP_BASE_NAME" \
        -classpath "$CLASSPATH" \
        org.gradle.wrapper.GradleWrapperMain \
        "$@"

# Use "xargs" to parse quoted args.
#
# With -n1 it outputs one arg per line, with the quotes and backslashes removed.
#
# In Bash we could simply go:
#
#   readarray ARGS < <( xargs -n1 <<<"$var" ) &&
#   set -- "${ARGS[@]}" "$@"
#
# but POSIX shell has neither arrays nor command substitution, so instead we
# post-process each arg (as a line of input to sed) to backslash-escape any
# character that might be a shell metacharacter, then use eval to reverse
# that process (while maintaining the separation between arguments), and wrap
# the whole thing up as a single "set" statement.
#
# This will of course break if any of these variables contains a newline or
# an unmatched quote.
#

eval "set -- $(
        printf '%s\n' "$DEFAULT_JVM_OPTS $JAVA_OPTS $GRADLE_OPTS" |
        xargs -n1 |
        sed ' s~[^-[:alnum:]+,./:=@_]~\\&~g; ' |
        tr '\n' ' '
    )" '"$@"'

exec "$JAVACMD" "$@"
<?xml version="1.0" encoding="UTF-8"?>
<module org.jetbrains.idea.maven.project.MavenProjectsManager.isMavenModule="true" type="JAVA_MODULE" version="4">
  <component name="FacetManager">
    <facet type="minecraft" name="Minecraft">
      <configuration>
        <autoDetectTypes>
          <platformType>SPIGOT</platformType>
        </autoDetectTypes>
      </configuration>
    </facet>
  </component>
  <component name="NewModuleRootManager" LANGUAGE_LEVEL="JDK_1_8">
    <output url="file://$MODULE_DIR$/target/classes" />
    <output-test url="file://$MODULE_DIR$/target/test-classes" />
    <content url="file://$MODULE_DIR$">
      <sourceFolder url="file://$MODULE_DIR$/src/main/java" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/src/main/resources" type="java-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/test/java" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/test/resources" type="java-test-resource" />
      <excludeFolder url="file://$MODULE_DIR$/target" />
    </content>
    <orderEntry type="inheritedJdk" />
    <orderEntry type="sourceFolder" forTests="false" />
    <orderEntry type="library" scope="PROVIDED" name="Maven: org.spigotmc:spigot:1.8.8-R0.1-SNAPSHOT" level="project" />
  </component>
</module>
<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>
    <groupId>me.illuminator3</groupId>
    <artifactId>AdvancedAntiReach</artifactId>
    <version>1.0-SNAPSHOT</version>
    <packaging>jar</packaging>
    <name>AdvancedAntiReach</name>
    <properties>
        <java.version>1.8</java.version>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
    </properties>
    <build>
        <finalName>${project.artifactId}</finalName>
        <defaultGoal>clean package</defaultGoal>
        <plugins>
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-compiler-plugin</artifactId>
                <version>3.7.0</version>
                <configuration>
                    <source>${java.version}</source>
                    <target>${java.version}</target>
                </configuration>
            </plugin>
        </plugins>
        <resources>
            <resource>
                <directory>src/main/resources</directory>
                <filtering>true</filtering>
            </resource>
        </resources>
    </build>
    <repositories>
        <repository>
            <id>spigotmc-repo</id>
            <url>https://hub.spigotmc.org/nexus/content/repositories/snapshots/</url>
        </repository>
        <repository>
            <id>sonatype</id>
            <url>https://oss.sonatype.org/content/repositories/snapshots</url>
        </repository>
    </repositories>
    <dependencies>
        <!-- spigot api + nms -->
        <dependency>
            <groupId>org.spigotmc</groupId>
            <artifactId>spigot</artifactId>
            <version>1.8.8-R0.1-SNAPSHOT</version>
            <scope>provided</scope>
        </dependency>
    </dependencies>
</project>
package io.github.astramgg-miuanticheat.detection.checks.damage.reach;

import io.github.astramgg-miuanticheat.detection.CheckType;
import io.github.astramgg-miuanticheat.detection.checks.Check;
import io.github.astramgg-miuanticheat.info.Profile;

public class Reach extends Check {

	public Reach(Profile profile) {
		super(profile, CheckType.REACH);

		versions.add(new ReachA(this));
	}

}

// For those who want the bleeding edge
buildscript {
    repositories {
        jcenter()
        maven {
            name = "forge"
            url = "http://files.minecraftforge.net/maven"
        }
    }
    dependencies {
        classpath 'net.minecraftforge.gradle:ForgeGradle:2.1-SNAPSHOT'
    }
}
apply plugin: 'net.minecraftforge.gradle.forge'

/*
// for people who want stable - not yet functional for MC 1.8.8 - we require the forgegradle 2.1 snapshot
plugins {
    id "net.minecraftforge.gradle.forge" version "2.0.2"
}
*/
version = "1.0"
group= "com.yourname.modid" // http://maven.apache.org/guides/mini/guide-naming-conventions.html
archivesBaseName = "modid"

minecraft {
    version = "1.8.9-11.15.1.1722"
    runDir = "run"
    
    // the mappings can be changed at any time, and must be in the following format.
    // snapshot_YYYYMMDD   snapshot are built nightly.
    // stable_#            stables are built at the discretion of the MCP team.
    // Use non-default mappings at your own risk. they may not allways work.
    // simply re-run your setup task after changing the mappings to update your workspace.
    mappings = "stable_20"
    // makeObfSourceJar = false // an Srg named sources jar is made by default. uncomment this to disable.
}

dependencies {
    // you may put jars on which you depend on in ./libs
    // or you may define them like so..
    //compile "some.group:artifact:version:classifier"
    //compile "some.group:artifact:version"
      
    // real examples
    //compile 'com.mod-buildcraft:buildcraft:6.0.8:dev'  // adds buildcraft to the dev env
    //compile 'com.googlecode.efficient-java-matrix-library:ejml:0.24' // adds ejml to the dev env

    // the 'provided' configuration is for optional dependencies that exist at compile-time but might not at runtime.
    //provided 'com.mod-buildcraft:buildcraft:6.0.8:dev'

    // the deobf configurations:  'deobfCompile' and 'deobfProvided' are the same as the normal compile and provided,
    // except that these dependencies get remapped to your current MCP mappings
    //deobfCompile 'com.mod-buildcraft:buildcraft:6.0.8:dev'
    //deobfProvided 'com.mod-buildcraft:buildcraft:6.0.8:dev'

    // for more info...
    // http://www.gradle.org/docs/current/userguide/artifact_dependencies_tutorial.html
    // http://www.gradle.org/docs/current/userguide/dependency_management.html

}

processResources
{
    // this will ensure that this task is redone when the versions change.
    inputs.property "version", project.version
    inputs.property "mcversion", project.minecraft.version

    // replace stuff in mcmod.info, nothing else
    from(sourceSets.main.resources.srcDirs) {
        include 'mcmod.info'
                
        // replace version and mcversion
        expand 'version':project.version, 'mcversion':project.minecraft.version
    }
        
    // copy everything else, thats not the mcmod.info
    from(sourceSets.main.resources.srcDirs) {
        exclude 'mcmod.info'
    }
}
#!/usr/bin/env bash

##############################################################################
##
##  Gradle start up script for UN*X
##
##############################################################################

# Add default JVM options here. You can also use JAVA_OPTS and GRADLE_OPTS to pass JVM options to this script.
DEFAULT_JVM_OPTS=""

APP_NAME="Gradle"
APP_BASE_NAME=`basename "$0"`

# Use the maximum available, or set MAX_FD != -1 to use that value.
MAX_FD="maximum"

warn ( ) {
    echo "$*"
}

die ( ) {
    echo
    echo "$*"
    echo
    exit 1
}

# OS specific support (must be 'true' or 'false').
cygwin=false
msys=false
darwin=false
case "`uname`" in
  CYGWIN* )
    cygwin=true
    ;;
  Darwin* )
    darwin=true
    ;;
  MINGW* )
    msys=true
    ;;
esac

# For Cygwin, ensure paths are in UNIX format before anything is touched.
if $cygwin ; then
    [ -n "$JAVA_HOME" ] && JAVA_HOME=`cygpath --unix "$JAVA_HOME"`
fi

# Attempt to set APP_HOME
# Resolve links: $0 may be a link
PRG="$0"
# Need this for relative symlinks.
while [ -h "$PRG" ] ; do
    ls=`ls -ld "$PRG"`
    link=`expr "$ls" : '.*-> \(.*\)$'`
    if expr "$link" : '/.*' > /dev/null; then
        PRG="$link"
    else
        PRG=`dirname "$PRG"`"/$link"
    fi
done
SAVED="`pwd`"
cd "`dirname \"$PRG\"`/" >&-
APP_HOME="`pwd -P`"
cd "$SAVED" >&-

CLASSPATH=$APP_HOME/gradle/wrapper/gradle-wrapper.jar

# Determine the Java command to use to start the JVM.
if [ -n "$JAVA_HOME" ] ; then
    if [ -x "$JAVA_HOME/jre/sh/java" ] ; then
        # IBM's JDK on AIX uses strange locations for the executables
        JAVACMD="$JAVA_HOME/jre/sh/java"
    else
        JAVACMD="$JAVA_HOME/bin/java"
    fi
    if [ ! -x "$JAVACMD" ] ; then
        die "ERROR: JAVA_HOME is set to an invalid directory: $JAVA_HOME

Please set the JAVA_HOME variable in your environment to match the
location of your Java installation."
    fi
else
    JAVACMD="java"
    which java >/dev/null 2>&1 || die "ERROR: JAVA_HOME is not set and no 'java' command could be found in your PATH.

Please set the JAVA_HOME variable in your environment to match the
location of your Java installation."
fi

# Increase the maximum file descriptors if we can.
if [ "$cygwin" = "false" -a "$darwin" = "false" ] ; then
    MAX_FD_LIMIT=`ulimit -H -n`
    if [ $? -eq 0 ] ; then
        if [ "$MAX_FD" = "maximum" -o "$MAX_FD" = "max" ] ; then
            MAX_FD="$MAX_FD_LIMIT"
        fi
        ulimit -n $MAX_FD
        if [ $? -ne 0 ] ; then
            warn "Could not set maximum file descriptor limit: $MAX_FD"
        fi
    else
        warn "Could not query maximum file descriptor limit: $MAX_FD_LIMIT"
    fi
fi

# For Darwin, add options to specify how the application appears in the dock
if $darwin; then
    GRADLE_OPTS="$GRADLE_OPTS \"-Xdock:name=$APP_NAME\" \"-Xdock:icon=$APP_HOME/media/gradle.icns\""
fi

# For Cygwin, switch paths to Windows format before running java
if $cygwin ; then
    APP_HOME=`cygpath --path --mixed "$APP_HOME"`
    CLASSPATH=`cygpath --path --mixed "$CLASSPATH"`

    # We build the pattern for arguments to be converted via cygpath
    ROOTDIRSRAW=`find -L / -maxdepth 1 -mindepth 1 -type d 2>/dev/null`
    SEP=""
    for dir in $ROOTDIRSRAW ; do
        ROOTDIRS="$ROOTDIRS$SEP$dir"
        SEP="|"
    done
    OURCYGPATTERN="(^($ROOTDIRS))"
    # Add a user-defined pattern to the cygpath arguments
    if [ "$GRADLE_CYGPATTERN" != "" ] ; then
        OURCYGPATTERN="$OURCYGPATTERN|($GRADLE_CYGPATTERN)"
    fi
    # Now convert the arguments - kludge to limit ourselves to /bin/sh
    i=0
    for arg in "$@" ; do
        CHECK=`echo "$arg"|egrep -c "$OURCYGPATTERN" -`
        CHECK2=`echo "$arg"|egrep -c "^-"`                                 ### Determine if an option

        if [ $CHECK -ne 0 ] && [ $CHECK2 -eq 0 ] ; then                    ### Added a condition
            eval `echo args$i`=`cygpath --path --ignore --mixed "$arg"`
        else
            eval `echo args$i`="\"$arg\""
        fi
        i=$((i+1))
    done
    case $i in
        (0) set -- ;;
        (1) set -- "$args0" ;;
        (2) set -- "$args0" "$args1" ;;
        (3) set -- "$args0" "$args1" "$args2" ;;
        (4) set -- "$args0" "$args1" "$args2" "$args3" ;;
        (5) set -- "$args0" "$args1" "$args2" "$args3" "$args4" ;;
        (6) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" ;;
        (7) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" "$args6" ;;
        (8) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" "$args6" "$args7" ;;
        (9) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" "$args6" "$args7" "$args8" ;;
    esac
fi

# Split up the JVM_OPTS And GRADLE_OPTS values into an array, following the shell quoting and substitution rules
function splitJvmOpts() {
    JVM_OPTS=("$@")
}
eval splitJvmOpts $DEFAULT_JVM_OPTS $JAVA_OPTS $GRADLE_OPTS
JVM_OPTS[${#JVM_OPTS[*]}]="-Dorg.gradle.appname=$APP_BASE_NAME"

exec "$JAVACMD" "${JVM_OPTS[@]}" -classpath "$CLASSPATH" org.gradle.wrapper.GradleWrapperMain "$@"
