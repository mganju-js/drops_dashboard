# Quick Edit Reference

## Common Updates You'll Want to Make

### 1. Update Percentages in Key Metrics Cards
**Location:** Lines 60-75 in index.html

```html
<!-- Overall Post-Drop Repeat Rate -->
<div class="metric-value">2%</div>

<!-- Existing Customer Conversion -->
<div class="metric-value">7.4%</div>
```

### 2. Update Key Takeaways Text
**Location:** Lines 45-65 in index.html

Look for the numbered takeaways:
```html
<p style="font-size: 16px; color: #333; line-height: 1.6; margin: 0;">
    Orders containing pretzelized items increased by only <strong>2%</strong>...
</p>
```

### 3. Update Product Comparison Stats
**Location:** Lines 200-270 in index.html

For each product, you'll see stats like:
```html
<div class="stat-row">
    <span class="stat-label">Customers who redeemed</span>
    <span class="stat-value">1,598</span>
</div>
```

### 4. Update Funnel Numbers
**Location:** Lines 150-190 in index.html

Look for funnel-step divs:
```html
<div class="funnel-bar" style="width: 100%;">1,598 users</div>
```

**Important:** When updating funnel bars, also update the `width` percentage to match the visual representation.

### 5. Update Dates/Periods
**Location:** Line 42 in index.html

```html
<div class="subtitle">Promotion Period: October 27 - November 3, 2024 | Analysis Period: Pre (9/15-10/13) vs Post (11/10-12/08)</div>
```

## Color Codes Reference

If you want to change colors:
- Purple gradient: `#667eea` to `#764ba2`
- Red/Warning gradient: `#f093fb` to `#f5576c`
- Green (success): `#4CAF50`

## Pro Tips

1. **Test locally first:** Open index.html in your browser before pushing to GitHub
2. **Use Find/Replace:** Most text editors have Find (Ctrl+F / Cmd+F) to quickly locate sections
3. **Keep backups:** Before major changes, save a copy as `index_backup.html`
4. **Commit often:** Small, frequent commits are easier to track and undo if needed
