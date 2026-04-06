# Carpark Engine Tests

xUnit test project for the [Carpark Engine](https://github.com/vinhngogia0906/VinhNgo-Emprevo-Challenge-CarparkEngine) application.

## Test Coverage

| Test Class | Scope |
|------------|-------|
| `PriceCalculatorTest` | Validates price calculation for Standard, Weekend, and other rate scenarios |
| `QueryTest` | Verifies the instruction string and pricing rate list returned by the Query API |
| `MutationTest` | Tests ticket submission with valid input, default/null values, reversed entry/exit, future dates, and `DateTime.MinValue` |
| `ModelTest` | Covers model instantiation and property assignment |

## Setup

This project must be placed in the same parent directory as the [Carpark Engine](https://github.com/vinhngogia0906/VinhNgo-Emprevo-Challenge-CarparkEngine) repository so the solution file can reference both projects.

```
parent-folder/
  VinhNgo-Emprevo-Challenge-CarparkEngine/
  CarparkEngine.Tests/
```

## Running Tests

From the Carpark Engine solution in Visual Studio, or from the command line:

```
dotnet test
```
