# release-notes

Turn supplied changes into clear release notes with user impact, upgrade steps, and known limitations.

Version: 1.0.0

This package contains one instruction-only skill. Review [SKILL.md](skills/release-notes/SKILL.md) before installation. It does not execute code, connect to external services, or publish a release. Review each generated draft before use.

## Example prompts

With the plugin enabled in Claude, try these prompts. Each includes sample input; replace it with your own changes.

### Customer release notes

```text
Use the release-notes skill to write release notes for version 2.3.0,
released on 8 October 2026, for customers of a task manager.
Changes:
- Users can filter tasks by due date.
- Fixed duplicate reminder notifications.
- CSV export still excludes archived tasks; this is a known limitation.
Use only these facts. Do not add performance or test claims.
```

### Breaking change and upgrade steps

```text
Use the release-notes skill to draft release notes for API version 3.0.0,
released on 8 October 2026. The audience is API developers.
Changes:
- Removed the deprecated /v1/tasks endpoint.
- Clients must use /v2/tasks instead.
- The response field task_name is now title.
- Existing API keys remain valid.
Put breaking changes and the required client changes first.
```

### Incomplete source information

```text
Use the release-notes skill to turn these changes into a Markdown draft
for workspace administrators:
- Added a setting to disable guest invitations.
- Fixed an error when removing an inactive member.
- Fixed a typo in the account settings page.
The release version and date are not decided. Leave clear placeholders
for them and list the questions needed to finish the draft.
```

## Privacy

See the [privacy notice](PRIVACY.md). The skill uses the text you supply in Claude. It instructs Claude to remove sensitive information from its output, but you must review the result. Claude's own privacy terms govern provider processing.

## Support and security reports

Use [GitHub issues](https://github.com/sobieskilabs/pluginlabs-publishing-example/issues) for questions, bugs, or an initial security report. This is a public channel. Do not include secrets, personal information, private source code, or sensitive exploit details. Use a minimal example with invented data.

## Package status

The repository and its files do not prove directory submission, acceptance, or publication.
