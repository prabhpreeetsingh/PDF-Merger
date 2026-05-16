# PDF Merger - Project Specification

## 1. Project Overview
- **Project Name**: PDF Merge Pro
- **Type**: Single-page web application
- **Core Functionality**: Upload multiple PDFs, select individual pages, merge into single PDF
- **Target Users**: Students, professionals needing to combine PDF pages

## 2. UI/UX Specification

### Visual Design (Gen Z Theme)
- **Background**: Dark (#08080a) with animated gradient mesh
- **Primary Accent**: #8b5cf6 (electric violet)
- **Secondary Accent**: #06ffa5 (neon mint)
- **Tertiary Accent**: #ff6b9d (hot pink)
- **Cards**: Glassmorphism with rgba(255,255,255,0.03)

### Layout
- Fixed header with logo
- Upload zone (drag & drop)
- PDF preview cards with page selector
- Merge button
- Download section

### Components
- Drop zone with dashed border and icon
- PDF cards showing thumbnail + page checkboxes
- Page preview on hover/click
- Reorderable pages via drag
- Merge button with loading state

## 3. Functionality
- Upload multiple PDFs via file input or drag-drop
- Display all pages as thumbnails
- Multi-select pages with checkboxes
- Drag to reorder selected pages
- Merge selected pages into new PDF
- Download merged file

## 4. Tech Stack
- HTML/CSS/JS
- pdf-lib (client-side PDF manipulation)
- No server needed - fully client-side