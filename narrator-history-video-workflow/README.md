# Historical narrator video workflow

Editable character bible and repeatable production workflow for one 3D history narrator with three role variants: Distinguished Historian, Eccentric Time Traveller, and History Showman.

## Start here
1. Read docs/character-bible.md. It is the design source of truth.
2. Add the approved concept image as assets/character/approved-concept.png. The supplied /mnt/data path was unavailable in this workspace, so this draft records only the visual anchors in the brief. Check image-specific details against the image before locking them.
3. Plan an episode with docs/production-workflow.md.
4. Use prompts/production-agent.md for a production run.
5. Copy the files in templates/ into a separate folder for each episode.

## Files
- docs/character-bible.md: identity, three looks, personality, voice, expressions, lip sync and references
- docs/production-workflow.md: research, image/video/voice production, review and export
- prompts/: reusable prompts and paste-ready production instructions
- templates/: brief, claim ledger, scene plan and production ledger
- assets/character/: approved concept and accepted reference sheets

Keep episode media separate from canonical character assets. Do not commit voice samples, credentials, or unreviewed generations.

The mouth, teeth, tongue, mismatched eyes, top hat silhouette, proportions and 3D finish stay consistent. Role outfits and episode props can change. The name, exact palette, image-specific details and voice source remain open. This project does not claim the character is unique; a name, mark and design search would be needed before making that claim.

## Workflow basis
This adapts the gate-based CloneVoice + VideoExpress workflow: research and frozen scene plan; character references before scenes; proof generation; per-scene production and review; assembly; completion ledger. This version supports visible dialogue and lip sync with one approved narration performance as the timing master. Check the selected apps' actual features rather than assuming a specific integration or lip-sync control.

Reference: https://github.com/strontiumplatform/CloneVoice-VideoExpress-Full-Length-2D-Narrative-Animated-Video-Workflow
