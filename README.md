# Test COP project

*description of the project*

**Timeframe** 2026-08-31 - 2026-12-07

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/test-cop-project-2026](https://cra-test-arc.canada.ca/test-cop-project-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-09-14

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Income tax)
    node4(Personal income tax)
    node5(Tax rates and income brackets)
    node6(Who should file a tax return)
    node7(Get ready to file a tax return)
    node8(How to file a tax return – Personal income tax)
    node9(After filing a tax return)
    node10(Help others with their taxes)
    node11(Reporting income)
    node12(Claiming deductions, credits, and expenses)
    node13(Due dates and payment dates)
    node14(Learn about your taxes)
    node15(Persons with disabilities, their caregivers, and the CRA)
    node16(Adults 65 years and older and the CRA)
    node17(Students and the CRA)
    node18(Test)
    node19(Business or professional income)
    node20(CRA resources for small and medium businesses)
    node21(Trust income tax)
    node22(Overview)
    node23(Trust income tax return)
    node24(Trust information returns – slips and summaries)
    node25(Trust types and codes)
    node26(Specified investment flow-through trust income and distribution tax)
    node27(Retirement Compensation Arrangements)
    node28(How to apply)
    node29(Sole proprietorships and partnerships)
    node30(T5013 Partnership Information Return filing requirements)
    node31(Business expenses)
    node32(International and non-resident taxes for bananas)
    node33(Non-residents living in and outside Canada)
    node34(Disposing of or acquiring certain Canadian property)
    node35(How the Canada Revenue Agency #40;CRA#41; works with other tax authorities)
    node36(Doing taxes for someone who died)
    node37(Brochure: Doing taxes for someone who died)
    node38(Represent someone who died)
    node39(Notify the CRA of a date of death)
    node40(Prepare tax returns for someone who died)
    node41(Apply for a clearance certificate)
    node42(Special elections and returns)
    node43(Keeping records)
    node44(Businesses – International and non-resident taxes)
    node45(Transfer pricing)
    node46(Income tax information for non-resident corporations)
    node47(Payments to non-residents)
    node48(Country-by-Country Reporting)
    node49(Corporation income tax)
    node50(Federal tax credits for corporations)
    node51(Corporate income tax payments)
    node52(Foreign spin-offs)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --x node5
    node4 --> node6
    node4 --> node7
    node4 --> node8
    node4 --> node9
    node4 --> node10
    node4 --> node11
    node11 --> node12
    node12 --> node13
    node4 --> node14
    node4 --> node15
    node4 --> node16
    node4 --> node17
    node17 --> node18
    node3 --> node19
    node19 --> node20
    node3 --> node21
    node21 --> node22
    node21 --> node23
    node21 --> node24
    node21 --> node25
    node21 --> node26
    node21 --> node27
    node21 --x node28
    node3 --x node29
    node29 --> node30
    node29 --> node31
    node3 --> node32
    node32 --> node33
    node32 --> node34
    node32 --> node35
    node3 --> node36
    node36 --> node37
    node36 --> node38
    node36 --> node39
    node36 --> node40
    node36 --> node41
    node3 --> node42
    node3 --x node43
    node3 --x node44
    node44 --> node45
    node44 --> node46
    node44 --> node47
    node44 --> node48
    node3 --> node49
    node49 --> node50
    node49 --> node51
    node49 --> node52

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node3,node4,node5,node6,node7,node8,node9,node10,node11,node12,node13,node14,node15,node16,node17,node18,node19,node20,node21,node22,node23,node24,node25,node26,node27,node28,node30,node31,node32,node33,node34,node35,node36,node37,node38,node39,node40,node41,node42,node43,node45,node46,node47,node48,node49,node50,node51,node52 inscope
    classDef isnew fill:#00706f,color:#fff
    class node18 isnew
    classDef ismoved fill:#eab308,color:#000
    class node12,node13 ismoved
```
