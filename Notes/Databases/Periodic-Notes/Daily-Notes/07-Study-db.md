---

database-plugin: basic

---

```yaml:dbfolder
name: new database
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 0
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  college-clock-in-time:
    input: number
    accessorKey: college-clock-in-time
    key: college-clock-in-time
    id: college-clock-in-time
    label: College Clock-in at
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  college-clock-out-time:
    input: number
    accessorKey: college-clock-out-time
    key: college-clock-out-time
    id: college-clock-out-time
    label: College Clock-out at
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  engineering-self-study-clockin-time:
    input: number
    accessorKey: engineering-self-study-clockin-time
    key: engineering-self-study-clockin-time
    id: engineering-self-study-clockin-time
    label: Engineering Self Study Clock-in time
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  engineering-self-study-clockout-time:
    input: number
    accessorKey: engineering-self-study-clockout-time
    key: engineering-self-study-clockout-time
    id: engineering-self-study-clockout-time
    label: Engineering Self Study Clock-out time
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  engineering-self-study-subjects:
    input: number
    accessorKey: engineering-self-study-subjects
    key: engineering-self-study-subjects
    id: engineering-self-study-subjects
    label: Engineering Self Study Subjects
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  bba-self-study-clockin-time:
    input: number
    accessorKey: bba-self-study-clockin-time
    key: bba-self-study-clockin-time
    id: bba-self-study-clockin-time
    label: BBA Self Study Clock-in time
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  bba-self-study-clockout-time:
    input: number
    accessorKey: bba-self-study-clockout-time
    key: bba-self-study-clockout-time
    id: bba-self-study-clockout-time
    label: BBA Self Study Clock-in time
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  bba-self-study-subjects:
    input: number
    accessorKey: bba-self-study-subjects
    key: bba-self-study-subjects
    id: bba-self-study-subjects
    label: BBA Self Study Subjects
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  coursera-hours-spent:
    input: number
    accessorKey: coursera-hours-spent
    key: coursera-hours-spent
    id: coursera-hours-spent
    label: coursera-hours-spent
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: tag
  source_form_result: "#templates/daily-note"
  source_destination_path: Notes/Periodic-Notes/Daily-Notes
  row_templates_folder: /
  current_row_template: 
  pagination_size: 10
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```