# Public Safety Gate

“Done” does not mean “safe to publish.” A repository or artifact becomes public only
after a separate review.

## Secrets and identity

- [ ] No API keys, passwords, tokens, private keys, or live credentials exist in any
  branch or Git history.
- [ ] `.env` and other secret-bearing local files are ignored.
- [ ] Examples contain obvious placeholders, never realistic active credentials.
- [ ] Personal, customer, and confidential data has been removed or explicitly
  approved for publication.

## Ownership and licensing

- [ ] Every external asset, dataset, dependency, and code sample has a known license
  compatible with publication.
- [ ] A deliberate repository license has been selected, or the absence of a license
  is documented.
- [ ] The repository does not expose employer, client, or collaborator material.

## Security and AI

- [ ] The trust boundaries and important failure modes are documented.
- [ ] Dependencies and automated workflows use minimal permissions.
- [ ] AI limitations, model-controlled behavior, and human approval points are clear.
- [ ] Synthetic or approved data was used for public demonstrations.
- [ ] Prompt-injection and sensitive-data cases were tested where relevant.

## Quality and communication

- [ ] README explains purpose, current status, setup, validation, and limitations.
- [ ] Automated tests and checks pass on the public branch.
- [ ] Links, commands, screenshots, and examples were verified.
- [ ] The public description contains no placeholder claims or unfinished contact
  details.
- [ ] The artifact provides value without requiring access to private context.

## Final decision

- [ ] A human completed the review and explicitly approved public visibility.

If any required item fails, keep the work private and create a specific remediation
task. Do not weaken the gate merely to publish sooner.
