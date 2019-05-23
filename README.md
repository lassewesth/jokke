nu har jeg 3 triggers:

1. Alle commits og pull requests
2. Kun reelle commits
3. Kun pull requests

OK again, now with branch spec `+:(refs/pull/*/head)`, creating the logical name `refs/pull/*/head` for discriminating in triggers' branch filters

For some reason commits-only is not triggering...

Right, works now with `+:<default>`.

And now, a PR!
