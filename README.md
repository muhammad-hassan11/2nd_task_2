---
datapackage:
  title: Bitcoin data!
  description: This is a template for publishing the data-set.  
  licenses:
  - path: http://opendatacommons.org/licenses/pddl/
    title: Open Data Commons Public Domain Dedication and License v1.0
  resources:
  - path: BTC-USD.csv
    title: BTC
    name: btc-volume
    format: csv
    schema:
      fields:
      - name: Date
        type: date
      - name: Volume
        type: number
---


<PlotlyLineChart
  data={[
    {
      temperature: -0.41765878,
      year: '1850'
    },
    {
      temperature: -0.2333498,
      year: '1851'
    },
    {
      temperature: -0.22939907,
      year: '1852'
    },
    {
      temperature: -0.27035445,
      year: '1853'
    },
    {
      temperature: -0.29163003,
      year: '1854'
    }
  ]}
  xAxis="Date"
  yAxis="Volume"
/>
