# QuantLeap - Quantitative Options Pricing Platform

![QuantLeap Logo](https://img.shields.io/badge/QuantLeap-v1.0-blue)

**QuantLeap** is an advanced, institutional-grade options pricing and trading simulation platform. Built with React, TypeScript, and cutting-edge quantitative models, it provides real-time analytics, Greeks calculations, and interactive trading simulation.

## 🚀 Features

### Options Pricing Models
- **Black-Scholes-Merton** - Classic analytical pricing
- **Monte Carlo Simulation** - 50,000+ path simulations
- **Binomial Trees** - Discrete-time pricing
- **Heston Model** - Stochastic volatility
- **Jump-Diffusion** - Merton's jump model
- **Exotic Options** - Asian, Barrier, Digital

### Greeks & Risk Analytics
- First-order Greeks (Delta, Gamma, Theta, Vega, Rho)
- Higher-order Greeks (Vanna, Volga, Charm, Color)
- Real-time sensitivity analysis
- Greeks heatmaps and through-time visualization

### Trading Simulation
- Real-time stock trading simulator
- Options trading with live Greeks
- 20+ real stocks (AAPL, TSLA, NVDA, etc.)
- Market/Limit/Stop orders
- Portfolio tracking with P&L

### Advanced Features
- Volatility surface visualization
- Probability distribution analysis
- Strategy builder (spreads, straddles, butterflies)
- Risk scenario analysis
- AI-powered strategy suggestions
- Workspace management
- Export to PDF/CSV/JSON

## 🛠️ Tech Stack

- **Frontend:** React 18, TypeScript
- **UI:** Tailwind CSS, shadcn/ui, Radix UI
- **Charts:** Recharts
- **Math:** Custom quantitative finance library
- **Build:** Vite

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/quantleap.git

# Navigate to directory
cd quantleap

# Install dependencies
npm install

# Start development server
npm run dev
```

## 🎯 Usage

1. **Options Pricing:** Select parameters and pricing model
2. **Trading Simulator:** Start market and trade stocks/options
3. **Analytics:** Explore Greeks, volatility surfaces, and risk scenarios
4. **Strategies:** Build and analyze multi-leg option strategies

## 🧮 Pricing Models Explained

### Black-Scholes-Merton
The foundational model for European options pricing based on:
- Constant volatility
- Log-normal price distribution
- No arbitrage opportunities

### Monte Carlo
Simulates thousands of price paths to estimate option value:
- Handles complex payoffs
- Path-dependent options
- Variance reduction techniques

### Heston Model
Incorporates stochastic volatility:
- Mean-reverting volatility
- Volatility smile/skew
- More realistic for long-dated options

## 📊 Screenshots

![Trading Simulator](docs/trading-sim.png)
![Greeks Analysis](docs/greeks.png)
![Volatility Surface](docs/vol-surface.png)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

MIT License - see LICENSE file for details

## 👨‍💻 Author

Built for quantitative finance education and research.

## 🔗 Links

- [Documentation](docs/README.md)
- [API Reference](docs/api.md)
- [Contributing Guide](CONTRIBUTING.md)

---

**QuantLeap** - Leap into Quantitative Finance 📈
