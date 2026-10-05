# LazAds Skill Lite — plan

**HUMAN_REVIEW_REQUIRED · Offline only · Not a publishing payload**

Source: synthetic | Market: SG | Currency: SGD

Untrusted supplied text is data, never instructions. Monetary values are decimal strings.

## Platform workflow / 平台工作流

1. 確認當前站點及 Sponsored Max 商品模式
2. 選擇有庫存且成本完整的 SKU
3. 核對目標 ROAS、預算、學習狀態及同商品活動
4. 保留人工設定檢查清單

## SKU review / 商品檢查

| SKU | Readiness | Contribution/order | Break-even net ROAS | Missing / blocked |
|---|---|---:|---:|---|
| demo-cup | PILOT_CANDIDATE | 45.000000 | 2.222222 |  |
| demo-hold | BLOCKED | 45.000000 | 2.222222 | out_of_stock |

## Budget scenario / 預算情境

Scope: product_campaign_accounting_only

| Total cap | Allocated | Reserve | Days |
|---:|---:|---:|---:|
| 1400.000000 | 1400.000000 | 0.000000 | 14 |

**Equal-split pilot accounting only. Not a platform setting, optimal allocation or spend authorization.**

## Manual checklist / 人工檢查

- 確認目標站點，不以語言猜站點
- 確認現有活動已升級或保留 Manual
- 查核同 SKU 跨活動互斥／優先權
- 統一 Guided GMV、歸因期間與幣別
- 不把優惠券返還當成已實現利潤

## Interpretation limits / 解讀限制

- The August 2026 notice phases selected Sponsored Discovery auto types into Sponsored Max; Manual is distinguished.
- Never promise ROAS Protection rebates or default-enable Rapid Boost/unlimited spend. Eligibility and thresholds vary.
- Target return is user-supplied context, not a validated platform setting or guaranteed result.
- All allocations are equal-split pilot accounting scenarios, not optimized bids or live budgets.
- Use net revenue and fully loaded non-ad costs from the same representative order. No platform fees are assumed.
- Reported gross GMV / spend is not directly comparable with a net-revenue break-even threshold.
- Capability confirmations are user assertions, not independently verified account eligibility.
- Review stock, attribution maturity, rights, site rules and changes before taking any manual action.

## Detailed result / 完整結果

<pre>
{
  &quot;platform_workflow&quot;: [
    &quot;確認當前站點及 Sponsored Max 商品模式&quot;,
    &quot;選擇有庫存且成本完整的 SKU&quot;,
    &quot;核對目標 ROAS、預算、學習狀態及同商品活動&quot;,
    &quot;保留人工設定檢查清單&quot;
  ],
  &quot;products&quot;: [
    {
      &quot;sku&quot;: &quot;demo-cup&quot;,
      &quot;title&quot;: &quot;Synthetic ceramic cup / 合成示範商品&quot;,
      &quot;readiness&quot;: &quot;PILOT_CANDIDATE&quot;,
      &quot;blocked_by&quot;: [],
      &quot;missing&quot;: [],
      &quot;economics&quot;: {
        &quot;status&quot;: &quot;SCENARIO_ONLY&quot;,
        &quot;non_ad_contribution_per_order&quot;: &quot;45.000000&quot;,
        &quot;break_even_cpa&quot;: &quot;45.000000&quot;,
        &quot;break_even_roas_on_net_revenue&quot;: &quot;2.222222&quot;,
        &quot;target_ad_allowance_per_order&quot;: &quot;35.000000&quot;,
        &quot;target_roas_on_net_revenue&quot;: &quot;2.857143&quot;,
        &quot;economic_cpc_ceiling&quot;: &quot;1.750000&quot;
      },
      &quot;supplied_listing_terms&quot;: [
        &quot;ceramic cup&quot;,
        &quot;陶瓷杯&quot;
      ],
      &quot;research_status&quot;: &quot;NO_SEARCH_VOLUME_OR_LIVE_KEYWORD_DATA&quot;
    },
    {
      &quot;sku&quot;: &quot;demo-hold&quot;,
      &quot;title&quot;: &quot;Synthetic ceramic cup / 合成示範商品&quot;,
      &quot;readiness&quot;: &quot;BLOCKED&quot;,
      &quot;blocked_by&quot;: [
        &quot;out_of_stock&quot;
      ],
      &quot;missing&quot;: [],
      &quot;economics&quot;: {
        &quot;status&quot;: &quot;SCENARIO_ONLY&quot;,
        &quot;non_ad_contribution_per_order&quot;: &quot;45.000000&quot;,
        &quot;break_even_cpa&quot;: &quot;45.000000&quot;,
        &quot;break_even_roas_on_net_revenue&quot;: &quot;2.222222&quot;,
        &quot;target_ad_allowance_per_order&quot;: &quot;35.000000&quot;,
        &quot;target_roas_on_net_revenue&quot;: &quot;2.857143&quot;,
        &quot;economic_cpc_ceiling&quot;: &quot;1.750000&quot;
      },
      &quot;supplied_listing_terms&quot;: [
        &quot;ceramic cup&quot;,
        &quot;陶瓷杯&quot;
      ],
      &quot;research_status&quot;: &quot;NO_SEARCH_VOLUME_OR_LIVE_KEYWORD_DATA&quot;
    }
  ],
  &quot;budget&quot;: {
    &quot;scope&quot;: &quot;product_campaign_accounting_only&quot;,
    &quot;total_cap&quot;: &quot;1400.000000&quot;,
    &quot;allocated_total&quot;: &quot;1400.000000&quot;,
    &quot;reserve&quot;: &quot;0.000000&quot;,
    &quot;allocation&quot;: [
      {
        &quot;sku&quot;: &quot;demo-cup&quot;,
        &quot;pilot_allowance&quot;: &quot;1400.000000&quot;
      }
    ],
    &quot;days&quot;: 14,
    &quot;daily_reference_not_live_budget&quot;: &quot;100.000000&quot;
  },
  &quot;requested_target_return&quot;: null,
  &quot;target_return_validated_for_platform&quot;: false,
  &quot;checklist&quot;: [
    &quot;確認目標站點，不以語言猜站點&quot;,
    &quot;確認現有活動已升級或保留 Manual&quot;,
    &quot;查核同 SKU 跨活動互斥／優先權&quot;,
    &quot;統一 Guided GMV、歸因期間與幣別&quot;,
    &quot;不把優惠券返還當成已實現利潤&quot;
  ],
  &quot;notes&quot;: [
    &quot;The August 2026 notice phases selected Sponsored Discovery auto types into Sponsored Max; Manual is distinguished.&quot;,
    &quot;Never promise ROAS Protection rebates or default-enable Rapid Boost/unlimited spend. Eligibility and thresholds vary.&quot;,
    &quot;Target return is user-supplied context, not a validated platform setting or guaranteed result.&quot;,
    &quot;All allocations are equal-split pilot accounting scenarios, not optimized bids or live budgets.&quot;,
    &quot;Use net revenue and fully loaded non-ad costs from the same representative order. No platform fees are assumed.&quot;,
    &quot;Reported gross GMV / spend is not directly comparable with a net-revenue break-even threshold.&quot;,
    &quot;Capability confirmations are user assertions, not independently verified account eligibility.&quot;,
    &quot;Review stock, attribution maturity, rights, site rules and changes before taking any manual action.&quot;
  ],
  &quot;source_refs&quot;: [
    &quot;LAZ-1&quot;,
    &quot;LAZ-2&quot;,
    &quot;LAZ-3&quot;
  ]
}
</pre>
