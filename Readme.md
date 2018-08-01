# Service Manifest

We seek to represent a service evolution in a environment of constant change, taking several aspects
that we consider important to encourage a secure collaboration environment.

We seek represent a service life cycle, to do this we split it into stages that describe its evolution clearly and allow to others eval, implement and collaborate

---

## Stages

### Stage-0

We consider a service that have been develop as a **POC** (Proof of concept) to test an idea and could
be deleted in any moment for any reason without any notification.

### Stage-1

We consider a service that have been initiate it development cycle and it is in an **early stage** when its definitions and features are in
constant change without previous notification and **without consider** a third connected parties.

It should have:

- A documentation page (**Readme**) where describe the bussiness domain is trying to resolve and the current stage of service.

### Stage-2

We consider a service that have been reach a madurity in its bussiness domain enought to have its resources well defined.
In this stage the service **adopt the compromise to consider a third connected parties**, keeping its resources inmmutables or retro compatible.

It should have:

- **Stage-1**
- Living documentation (Swagger, static documentation).
- Interface schema well defined (Restful, grpc).

### Stage-3

We consider a service that have been reach a complete madurity on its bussiness domain and it has been open to its comunity for support
and probable development.

It should have;

- **Stage-2**
- Well defined **collaboration model**

### Deprecated

We consider a service that will be deprecated for any reason in a short of time.

It should have:

- Term of service date
