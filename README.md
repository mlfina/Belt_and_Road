# Belt_and_Road
We use text analysis to construct two indicators of **firms' engagement in BRI**, and then explore their **impact on firms' stock return**.
Please refer to [He, Liao, and Wang (2024)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4991688) for details.
### Download via links
- [The first measure: BR_Report](https://github.com/mlfina/Belt_and_Road/blob/main/BRC12.csv)
  - We construct the first measure of firm-level BRI exposure based on firms' self-disclosure in their annual reports. Specifically, we count the frequency of the term "Belt and Road" in these reports to assess how actively firms report their engagement.
    Our dataset covers 26,131 annual reports from 4,996 A-share public firms between 2014 and 2021. The BR_Report score reflects the extent of a firm's self-disclosed engagement with the BRI, where a higher score indicates more active reporting.
- [The second measure: BR_Beta](https://github.com/mlfina/Belt_and_Road/blob/main/bri_beta_set.csv)
  - We construct the second measure of firm-level BRI exposure using a market-based BRI news index. This index tracks the frequency of "Belt and Road" mentions in news articles, adjusting for article length. The data spans from 2015 to 2021, capturing how the market reacts to BRI-related developments.

    From this index, we calculate BR_Beta through rolling regressions of stock returns on the BRI index, controlling for key market factors. BR_Beta reflects the firm's engagement with BRI from a market perspective, where a higher value indicates a stronger connection to the initiative.
