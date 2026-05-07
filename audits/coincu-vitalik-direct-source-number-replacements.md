# Coincu Vitalik Direct-Source Number Replacements

- Target URL: `https://coincu.com/vitalik-buterin-net-worth-2024-update/`
- Audit type: direct-source numeric replacement plan
- Source basis: Arkham entity screenshots supplied by user
- Audit date: 2026-05-07

## Scope

This file only covers numeric replacements that can be supported directly by the screenshots provided from the Arkham entity page. It intentionally avoids numbers that are not visible in those screenshots.

## Primary numeric values visible in the screenshots

### Current portfolio snapshot

Source: `Image #1` and `Image #2`

- total portfolio value: `$528,699,983.91`
- ETH price: `$2,336.21`
- ETH holdings: `224.234K ETH`
- ETH value: `$523.86M`
- WHITE holdings: `10B WHITE`
- WHITE value: `$1.89M`
- AETHLUSD holdings: `1.755M`
- AETHLUSD value: `$1.76M`
- ZCHF holdings: `398.718K ZCHF`
- ZCHF value: `$510.36K`
- MOODENG holdings: `30.002B MOODENG`
- MOODENG value: `$178.51K`
- USDC holdings: `120.99K USDC`
- USDC value: `$120.99K`
- WETH holdings: `46.38 WETH`
- WETH value: `$108.43K`

### Portfolio archive snapshot

Source: `Image #3`

- archive date shown: `5/7/2026`
- holdings value on that snapshot: `$534.77M`
- net change since 10/11/2015: `+$534.76M`
- ETH holdings in archive snapshot: `224.57K ETH`
- ETH value in archive snapshot: `$530.15M`
- ETH price in archive snapshot: `$2,360.72`

### Historical ETH ownership table

Source: `Image #4`

- 31 Dec 2024 ETH owned: `240,610`
- 31 Dec 2024 ETH supply share: `0.20%`
- 31 Dec 2025 ETH owned: `240,010`
- 31 Dec 2025 ETH supply share: `0.20%`

## Old-number to new-number replacement plan

### 1. Replace the outdated current net worth framing

If the article currently says or implies:

> As of May 2025, Vitalik Buterin's net worth has exceeded $1 billion.

Replace with:

> As of Arkham’s latest visible portfolio snapshot, Vitalik Buterin’s tracked holdings are worth $528,699,983.91.

Source:

- `Image #1`

### 2. Replace the outdated current ETH holdings value

If the article currently says or implies:

> his ETH holdings on June 6, 2024 were worth about $949.72 million

Replace with:

> Based on Arkham’s latest visible portfolio snapshot, Vitalik Buterin currently holds 224.234K ETH worth about $523.86 million at an ETH price of $2,336.21.

Source:

- `Image #1`
- `Image #2`

### 3. Replace the outdated majority-of-net-worth claim

If the article currently says or implies:

> the majority of his net worth of $953.4 million comes from ETH

Replace with:

> Ethereum remains the dominant part of Buterin’s tracked portfolio. Arkham’s current snapshot shows 224.234K ETH worth about $523.86 million out of a total portfolio value of $528.70 million.

Source:

- `Image #1`
- `Image #2`

### 4. Add an archive-based current-year checkpoint

Suggested replacement or insertion:

> Arkham’s portfolio archive dated 5/7/2026 shows Buterin’s tracked holdings at $534.77 million, including about 224.57K ETH worth $530.15 million.

Source:

- `Image #3`

### 5. Replace vague historical 2024-2025 ETH balance references

If the article currently has historical 2024-2025 ETH balance claims without a direct source table, replace them with:

> Arkham’s historical holdings table shows that Buterin held 240,610 ETH on 31 December 2024 and 240,010 ETH on 31 December 2025, equal to about 0.20% of Ethereum’s total supply in both years.

Source:

- `Image #4`

## Ready-to-paste replacement paragraphs

### Current net worth paragraph

```md
As of Arkham’s latest visible portfolio snapshot, Vitalik Buterin’s tracked holdings are worth $528,699,983.91. Ethereum remains the largest part of his portfolio, with 224.234K ETH valued at about $523.86 million at an ETH price of $2,336.21.
```

### Archive-based current-year paragraph

```md
Arkham’s portfolio archive dated 5/7/2026 shows his tracked holdings at $534.77 million, including about 224.57K ETH worth $530.15 million at an ETH price of $2,360.72.
```

### Historical 2024-2025 paragraph

```md
Arkham’s historical ETH ownership table shows that Buterin held 240,610 ETH on 31 December 2024 and 240,010 ETH on 31 December 2025, representing about 0.20% of Ethereum’s total supply in both years.
```

## Important usage notes

- Do not mix the `Image #1 / Image #2` current snapshot numbers with the `Image #3` archive snapshot numbers in the same sentence unless you explicitly name the snapshot date.
- Do not replace ranking claims such as `Vitalik is 29th among ETH holders` using the supplied screenshots, because the provided top-holders image does not show Vitalik’s row directly.
- Do not replace sale-specific numbers such as `17,196 ETH sold` or `$35M sold` from this file alone, because those numbers are not visible in the screenshots supplied for this step.

## Source image mapping

- `Image #1`: current total portfolio value and asset list
- `Image #2`: current holdings by asset and value
- `Image #3`: portfolio archive snapshot dated `5/7/2026`
- `Image #4`: historical ETH ownership and ETH supply percentage table
- `Image #5`: not sufficient on its own to update Vitalik-specific holder ranking claims
