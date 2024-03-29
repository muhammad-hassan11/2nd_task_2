<FlatUiTable url="https://query1.finance.yahoo.com/v7/finance/download/BTC-USD?period1=1410912000&period2=1711670400&interval=1mo&events=history&includeAdjustedClose=true" />

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
  xAxis="year"
  yAxis="temperature"
/>



<VegaLite
  data={{
    table: [
      {
        x: 1850,
        y: -0.418
      },
      {
        x: 2020,
        y: 0.923
      }
    ]
  }}
  spec={{
    $schema: 'https://vega.github.io/schema/vega-lite/v4.json',
    data: {
      name: 'table'
    },
    encoding: {
      x: {
        field: 'x',
        type: 'ordinal'
      },
      y: {
        field: 'y',
        type: 'quantitative'
      }
    },
    mark: 'bar'
  }}
/>

