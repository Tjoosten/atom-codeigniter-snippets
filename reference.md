Snippet reference
===================

To use the a snippet just type the prefix and hit your tab.

## Active record

| Prefix:     | Output:                                      |
| ----------- | -------------------------------------------- |
| `db_delete` | `$this->db->delete('table');`                |
| `db_get`    | `$this->db->get('table','limit', 'offset');` |

## Session

**Coming soons**

## miscanelious CI

| Prefix:        | Output:                                       |
| -------------- | --------------------------------------------- |
| `controller`   | A controller                                  |
| `load_helper`  | `$this->load->helper(array('helper_name'));`  |
| `load_library` | `$this->load->helper(array('library_name'));` |
| `load_model`   | `$this->load->model('model_name', 'name');`   |
| `load_view`    | `$this->load->view('name', '$data');`         |
| `log`          | `log_message('error','message')`              |
| `ciline`       | `// ---------------------------------------`  |

## Miscanelious PHP

| Prefix:    | Output:                 |
| ---------- | ----------------------- |
| `dump`     | `var_dump($variable);`  |
| `docblock` | a comment docblock      |
| `e`        | `echo`                  |
