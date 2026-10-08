# Privacy notice

Effective date: 8 October 2026

This notice covers the `release-notes` plugin published by Sobieski Labs in this repository.

## What the plugin does

The plugin contains an instruction-only skill. It runs within Claude and uses text that you supply, such as change lists, commit summaries, or diffs, to draft release notes. That text can contain names, email addresses, or other personal information if you include them.

The skill instructs Claude to remove passwords, access tokens, private email addresses, and other secrets from the output. This instruction is not a guarantee of complete removal. Review the input and the generated draft before you share them. Do not supply secrets or personal information that is not needed for the task.

## Data handling

The plugin includes no executable scripts, hooks, network tools, or external services. It does not send your text to a service operated by Sobieski Labs. Sobieski Labs does not collect or store your input or generated release notes through this plugin.

Claude processes your conversation and the supplied text. Anthropic's applicable privacy policy, your Claude account settings, and any agreement for your account govern that processing. This notice does not make promises about Anthropic's data retention or other data practices. See [Anthropic's privacy policy](https://www.anthropic.com/legal/privacy).

## Support and reports

For plugin questions or a security concern, use [the repository issue tracker](https://github.com/sobieskilabs/pluginlabs-publishing-example/issues). Issues are public. Do not post secrets, personal information, private source code, or sensitive exploit details. A report about the plugin can use a minimal example with invented data.

GitHub processes information that you choose to post under its own terms and privacy policy. This support channel is separate from use of the skill in Claude.
