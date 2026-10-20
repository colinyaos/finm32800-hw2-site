# Dataframe: `hw2:fed_funds_futures` - Fed Funds Futures

Daily ohlcv prices of futures contracts corresponding to fed funds rates.


## DataFrame Glimpse

```
Rows: 11764
Columns: 7
$ date   <datetime[ns]> 2026-10-18 00:00:00
$ symbol          <str> 'ZQJ7-ZQK7'
$ open            <f64> 7.5
$ high            <f64> 7.5
$ low             <f64> 7.5
$ close           <f64> 7.5
$ volume          <u64> 8


```

## Dataframe Manifest

| Dataframe Name                 | Fed Funds Futures                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | Databento                                          |
| Providers                      | Databento                                        |
| Provider Links                 |                                    |
| Tags                           | Futures, Federal Reserve                                             |
| Access Types                   |                                       |
| How is data pulled?            | API request via Python                                                   |
| Data available up to (min)     | None                                                             |
| Data available up to (max)     | None                                                             |
| Dataframe Path                 | /Users/colinyao/Desktop/Code/FINM/DataPipelines_32800/hw2-colinyaos/_data/fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file:///Users/colinyao/Desktop/Code/FINM/DataPipelines_32800/hw2-colinyaos/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-20 10:10:46           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

