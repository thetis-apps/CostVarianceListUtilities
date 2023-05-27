# Introduction

This application offers functions that may run automatically every time a cost variance list is created.

# Installation

You install the application from the connection view in Thetis IMS. The name of the application is 'thetis-ims-cost-variance-list-utilities'.

# Configuration

In the data document of the context:

```
{
  "CostVarianceListUtilities": {
    "setStandardCostPriceToActualCostPrice": true
  }
}
```
# Options

#### setStandardCostPriceToActualCostPrice

If this field is true, the application will automatically set the standard cost price of all items present on the inbound shipment for which the cost variance list was made. The application sets the standard cost price of each trade item to the actual cost price of that trade item on this inbound shipment.


