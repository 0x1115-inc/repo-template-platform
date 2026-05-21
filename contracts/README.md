# Contracts

## Purpose
This directory contains canonical system contracts shared across services. 

Contracts define how services communicate and integrate.

## Example
- Open API specifications for REST APIs
- Event schemas for message queues
- Shared JSON schemas for data validation
- gRPC contracts for RPC communication
- Authentication and authorization contracts

## Principles
### Canonical Ownership
Contracts stored here considered the single source of truth. 

Service repositories may generate clients or models from these contracts, but should not redefine them independently.

### Backward Compatibility
Breaking contract changes must:
- Be documented
- Be versioned
- Include migration strategy

### Example structure
```text
contracts/
├── openapi/
│   ├── service-a.yaml
│   └── service-b.yaml
├── events/
│   ├── user-created.json
│   └── order-placed.json
├── schemas/
│   ├── user.json
│   └── order.json
├── grpc/
│   ├── service-a.proto
│   └── service-b.proto
└── auth/
    ├── jwt-schema.json
    └── oauth2-flows.yaml
```