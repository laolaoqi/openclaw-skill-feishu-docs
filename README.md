# Feishu Document Skill Pack

## Description
Feishu document read/write automation for OpenClaw. Read, create, edit, append, and manage Feishu documents.

## Quick Install
```
openclaw skills enable feishu-doc
```

## Features
- Read document content (plain text + structured blocks)
- Create new documents with markdown content
- Write/append markdown to documents
- Upload images and file attachments
- Create and edit tables
- List, get, update, delete document blocks

## Configuration
```yaml
channels:
  feishu:
    tools:
      doc: true
```

## Required Permissions
docx:document, docx:document:readonly, docx:document.block:convert, drive:drive

## License MIT