# Jobs to be Done (JTBD) Analysis

This directory contains a detailed analysis of the Jobs to be Done across Applogie's external personas. The analysis focuses on understanding what users are trying to accomplish, the steps involved, and how different roles interact in completing these jobs.

## Structure

```
jobs-to-be-done/
├── README.md (this file)
├── cross-role/
│   ├── subscription-onboarding.md
│   ├── cost-optimization.md
│   ├── compliance-management.md
│   └── financial-reporting.md
└── role-specific/
    ├── data-specialist/
    ├── subscription-owner/
    ├── finance-director/
    └── company-executive/
```

## Priority Matrix

Below is a prioritized list of Jobs to be Done, ranked by frequency, importance, and number of roles involved:

### High Priority (Critical & Frequent)
1. **[Subscription Onboarding](cross-role/subscription-onboarding.md)** 🔄
   - Affects: All external personas
   - Frequency: Daily/Weekly
   - Impact: High (Financial & Operational)
   - Primary Owner: Samuel Singh (Subscription Owner)
   - Supporting Roles: Diana Dwyer (Data Specialist), Francine Fitzgerald (Finance Director)

2. **[Cost Optimization](cross-role/cost-optimization.md)** 💰
   - Affects: Francine Fitzgerald (Finance Director), Edward Ellsworth (Company Executive), Samuel Singh (Subscription Owner)
   - Frequency: Monthly
   - Impact: High (Financial)
   - Primary Owner: Francine Fitzgerald (Finance Director)
   - Supporting Roles: Samuel Singh (Subscription Owner)

3. **[Financial Reporting & Analysis](cross-role/financial-reporting.md)** 📊
   - Affects: Francine Fitzgerald (Finance Director), Edward Ellsworth (Company Executive)
   - Frequency: Monthly/Quarterly
   - Impact: High (Strategic)
   - Primary Owner: Francine Fitzgerald (Finance Director)
   - Supporting Roles: Diana Dwyer (Data Specialist)

### Medium Priority (Important & Regular)
4. **[Vendor Data Management](role-specific/subscription-specialist/vendor-data-management.md)** 🔍
   - Affects: All customer experiences
   - Frequency: Daily/Ongoing
   - Impact: High (Data Quality)
   - Primary Owner: Sean Statler (Subscription Specialist)
   - Supporting Systems: AI/ML Classification

5. **Data Quality Management** ✅
   - Affects: Diana Dwyer (Data Specialist), Francine Fitzgerald (Finance Director)
   - Frequency: Ongoing
   - Impact: Medium-High (Operational)
   - Primary Owner: Diana Dwyer (Data Specialist)

5. **License Compliance Management** ⚖️
   - Affects: Samuel Singh (Subscription Owner), Francine Fitzgerald (Finance Director)
   - Frequency: Monthly
   - Impact: Medium-High (Risk Management)
   - Primary Owner: Samuel Singh (Subscription Owner)

6. **Vendor Relationship Management** 🤝
   - Affects: Samuel Singh (Subscription Owner), Francine Fitzgerald (Finance Director)
   - Frequency: Ongoing
   - Impact: Medium (Operational)
   - Primary Owner: Samuel Singh (Subscription Owner)

### Lower Priority (Important but Less Frequent)
7. **Strategic Technology Planning** 🎯
   - Affects: Edward Ellsworth (Company Executive), Francine Fitzgerald (Finance Director)
   - Frequency: Quarterly/Annually
   - Impact: High (Strategic)
   - Primary Owner: Edward Ellsworth (Company Executive)

8. **Budget Planning & Allocation** 💵
   - Affects: Francine Fitzgerald (Finance Director), Edward Ellsworth (Company Executive)
   - Frequency: Annually
   - Impact: High (Financial)
   - Primary Owner: Francine Fitzgerald (Finance Director)

## Cross-Role Jobs Detail Files

The following cross-role JTBD documents are available:

- **[Subscription Onboarding](cross-role/subscription-onboarding.md)** - Managing new SaaS subscription integration
- **[Cost Optimization](cross-role/cost-optimization.md)** - Reducing and controlling software spend
- **[Compliance Management](cross-role/compliance-management.md)** - Ensuring security and regulatory requirements
- **[Financial Reporting](cross-role/financial-reporting.md)** - Analyzing and presenting SaaS spend data

Each document includes:
- Step-by-step workflow
- Role responsibilities
- Required inputs and outputs
- Success criteria
- Common challenges
- Related processes

## Role-Specific Jobs

Each persona directory contains detailed documentation for jobs specific to that role, including:
- Daily operational tasks
- Role-specific responsibilities
- Individual success metrics
- Personal challenges and needs

## Usage Guidelines

1. **Reference these JTBDs** when designing new features or workflows
2. **Consider cross-role impacts** when making changes to any process
3. **Update job details** as new insights are gathered from users
4. **Map features** to specific jobs to ensure alignment with user needs

## Next Steps

- [ ] Document detailed workflows for each cross-role JTBD
- [ ] Create process diagrams for complex multi-role jobs
- [ ] Map existing features to specific jobs
- [ ] Identify gaps in current feature support for critical jobs
- [ ] Validate job priorities with user research

---

**Last Updated:** July 21, 2025  
**Maintained by:** Product Research Team
