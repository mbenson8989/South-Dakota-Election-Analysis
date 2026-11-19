# South Dakota Election Analysis

South Dakota 2022 vs 2026 governor race, county-level ΔG method developed by Morissa Benson. South Dakota data only (SD Secretary of State; Census Vintage 2025 population).

- **Wiki:** https://github.com/mbenson8989/South-Dakota-Election-Analysis/wiki
- **Locked formula:** gap = (Democratic votes ÷ total ballots cast) − (Democratic registered voters ÷ total registered voters); ΔG = gap 2026 − gap 2022. Registration = active registered voters.
- **Status:** 2026 governor votes certified by the SD State Canvass Board (Nov 10, 2026). 2026 ballots cast come from the SOS results site, still labeled unofficial.
- These files measure a pattern; they make no claim about intent, fraud or cause. Reading residuals as offset votes is Morissa Benson's hypothesis.

## Chart images (repo root; the wiki links each one by its full raw URL)

| File | Raw URL |
|---|---|
| SD_2022_Dem_share_vs_gain_paired_bars.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_2022_Dem_share_vs_gain_paired_bars.png |
| SD_ceiling_counties_deltaG_by_population.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_ceiling_counties_deltaG_by_population.png |
| SD_county_slope_chart_2022_2026_Dem_surplus.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_county_slope_chart_2022_2026_Dem_surplus.png |
| SD_deltaG_by_county_population_order.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_deltaG_by_county_population_order.png |
| SD_deltaG_vs_population_precinct_vs_vote_center.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_deltaG_vs_population_precinct_vs_vote_center.png |
| SD_dem_vote_share_vs_registration_share_2022_2026.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_dem_vote_share_vs_registration_share_2022_2026.png |
| SD_in_band_29_implied_extra_votes_by_population.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_in_band_29_implied_extra_votes_by_population.png |
| SD_residual_deltaG_minus_statewide_mean_by_population.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_residual_deltaG_minus_statewide_mean_by_population.png |
| SD_stacked_share_all_66_groups_marked.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_stacked_share_all_66_groups_marked.png |
| SD_stacked_share_by_group_panels.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_stacked_share_by_group_panels.png |
| SD_stacked_share_with_Dem_registration_loss_by_2022_Dem_share.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_stacked_share_with_Dem_registration_loss_by_2022_Dem_share.png |
| SD_stacked_share_with_Dem_registration_loss_by_population.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_stacked_share_with_Dem_registration_loss_by_population.png |
| SD_surplus_vs_Dem_registration_fit_2022_2026.png | https://raw.githubusercontent.com/mbenson8989/South-Dakota-Election-Analysis/main/SD_surplus_vs_Dem_registration_fit_2022_2026.png |

## Data file

- `sd_forward_surplus_2022_2026.csv`: per-county shares, gaps, fitted values and residuals, sorted by population.
