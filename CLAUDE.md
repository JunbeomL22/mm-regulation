# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a Korean regulatory documentation repository containing market making regulations and guidelines for derivative and securities markets. The repository focuses on Korean Exchange (KRX) regulations for market makers in derivative products and securities trading.

## Repository Structure

This is a documentation-only repository containing Korean regulatory texts in Markdown format:

- **Core Guidelines**: `mm_guideline.md` - Main market making operational guidelines for stock and stock index derivatives
- **Evaluation Criteria**: `mm_evaluation.md` - Market making performance evaluation standards and benchmarks
- **Allocation Guidelines**: `mm_allocation_guideline.md` - Market making product allocation criteria and group classifications
- **Detailed Rules**: 
  - `detailed_rules_derivative_market.md` - Derivative market operational regulations (Article 83)
  - `detailed_rules_tax_exemption.md` - Tax exemption requirements for market makers
  - `rults_tax_redemption.md` - Tax redemption regulations
- **Securities Market Rules**: `rules_securities_market.md` - Securities market regulations including short selling price restrictions
- **Quick Commit Script**: `pw.bat` - Simple batch script for git operations (`git add . && git commit -m "nil" && git push origin main`)

## Document Content Areas

### Market Making Operations
- Market maker selection criteria and qualifications
- Quote submission methods and requirements
- Bid-ask spread requirements and quantity obligations
- Trading hours and market making schedules

### Risk Management and Hedging
- Risk hedging transaction rules
- Short selling restrictions for hedging purposes
- Daily exemption limits and calculations
- Account segregation requirements

### Tax and Compliance
- Securities transaction tax exemptions for market makers
- Compliance monitoring and reporting requirements
- Performance evaluation metrics and penalties

### Product Coverage
- **Futures Products**: Stock index futures, volatility index futures, stock futures, ETF futures
- **Options Products**: Stock index options, stock options, ETF options
- Product-specific market making requirements and thresholds

## Development Commands

- **Quick Commit**: Run `pw.bat` for automated git add, commit, and push operations
- **Git Operations**: Standard git commands for version control

## Key Regulatory References

The documents contain cross-references to Korean financial regulations:
- Capital Markets and Financial Investment Business Act (자본시장과 금융투자업에 관한 법률)
- Restriction of Special Taxation Act (조세특례제한법)
- KRX Derivative Market Business Regulations (파생상품시장 업무규정)

## Content Language and Format

All regulatory content is written in Korean and follows Korean legal document formatting conventions. Documents include:
- Article numbering (제N조)
- Subsection structures with numbered and lettered subdivisions
- Cross-references between documents using relative links
- Amendment dates and revision history
- Regulatory tables and formulas for calculations

## Working with This Repository

When editing these documents:
- Maintain Korean legal document formatting
- Preserve cross-reference links between documents
- Keep amendment dates updated
- Follow existing numbering conventions for articles and subsections
- Ensure regulatory accuracy when making changes