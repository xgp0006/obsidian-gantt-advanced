# Advanced Gantt Chart for Obsidian

A powerful Gantt chart plugin for Obsidian that visualizes your tasks with dependencies, drag-and-drop scheduling, and advanced filtering.

## 🚨 REFACTORING NEEDED

**Audit Results (June 2025)**:
- Overall Health: 45/100 ⚠️
- JPL Compliance: 3/10 ❌  
- Security Grade: A- ✅
- Performance: FAIL ❌

**Critical Issues**:
1. **6 duplicate GanttChart components** - 4,000+ lines of duplicated code
2. **No tests** - 0% coverage, no test framework
3. **Bundle size 1.3MB** - 2.6x over recommended limit
4. **75 'any' types** - Poor type safety

**Next Steps**: See `refactor/jpl-compliance` branch for fixes.

## Features

- 📊 **Interactive Gantt Chart**: Visualize tasks on a timeline with day/week/month views
- 🔗 **Dependency Arrows**: Uses `[[id::xxx]]` format to show task dependencies
- 🎯 **Critical Path Analysis**: Automatically highlights the critical path
- 🖱️ **Drag-and-Drop**: Reschedule tasks by dragging them on the timeline
- 🔍 **Advanced Filtering**: Filter by tags, priority, completion status, and more
- 🎨 **Customizable Colors**: Set colors for different priority levels
- 📅 **Calendar Integration**: Fixes calendar stacking issues
- ⚡ **Real-time Updates**: Changes sync immediately with your vault

## Installation

⚠️ **Warning**: This version needs significant refactoring before production use.

### From Source

1. Clone this repository into your vault's `.obsidian/plugins/` folder:
```bash
cd /path/to/vault/.obsidian/plugins/
git clone https://github.com/xgp0006/obsidian-gantt-advanced
```

2. Install dependencies and build:
```bash
cd obsidian-gantt-advanced
npm install
npm run build
```

3. Enable the plugin in Obsidian settings

## Development Status

- ✅ Core functionality working
- ❌ Needs comprehensive refactoring
- ❌ Needs test coverage
- ❌ Needs performance optimization
- ❌ Needs code consolidation

See audit report for detailed findings.