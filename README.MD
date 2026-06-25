```markdown
---

## ⚡ PowerCruncher

:contentReference[oaicite:0]{index=0} is a work-in-progress web tool for comparing electricity retailers in New Zealand.

It processes real electricity usage data exported from your power company, calculates estimated monthly costs, and visualises usage patterns with separate graphs for weekdays and weekends.

🔗 Project page: :contentReference[oaicite:1]{index=1}

### What it does

PowerCruncher takes your real-world electricity usage data and helps you compare different retail plans side by side.

It:
- Imports and processes CSV usage data (NZ electricity retail datasets)
- Calculates monthly electricity costs
- Splits usage analysis into:
  - Weekday usage graphs
  - Weekend usage graphs
- Lets you compare multiple electricity plans

### Workflow

1. Request at least 12 months of usage data from your electricity retailer  
   - Format: EIEP13A (standard NZ electricity consumption data format)
2. Upload the CSV file into PowerCruncher
3. Select the CSV type (depending on your retailer/export format)
4. Load or create electricity plans you want to compare
5. View cost breakdowns and usage graphs

---

## 🧱 AlphaPix (LEGO Dots Designer)

:contentReference[oaicite:2]{index=2} is a lightweight HTML/JavaScript tool that lets you design custom LEGO Dots-style boards directly in your browser.

🔗 Project page: :contentReference[oaicite:3]{index=3}

### What it does

AlphaPix is designed for quick, keyboard-friendly creation of LEGO Dots patterns, including text-based designs and custom layouts.

### Features

- Pre-loaded fonts for fast text creation
- Auto-centring for clean layout alignment
- Save and load designs using JSON files
- Inventory checking:
  - Compare your design against available LEGO sets
  - Uses set inventories (XML format from Rebrickable)
- Custom font creation and saving (JSON format)

### Notes on LEGO inventory data

- Set inventories can be exported from Rebrickable
- Example source:
  - https://rebrickable.com/sets/41952-1/big-message-board/?inventory=1#parts
- Recommended export method:
  - Inventory → Export Parts → BrickLink XML format

---
```
