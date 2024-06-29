# Wyvern Maturation Calculator

## Introduction
Welcome to the Wyvern Maturation Calculator. This tool helps you calculate the food needed and the time required for a wyvern to reach 100% maturity in Ark: Survival Evolved. Simply input the current maturation percentage, food level, and maturation rate, and our calculator will provide the information you need.

## Calculator Form
### Input the Following Details:
- **Percent Maturity:** Enter the current percent maturity of the wyvern (0-100).
- **Current Food Level:** Enter the current food level of the wyvern.
- **Maturation Rate:** Enter the maturation rate (e.g., 1 for 1x, 2 for 2x).

```html
<form method="post" action="/Wyvern/Calculate">
    <div>
        <label for="percentMaturity">Percent Maturity (0-100):</label>
        <input type="number" id="percentMaturity" name="percentMaturity" step="0.01" required>
    </div>
    <div>
        <label for="foodLevel">Current Food Level:</label>
        <input type="number" id="foodLevel" name="foodLevel" step="0.01" required>
    </div>
    <div>
        <label for="maturationRate">Maturation Rate (e.g., 1 for 1x, 2 for 2x):</label>
        <input type="number" id="maturationRate" name="maturationRate" step="0.01" required>
    </div>
    <button type="submit">Calculate</button>
</form>
