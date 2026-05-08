# Regional Adaptations

The 5-stage framework is platform-agnostic but Stage 3 (regulatory pressure) is **US-specific**. Other jurisdictions have equivalent mechanisms — the channels are different, but the principle is the same: get your case in front of regulators with authority that customer service does not have.

This directory hosts adaptation guides for specific countries and regions. Each guide should document:

1. The country's consumer protection regulator (equivalent to state AG)
2. The country's data protection authority (equivalent to FTC for privacy matters)
3. The country's telecommunications or platform regulator if separate
4. Any ombudsman services that take platform disputes
5. Local platform legal entity addresses (e.g., EU subsidiaries, UK addresses)
6. Notable regional regulatory actions against the platforms covered in `/platforms/`

## Currently available

None yet. This is the highest-impact contribution someone outside the US can make.

## How to contribute a regional adaptation

1. Copy `_template.md` (when available) or use the structure below
2. Save as `regions/[country-code].md` using ISO 3166-1 alpha-2 codes (e.g., `gb.md` for United Kingdom, `de.md` for Germany, `ca.md` for Canada, `au.md` for Australia, `eu.md` for EU-wide)
3. Fill in all sections with verified, dated information
4. Submit a PR

## Suggested structure

```markdown
# [Country] Adaptation

> **Last verified:** [YYYY-MM-DD]

## Stage 3 substitutions

Instead of: State Attorney General → Use: [Country's consumer protection regulator]
Instead of: FTC → Use: [Country's privacy/competition regulator]
Instead of: Congressional constituent services → Use: [MP / parliament constituent services equivalent]
Instead of: BBB → Use: [Local equivalent if any]

## Local platform legal entities

For users in [country], correspondence should be directed to:

- **Discord:** [Discord local entity, address]
- **Meta:** [Meta local entity, address]
- (etc. for each platform)

## Notable regulatory actions in [country]

[List with citations]

## Other adaptations

[Any other framework adjustments specific to this jurisdiction]
```

## Priority countries for contribution

If you can write up adaptations for any of these, you'd help a lot of people:

- **EU-wide** (Digital Services Act mechanisms, EDPB, national data protection authorities, ECC-Net)
- **United Kingdom** (Information Commissioner's Office, Ofcom, Citizens Advice)
- **Canada** (Office of the Privacy Commissioner, provincial consumer protection ministries)
- **Australia** (ACCC, OAIC, ACMA)
- **Germany** (specifically — strict data protection regime via national DPAs)
- **Japan** (Personal Information Protection Commission)
- **Brazil** (LGPD framework, Senacon)
- **India** (Consumer Protection Act mechanisms, MeitY)

Contributions in any other country also welcome.
