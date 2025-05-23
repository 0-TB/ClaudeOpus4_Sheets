# ClaudeOpus4_Sheets

A collection of polished, interactive sheet components for React applications featuring smooth animations and native-like gestures.

## Components

### 1. Side Sheet (Button A)
- Slides in from the right side
- **Expandable**: Can expand from 1/3 to full width (minus navigation)
- **Draggable**: Drag left to expand, drag right to collapse/close
- **Responsive**: Maintains fixed position to right edge
- Chevron toggle for expansion/collapse
- Close button (X) in top-right corner

### 2. Bottom Sheet (Button B)
- Emerges from the bottom of the screen
- **Expandable**: Can expand to full screen height
- **Stackable**: Supports multiple stacked sheets with visual hierarchy
- **Draggable**: Drag up to expand, drag down to collapse/close
- Depth effect on main content when active
- Visual dimming when stacked sheets are open

### 3. Popup (Button C)
- Slides up from bottom center
- Click outside to close
- Compact design for quick actions
- Smooth scale and fade animations

## Features

- 🎯 **Gesture Support**: Full mouse and touch drag support
- 🎨 **Smooth Animations**: Polished transitions using CSS
- 📱 **Mobile-First**: Native mobile sheet behavior
- 🔄 **State Management**: Clean state handling with React hooks
- 🎭 **Visual Hierarchy**: Clear stacking with dimming effects
- ⚡ **Performance**: Optimized render cycles and animations

## Installation

```bash
npm install lucide-react
# or
yarn add lucide-react
