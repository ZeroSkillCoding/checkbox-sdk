# @checkbox-sdk/types

TypeScript definitions for the Checkbox API, automatically generated with `openapi-typescript`
from the official [OpenAPI schema](https://api.checkbox.ua/api/openapi.json).

The package provides types only. It does not make HTTP requests or include an API client.

## Installation

```sh
npm install --save-dev @checkbox-sdk/types
```

## Usage

```ts
import type { components, operations, paths } from '@checkbox-sdk/types';

type ValidationError = components['schemas']['HTTPValidationError'];
```

- `components` — reusable API schemas, including request and response models.
- `operations` — endpoint definitions indexed by operation ID.
- `paths` — endpoint definitions indexed by URL path and HTTP method.

Use `import type` to keep these definitions out of your JavaScript bundle. The types
describe the API schema; they do not validate responses at runtime.
