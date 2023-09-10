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
    position: 1
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
  breakfast-name:
    input: text
    accessorKey: breakfast-name
    key: breakfast-name
    id: breakfast-name
    label: Breakfast Name
    position: 2
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
  breakfast-feedback:
    input: text
    accessorKey: breakfast-feedback
    key: breakfast-feedback
    id: breakfast-feedback
    label: Breakfast Feedback
    position: 3
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
  lunch-name:
    input: text
    accessorKey: lunch-name
    key: lunch-name
    id: lunch-name
    label: Lunch Name
    position: 7
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
  lunch-time:
    input: number
    accessorKey: lunch-time
    key: lunch-time
    id: lunch-time
    label: Lunch Time
    position: 8
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
  lunch-feedback:
    input: text
    accessorKey: lunch-feedback
    key: lunch-feedback
    id: lunch-feedback
    label: Lunch Feedback
    position: 9
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
  snacks-name:
    input: text
    accessorKey: snacks-name
    key: snacks-name
    id: snacks-name
    label: Snacks Name
    position: 13
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
  snacks-time:
    input: number
    accessorKey: snacks-time
    key: snacks-time
    id: snacks-time
    label: Snacks Time
    position: 14
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
  snacks-feedback:
    input: text
    accessorKey: snacks-feedback
    key: snacks-feedback
    id: snacks-feedback
    label: Snacks Feedback
    position: 15
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
  dinner-name:
    input: text
    accessorKey: dinner-name
    key: dinner-name
    id: dinner-name
    label: Dinner Name
    position: 17
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
  dinner-time:
    input: number
    accessorKey: dinner-time
    key: dinner-time
    id: dinner-time
    label: Dinner Time
    position: 18
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
  dinner-feedback:
    input: text
    accessorKey: dinner-feedback
    key: dinner-feedback
    id: dinner-feedback
    label: Dinner Feedback
    position: 21
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
  breakfast-estimated-cost:
    input: number
    accessorKey: breakfast-estimated-cost
    key: breakfast-estimated-cost
    id: breakfast-estimated-cost
    label: Breakfast-Cost
    position: 4
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
  lunch-estimated-cost:
    input: number
    accessorKey: lunch-estimated-cost
    key: lunch-estimated-cost
    id: lunch-estimated-cost
    label: Lunch-Cost
    position: 10
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
  dinner-estimated-cost:
    input: number
    accessorKey: dinner-estimated-cost
    key: dinner-estimated-cost
    id: dinner-estimated-cost
    label: Dinner-Cost
    position: 22
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
  snacks-estimated-cost:
    input: number
    accessorKey: snacks-estimated-cost
    key: snacks-estimated-cost
    id: snacks-estimated-cost
    label: Snacks-Cost
    position: 16
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
  breakfast-clock-in-time:
    input: number
    accessorKey: breakfast-clock-in-time
    key: breakfast-clock-in-time
    id: breakfast-clock-in-time
    label: breakfast-clock-in-time
    position: 5
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
  breakfast-clock-out-time:
    input: number
    accessorKey: breakfast-clock-out-time
    key: breakfast-clock-out-time
    id: breakfast-clock-out-time
    label: breakfast-clock-out-time
    position: 6
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
  lunch-clock-in-time:
    input: number
    accessorKey: lunch-clock-in-time
    key: lunch-clock-in-time
    id: lunch-clock-in-time
    label: lunch-clock-in-time
    position: 11
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
  lunch-clock-out-time:
    input: number
    accessorKey: lunch-clock-out-time
    key: lunch-clock-out-time
    id: lunch-clock-out-time
    label: lunch-clock-out-time
    position: 12
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
  dinner-clock-in-time:
    input: number
    accessorKey: dinner-clock-in-time
    key: dinner-clock-in-time
    id: dinner-clock-in-time
    label: dinner-clock-in-time
    position: 23
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
  dinner-clock-out-time:
    input: number
    accessorKey: dinner-clock-out-time
    key: dinner-clock-out-time
    id: dinner-clock-out-time
    label: dinner-clock-out-time
    position: 24
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
  snacks-clock-in-time:
    input: number
    accessorKey: snacks-clock-in-time
    key: snacks-clock-in-time
    id: snacks-clock-in-time
    label: snacks-clock-in-time
    position: 19
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
  snacks-clock-out-time:
    input: number
    accessorKey: snacks-clock-out-time
    key: snacks-clock-out-time
    id: snacks-clock-out-time
    label: snacks-clock-out-time
    position: 20
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
  source_form_result: "#daily-note"
  source_destination_path: Notes/Periodic-Notes/Daily-Notes
  row_templates_folder: /
  current_row_template: 
  pagination_size: 10
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: true
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