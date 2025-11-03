# Architecture
- Data: SharePoint List **Credit Requests**
- Workflow: Power Automate (SP trigger → Teams Adaptive Card → Update SP)
- Notifications: Teams (Adaptive Card) + optional email
- UI (optional): SPFx web part showing counts by Status

## Components
- SharePoint: list + columns
- Flow: trigger (When item is created) + Teams card + condition + update item
- Optional SPFx: status card

## Data flow (will add Mermaid on Day 10)
