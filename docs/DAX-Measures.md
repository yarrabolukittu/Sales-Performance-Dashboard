# DAX Measures

## Total Sales

```DAX
Total Sales Measure = SUM(Raw_Sales_Data[Sales])
```

## Total Profit

```DAX
Total Profit Measure = SUM(Raw_Sales_Data[Profit])
```

## Total Orders

```DAX
Total Order Measure = DISTINCTCOUNT(Raw_Sales_Data[Order_ID])
```

## Total Customers

```DAX
Total customer Measure = DISTINCTCOUNT(Raw_Sales_Data[Customer_ID])
```

## Profit Margin

```DAX
Profit Margin =
DIVIDE([Total Profit Measure], [Total Sales Measure], 0)
```
