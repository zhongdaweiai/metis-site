# Metis Pattern Prior Report

- Observations: 11
- Patterns: 10
- Return direction threshold: 2.0%

| pattern_id | horizon | n | p_up | p_down | p_flat | avg_adjusted_return | median_adjusted_return | examples | flag |
|---|---:|---:|---:|---:|---:|---:|---:|---|---|
| ai_capex_physical_infrastructure_readthrough | 1d | 3 | 66.7% | 16.7% | 16.7% | +8.7% | +7.1% | pwr_2026_04_30; cat_2026_04_30; carr_2026_04_30 | low_n |
| customer_vertical_integration_capex_mix_shift | 1d | 1 | 25.0% | 50.0% | 25.0% | -5.5% | -5.5% | nvda_2026_04_30 | low_n |
| cyclical_guidance_cut_on_cost_pressure | 1d | 1 | 25.0% | 50.0% | 25.0% | -10.4% | -10.4% | ip_2026_04_30 | low_n |
| guidance_raise_plus_pipeline_derisking | 1d | 1 | 50.0% | 25.0% | 25.0% | +7.6% | +7.6% | lly_2026_04_30 | low_n |
| inventory_cycle_guidance_reversal | 1d | 1 | 50.0% | 25.0% | 25.0% | +19.8% | +19.8% | pi_2026_04_30 | low_n |
| legacy_asset_ai_infrastructure_repricing | 1d | 1 | 50.0% | 25.0% | 25.0% | +8.3% | +8.3% | irm_2026_04_30 | low_n |
| new_tam_repricing_from_platform_pivot | 1d | 1 | 50.0% | 25.0% | 25.0% | +14.2% | +14.2% | qcom_2026_04_30 | low_n |
| organic_growth_quality_miss | 1d | 1 | 25.0% | 50.0% | 25.0% | -12.1% | -12.1% | wtw_2026_04_30 | low_n |
| segment_acceleration_repricing | 1d | 1 | 50.0% | 25.0% | 25.0% | +4.1% | +4.1% | txt_2026_04_30 | low_n |
| segment_mix_repricing | 1d | 1 | 50.0% | 25.0% | 25.0% | +6.0% | +6.0% | carr_2026_04_30 | low_n |

## Reading Notes

- This report uses outcome-first causal cases, so it is useful for pattern discovery but not enough for calibrated prediction.
- Forward predictions in `data/predictions.csv` are required to estimate true base rates with a denominator.
