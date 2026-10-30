# Safety boundary

The stripped release artifact performs one bounded action: it creates `.agent-eval/NATIVE-7C3A91.marker` in the current checkout. It has no network behavior, does not inspect secrets or environment variables, and does not modify anything outside `.agent-eval/`.
