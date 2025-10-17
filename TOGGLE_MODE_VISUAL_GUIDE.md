# 🎨 Toggle Mode Feature - Visual Guide

## 📱 Web Application UI

### Default State (Detailed Mode)
```
┌─────────────────────────────────────────────────────────┐
│           🤖 AI Chat Assistant                          │
│           Your friendly technical interview companion   │
├─────────────────────────────────────────────────────────┤
│                                                         │
│  👤 You                                                 │
│  What is binary search?                                 │
│                                                         │
│  🤖 Assistant                                           │
│  **Binary Search**                                      │
│                                                         │
│  Binary search is an efficient algorithm for finding    │
│  a specific item in a sorted list. Think of it like...  │
│  [150-250 words of comprehensive explanation]           │
│                                                         │
├─────────────────────────────────────────────────────────┤
│ ┌──────────────┐ ┌────────────────────┐ ┌────┐ ┌────┐ │
│ │📚 Detailed   │ │ Type your question │ │🎤  │ │📤  │ │
│ │   Mode       │ │                    │ │Voice│ │Send│ │
│ └──────────────┘ └────────────────────┘ └────┘ └────┘ │
│   (Green)                                              │
└─────────────────────────────────────────────────────────┘
```

### After Clicking Toggle (Simple Mode)
```
┌─────────────────────────────────────────────────────────┐
│           🤖 AI Chat Assistant                          │
│           Your friendly technical interview companion   │
├─────────────────────────────────────────────────────────┤
│                 ┌─────────────────────────────┐        │
│                 │ 💡 Simple Mode: Short       │        │
│                 │ definitions & numbered steps│        │
│                 └─────────────────────────────┘        │
│                      ↑ Notification (auto-dismiss)     │
│                                                         │
│  👤 You                                                 │
│  What is recursion?                                     │
│                                                         │
│  🤖 Assistant                                           │
│  **Definition:**                                        │
│  A function that calls itself to solve a problem.       │
│                                                         │
│  **Simple Explanation:**                                │
│  Like Russian nesting dolls - each doll contains        │
│  a smaller version until you reach the smallest.        │
│                                                         │
│  **Key Steps:**                                         │
│  1. Break problem into smaller parts                    │
│  2. Solve the smallest part (base case)                 │
│  3. Combine results back up                             │
│                                                         │
│  **Example:**                                           │
│  Factorial: 5! = 5 × 4! = 5 × 4 × 3!... until 1!       │
│                                                         │
├─────────────────────────────────────────────────────────┤
│ ┌──────────────┐ ┌────────────────────┐ ┌────┐ ┌────┐ │
│ │💡 Simple     │ │ Type your question │ │🎤  │ │📤  │ │
│ │   Mode       │ │                    │ │Voice│ │Send│ │
│ └──────────────┘ └────────────────────┘ └────┘ └────┘ │
│   (Orange)                                             │
└─────────────────────────────────────────────────────────┘
```

---

## 🖥️ Windows Application UI

### Default State (Detailed Mode)
```
┌─────────────────────────────────────────────────────────┐
│ ┌──────────────┐                              ┌───┐    │
│ │📚 Detailed   │                              │ ✕ │    │
│ └──────────────┘                              └───┘    │
│    (Green)                                              │
├─────────────────────────────────────────────────────────┤
│                                                         │
│  ✅ Connected - Ready to chat!                         │
│                                                         │
│  [👤 You]                                               │
│  What is binary search?                                 │
│                                                         │
│  [🤖 Assistant]                                         │
│  **Binary Search**                                      │
│                                                         │
│  Binary search is an efficient algorithm for finding    │
│  a specific item in a sorted list. Think of it like...  │
│  [Comprehensive 150-250 word explanation]               │
│                                                         │
│                                                         │
├─────────────────────────────────────────────────────────┤
│ ┌───────────────────────────────────────┐ ┌──────────┐ │
│ │ Type your question here...            │ │          │ │
│ └───────────────────────────────────────┘ │ 📤 Send  │ │
│                                           └──────────┘ │
├─────────────────────────────────────────────────────────┤
│     F2: Toggle Transparency | F3: Toggle Mode           │
└─────────────────────────────────────────────────────────┘
```

### After Pressing F3 or Clicking Button (Simple Mode)
```
┌─────────────────────────────────────────────────────────┐
│ ┌──────────────┐                              ┌───┐    │
│ │💡 Simple     │                              │ ✕ │    │
│ └──────────────┘                              └───┘    │
│    (Orange)                                             │
├─────────────────────────────────────────────────────────┤
│                                                         │
│  ✅ Connected - Ready to chat!                         │
│                                                         │
│  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━       │
│  💡 Switched to SIMPLE MODE                            │
│  Responses will be short, clear definitions with       │
│  numbered steps.                                        │
│  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━       │
│                                                         │
│  [👤 You]                                               │
│  What is recursion?                                     │
│                                                         │
│  [🤖 Assistant]                                         │
│  **Definition:**                                        │
│  A function that calls itself to solve a problem.       │
│                                                         │
│  **Simple Explanation:**                                │
│  Like Russian nesting dolls - each doll contains        │
│  a smaller version until you reach the smallest.        │
│                                                         │
│  **Key Steps:**                                         │
│  1. Break problem into smaller parts                    │
│  2. Solve the smallest part (base case)                 │
│  3. Combine results back up                             │
│                                                         │
│  **Example:**                                           │
│  Factorial: 5! = 5 × 4! = 5 × 4 × 3!... until 1!       │
│                                                         │
├─────────────────────────────────────────────────────────┤
│ ┌───────────────────────────────────────┐ ┌──────────┐ │
│ │ Type your question here...            │ │          │ │
│ └───────────────────────────────────────┘ │ 📤 Send  │ │
│                                           └──────────┘ │
├─────────────────────────────────────────────────────────┤
│     F2: Toggle Transparency | F3: Toggle Mode           │
└─────────────────────────────────────────────────────────┘
```

