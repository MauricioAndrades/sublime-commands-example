# sublime-commands-example

```js
[

  {"caption":"About","command":"show_about_window"},

  {"caption":"Bookmarks: Clear All","command":"clear_bookmarks"},

  {"caption":"Bookmarks: Select All","command":"select_all_bookmarks"},

  {"caption":"Bookmarks: Select Next","command":"next_bookmark"},

  {"caption":"Bookmarks: Select Previous","command":"prev_bookmark"},

  {"caption":"Bookmarks: Toggle","command":"toggle_bookmark"},

  {"caption":"brh: (Debug) Filter Rules by Key","command":"bh_debug_rule","args":{"filter_key":true}},

  {"caption":"brh: (Debug) Show Merged Rules","command":"bh_debug_rule"},

  {"caption":"brh: Disable Debug Mode","command":"bh_debug","args":{"set_value":false}},

  {"caption":"brh: Enable Debug Mode","command":"bh_debug","args":{"set_value":true}},

  {"caption":"brh: Fold Bracket Content","command":"bh_async_key","args":{"plugin":{"type":["__all__"],"command":"bh_modules.foldbracket"}}},

  {"caption":"brh: Jump to Left Bracket","command":"bh_async_key","args":{"no_outside_adj":null,"no_block_mode":null,"lines":true,"plugin":{"type":["__all__"],"command":"bh_modules.bracketselect","args":{"select":"left"}}}},

  {"caption":"brh: Jump to Right Bracket","command":"bh_async_key","args":{"no_outside_adj":null,"no_block_mode":null,"lines":true,"plugin":{"type":["__all__"],"command":"bh_modules.bracketselect","args":{"select":"right"}}}},

  {"caption":"brh: Match Brackets (ignore threshold)","command":"bh_async_key","args":{"lines":true}},

  {"caption":"brh: Remove Brackets","command":"bh_remove_brackets"},

  {"caption":"brh: Select Bracket Content with Brackets","command":"bh_async_key","args":{"no_outside_adj":null,"lines":true,"plugin":{"type":["__all__"],"command":"bh_modules.bracketselect","args":{"always_include_brackets":true}}}},

  {"caption":"brh: Select Bracket Content","command":"bh_async_key","args":{"no_outside_adj":null,"lines":true,"plugin":{"type":["__all__"],"command":"bh_modules.bracketselect"}}},

  {"caption":"brh: Select Next Attribute (left)","command":"bh_async_key","args":{"plugin":{"type":["cfml","html","angle"],"command":"bh_modules.tagattrselect","args":{"direction":"left"}}}},

  {"caption":"brh: Select Next Attribute (right)","command":"bh_async_key","args":{"plugin":{"type":["cfml","html","angle"],"command":"bh_modules.tagattrselect","args":{"direction":"right"}}}},

  {"caption":"brh: Select Tag Name (closing and opening)","command":"bh_async_key","args":{"plugin":{"type":["cfml","html","angle"],"command":"bh_modules.tagnameselect"}}},

  {"caption":"brh: Swap Brackets","command":"swap_brackets","args":{"async":true}},

  {"caption":"brh: Swap Quotes","command":"bh_async_key","args":{"lines":true,"plugin":{"type":["single_quote","double_quote","py_single_quote","py_double_quote"],"command":"bh_modules.swapquotes"}}},

  {"caption":"brh: Toggle Global Enable","command":"bh_toggle_enable"},

  {"caption":"brh: Toggle High Visibility Mode","command":"bh_toggle_high_visibility"},

  {"caption":"brh: Toggle String Bracket Escape Mode","command":"bh_toggle_string_escape_mode"},

  {"caption":"brh: Wrap Selections with Brackets","command":"wrap_brackets"},

  {"caption":"Build: Run Build","command":"build","args":{"variant":"Run"}},

  {"caption":"Build: Show Results","command":"show_panel","args":{"panel":"output.exec"}},

  {"caption":"chain: cleanup js","command":"chain","args":{"commands":[["js_format"],["delte_empty_lines"],["jshint"]]}},

  {"caption":"Changelog","command":"show_changelog"},

  {"caption":"Check for Updates","command":"update_check"},

  {"caption":"Close Window","command":"close_window"},

  {"caption":"Code Folding: Fold Tag Attributes","command":"fold_tag_attributes"},

  {"caption":"Code Folding: Fold","command":"fold"},

  {"caption":"Code Folding: Unfold All","command":"unfold_all"},

  {"caption":"Code Folding: Unfold","command":"unfold"},

  {"caption":"Color Picker","command":"color_pick"},

  {"caption":"commands-default","command":"edit_command_palette_open_file","args":{"file":"${packages}/Default/Default.sublime-commands"}},

  {"caption":"commands-user","command":"edit_command_palette_open_user"},

  {"caption":"Convert Case: Lower Case","command":"lower_case"},

  {"caption":"Convert Case: Swap Case","command":"swap_case"},

  {"caption":"Convert Case: Title Case","command":"title_case"},

  {"caption":"Convert Case: Upper Case","command":"upper_case"},

  {"caption":"Disable Python Fix Imports (until restart)","command":"disable_python_fiximports"},

  {"caption":"Disable Python Fix Imports for this file (until restart)","command":"disable_python_fiximports_for_file"},

  {"caption":"Edit: Copy","command":"copy"},

  {"caption":"Edit: Cut","command":"cut"},

  {"caption":"Edit: Duplicate Line","command":"duplicate_line"},

  {"caption":"Edit: Join Lines","command":"join_lines"},

  {"caption":"Edit: Paste and Indent","command":"paste_and_indent"},

  {"caption":"Edit: Paste from History","command":"paste_from_history"},

  {"caption":"Edit: Paste","command":"paste"},

  {"caption":"Edit: Redo or Repeat","command":"redo_or_repeat"},

  {"caption":"Edit: Swap Line Down","command":"swap_line_down"},

  {"caption":"Edit: Swap Line Up","command":"swap_line_up"},

  {"caption":"Edit: Undo","command":"undo"},

  {"caption":"em: Balance (inward)","command":"run_emmet_action","args":{"action":"balance_inward"}},

  {"caption":"em: Balance (outward)","command":"run_emmet_action","args":{"action":"balance_outward"}},

  {"caption":"em: Decrement Number by 0.1","command":"run_emmet_action","args":{"action":"decrement_number_by_01"}},

  {"caption":"em: Decrement Number by 1","command":"run_emmet_action","args":{"action":"decrement_number_by_1"}},

  {"caption":"em: Decrement Number by 10","command":"run_emmet_action","args":{"action":"decrement_number_by_10"}},

  {"caption":"em: Encode-Decode Image to data:URL","command":"run_emmet_action","args":{"action":"encode_decode_data_url"}},

  {"caption":"em: Evaluate Math Expression","command":"run_emmet_action","args":{"action":"evaluate_math_expression"}},

  {"caption":"em: Expand Abbreviation","command":"run_emmet_action","args":{"action":"expand_abbreviation"}},

  {"caption":"em: Go to Matching Pair","command":"run_emmet_action","args":{"action":"matching_pair"}},

  {"caption":"em: Increment Number by 0.1","command":"run_emmet_action","args":{"action":"increment_number_by_01"}},

  {"caption":"em: Increment Number by 1","command":"run_emmet_action","args":{"action":"increment_number_by_1"}},

  {"caption":"em: Increment Number by 10","command":"run_emmet_action","args":{"action":"increment_number_by_10"}},

  {"caption":"em: Merge Lines","command":"run_emmet_action","args":{"action":"merge_lines"}},

  {"caption":"em: Next Edit Point","command":"run_emmet_action","args":{"action":"next_edit_point"}},

  {"caption":"em: Previous Edit Point","command":"run_emmet_action","args":{"action":"prev_edit_point"}},

  {"caption":"em: Reflect CSS Value","command":"run_emmet_action","args":{"action":"reflect_css_value"}},

  {"caption":"em: Reload Extensions","command":"emmet_reset_context"},

  {"caption":"em: Remove Tag","command":"run_emmet_action","args":{"action":"remove_tag"}},

  {"caption":"em: Rename Tag","command":"rename_tag"},

  {"caption":"em: Select Next Item","command":"run_emmet_action","args":{"action":"select_next_item"}},

  {"caption":"em: Select Previous Item","command":"run_emmet_action","args":{"action":"select_previous_item"}},

  {"caption":"em: Split-Join Tag","command":"run_emmet_action","args":{"action":"split_join_tag"}},

  {"caption":"em: Toggle Comment","command":"run_emmet_action","args":{"action":"toggle_comment"}},

  {"caption":"em: Update Image Size","command":"run_emmet_action","args":{"action":"update_image_size"}},

  {"caption":"em: Wrap With Abbreviation","command":"wrap_as_you_type"},

  {"caption":"Enable Python Fix Imports (until restart)","command":"enable_python_fiximports"},

  {"caption":"Enable Python Fix Imports for this file (until restart)","command":"enable_python_fiximports_for_file"},

  {"caption":"Exit Sublime Text","command":"exit"},

  {"caption":"expand: br","command":"expand_selection","args":{"to":"brackets"}},

  {"caption":"expand: indentation","command":"expand_selection","args":{"to":"indentation"}},

  {"caption":"expand: p","command":"expand_selection_to_paragraph"},

  {"caption":"expand: scope","command":"expand_selection","args":{"to":"scope"}},

  {"caption":"expand: tag","command":"expand_selection","args":{"to":"tag"}},

  {"caption":"Extract Sublime Package: Extract all packages","command":"extract_all_packages"},

  {"caption":"Extract Sublime Package: Extract open Package File","command":"extract_current_package_file"},

  {"caption":"File: Close All","command":"close_all"},

  {"caption":"File: Close","command":"close"},

  {"caption":"File: Copy as Tag a","command":"side_bar_copy_tag_ahref"},

  {"caption":"File: Copy as Tag script","command":"side_bar_copy_tag_script"},

  {"caption":"File: Copy as Tag style","command":"side_bar_copy_tag_style"},

  {"caption":"File: Copy Name Encoded","command":"side_bar_copy_name_encoded"},

  {"caption":"File: Copy Name","command":"side_bar_copy_name"},

  {"caption":"File: Copy Path as URI","command":"side_bar_copy_path_encoded"},

  {"caption":"File: Copy Path From Project Encoded","command":"side_bar_copy_path_absolute_from_project_encoded"},

  {"caption":"File: Copy Path From Project","command":"side_bar_copy_path_absolute_from_project"},

  {"caption":"File: Copy Path","command":"side_bar_copy_path"},

  {"caption":"File: Copy URL","command":"side_bar_copy_url"},

  {"caption":"File: Delete","command":"side_bar_delete"},

  {"caption":"File: Duplicate","command":"side_bar_duplicate"},

  {"caption":"File: Locate","command":"reveal_in_side_bar"},

  {"caption":"File: Move","command":"side_bar_move"},

  {"caption":"File: New File Relative to Current View","command":"side_bar_new_file"},

  {"caption":"File: New File Relative to Project Root","command":"side_bar_new_file2"},

  {"caption":"File: New File","command":"new_file"},

  {"caption":"File: New Folder Relative to Current View","command":"side_bar_new_directory"},

  {"caption":"File: New Folder Relative to Project Root","command":"side_bar_new_directory2"},

  {"caption":"File: New View into File","command":"clone_file"},

  {"caption":"File: Open In Browser - Production Server","command":"side_bar_open_in_browser","args":{"paths":[],"type":"production"}},

  {"caption":"File: Open In Browser - Testing Server","command":"side_bar_open_in_browser","args":{"paths":[],"type":"testing"}},

  {"caption":"File: Rename","command":"side_bar_rename"},

  {"caption":"File: Reopen Closed File","command":"reopen_last_file"},

  {"caption":"File: Reveal","command":"side_bar_reveal"},

  {"caption":"File: Revert","command":"revert"},

  {"caption":"File: Save All","command":"save_all"},

  {"caption":"File: Save","command":"save"},

  {"caption":"File: Search Files","command":"side_bar_find_files_path_containing"},

  {"caption":"Find in Files…","command":"show_panel","args":{"panel":"find_in_files"}},

  {"caption":"Find Next","command":"find_next"},

  {"caption":"Find Previous","command":"find_prev"},

  {"caption":"Find…","command":"show_panel","args":{"panel":"find","reverse":false}},

  {"caption":"Font: Decrease Font Size","command":"decrease_font_size"},

  {"caption":"Font: Increase Font Size","command":"increase_font_size"},

  {"caption":"Font: Reset Font Size","command":"reset_font_size"},

  {"caption":"git flow: feature finish","command":"git_flow_feature_finish"},

  {"caption":"git flow: feature start","command":"git_flow_feature_start"},

  {"caption":"git flow: hotfix finish","command":"git_flow_hotfix_finish"},

  {"caption":"git flow: hotfix start","command":"git_flow_hotfix_start"},

  {"caption":"git flow: release finish","command":"git_flow_release_finish"},

  {"caption":"git flow: release start","command":"git_flow_release_start"},

  {"caption":"Git: Add Selected Hunk","command":"git_add_selected_hunk"},

  {"caption":"Git: Add","command":"git_raw","args":{"append_current_file":true,"command":"git add"}},

  {"caption":"Git: Amend Commit","command":"git_commit_amend"},

  {"caption":"Git: Blame","command":"git_blame"},

  {"caption":"Git: Change Branch","command":"git_branch"},

  {"caption":"Git: Checkout Current File","command":"git_raw","args":{"append_current_file":true,"command":"git checkout"}},

  {"caption":"Git: Checkout Tag","command":"git_checkout_tag"},

  {"caption":"Git: Commit History","command":"git_commit_history"},

  {"caption":"Git: Commit Selected Hunk","command":"git_commit_selected_hunk"},

  {"caption":"Git: Commit","command":"git_commit"},

  {"caption":"Git: Custom Command","command":"git_custom"},

  {"caption":"Git: Delete Branch","command":"git_delete_branch"},

  {"caption":"Git: Delete Tag","command":"git_delete_tag"},

  {"caption":"Git: Diff All Files (ignore Whitespace)","command":"git_diff_all","args":{"ignore_whitespace":true}},

  {"caption":"Git: Diff All Files","command":"git_diff_all"},

  {"caption":"Git: Diff Current File (ignore Whitespace)","command":"git_diff","args":{"ignore_whitespace":true}},

  {"caption":"Git: Diff Current File","command":"git_diff"},

  {"caption":"Git: Diff Staged Files (ignore Whitespace)","command":"git_diff_commit","args":{"ignore_whitespace":true}},

  {"caption":"Git: Diff Staged Files","command":"git_diff_commit"},

  {"caption":"Git: Diff Tool All","command":"git_raw","args":{"command":"git difftool","may_change_files":false}},

  {"caption":"Git: Diff Tool Current File Staged","command":"git_diff_tool_commit"},

  {"caption":"Git: Diff Tool Current File","command":"git_raw","args":{"append_current_file":true,"command":"git difftool","may_change_files":false}},

  {"caption":"Git: Diff Tool Staged","command":"git_diff_tool_commit_all"},

  {"caption":"Git: Document Selection","command":"git_document"},

  {"caption":"Git: Fetch","command":"git_raw","args":{"command":"git fetch","may_change_files":false}},

  {"caption":"Git: Gitk All","command":"git_gitk_all"},

  {"caption":"Git: Gitk This File","command":"git_gitk_this_file"},

  {"caption":"Git: Gitk","command":"git_gitk"},

  {"caption":"Git: Graph All","command":"git_graph_all"},

  {"caption":"Git: Graph Current File","command":"git_graph"},

  {"caption":"Git: Gui","command":"git_gui"},

  {"caption":"Git: Log All","command":"git_log_all"},

  {"caption":"Git: Log Current File","command":"git_log"},

  {"caption":"Git: Merge Branch","command":"git_merge"},

  {"caption":"Git: New Branch","command":"git_new_branch"},

  {"caption":"Git: New Tag","command":"git_new_tag"},

  {"caption":"Git: Open Modified Files","command":"git_open_modified_files"},

  {"caption":"Git: Open...","command":"git_open_file"},

  {"caption":"Git: Pull Current Branch","command":"git_pull_current_branch"},

  {"caption":"Git: Pull Using Rebase","command":"git_pull_rebase"},

  {"caption":"Git: Pull Using Rebase","command":"git_raw","args":{"command":"git pull --rebase"}},

  {"caption":"Git: Pull","command":"git_raw","args":{"command":"git pull"}},

  {"caption":"Git: Push Current Branch","command":"git_push_current_branch"},

  {"caption":"Git: Push Tags","command":"git_raw","args":{"command":"git push --tags","may_change_files":false}},

  {"caption":"Git: Push","command":"git_raw","args":{"command":"git push","may_change_files":false}},

  {"caption":"Git: Quick Commit","command":"git_quick_commit"},

  {"caption":"Git: Reset (hard) Head","command":"git_reset_hard_head"},

  {"caption":"Git: Reset (unstage) All","command":"git_raw","args":{"command":"git reset head","show_in":"suppress"}},

  {"caption":"Git: Reset (unstage) Current File","command":"git_raw","args":{"append_current_file":true,"command":"git reset head","show_in":"suppress"}},

  {"caption":"Git: Show Current File","command":"git_show"},

  {"caption":"Git: Show Tags","command":"git_show_tags"},

  {"caption":"Git: Stash Apply","command":"git_stash_apply"},

  {"caption":"Git: Stash Changes","command":"git_raw","args":{"command":"git stash"}},

  {"caption":"Git: Stash Drop","command":"git_stash_drop"},

  {"caption":"Git: Stash List","command":"git_stash_list"},

  {"caption":"Git: Stash Pop","command":"git_raw","args":{"command":"git stash pop"}},

  {"caption":"Git: Status","command":"git_status"},

  {"caption":"Git: Toggle Annotations","command":"git_toggle_annotations"},

  {"caption":"Git: Track Remote Branch","command":"git_track_remote_branch"},

  {"caption":"Git: Update Project Ignored Files","command":"git_update_ignore"},

  {"caption":"Git:add All","command":"git_raw","args":{"command":"git add -a"}},

  {"caption":"Git:add Choose","command":"git_add_choice"},

  {"caption":"Git:init","command":"git_init"},

  {"caption":"Goto: Anything…","command":"show_overlay","args":{"overlay":"goto","show_files":true}},

  {"caption":"Goto: Definition…","command":"goto_definition"},

  {"caption":"Goto: Line…","command":"show_overlay","args":{"overlay":"goto","text":":"}},

  {"caption":"Goto: Symbol in Project…","command":"goto_symbol_in_project"},

  {"caption":"Goto: Symbol…","command":"show_overlay","args":{"overlay":"goto","text":"@"}},

  {"caption":"Group: Close Group","command":"close_pane"},

  {"caption":"Group: Focus Group 1","command":"focus_group","args":{"group":0}},

  {"caption":"Group: Focus Group 2","command":"focus_group","args":{"group":1}},

  {"caption":"Group: Focus Group 3","command":"focus_group","args":{"group":2}},

  {"caption":"Group: Focus Group 4","command":"focus_group","args":{"group":3}},

  {"caption":"Group: Focus Next Group","command":"focus_neighboring_group"},

  {"caption":"Group: Focus Previous Group","command":"focus_neighboring_group","args":{"forward":false}},

  {"caption":"Group: Move to Group 1","command":"move_to_group","args":{"group":0}},

  {"caption":"Group: Move to Group 2","command":"move_to_group","args":{"group":1}},

  {"caption":"Group: Move to Group 3","command":"move_to_group","args":{"group":2}},

  {"caption":"Group: Move to Group 4","command":"move_to_group","args":{"group":3}},

  {"caption":"Group: Move to New Group","command":"new_pane"},

  {"caption":"Group: Move to Next Group","command":"move_to_neighboring_group"},

  {"caption":"Group: Move to Previous Group","command":"move_to_neighboring_group","args":{"forward":false}},

  {"caption":"Group: New Group","command":"new_pane","args":{"move":false}},

  {"caption":"Gulp (silent)","command":"gulp","args":{"silent":true}},

  {"caption":"Gulp","command":"gulp"},

  {"caption":"Gulp: Delete cache","command":"gulp_delete_cache"},

  {"caption":"Gulp: Exit editor killing running tasks","command":"gulp_exit"},

  {"caption":"Gulp: Hide panel","command":"gulp_hide_panel"},

  {"caption":"Gulp: Kill running tasks","command":"gulp_kill"},

  {"caption":"Gulp: List plugins","command":"gulp_plugins"},

  {"caption":"Gulp: Run arbitrary task","command":"gulp_arbitrary"},

  {"caption":"Gulp: Run last task","command":"gulp_last"},

  {"caption":"Gulp: Show panel","command":"gulp_show_panel"},

  {"caption":"HTML: Encode Special Characters","command":"encode_html_entities"},

  {"caption":"HTML: Wrap Selection With Tag","command":"insert_snippet","args":{"name":"Packages/XML/long-tag.sublime-snippet"}},

  {"caption":"Incremental Find","command":"show_panel","args":{"panel":"incremental_find","reverse":false}},

  {"caption":"Indent: Convert to Spaces","command":"expand_tabs","args":{"set_translate_tabs":true}},

  {"caption":"Indent: Convert to Tabs","command":"unexpand_tabs","args":{"set_translate_tabs":true}},

  {"caption":"Indent: Reindent Lines","command":"reindent","args":{"single_line":false}},

  {"caption":"Indentation: Guess Settings From Buffer","command":"detect_indentation"},

  {"caption":"Indentation: Indent","command":"indent"},

  {"caption":"Indentation: Tab Width: 1","command":"set_setting","args":{"setting":"tab_size","value":1}},

  {"caption":"Indentation: Tab Width: 2","command":"set_setting","args":{"setting":"tab_size","value":2}},

  {"caption":"Indentation: Tab Width: 3","command":"set_setting","args":{"setting":"tab_size","value":3}},

  {"caption":"Indentation: Tab Width: 4","command":"set_setting","args":{"setting":"tab_size","value":4}},

  {"caption":"Indentation: Tab Width: 5","command":"set_setting","args":{"setting":"tab_size","value":5}},

  {"caption":"Indentation: Tab Width: 6","command":"set_setting","args":{"setting":"tab_size","value":6}},

  {"caption":"Indentation: Tab Width: 7","command":"set_setting","args":{"setting":"tab_size","value":7}},

  {"caption":"Indentation: Tab Width: 8","command":"set_setting","args":{"setting":"tab_size","value":8}},

  {"caption":"Indentation: Unindent","command":"unindent"},

  {"caption":"Indentation: Use Spaces","command":"toggle_setting","args":{"setting":"translate_tabs_to_spaces"}},

  {"caption":"JoinLinesEnhanced: join","command":"join_lines_enhanced"},

  {"caption":"JSONtree: show tree","command":"json_tree"},

  {"caption":"Jump Back","command":"jump_back"},

  {"caption":"Jump Forward","command":"jump_forward"},

  {"caption":"Jump to Matching Bracket","command":"move_to","args":{"to":"brackets"}},

  {"caption":"Layout: 2 Columns","command":"set_layout","args":{"cols":[0,0.5,1],"rows":[0,1],"cells":[[0,0,1,1],[1,0,2,1]]}},

  {"caption":"Layout: 2 Rows","command":"set_layout","args":{"cols":[0,1],"rows":[0,0.5,1],"cells":[[0,0,1,1],[0,1,1,2]]}},

  {"caption":"Layout: 3 Columns","command":"set_layout","args":{"cols":[0,0.33,0.66,1],"rows":[0,1],"cells":[[0,0,1,1],[1,0,2,1],[2,0,3,1]]}},

  {"caption":"Layout: 3 Rows","command":"set_layout","args":{"cols":[0,1],"rows":[0,0.33,0.66,1],"cells":[[0,0,1,1],[0,1,1,2],[0,2,1,3]]}},

  {"caption":"Layout: 4 Columns","command":"set_layout","args":{"cols":[0,0.25,0.5,0.75,1],"rows":[0,1],"cells":[[0,0,1,1],[1,0,2,1],[2,0,3,1],[3,0,4,1]]}},

  {"caption":"Layout: Grid","command":"set_layout","args":{"cols":[0,0.5,1],"rows":[0,0.5,1],"cells":[[0,0,1,1],[1,0,2,1],[0,1,1,2],[1,1,2,2]]}},

  {"caption":"Layout: Single","command":"set_layout","args":{"cols":[0,1],"rows":[0,1],"cells":[[0,0,1,1]]}},

  {"caption":"Line Endings: Mac OS 9","command":"set_line_ending","args":{"type":"cr"}},

  {"caption":"Line Endings: Unix","command":"set_line_ending","args":{"type":"unix"}},

  {"caption":"Line Endings: Windows","command":"set_line_ending","args":{"type":"windows"}},

  {"caption":"Macro: Playback Macro","command":"run_macro"},

  {"caption":"Macro: Record Macro","command":"toggle_record_macro"},

  {"caption":"Macro: Save Macro…","command":"save_macro"},

  {"caption":"Mark: Clear Mark","command":"clear_bookmarks","args":{"name":"mark"}},

  {"caption":"Mark: Delete to Mark","command":"delete_to_mark"},

  {"caption":"Mark: Select to Mark","command":"select_to_mark"},

  {"caption":"Mark: Set Mark","command":"set_mark"},

  {"caption":"Mark: Swap with Mark","command":"swap_with_mark"},

  {"caption":"Mark: Yank","command":"yank"},

  {"caption":"New Snippet…","command":"new_snippet"},

  {"caption":"New Window","command":"new_window"},

  {"caption":"Nodejs::Build Completions","command":"node_builddocs"},

  {"caption":"Nodejs::Debug::Run::Current File + Arguments","command":"node_drun_arguments"},

  {"caption":"Nodejs::Debug::Run::Current File","command":"node_drun"},

  {"caption":"Nodejs::Default File Settings","command":"open_file","args":{"file":"${packages}/Nodejs/Nodejs.sublime-settings"}},

  {"caption":"Nodejs::NPM::Command","command":"node_npm"},

  {"caption":"Nodejs::NPM::Install","command":"node_npm_install"},

  {"caption":"Nodejs::NPM::List","command":"node_npm_list"},

  {"caption":"Nodejs::NPM::Publish","command":"node_npm_publish"},

  {"caption":"Nodejs::NPM::Search","command":"node_npm_search"},

  {"caption":"Nodejs::NPM::Uninstall","command":"node_npm_uninstall"},

  {"caption":"Nodejs::NPM::Update","command":"node_npm_update"},

  {"caption":"Nodejs::Run::Current File + Arguments","command":"node_run_arguments"},

  {"caption":"Nodejs::Run::Current File","command":"node_run"},

  {"caption":"Nodejs::UglifyJS","command":"node_uglify"},

  {"caption":"Nodejs::User File Settings","command":"open_file","args":{"file":"${packages}/User/Nodejs.sublime-settings"}},

  {"caption":"packagectrl: Add Channel","command":"add_channel"},

  {"caption":"packagectrl: Add Repository","command":"add_repository"},

  {"caption":"packagectrl: Advanced Install Package","command":"advanced_install_package"},

  {"caption":"packagectrl: Create Package File","command":"create_package"},

  {"caption":"packagectrl: Disable Package","command":"disable_package"},

  {"caption":"packagectrl: Discover Packages","command":"discover_packages"},

  {"caption":"packagectrl: Enable Package","command":"enable_package"},

  {"caption":"packagectrl: Grab CA Certs","command":"grab_certs"},

  {"caption":"packagectrl: Install Local Dependency","command":"install_local_dependency"},

  {"caption":"packagectrl: Install Package","command":"install_package"},

  {"caption":"packagectrl: List Packages","command":"list_packages"},

  {"caption":"packagectrl: List Unmanaged Packages","command":"list_unmanaged_packages"},

  {"caption":"packagectrl: Remove Channel","command":"remove_channel"},

  {"caption":"packagectrl: Remove Package","command":"remove_package"},

  {"caption":"packagectrl: Remove Repository","command":"remove_repository"},

  {"caption":"packagectrl: Satisfy Dependencies","command":"satisfy_dependencies"},

  {"caption":"packagectrl: Tests","command":"package_control_tests"},

  {"caption":"packagectrl: Upgrade Package","command":"upgrade_package"},

  {"caption":"packagectrl: Upgrade/Overwrite All Packages","command":"upgrade_all_packages"},

  {"caption":"path: Copy File Directory","command":"copy_file_directory"},

  {"caption":"path: Copy File Name","command":"copy_file_name"},

  {"caption":"path: Copy File Path","command":"copy_path"},

  {"caption":"path: Copy Path Relative to Project","command":"copy_relative_path"},

  {"caption":"path: Insert Directory Relative to Project","command":"insert_relative_directory"},

  {"caption":"path: Insert File Directory","command":"insert_file_directory"},

  {"caption":"path: Insert File Name","command":"insert_file_name"},

  {"caption":"path: Insert File Path","command":"insert_file_path"},

  {"caption":"path: Insert Path Relative to Project","command":"insert_relative_path"},

  {"caption":"Permute Lines: Reverse","command":"permute_lines","args":{"operation":"reverse"}},

  {"caption":"Permute Lines: Shuffle","command":"permute_lines","args":{"operation":"shuffle"}},

  {"caption":"Permute Lines: Unique","command":"permute_lines","args":{"operation":"unique"}},

  {"caption":"Permute Selections: Reverse","command":"permute_selection","args":{"operation":"reverse"}},

  {"caption":"Permute Selections: Shuffle","command":"permute_selection","args":{"operation":"shuffle"}},

  {"caption":"Permute Selections: Sort (Case Sensitive)","command":"sort_selection","args":{"case_sensitive":true}},

  {"caption":"Permute Selections: Sort","command":"sort_selection","args":{"case_sensitive":false}},

  {"caption":"Permute Selections: Unique","command":"permute_selection","args":{"operation":"unique"}},

  {"caption":"Preferences: Browse Packages","command":"open_dir","args":{"dir":"$packages"}},

  {"caption":"Preferences: Key Bindings - Default","command":"open_file","args":{"file":"${packages}/Default/Default (OSX).sublime-keymap","platform":"OSX"}},

  {"caption":"Preferences: Key Bindings - User","command":"open_file","args":{"file":"${packages}/User/Default (OSX).sublime-keymap","platform":"OSX"}},

  {"caption":"Preferences: Package Control Settings – Default","command":"open_file","args":{"file":"${packages}/Package Control/Package Control.sublime-settings"}},

  {"caption":"Preferences: Package Control Settings – User","command":"open_file","args":{"file":"${packages}/User/Package Control.sublime-settings"}},

  {"caption":"Preferences: Settings - Default","command":"open_file","args":{"file":"${packages}/Default/Preferences.sublime-settings"}},

  {"caption":"Preferences: Settings - User","command":"open_file","args":{"file":"${packages}/User/Preferences.sublime-settings"}},

  {"caption":"Preferences: SublimeLinter Key Bindings – Default","command":"open_file","args":{"file":"${packages}/SublimeLinter/Default (OSX).sublime-keymap","platform":"OSX"}},

  {"caption":"Preferences: SublimeLinter Key Bindings – User","command":"open_file","args":{"file":"${packages}/User/Default (OSX).sublime-keymap","platform":"OSX"}},

  {"caption":"Preferences: SublimeLinter Settings – Default","command":"open_file","args":{"file":"${packages}/SublimeLinter/SublimeLinter.sublime-settings"}},

  {"caption":"Preferences: SublimeLinter Settings – User","command":"open_file","args":{"file":"${packages}/User/SublimeLinter.sublime-settings"}},

  {"caption":"Preferences: Syntax Specific – User","command":"open_file_settings"},

  {"caption":"pjs: ./jq","command":"jq_pretty_json"},

  {"caption":"pjs: Format","command":"pretty_json"},

  {"caption":"pjs: Minify","command":"un_pretty_json"},

  {"caption":"pjs: Validate","command":"pretty_json_validate"},

  {"caption":"pjs: XML","command":"json_to_xml"},

  {"caption":"proj: Add Folder","command":"prompt_add_folder"},

  {"caption":"proj: Close Project","command":"close_workspace"},

  {"caption":"proj: Close","command":"close_workspace"},

  {"caption":"proj: Edit Project","command":"open_file","args":{"file":"${project}"}},

  {"caption":"proj: Edit","command":"side_bar_project_open_file"},

  {"caption":"proj: New Workspace for Project","command":"new_window_for_project"},

  {"caption":"proj: Open Project…","command":"prompt_open_project_or_workspace"},

  {"caption":"proj: Quick Switch Project…","command":"prompt_select_workspace"},

  {"caption":"proj: Refresh Folders","command":"refresh_folder_list"},

  {"caption":"proj: Remove all Folders from Project","command":"close_folder_list"},

  {"caption":"proj: Save As","command":"save_project_and_workspace_as"},

  {"caption":"proj: Switch Project…","command":"prompt_switch_project_or_workspace"},

  {"caption":"PRV: Edit Package Resource","command":"edit_package_file"},

  {"caption":"PRV: Extract Package","command":"extract_package"},

  {"caption":"PRV: Open Resource","command":"package_resource_viewer"},

  {"caption":"PRV: View Package Resource","command":"view_package_file"},

  {"caption":"Python Fix Imports","command":"python_fiximports"},

  {"caption":"Quick Add Next","command":"find_under_expand"},

  {"caption":"Quick Find All","command":"find_all_under"},

  {"caption":"Quick Find","command":"find_under"},

  {"caption":"Replace Next","command":"replace_next"},

  {"caption":"Replace…","command":"show_panel","args":{"panel":"replace","reverse":false}},

  {"caption":"Reveal Current File in Side Bar","command":"reveal_in_side_bar"},

  {"caption":"Rot13 Selection","command":"rot13"},

  {"caption":"Scope Hunter: Show Scope Under Cursor(s)","command":"get_selection_scope"},

  {"caption":"Scope Hunter: Toggle Instant Scoper","command":"toggle_selection_scope"},

  {"caption":"Scroll to Selection","command":"show_at_center"},

  {"caption":"sel: Add Next Line","command":"select_lines","args":{"forward":"true"}},

  {"caption":"sel: Add Previous Line","command":"select_lines","args":{"forward":"false"}},

  {"caption":"sel: Expand to Brackets","command":"expand_selection","args":{"to":"brackets"}},

  {"caption":"sel: Expand to Indentation","command":"expand_selection","args":{"to":"indentation"}},

  {"caption":"sel: Expand to Line","command":"expand_selection","args":{"to":"line"}},

  {"caption":"sel: Expand to Paragraph","command":"expand_selection_to_paragraph"},

  {"caption":"sel: Expand to Scope","command":"expand_selection","args":{"to":"scope"}},

  {"caption":"sel: Expand to Tag","command":"expand_selection","args":{"to":"tag"}},

  {"caption":"sel: Expand to Word","command":"find_under_expand"},

  {"caption":"sel: Invert Selection","command":"invert_selection"},

  {"caption":"sel: Redo Selection","command":"soft_redo"},

  {"caption":"sel: Select All","command":"select_all"},

  {"caption":"sel: Single Selection","command":"single_selection"},

  {"caption":"sel: Split into Lines","command":"split_selection_into_lines"},

  {"caption":"sel: Undo Selection","command":"soft_undo"},

  {"caption":"Side Bar: Refresh","command":"refresh_folder_list"},

  {"caption":"Sort Lines (Case Sensitive)","command":"sort_lines","args":{"case_sensitive":true}},

  {"caption":"Sort Lines","command":"sort_lines","args":{"case_sensitive":false}},

  {"caption":"Spelling: Next Misspelling","command":"next_misspelling"},

  {"caption":"Spelling: Previous Misspelling","command":"prev_misspelling"},

  {"caption":"Spelling: Spell Check","command":"toggle_setting","args":{"setting":"spell_check"}},

  {"caption":"Standard Format: Format current file","command":"standard_format"},

  {"caption":"Standard Format: Toggle format on save","command":"toggle_standard_format"},

  {"caption":"linter: Choose Gutter Theme","command":"sublimelinter_choose_gutter_theme"},

  {"caption":"linter: Choose Lint Mode","command":"sublimelinter_choose_lint_mode"},

  {"caption":"linter: Choose Mark Style","command":"sublimelinter_choose_mark_style"},

  {"caption":"linter: Clear Caches","command":"sublimelinter_clear_caches"},

  {"caption":"linter: Clear Color Scheme Folder","command":"sublimelinter_clear_color_scheme_folder"},

  {"caption":"linter: Create Linter Plugin","command":"sublimelinter_create_linter_plugin"},

  {"caption":"linter: Disable Debug Mode","command":"sublimelinter_toggle_setting","args":{"setting":"debug","value":false}},

  {"caption":"linter: Disable Linter","command":"sublimelinter_toggle_linter","args":{"which":"enabled"}},

  {"caption":"linter: Disable Linting","command":"sublimelinter_toggle_setting","args":{"setting":"@disable","value":true}},

  {"caption":"linter: Don't Make Warnings Passive","command":"sublimelinter_toggle_setting","args":{"setting":"passive_warnings","value":false}},

  {"caption":"linter: Don’t Show Errors on Save","command":"sublimelinter_toggle_setting","args":{"setting":"show_errors_on_save","value":false}},

  {"caption":"linter: Enable Debug Mode","command":"sublimelinter_toggle_setting","args":{"setting":"debug","value":true}},

  {"caption":"linter: Enable Linter","command":"sublimelinter_toggle_linter","args":{"which":"disabled"}},

  {"caption":"linter: Enable Linting","command":"sublimelinter_toggle_setting","args":{"setting":"@disable","value":null}},

  {"caption":"linter: Lint This View","command":"sublimelinter_lint"},

  {"caption":"linter: Make Warnings Passive","command":"sublimelinter_toggle_setting","args":{"setting":"passive_warnings","value":true}},

  {"caption":"linter: Next Error","command":"sublimelinter_goto_error","args":{"direction":"next"}},

  {"caption":"linter: No Column Highlights Entire Line","command":"sublimelinter_toggle_setting","args":{"setting":"no_column_highlights_line","value":true}},

  {"caption":"linter: No Column Only Marks Gutter","command":"sublimelinter_toggle_setting","args":{"setting":"no_column_highlights_line","value":false}},

  {"caption":"linter: Previous Error","command":"sublimelinter_goto_error","args":{"direction":"previous"}},

  {"caption":"linter: Report (Open Files)","command":"sublimelinter_report","args":{"on":"files"}},

  {"caption":"linter: Show All Errors","command":"sublimelinter_show_all_errors"},

  {"caption":"linter: Show Errors on Save","command":"sublimelinter_toggle_setting","args":{"setting":"show_errors_on_save","value":true}},

  {"caption":"linter: Toggle Linter","command":"sublimelinter_toggle_linter","args":{"which":"all"}},

  {"caption":"Switch: Next File in Stack","command":"next_view_in_stack"},

  {"caption":"Switch: Next File","command":"next_view"},

  {"caption":"Switch: Previous File in Stack","command":"prev_view_in_stack"},

  {"caption":"Switch: Previous File","command":"prev_view"},

  {"caption":"tern_for_sublime: Describe","command":"tern_describe"},

  {"caption":"tern_for_sublime: Jump Back","command":"tern_jump_back"},

  {"caption":"tern_for_sublime: Jump to Definition","command":"tern_jump_to_def"},

  {"caption":"tern_for_sublime: Select Variable","command":"tern_select_variable"},

  {"caption":"tog Block Comment","command":"tog_comment","args":{"block":true}},

  {"caption":"tog Comment","command":"toggle_comment","args":{"block":false}},

  {"caption":"Use Selection for Find","command":"slurp_find_string"},

  {"caption":"Use Selection for Replace","command":"slurp_replace_string"},

  {"caption":"User: Disable Python Flake8 Lint for this file","command":"flake8_disable"},

  {"caption":"User: Jump to next Python Flake8 Lint error","command":"flake8_next_error"},

  {"caption":"User: Python Flake8 Lint","command":"flake8_lint"},

  {"caption":"View: Show Console","command":"show_panel","args":{"panel":"console"}},

  {"caption":"tog Distraction Free Mode","command":"toggle_distraction_free"},

  {"caption":"tog Full Screen","command":"toggle_full_screen"},

  {"caption":"tog Gutter","command":"toggle_setting","args":{"setting":"gutter"}},

  {"caption":"tog Line Numbers","command":"toggle_setting","args":{"setting":"line_numbers"}},

  {"caption":"tog Menu","command":"toggle_menu"},

  {"caption":"tog Minimap","command":"toggle_minimap"},

  {"caption":"tog Open Files in Side Bar","command":"toggle_show_open_files"},

  {"caption":"tog Side Bar","command":"toggle_side_bar"},

  {"caption":"tog Status Bar","command":"toggle_status_bar"},

  {"caption":"tog Tabs","command":"toggle_tabs"},

  {"caption":"Web Inspector","command":"swi_debug"},

  {"caption":"Word Wrap: Toggle","command":"toggle_setting","args":{"setting":"word_wrap"}}
]
```
