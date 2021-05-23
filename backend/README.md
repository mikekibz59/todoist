# Todoist backend
In this directory is where all code pertaining to backend operations lie. Such operations include: writing backend based unit tests, setting up databases, backend based caching using redis, session and security management.

## Directory structure.
- Below is a representation of how the folder structure is.
```bash
internal/
├── httptransport
|   |restapi
│   |   ├── restapitransport.go
│   |   └── utl.go
├── service
│   ├── service.go
│   └── utl.go
└── service.go
main.go
```

### Directory structure breakdown

#### **Internal**
Parent directory that houses other configuration files and actual business logic
 
`internal/service.go`:~> houses all low level utility functions
