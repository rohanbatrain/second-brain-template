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
  expense:
    input: text
    accessorKey: expense
    key: expense
    id: expense
    label: Expense
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
  income:
    input: text
    accessorKey: income
    key: income
    id: income
    label: Income
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
  investment:
    input: text
    accessorKey: investment
    key: investment
    id: investment
    label: Investment
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
  mood:
    input: text
    accessorKey: mood
    key: mood
    id: mood
    label: Mood
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
  productivity:
    input: text
    accessorKey: productivity
    key: productivity
    id: productivity
    label: Productivity
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
  health:
    input: text
    accessorKey: health
    key: health
    id: health
    label: Health
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
  water-counter:
    input: text
    accessorKey: water-counter
    key: water-counter
    id: water-counter
    label: Water Litre Counter
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
  weight-tracker:
    input: text
    accessorKey: weight-tracker
    key: weight-tracker
    id: weight-tracker
    label: Weight Tracker
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
  stress-levels:
    input: text
    accessorKey: stress-levels
    key: stress-levels
    id: stress-levels
    label: Stress Levels
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
  sleep-hrs:
    input: text
    accessorKey: sleep-hrs
    key: sleep-hrs
    id: sleep-hrs
    label: Sleep Hours
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
  total-calorie-intake-amount:
    input: text
    accessorKey: total-calorie-intake-amount
    key: total-calorie-intake-amount
    id: total-calorie-intake-amount
    label: Total Calorie Intake Amount
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
  total-protein-intake-amount:
    input: text
    accessorKey: total-protein-intake-amount
    key: total-protein-intake-amount
    id: total-protein-intake-amount
    label: Total Protein Intake Amount
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
  morning-wakeup-routine-wake-up-time:
    input: text
    accessorKey: morning-wakeup-routine-wake-up-time
    key: morning-wakeup-routine-wake-up-time
    id: morning-wakeup-routine-wake-up-time
    label: Morning Wakeup Routine Wake-up Time
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
  morning-mental-health-meditation-duration:
    input: text
    accessorKey: morning-mental-health-meditation-duration
    key: morning-mental-health-meditation-duration
    id: morning-mental-health-meditation-duration
    label: Morning Mental Health Meditation Duration
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
  evening-mental-health-meditation-duration:
    input: text
    accessorKey: evening-mental-health-meditation-duration
    key: evening-mental-health-meditation-duration
    id: evening-mental-health-meditation-duration
    label: Evening Mental Health Meditation Duration
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
  cried-counter:
    input: text
    accessorKey: cried-counter
    key: cried-counter
    id: cried-counter
    label: Cried Counter
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
  morning-shower-duration:
    input: text
    accessorKey: morning-shower-duration
    key: morning-shower-duration
    id: morning-shower-duration
    label: Morning Shower Duration
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
  evening-shower-duration:
    input: text
    accessorKey: evening-shower-duration
    key: evening-shower-duration
    id: evening-shower-duration
    label: Evening Shower Duration
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
  source_form_result: "#daily-note"
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