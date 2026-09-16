# Ledger
A credits-and-ledger service in Node + TypeScript. 

## In scope
One mock store webhook → idempotent credit issuance
Conditional-update debit that can't go negative
Append-only ledger
Reconciliation endpoint + replay
A load test that proves the invariant holds