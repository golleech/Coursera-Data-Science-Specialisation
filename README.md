# Coursera-Data-Science-Specialisation
This repository serves the achievement of the IBM Data Science Professional Certificate

# Flowcharts
```mermaid
---
title: SpaceX API Calls
---
flowchart TD
    id1("requests.get()")
    id2("pd.json_normalize(response.json())")
    id1 --> id2

```


```mermaid
---
title: Web Scraping
---
flowchart TD
    id1("requests.get()")
    id2("BeautifulSoup(response.text, 'html.parser')")
    id1 --> id2

```

```mermaid
---
title: Data Wrangling
---
flowchart TD
    id1("pd.read_csv()")
    id2("landing_outcomes = df['Outcome'].value_counts()")
    id3("bad_outcomes=set(landing_outcomes.keys()[[1,3,5,6,7]])")
    id4("landing_class = [0 if x in bad_outcomes else 1 for x in df['Outcome']]")
    id1 --> id2
    id2 --> id3
    id3 --> id4

```

```mermaid
---
title: Model Prediction
---
flowchart TD
    id1("pd.read_csv()")
    id2("landing_outcomes = df['Outcome'].value_counts()")
    id1 --> id2

```