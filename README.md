# interactor-rebac

Relationship-based access control graph checks for Elixir, backed by the taskweft native library.

## What it is for

A graph is a set of subject, relation and object edges. A check asks whether a subject satisfies a relation expression against an object, where an expression combines base relations by union, intersection, difference and tuple-to-userset pivots.

## Build and run

```sh
mix deps.get
mix compile
```

## Licence

MIT; see LICENSE.
