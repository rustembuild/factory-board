# factory-board

Data feed of the dark factory's board: https://rustembuild.github.io/dark-factory-aws/

- Branch `factory-data`, files `data/<short>-state.json`: one snapshot per product repo, written by the factory's state-machine tick (IstiN/dmtools-agents `statePublish`, schema of `js/factoryState.js`) and copied here because the product repos are private.
- Links on the board point at private repos and open only for their collaborators.
- Tokens come from Claude Code's own usage report. $ is the Anthropic API list-price equivalent: the factory runs on a subscription, so this is not a bill. Cache reads are not counted (upstream's leg publish step does not carry them), so $ is a lower bound.

Nothing but the tick writes here. Please do not open pull requests.
