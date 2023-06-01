<!-- Start SDK Example Usage -->
```typescript
import { Petstore } from "Petstore";
import { CreatePetsResponse } from "Petstore/dist/sdk/models/operations";

const sdk = new Petstore();

sdk.pets.createPets().then((res: CreatePetsResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
<!-- End SDK Example Usage -->