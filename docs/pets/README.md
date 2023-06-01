# pets

### Available Operations

* [createPets](#createpets) - Create a pet
* [listPets](#listpets) - List all pets
* [showPetById](#showpetbyid) - Info for a specific pet

## createPets

Create a pet

### Example Usage

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

## listPets

List all pets

### Example Usage

```typescript
import { Petstore } from "Petstore";
import { ListPetsResponse } from "Petstore/dist/sdk/models/operations";

const sdk = new Petstore();

sdk.pets.listPets({
  limit: 548814,
}).then((res: ListPetsResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```

## showPetById

Info for a specific pet

### Example Usage

```typescript
import { Petstore } from "Petstore";
import { ShowPetByIdResponse } from "Petstore/dist/sdk/models/operations";

const sdk = new Petstore();

sdk.pets.showPetById({
  petId: "provident",
}).then((res: ShowPetByIdResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
