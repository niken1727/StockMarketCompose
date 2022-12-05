# StockMarketCompose

## Reuseable Component

1. IconDropDown

### Usage
```kotlin
val countryList = listOf("Nepal", "USA", "JAPAN", "CHINA")
IconDropDown(
    countryList,
    "Select Country",
    false,
    Icons.Default.Flag,
    false,
    Icons.Default.Flag
) {
    Toast.makeText(this, it, Toast.LENGTH_SHORT).show()
}
```