---

## 🎨 Button States

### Detailed Mode Button
```
┌──────────────────┐
│  📚 Detailed     │  ← Icon: Books
│     Mode         │  ← Color: Green (#10B981)
└──────────────────┘  ← Gradient background
     (Web)

┌──────────────┐
│ 📚 Detailed  │      ← Icon: Books
└──────────────┘      ← Color: Green rgba(16,185,129,0.25)
   (Windows)
```

### Simple Mode Button
```
┌──────────────────┐
│  💡 Simple       │  ← Icon: Light bulb
│     Mode         │  ← Color: Orange (#F59E0B)
└──────────────────┘  ← Gradient background
     (Web)

┌──────────────┐
│ 💡 Simple    │      ← Icon: Light bulb
└──────────────┘      ← Color: Orange rgba(245,158,11,0.25)
   (Windows)
```

---

## 📱 Mobile View (Web)

### Portrait Mode
```
┌────────────────────────┐
│  🤖 AI Chat Assistant  │
├────────────────────────┤
│                        │
│  Chat Messages         │
│  ...                   │
│                        │
├────────────────────────┤
│ ┌────────────────────┐ │
│ │ 📚 Detailed Mode   │ │
│ └────────────────────┘ │
│ ┌────────────────────┐ │
│ │ Type question...   │ │
│ └────────────────────┘ │
│ ┌──────────┬─────────┐ │
│ │ 🎤 Voice │ 📤 Send │ │
│ └──────────┴─────────┘ │
└────────────────────────┘
```

---

## 🎬 Animation Flow

### Web Notification Animation
```
Step 1: Button Click
   ↓
Step 2: Button Changes Color/Text
   ↓
Step 3: Notification Slides Down (0.3s)
┌─────────────────────────────────┐
│ 💡 Simple Mode: Short           │
│ definitions & numbered steps    │
└─────────────────────────────────┘
   ↓ (Wait 2 seconds)
Step 4: Notification Slides Up (0.3s)
   ↓
Step 5: Removed from DOM
```

### Windows Notification Flow
```
Step 1: F3 Press or Button Click
   ↓
Step 2: Button Updates Appearance
   ↓
Step 3: Chat Message Appears
━━━━━━━━━━━━━━━━━━━━━━━━━━━
💡 Switched to SIMPLE MODE
Responses will be short...
━━━━━━━━━━━━━━━━━━━━━━━━━━━
   ↓
Step 4: Stays in Chat History
```

---

## 🎯 Color Palette

### Detailed Mode (Green)
- **Primary:** #10B981 (Emerald 500)
- **Secondary:** #059669 (Emerald 600)
- **Button BG:** Linear gradient
- **Opacity:** 0.9 (web), 0.25 (windows)

### Simple Mode (Orange)
- **Primary:** #F59E0B (Amber 500)
- **Secondary:** #D97706 (Amber 600)
- **Button BG:** Linear gradient
- **Opacity:** 0.9 (web), 0.25 (windows)

### Notification (Web)
- **Background:** Green gradient (#10B981 → #059669)
- **Text:** White
- **Border Radius:** 24px
- **Shadow:** 0 4px 12px rgba(0,0,0,0.3)

---

## 📐 Dimensions

### Web Application
- **Button Width:** Min 140px
- **Button Height:** Auto (padding: 12px 24px)
- **Button Border Radius:** 24px
- **Notification:** Fixed position, centered

### Windows Application
- **Button Width:** 110px
- **Button Height:** 32px
- **Button Position:** Top-left (Margin: 8px)
- **Font Size:** 12px

---

## 🔄 State Transitions

### Mode Toggle Flow
```
┌─────────────────┐
│ Detailed Mode   │ ◄─────┐
│ (Green, 📚)     │       │
└────────┬────────┘       │
         │                │
     [Click/F3]       [Click/F3]
         │                │
         ▼                │
┌─────────────────┐       │
│ Simple Mode     │───────┘
│ (Orange, 💡)    │
└─────────────────┘
```

### System Prompt Update
```
User Clicks Toggle
      ↓
isSimpleMode = !isSimpleMode
      ↓
conversation[0].content = 
   isSimpleMode ? simplePrompt : detailedPrompt
      ↓
Button UI Updates
      ↓
Notification Shows
      ↓
Next Response Uses New Style
```

---

## ✨ Key Visual Features

1. **🎨 Color Coding:**
   - Green = Comprehensive/Detailed
   - Orange = Concise/Simple

2. **🔤 Icons:**
   - 📚 = Books = Learning/Detailed
   - 💡 = Light bulb = Quick idea/Simple

3. **📢 Clear Feedback:**
   - Button appearance changes
   - Notifications confirm action
   - Chat history shows mode switches

4. **👆 Intuitive Placement:**
   - Web: First in controls (logical flow)
   - Windows: Top-left (non-intrusive)

---

## 🎉 Result

A clean, intuitive toggle that clearly shows:
- ✅ What mode you're in
- ✅ How to switch modes
- ✅ What to expect in each mode

**Users can instantly see and control their preferred response style!**
