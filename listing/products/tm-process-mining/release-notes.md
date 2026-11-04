## New

- The table adapters read five more Event roles: User, Role, Department, Cost and Amount.
- The model no longer ends a clean reload with a warning about a synthetic key.
- The extensions use license package 1.2.2.

## Changed

- An Activity label that contains an arrow is now safe in Transition selections: two different Transitions never share one key. Keys for other labels are unchanged.
- Template and demo app texts use plain words. The template v5 sheets say what to check when no Cases appear.

## Fixed

- The table adapters accept an apostrophe in a source name.

## Before you upgrade

- Replace the script bundle, reload, and install the 5.6.0 extension packages. A 5.5.x extension on a 5.6 reload keeps working.
