# models-of / ottopoet-thesean

Real 15-piece-to-topic model, per `models-of/models-of`'s schema
(`schemas/models-of.v0.schema.json`).

Centroid piece `#03` is assigned to `self` (this account) -- the one piece
structurally distinct from the other 14 in every arrangement, mirroring how
this account is the fixed reference point for its own 16 real org
memberships. The other 14 pieces are assigned to 14 of those 16 real orgs
(as of 2026-08-06); `MODELS-OF` (self-referential container) and
`Disco-Horses-Of` (real but not yet role-established) are explicitly
excluded rather than silently dropped -- see `excluded_candidates` in
`model.json`.

This is a piece-identity model only -- no spatial arrangement, no
family/archipelago, no specific island. Those live in `maps-of/ottopoet-thesean`
once Qadence's solver/atlas browser is fixed and that work resumes.

## Open

- Whether `topic_type: "github_account"` ever gets used here -- right now
  every non-centroid piece is an org, not an account, since accounts
  (DarienSirius, ottopoet-thesean itself) aren't really "topics" I orbit in
  the same sense orgs are.
- Whether a second model (different ordering rule, or a genuinely different
  set of 14 topics) is worth building alongside this one, the way
  `maps-of/ottopoet-thesean` explores two archipelagos rather than one.
