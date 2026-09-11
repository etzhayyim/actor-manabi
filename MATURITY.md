# Maturity

Manabi remains an R0 actor with executable CLJC boundaries and intentionally
blocked certificate-preparation scaffolds. Activation still requires the Council
conditions recorded in the actor-owned ADRs.

The standalone migration makes EDN authoritative, isolates protocol JSON under
`wire/`, and removes deprecated Python and shell execution paths. `kbb -M:test` covers
the actor boundary, education handlers, constitutional gates, and cert-prep
activation guards.
