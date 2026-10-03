# veritas-bridge
Veritas Bridge is a local-first developmental AI runtime that separates candidate development from deployment authority.
Demonstrated qualification includes:
6 failures → 122/122 passing in a fresh autonomous repair run
87 model calls / 2.107M actual tokens processed locally
Successful candidate stopped at creator approval rather than self-deploying
Separate healthy-source investigation:
122/122 → NO CHANGE
53 calls / 1.135M tokens
Across the two completed runs:
140 local model calls / 3.243M tokens on one RTX 4090
Separate release qualification demonstrated rollback/re-adoption while preserving declared persistent state and intervening activity.

Veritas Bridge passed its first independently scored SWE-bench task.

django__django-15382 was evaluated as Resolved using the original saved Veritas patch.

1 task evaluated
1 task resolved
official tests executed
no model rerun for scoring
no patch regeneration

The patch was produced earlier through the Veritas development workflow, preserved, and later submitted unchanged to the independent evaluator.

Broader SWE-bench evaluation is continuing.
