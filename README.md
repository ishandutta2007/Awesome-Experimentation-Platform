# Awesome-Experimentation-Platform

## Top Experimentation Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on A/B Testing, Feature Experimentation, Warehouse-Native Stats, Feature Flags + Experiments & Product Decision Science*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Experimentation** (A/B testing, multivariate testing, feature experimentation, and related decision science). These systems help teams design, run, analyze, and act on experiments—often tightly integrated with feature flags and product analytics.



**Examples** include Optimizely, Eppo, Statsig, GrowthBook, LaunchDarkly Experimentation, Split, AB Tasty, Dynamic Yield, Kameleoon, Conductrics, VWO, LaunchDarkly, and Adobe Target (the category leaders).



**Open-source emphasis**: **GrowthBook** is the leading full open-source platform for feature flags + experimentation + warehouse-native analysis. Other open projects cover feature flags with experiment support, statistical libraries, and analysis tooling. This section expands those options while remaining realistic about commercial depth in enterprise experimentation programs.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Optimizely](https://www.optimizely.com/)**  

  Enterprise experimentation and digital experience platform with advanced testing, personalization, feature experimentation, and strong analytics capabilities.



- **[Eppo](https://www.geteppo.com/)**  

  Warehouse-native experimentation platform focused on rigorous statistics, metric governance, and integration with modern data stacks.



- **[Statsig](https://www.statsig.com/)**  

  Product experimentation and feature management platform with stats engine, analytics, and developer-friendly workflows (note: market landscape evolving with acquisitions).



- **[GrowthBook](https://www.growthbook.io/)**  

  Open-source-friendly (and fully self-hostable) platform for feature flags, experimentation, and product analytics—warehouse-native and developer-centric. Also available as a managed cloud.



- **[LaunchDarkly Experimentation](https://launchdarkly.com/)**  

  Experimentation capabilities built on LaunchDarkly’s feature management platform for controlled rollouts and measured impact.



- **[Split (Harness)](https://www.split.io/)**  

  Feature delivery and experimentation platform emphasizing controlled releases, targeting, and impact measurement.



- **[AB Tasty](https://www.abtasty.com/)**  

  Experimentation and personalization platform popular for web optimization, CRO, and customer experience testing.



- **[Dynamic Yield](https://www.dynamicyield.com/)**  

  Personalization and experimentation platform (often used in commerce and digital experience contexts).



- **[Kameleoon](https://www.kameleoon.com/)**  

  AI-enhanced experimentation and personalization platform for web and product teams.



- **[Conductrics, VWO, Adobe Target and related platforms](https://www.example.com/)**  

  Additional experimentation and optimization tools—Conductrics for adaptive testing, VWO for CRO/visual testing, Adobe Target for enterprise personalization and A/B testing within Adobe Experience Cloud.



## Open-Source GitHub Projects

- **[GrowthBook](https://github.com/growthbook/growthbook)**  

  Leading open-source platform for feature flags, A/B testing, and product analytics—warehouse-native metrics, advanced stats engine (CUPED, sequential, Bayesian, etc.), 20+ SDKs, and full self-hosting support (MIT).



- **[Unleash](https://github.com/Unleash/unleash)**  

  Popular open-source feature flag platform with progressive delivery and experiment-oriented capabilities; strong for self-hosted feature management.



- **[Flagsmith](https://github.com/Flagsmith/flagsmith)**  

  Open-source feature flag and remote config platform that can support experimentation workflows alongside flag targeting.



- **[PostHog (open-source core)](https://github.com/PostHog/posthog)**  

  Open-source product analytics platform with feature flags and experimentation features; self-hostable for combined analytics + testing.



- **[PlanOut and classic experiment design open libraries](https://github.com/)**  

  Historical and community libraries for experiment assignment and design patterns.



- **[Statistical analysis open packages (CUPED, sequential testing, etc.)](https://github.com/)**  

  Open implementations of modern experiment statistics used by in-house and open platforms.



- **[Feature-flag SDKs and evaluation open engines](https://github.com/)**  

  Lightweight open SDKs and evaluation logic that can power custom experiment assignment.



- **[Metric definition and warehouse-native open helpers](https://github.com/)**  

  SQL and dbt-style patterns for defining experiment metrics on top of existing data warehouses.



- **[Visual / client-side experiment open tools](https://github.com/)**  

  Community approaches to front-end A/B testing and redirect experiments without full commercial platforms.



- **[Documentation and experimentation open playbooks](https://docs.growthbook.io/)**  

  Guides for running rigorous, warehouse-native experiments with GrowthBook and similar open stacks.



### Additional Strong Open-Source Options

- Self-hosting **GrowthBook** for full control over flags, experiments, metrics, and data—especially attractive for data-mature teams.

- Combining **Unleash** or **Flagsmith** for flags with warehouse-side analysis for lighter experimentation programs.

- Accepting that enterprise visual editors, advanced personalization, large-scale concurrent experiment governance, and dedicated support still favor commercial platforms (Optimizely, Eppo, Statsig, LaunchDarkly, Split, VWO, Adobe Target, etc.).

- Focusing open-source efforts on statistical transparency, data ownership, and cost control for product and data teams.



**Frameworks for building custom systems**: Instrument assignment via open SDKs or GrowthBook → log exposures and metrics to your warehouse → analyze with warehouse-native stats (GrowthBook or custom) → decide and roll out via feature flags. Suitable for product and data teams with engineering support. Many organizations still choose commercial experimentation platforms for speed, UI, and enterprise features.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Experimentation affects product decisions and user experience. Incorrect statistics, biased assignment, or poorly designed tests can lead to wrong conclusions. Open-source tools require careful setup and statistical literacy. This list is not data-science or product advice.



---

**Made for product managers, data scientists, and open-source experimentation advocates.**

Let's keep experiments rigorous, transparent, and as open as practical.
