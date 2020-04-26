+++
authors = []
date = 2020-04-29T14:00:00Z
draft = true
excerpt = "lorem ipsum"
hero = ""
timeToRead = 5
title = "Test Title"

+++
body

    {
      "orderNumber": "string",
      "warehouseCode": "string",  
      // "orderType": "string",
      "orderLineDetails": [
        {
          "lineItemCode": "string",
          "materialCode": "string",
          "quantity": 0,
          "unitOfMeasure": "string",
          "lotNumber": "string",
          "useByDate": "2020-04-10T06:38:38.470Z",
          "totWeight": 0,
          "bondItem": "string",
          "bondWarehouseUnitValue": 0,
          "bondTransportInsuranceValue": 0,
          "bondMovePermission": "string",
          "bondRemissionNumber": "string",
          "bondDestructionNumber": "string",
          "palletDetails": [
            {
              "palletSeqNumber": "string",
              "despatchPalletNumber": "string",
              "eanPalletNumber": "string",
              "fromPalletNumber": "string",
              "palletQuantity": 0,
              // "palletUnitOfMeasure": "string",
              // "palletLotNumber": "string",
              // "palletUseByDate": "2020-04-10T06:38:38.470Z",
              "palletWeight": 0,
              // "palletBondItem": "string"
              "palletTypeCode": "string",
              "itemDetails": [
                {
                  "itemSeqNumber": "string", 
                  "itemNumber": "string",
                  "itemQuantity": 0 
                }
            ]
            }
          ]
        }
      ]
    }