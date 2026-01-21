# Stochastic-LCOS-of-FB
A comprehensive Python visualization suite for techno-economic analysis of flow battery chemistries, focusing on Levelized Cost of Storage (LCOS) calculations with stochastic modeling and risk assessment.

## Overview

This open-source script provides a complete framework for analyzing and comparing different flow battery chemistries through:
- **Deterministic LCOS ranking** with economic benchmarks
- **Monte Carlo simulation** with 10,000-run stochastic modeling
- **Risk-return analysis** incorporating energy density metrics
- **Comprehensive visualization** with publication-ready figures

## Features

### 🔋 **Multi-Chemistry Support**
- 8 flow battery chemistries: V-H₂, V-Zn, V-Br, V-Ce, V-Mn, V-Fe, V-V (Baseline), V-O₂
- Energy density integration (15-65 Wh L⁻¹)
- Baseline comparison with V-V system

### 📊 **Advanced Economic Modeling**
- **DOE target benchmarking** (0.05 USD/kWh·cycle)
- **20% reduction threshold** analysis from baseline
- **Monte Carlo simulation** with skewed distributions
- **Value-at-Risk (VaR)** calculations at 95% confidence

### 📈 **Publication-Ready Visualizations**
- **Figure 1**: Deterministic ranking with economic thresholds
- **Figure 2**: Stochastic distributions with confidence intervals
- **Figure 3**: Risk-return bubble chart with energy density scaling
- **Sequential layout** for progressive analysis

## Methodology

### LCOS Calculation
Based on NREL methodology with:
- Capital expenditure (CAPEX) amortization
- Operational expenditure (OPEX) projections
- Efficiency degradation modeling
- End-of-life considerations

### Stochastic Modeling
- **Distribution**: Lognormal with skewness adjustment
- **Simulation**: 10,000 Monte Carlo runs
- **Confidence intervals**: 95% two-tailed
- **Risk metrics**: VaR(95%) and Sharpe ratios

## Applications

- **Research institutions**: Comparative techno-economic analysis
- **Industry stakeholders**: Technology benchmarking
- **Policy makers**: Cost target assessment
- **Investors**: Risk-return evaluation

## Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for:
- Code style guidelines
- Testing procedures
- Pull request process

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Citation

If you use this code in an academic work, please cite: Khaje, K. (2026). Flow Battery LCOS Analysis Tool (v1.0), https://github.com/kourosh-khaje/Stochastic-LCOS-of-FB.git 

## Contact

For questions or suggestions:
- Create an [Issue](https://github.com/yourusername/flow-battery-lcos-analysis/issues)
- Email: kourosh.khaje@outlook.com 
- Discussion forum: [GitHub Discussions](https://github.com/yourusername/flow-battery-lcos-analysis/discussions)

---

**Keywords**: flow battery, LCOS, techno-economic analysis, Monte Carlo simulation, energy storage, vanadium redox, risk assessment
