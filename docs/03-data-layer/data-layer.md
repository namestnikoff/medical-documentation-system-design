# Data Layer

## Logical Model
- Key entities: Patient, Doctor, MedicalDocument, Appointment, Service, Signature, DataEvent.

## Database rationale
- Primary DBMS: PostgreSQL.
- Rationale: transactions, scalability, medical domain adoption.

## GraphQL Example
```graphql
type Patient {
  id: ID!
  fio: String!
  appointments: [Appointment]
  documents: [MedicalDocument]
}
type Query {
}
```

