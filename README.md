# Schoology-Close-Overdue-Assignments

A simple userscript for Schoology that helps you close overdue assignments using a keyboard shortcut.

## 📥 Installation Guide

### Step 1: Install Tampermonkey

Download and install the **Tampermonkey** browser extension.

### Step 2: Allow User Scripts

Make sure Tampermonkey is allowed to run userscripts in your browser.

1. Open your browser's **Extensions** menu.
2. Find **Tampermonkey** and click the three dots next to it.
3. Select **Manage Extension**.
4. Turn on **Allow user scripts**.

*Note: The exact steps may vary depending on your browser.*

### Step 3: Copy the Script

1. Open the [SchoologyScript](SchoologyScript) page in this repository.
2. Open the script's code.
3. Copy the entire script.

### Step 4: Add the Script to Tampermonkey

1. Click the Tampermonkey extension icon.
2. Open the **Dashboard**.
3. Click the **+** button to create a new script.
4. Select the default code in the editor and replace it with the script you copied.
5. Do not change anything else yet.

### Step 5: Add Your School's Schoology Link

1. Open your school's Schoology homepage.
2. Copy the website address from your browser's address bar.
3. Return to the Tampermonkey script editor.
4. Find the `@match` line near the top of the script.

It should look like this:

```javascript
// @match      *(YOUR SCHOOLOGY HOME LINK)*
```

5. Replace `YOUR SCHOOLOGY HOME LINK` with your school's actual Schoology link. **Keep the `*` at both the start and end of the link.**

**Example:**

```javascript
// @match      *https://schoolname.schoology.com/*
```

Make sure you use your own school's link instead of the example. Save the script when you're finished.

### Step 6: Save the Script

Click **File → Save** or press `Ctrl + S`.

Make sure the script is enabled in Tampermonkey.

### Step 7: Test the Script

1. Open your school's Schoology homepage.

2. Press these keys in this exact order:

   **`/`  `.`  `,`**

3. Check whether the overdue assignments interface appears.

### ✅ You're Done!

If the overdue assignments interface appears, the script is working!

If nothing happens, double-check that:

- Tampermonkey is installed and enabled.
- **Allow user scripts** is turned on.
- Your script is saved and enabled.
- The `@match` line matches your school's Schoology website.
- You are testing on the correct Schoology page.

## ⚠️ Important

This script is intended to help manage overdue assignments. Review any changes before applying them, and make sure you follow your school's rules when managing assignments.
