# PPF Revenue Maximization Calculator

An interactive web-based application that demonstrates revenue maximization on the Production Possibility Frontier (PPF) using economic theory. The application calculates and visualizes the optimal production point for two goods (corn and wheat) given their maximum production capacities and market prices.

## Quick Start

**No installation required!** Simply open the web application:

```bash
open ppf_web.html
```

The application runs entirely in your web browser with no dependencies.

## Features

- **Interactive Web Interface**: Real-time parameter adjustment with instant visualization updates
- **Concave PPF**: Realistic increasing opportunity cost model matching economics textbooks
- **Revenue Analysis**: Shows revenue at each point along the PPF curve
- **MRPS Integration**: Uses Marginal Rate of Product Substitution terminology
- **Educational Tooltips**: Hover over PPF points to see corn, wheat, and revenue values
- **Professional Visualization**: Interactive charts with zoom, pan, and detailed hover information

## How to Use

1. **Adjust Parameters**: 
   - Enter corn and wheat production capacities (PPF in bushels)
   - Set corn and wheat prices ($/bushel)

2. **Observe Results**:
   - Chart updates automatically as you type
   - Green curve shows the Production Possibility Frontier
   - Blue dashed line shows the isorevenue line
   - Red dot indicates the revenue-maximizing point

3. **Interactive Analysis**:
   - Hover over the PPF curve to see revenue at each production combination
   - Compare revenues to understand why only one point maximizes revenue
   - Observe how price changes affect the optimal production mix

## Economic Concepts Demonstrated

### Core Theory
- **Production Possibility Frontier (PPF)**: Concave curve showing maximum output combinations with increasing opportunity costs
- **Marginal Rate of Product Substitution (MRPS)**: Rate at which wheat production decreases as corn production increases (ΔWheat/ΔCorn)
- **Revenue Maximization**: Finding the production point that maximizes total revenue given market prices
- **Isorevenue Lines**: Lines showing all combinations that yield the same total revenue

### Key Insights
- **Not all PPF points are equal**: Different production combinations yield different revenues
- **Optimal tangency**: Revenue is maximized where the isorevenue line is tangent to the PPF
- **MRPS = Price Ratio**: At the optimal point, MRPS equals the ratio of corn price to wheat price
- **Interior vs Corner Solutions**: Concave PPF often yields mixed production strategies

## Educational Value

This tool helps students understand:
- Why producers don't always specialize completely in one good
- How market prices influence optimal production decisions  
- The relationship between opportunity costs and market prices
- The mathematical relationship between MRPS and price ratios

## Technical Details

### Web-Based Architecture
- **Pure HTML/JavaScript**: No server or installation required
- **Cross-platform compatibility**: Works on Windows, macOS, and Linux
- **Modern browsers**: Requires JavaScript-enabled browser
- **Interactive visualization**: Uses Plotly.js for professional charts

### Economic Model
- **Concave PPF**: Uses quarter-circle equation representing increasing opportunity costs
- **Mathematical formula**: `wheat = wheatMax × √(1 - (corn/cornMax)²)`
- **MRPS calculation**: Derivative of PPF equation at each point
- **Revenue optimization**: Numerical search for maximum revenue point

## Customization

### For Instructors
You can modify default values by editing the HTML file:
- Look for `value="10.0"` attributes in the input fields
- Change default prices and production capacities
- All economic formulas are clearly commented in the JavaScript section

### Default Scenario
- Corn price: $10.0 per bushel
- Corn max production: 100 bushels  
- Wheat price: $15.0 per bushel
- Wheat max production: 50 bushels

This creates a scenario where wheat is more expensive, typically leading to mixed production strategies.

## Project Structure

```
ppf-profit-maximizing/
├── ppf_web.html    # Complete web application
└── README.md       # This documentation
```

## Browser Requirements

- **Modern web browser** with JavaScript enabled
- **Internet connection** (for loading Plotly.js library)
- **No plugins required** - uses standard web technologies

## Contributing

This project is designed for educational use in economics courses. Contributions that enhance the educational value or improve the user experience are welcome.

## License

This project is intended for educational purposes in economics instruction and learning.