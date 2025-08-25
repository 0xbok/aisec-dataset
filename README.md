# AI Security Dataset

A curated dataset of Solidity smart contract security audit reports and corresponding source code for AI training purposes.

## Overview

This dataset contains 20 recent Solidity projects (June 2024 - November 2024) with their security audit reports, carefully selected and cleaned for AI training applications.

## Dataset Structure

```
├── repos/           # Source code repositories (20 projects)
│   ├── 2024-11-ethena-labs/
│   ├── 2024-10-kleidi/
│   ├── ...
│   └── 2024-06-vultisig/
└── reports/         # Security audit reports (214 files)
    ├── 2024-11-ethena-labs/
    ├── 2024-10-kleidi/
    ├── ...
    └── 2024-06-vultisig/
```

## Project Types

The dataset includes diverse protocol types:

- **DeFi Protocols**: Lending, DEXs, AMMs, aggregators
- **Stablecoin Protocols**: UStb, Reserve Protocol
- **NFT Protocols**: Trading, gaming, trait systems
- **Staking/Restaking**: Ethereum staking infrastructure  
- **Cross-chain**: Bridge and multi-chain protocols
- **Security Tools**: Multisig, access control systems

## Data Statistics

- **Total Projects**: 20
- **Repository Files**: 8,104 files
- **Audit Reports**: 214 security findings
- **Time Range**: June 2024 - November 2024
- **Languages**: Primarily Solidity with test files

## Report Format

All reports follow a standardized format:
- `## [H]` - High severity findings
- `## [M]` - Medium severity findings  
- `## [L]` - Low severity findings

Reports have been cleaned to remove:
- External URLs and links
- Audit commentary and administrative notes
- Test artifacts and build outputs
- Relative path references

## Projects Included

1. **2024-11-ethena-labs** - Stablecoin Protocol (2 reports)
2. **2024-10-kleidi** - Smart Contract Security/Multisig (3 reports)
3. **2024-10-loopfi** - DeFi Lending Protocol (7 reports)
4. **2024-10-ramses-exchange** - DEX/AMM Protocol (2 reports)
5. **2024-09-fenix-finance** - DeFi Protocol (7 reports)
6. **2024-08-basin** - Liquidity Pool Protocol (1 report)
7. **2024-08-phi** - Gaming/NFT Protocol (15 reports)
8. **2024-08-wildcat** - Lending Protocol (9 reports)
9. **2024-07-basin** - Liquidity Pool Protocol (4 reports)
10. **2024-07-benddao** - NFT Lending Protocol (28 reports)
11. **2024-07-dittoeth** - DeFi Protocol (5 reports)
12. **2024-07-karak** - Staking/Restaking Protocol (9 reports)
13. **2024-07-loopfi** - DeFi Lending Protocol (54 reports)
14. **2024-07-munchables** - Gaming Protocol (6 reports)
15. **2024-07-reserve** - Stablecoin Protocol (7 reports)
16. **2024-07-traitforge** - NFT Protocol (25 reports)
17. **2024-06-badger** - DeFi Protocol (2 reports)
18. **2024-06-krystal-defi** - DeFi Aggregator (5 reports)
19. **2024-06-size** - DeFi Protocol (17 reports)
20. **2024-06-vultisig** - Cross-chain Protocol (6 reports)

## Usage

This dataset is intended for:
- Training AI models on smart contract security analysis
- Research in automated vulnerability detection
- Educational purposes in blockchain security
- Development of static analysis tools

## Data Quality

- All projects are verified Solidity-based
- Reports are standardized and cleaned
- Source code includes tests and documentation
- Recent timeframe ensures modern Solidity patterns

## License

The individual projects retain their original licenses. This dataset compilation is provided for research and educational purposes.