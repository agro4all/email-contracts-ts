# email-contracts-ts

Auto-generated TypeScript interfaces for Agro4all email templates.

**Do not edit manually.** This repo is updated by the `email-contracts-publish` CI job in the server repo whenever `email_contracts/` changes.

## Usage

```json
"email-contracts-ts": "github:agro4all/email-contracts-ts"
```

```ts
import type { ConnectMPSData, ForgotPasswordData } from 'email-contracts-ts'
```

## Source

Go structs: `email_contracts/` in the server repo.  
Regenerate: `cd email_contracts && go tool tygo generate`
