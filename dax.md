# DAX Measures

## Total Purchase Spend

```DAX
Total Spend =
SUM(Purchases[Price])
```

## Purchase Orders

```DAX
Purchase Orders =
COUNT(Purchases[Order No])
```

## Spend YoY %

```DAX
YoY Spend % =
DIVIDE(
    [Current Year Spend] - [Previous Year Spend],
    [Previous Year Spend]
)
