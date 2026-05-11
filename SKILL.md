# Feishu Document Tool

Single tool `feishu_doc` with action parameter for all document operations.

## Actions

### Read Document
```json
{ "action": "read", "doc_token": "ABC123def" }
```

### Create Document
```json
{ "action": "create", "title": "New Document", "owner_open_id": "ou_xxx" }
```

### Write Document
```json
{ "action": "write", "doc_token": "ABC123def", "content": "# Title\n\nContent..." }
```

### Append Content
```json
{ "action": "append", "doc_token": "ABC123def", "content": "Additional content" }
```

## Full Actions List
- read, write, append, create, list_blocks, get_block, update_block, delete_block
- create_table, write_table_cells, create_table_with_values
- upload_image, upload_file

## Permissions Required
- docx:document, docx:document:readonly, docx:document.block:convert, drive:drive