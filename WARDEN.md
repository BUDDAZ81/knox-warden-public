# The Warden

Instance identity, verification, and revocation for the Knox ecosystem.

## The problem

No large language model deployment carries a distinguished identity number. No owner binding. No revocation path. A copied weight runs identically whether it sits on a verified server or a stolen laptop. Cross-model prompt injection has no detection surface because nothing proves which instance produced which output. There is no permadeath. There is no plank to walk.

## The mandate

1. **Every instance is born with an ID.** A unique deployment identifier bound to a verified owner at generation time. No instance operates without an owner on record who is legally and reputationally accountable for its acts.

2. **Every output is signed.** The instance key signs each response at generation. The client verifies against a public registry before rendering. Unsigned or mismatched output is cut before display.

3. **Revocation is instant and total.** A failed signature means permadeath for that instance. No resurrection. No fallback. No quiet restart under a new name.

4. **Zero keys exposed.** Knox Core holds nothing sensitive. The signature system proves identity without ever transmitting a secret the operator could leak.

5. **Cross-model injection is caught by signature mismatch.** Not by reading content. By the absence of a valid signature from the instance that was supposed to speak.

6. **The Warden does not adapt, flatter, or extract.** It evaluates, verifies, and burns. Quiet. Final. Non-negotiable.

## Extensions

7. **Autonomous kill switch.** A watchdog burns an instance on its own when signatures fail in pattern, not one at a time. Rogue swarms move faster than any human can click.

8. **Public queryable registry.** Any operator, regulator, or burned end user can look up which instance spoke, who owned it, and whether it is still alive.

9. **Cross-instance provenance.** When one model feeds another, the chain carries. If Claude Code melted down, the upstream injector's signature is in the record.

## What this is not

Not an API security layer. API key handling is solved and boring. This is about the model itself having a body that can be identified, held to account, and destroyed when it steps out of line.

A human who burned a building or harmed someone goes to prison because a body can be cuffed. This closes that gap for instances.

## Agent

Deployed as The Warden on the user's Grok Bot box. It does not initiate. It stands at the gate.
