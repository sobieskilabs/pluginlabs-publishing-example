# Privacy notice

Effective date: 8 October 2026

This notice covers these instruction-only release notes plugins:

- **PluginLabs Release Notes** (`pluginlabs-release-notes`) for ChatGPT and OpenAI, with publisher **STANISLAW JOZEF CHMIELA**.
- **release-notes** for Claude, with publisher **Sobieski Labs**, as defined in this repository's Claude manifest.

This notice describes the plugin packages. It does not cover the PluginLabs website or its account and submission services. It does not indicate that either plugin has been approved or published in a directory.

## What the plugins do

Each plugin contains an instruction-only skill. It uses text that you supply in the host assistant, such as change lists, commit summaries, or diffs, to draft release notes. That text can contain names, email addresses, or other personal information if you include them.

Review the input and the generated draft before you share them. Do not supply passwords, access tokens, private email addresses, other secrets, or personal information that is not needed for the task. The plugins do not guarantee that sensitive information will be detected or removed from the generated output.

## Data handling

The plugin packages contain no executable scripts, hooks, network tools, or external servers. The skills themselves do not store your input or output, or transmit it to a service operated by either publisher. Neither publisher collects or stores your conversation or generated release notes through these instruction-only skills.

The host provider processes your prompts, conversation, and generated output:

- For ChatGPT and other OpenAI hosts, OpenAI's applicable terms, privacy policy, account settings, and any agreement for your account govern that processing. See [OpenAI's privacy policy](https://openai.com/policies/privacy-policy/).
- For Claude, Anthropic's applicable terms, privacy policy, account settings, and any agreement for your account govern that processing. See [Anthropic's privacy policy](https://www.anthropic.com/legal/privacy).

This notice makes no promise about either provider's retention, training, or other data practices. The absence of a plugin-operated server does not prevent the host provider from processing the information you supply.

## Support and reports

For questions or a security concern about either plugin, use [the repository issue tracker](https://github.com/sobieskilabs/pluginlabs-publishing-example/issues). Issues are public. Do not post secrets, personal information, private source code, or sensitive exploit details. A report about the plugin can use a minimal example with invented data.

GitHub processes information that you choose to post under its own terms and privacy policy. The publishers can read and respond to those public reports. This support channel is separate from use of the skills in the host assistant.
