# Wyvern Maturation Calculator

## Introduction
Welcome to the Wyvern Maturation Calculator. This tool helps you calculate the food needed and the time required for a wyvern to reach 100% maturity in Ark: Survival Evolved. Simply input the current maturation percentage, food level, and maturation rate, and our calculator will provide the information you need.

## Calculator Form
### Input the Following Details:
- **Percent Maturity:** Enter the current percent maturity of the wyvern (0-100).
- **Current Food Level:** Enter the current food level of the wyvern.
- **Maturation Rate:** Enter the maturation rate (e.g., 1 for 1x, 2 for 2x).

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

## Results
After submitting the form, the results will be displayed here, showing:
- The remaining food needed for the wyvern to reach 100% maturity.
- The equivalent amount of milk units needed.
- The time remaining to reach 100% maturity.

@if (ViewBag.RemainingFoodNeeded != null)
{
    <h2>Results</h2>
    <p>The wyvern needs @ViewBag.RemainingFoodNeeded more food to reach 100% maturity.</p>
    <p>This is equivalent to @ViewBag.RemainingMilkNeeded units of milk.</p>
    <p>It will take approximately @ViewBag.RemainingTime hours to reach 100% maturity.</p>
}

## About This Tool
This calculator is designed to help players of Ark: Survival Evolved manage the maturation of their wyverns more effectively. By providing accurate calculations, players can ensure their wyverns are properly fed and mature within the expected time frames.

## Contact Information
If you have any questions or feedback about this tool, please feel free to contact us at [your-email@example.com].

## Footer
Thank you for using the Wyvern Maturation Calculator. Happy gaming!
