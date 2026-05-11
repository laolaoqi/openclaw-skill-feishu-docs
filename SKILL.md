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

### Full Actions List
- read - Read document content
- write - Replace all content with markdown
- append - Append markdown to end
- create - Create new document
- list_blocks - Get structured block data
- get_block - Get single block
- update_block - Update block text
- delete_block - Delete a block
- create_table - Create table in document
- write_table_cells - Write values to table cells
- create_table_with_values - One-step table creation
- upload_image - Upload image from URL or local file
- upload_file - Upload file attachment

## Permissions Required
- docx:document
- docx:document:readonly
- docx:document.block:convert
- drive:drive

## Dependencies
- Feishu channel must be enabled