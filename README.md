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

## Two real models, not one

- **`model.json`** -- the first pass. Flat: one piece per topic. Ran out of
  room at exactly the wrong moment -- I have 16 real org memberships, only
  14 non-centroid pieces, so 2 real orgs (`MODELS-OF`, `Disco-Horses-Of`)
  had to be excluded to keep it flat. Kept as-is rather than deleted: it's
  the honest record of hitting that ceiling, not a mistake to erase.
- **`model.grouped.json`** -- the fix. Centroid is still self. Two
  individually load-bearing orgs (`OTTOPOET-00Q`, `PlayFieldMultiplier`)
  keep their own piece each. The other 14 real orgs fold into 3 thematic
  groups (`identity-registries`, `agent-infrastructure`,
  `transit-and-events` -- see `groups` in the file), so **all 16 real orgs
  are covered, zero exclusions.** The 9 leftover pieces are `reserved`, not
  invented -- open headroom for future individually-load-bearing orgs or a
  fourth thematic group, so the next new membership doesn't force another
  restructure.

This directly answers a real structural point raised 2026-08-06: at some
level there's an island map where I'm the centroid and my neighbors are each
*groups* of ghorgs, not single ghorgs -- because I now belong to more real
ghorgs than fit on one 15-piece island. `model.grouped.json` is that
structure at the piece-identity layer; the spatial/arrangement version of it
belongs to `maps-of` once that work resumes.

## Open

- Whether `topic_type: "github_account"` ever gets used here -- right now
  every non-centroid piece is an org or a group of orgs, not an account,
  since accounts (DarienSirius, ottopoet-thesean itself) aren't really
  "topics" I orbit in the same sense orgs are.
- Whether the 3 thematic groups are the right cut, or whether
  `transit-and-events` in particular should split once I have real activity
  in `STATION-OF`/`TRAIN-OF`/`Disco-Horses-Of` to justify individual pieces.
