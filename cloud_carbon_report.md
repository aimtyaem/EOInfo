# Carbon Footprint Report for CloudTech Solutions

## Energy Cost Analysis
| Energy Source | Cost per Unit |
|---------------|-------------|
| electricity | $85.00 |
| natural_gas | $12.00 |
| fuel_oil | $0.75 |

## Cloud Infrastructure Profile
### AWS Region Emissions Factors
| Region | Emissions Factor (tCO2e) | Data Source |
|--------|--------------------------|-------------|
| us-east-1 | 0.000416 | EPA |
| us-east-2 | 0.000440 | EPA |
| us-west-1 | 0.000351 | EPA |
| us-west-2 | 0.000351 | EPA |
| us-gov-east-1 | 0.000416 | EPA |
| us-gov-west-1 | 0.000351 | EPA |
| af-south-1 | 0.000928 | carbonfootprint.com |
| ap-east-1 | 0.000810 | carbonfootprint.com |
| ap-south-1 | 0.000708 | carbonfootprint.com |
| ap-northeast-3 | 0.000506 | carbonfootprint.com |
| ap-northeast-2 | 0.000500 | carbonfootprint.com |
| ap-southeast-1 | 0.000409 | EMA Singapore |
| ap-southeast-2 | 0.000790 | carbonfootprint.com |
| ap-northeast-1 | 0.000506 | carbonfootprint.com |
| ca-central-1 | 0.000130 | carbonfootprint.com |
| cn-north-1 | 0.000555 | carbonfootprint.com |
| cn-northwest-1 | 0.000555 | carbonfootprint.com |
| eu-central-1 | 0.000338 | EEA |
| eu-west-1 | 0.000316 | EEA |
| eu-west-2 | 0.000228 | EEA |
| eu-south-1 | 0.000233 | EEA |
| eu-west-3 | 0.000052 | EEA |
| eu-north-1 | 0.000008 | EEA |
| me-south-1 | 0.000732 | carbonfootprint.com |
| sa-east-1 | 0.000074 | carbonfootprint.com |

### Server Architecture Efficiency
| Architecture | Power Consumption Range |
|--------------|--------------------------|
| Graviton | 0.47-1.69 W |
| Ivy Bridge | 3.04-8.25 W |
| Sandy Bridge | 2.17-8.58 W |
| Haswell | 1.90-6.01 W |
| Sky Lake | 0.64-4.19 W |
| Cascade Lake | 0.64-3.97 W |
| EPYC 2nd Gen | 0.47-1.69 W |
| Graviton2 | 0.47-1.69 W |
| Broadwell | 0.71-3.69 W |
| EPYC 1st Gen | 0.82-2.55 W |
| Coffee Lake | 1.14-5.42 W |

## Optimization Recommendations
1. **Region Optimization**: Consider shifting workloads to lower-emission regions like eu-north-1
2. **Architecture Upgrade**: Migrate to Graviton-based instances for better energy efficiency
3. **Renewable Energy**: Explore AWS Renewable Energy Programs for carbon offset
4. **Instance Right-Sizing**: Use compute-optimized architectures for energy-intensive workloads