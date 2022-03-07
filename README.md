# vrs-magenta-poc

## __PROBLEM__
ttt
Today, there is no straightforward way to deploy a skill or voice application on multiple conversation platforms. Interoperability is pretty much non-existent.

We will cover two use cases:
1. Small companies that do not have their conversation platform
2. Big enterprise companies that can afford their conversation platform

See [diagram](https://app.diagrams.net/#G1PefRExlnl6POx4aTzf_Zw__PpWzA5E0Q)

## __SCOPE__
- Integration with Deutsche Telekom Voice Platform (Magenta) and VRS
- Use Case: Target shops opening hours request (not for specific date)
- Explicit Utterance: User utters explicitely the agent name "Target" in his request
- Magenta always forwards to VRS
- Magenta is destination for VRS response, no 3rd part agent integrated in PoC
- Simple web frontend with Push-to-Talk interaction for input and output (TTS)
- Enabled language = English only

## __EXPECTED OUTCOMES__
Prio 1:
- Deliver VRS and Magenta integration
- Understand the minimum viable contract between VRS and Magenta
- Understand which and how much meta data needs to be shared between systems

Prio 2:
- Understand better how much business logic needs to be implemented in the VRS
- Understand requirements for VRS (incl. future requirements)
- Raise questions for future VRS development

Prio 3:
- Understand the latency criteria between VRS and Magenta

## __OUT OF SCOPE__
- Privacy and Security are not part of the POC
- Latency
- Disambiguation 
- Reprompt handling
- Domain unknown
- Reuse of existing Magenta voice assistant

## __REPOSITORIES__
- [VRS](https://github.com/open-voice-network/vrs)
- Magenta Voice Platform (Deutsche Telekom internal)
