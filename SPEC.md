# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page dinosaur personality quiz that matches visitors with a dinosaur friend.
- **Audience:** Anyone looking for a dinosaur friend, especially younger children who enjoy cute characters and playful colors.
- **Requirements:** Five personality questions with clearly selected answers; one dinosaur match based on the responses; a short, encouraging explanation; and a way to restart. Honor the approved standing rule in `AGENTS.md`.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label fictional or sample content, including personality matches as pretend play. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** Cute dinosaur illustrations, vibrant colors, readable text, and large buttons. A brief stampede of little dinosaurs crosses the opening screen without blocking the quiz. The matched dinosaur performs a short, playful animation. Respect reduced-motion preferences with still illustrations.
- **Test:** I can finish the quiz, understand my match, and restart. Unanswered questions cannot silently count as answers. Test different answer combinations, keyboard controls, a small screen, and reduced-motion behavior. Verify the standing rule in the preview. After approval and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
