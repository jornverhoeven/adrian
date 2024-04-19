# ADRIAN: Automated decentralized management of cybersecurity risks

This is the repository for the ADRIAN project, containing the source code and results of the research project.

## Authors

- Sven Smolka (1)
- Jorn J. Verhoeven (2)
- Zoltán  Ádám Mann (2)

1. University of Duisburg-Essen, Essen, Germany
2. University of Amsterdam, Amsterdam, The Netherlands


## Risk Rules

| Name | Rule Type | Pk | Adaptation | Mitigation Probability
| ---- | --------- | ---- | ---- | --- |
| Uncertainty | Inward | 0.08 | N.A. |
| Firewall | Backward | 0.8 | Enable Property | 0.2
| Physically Secured | Backward | 0.8 | Enable Property | 0.2
| Software Encrypted | Backward | 0.8 | Enable Property | 0.2
| CVE-2020-3676 | Forward | 0.8 | Enable Property | 0.2
| CVE-2021-22547 | Forward | 0.18 | Version Change | 0.0
| CVE-2021-40830 | Inward | 0.18 | Version Change | 0.0
| CVE-2022-25666 | Forward | 0.28 | Version Change | 0.0
| CVE-2022-359274 | Backward | 0.08 | Version Change | 0.0
| CVE-2022-359274 | Inward | 0.39 | Version Change | 0.0
| Firmware Risk* | Forward | 0.1 | N.A. |
| OS Risk* | Forward | 0.4 | Version Change | 0.0
| SDK Risk* | Forward | 0.99 | Version Change | 0.0

* These risks are used for testing and are made up, and thus they have no real-world


## Results

### Scenario 1
![damage](graphs/scenario-1/damage.png)
![messages](graphs/scenario-1/messages.png)
![adaptations](graphs/scenario-1/adaptations.png)
![unique-risks](graphs/scenario-1/unique-risks.png)
![remaining-risks](graphs/scenario-1/remaining-risks.png)
![auctioning-time](graphs/scenario-1/auctioning-time.png)
![adapting-time](graphs/scenario-1/adapting-time.png)

### Scenario 2
![damage](graphs/scenario-2/damage.png)
![messages](graphs/scenario-2/messages.png)
![adaptations](graphs/scenario-2/adaptations.png)
![unique-risks](graphs/scenario-2/unique-risks.png)
![remaining-risks](graphs/scenario-2/remaining-risks.png)
![auctioning-time](graphs/scenario-2/auctioning-time.png)
![adapting-time](graphs/scenario-2/adapting-time.png)

### Scenario 3
![damage](graphs/scenario-3/damage.png)
![messages](graphs/scenario-3/messages.png)
![adaptations](graphs/scenario-3/adaptations.png)
![unique-risks](graphs/scenario-3/unique-risks.png)
![remaining-risks](graphs/scenario-3/remaining-risks.png)
![auctioning-time](graphs/scenario-3/auctioning-time.png)
![adapting-time](graphs/scenario-3/adapting-time.png)

### Scenario 4
![damage](graphs/scenario-4/damage.png)
![messages](graphs/scenario-4/messages.png)
![adaptations](graphs/scenario-4/adaptations.png)
![unique-risks](graphs/scenario-4/unique-risks.png)
![remaining-risks](graphs/scenario-4/remaining-risks.png)
![auctioning-time](graphs/scenario-4/auctioning-time.png)
![adapting-time](graphs/scenario-4/adapting-time.png)

### Miscellaneous
![small-infrastructures](graphs/small-infra.png)
![consistency](graphs/consistency.png)
