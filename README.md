# Proposal Builder App

<!-- Add actual screenshot path -->*

A lightweight client proposal builder with real-time preview and local storage persistence.

## Key Features

### Proposal Dashboard
- **All Proposals View**: Clean table displaying saved proposals
- **Quick Search**: Filter by client name or tags
- **Status Indicators**: 
  - 🟢 Created (draft)
  - 🟠 Pending (sent to client)
  - 🔴 Error (failed to save)
- **Quick Actions**:
  - 👁️ View/Edit proposal details
  - 🗑️ Delete proposals

### Proposal Creation
- **Interactive Form**:
  - Client name input
  - Multi-select services
  - Dynamic pricing table with auto-total calculation
  - Date range selection
  - Optional notes field
- **Live Preview**:
  - Real-time updates as you type
  - Professional formatting
  - Responsive layout

### Data Management
- **Local Storage**: All proposals saved to browser storage
- **Simple Organization**: Basic tagging system

## Usage Guide

### Creating Proposals
1. Click "New Proposal"
2. Fill in client details
3. Select services from dropdown
4. Adjust quantities/prices (totals calculate automatically)
5. Set timeline dates
6. View updates in real-time preview pane
7. Click "Save" to store in local storage

### Managing Proposals
- **Search**: Type in search bar to filter by client name
- **View/Edit**: Click eye icon to open proposal
- **Delete**: Click trash icon to remove permanently
- **Status**: Colored dots indicate current state

### Exporting
- Click "Download PDF" to generate client-ready version

## Technical Details
- Built with React.js
- LocalStorage for data persistence
- Responsive split-panel layout
- Form validation for required fields
- Lightweight state management

## Future Improvements
- PDF export functionality
- Enhanced tagging system
- More status types
- UI theme customization
