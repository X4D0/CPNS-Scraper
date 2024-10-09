
# CPNS Scraper 2024

Scrape all CPNS formation (from sscasn.bkn.go.id) based on Study Program and export it to excel.


## API Reference

#### Get Data

```http
  GET https://api-sscasn.bkn.go.id/2024/portal/spf
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `kode_ref_pend` | `string` | **Required**. Education ID |
| `offset` | `string` | **Required**. Offset = 0 |

