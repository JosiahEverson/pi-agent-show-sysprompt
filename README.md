# show-sysprompt

Maintained fork of the archived
[`xl0/pi-agent-show-sysprompt`](https://github.com/xl0/pi-agent-show-sysprompt),
updated for `@earendil-works/pi-*` packages and verified against Pi 0.80.7.

The extension shows the rendered system prompt and active tool schemas at the
start of a session. It is useful while developing extensions or diagnosing why
an agent sees particular instructions and tools.

For a larger maintained toolkit with `/show-sysprompt`, `/show-context`,
`/llm-stats`, and `/tool`, see
[`@xl0/pi-lovely-dev-tools`](https://github.com/xl0/pi-lovely-dev-tools).

## Install

```bash
pi install git:git@github.com-personal:JosiahEverson/pi-agent-show-sysprompt.git
```

Or load without installing:

```bash
pi -e git:git@github.com-personal:JosiahEverson/pi-agent-show-sysprompt.git
```

![Screenshot](https://raw.githubusercontent.com/JosiahEverson/pi-agent-show-sysprompt/master/screenshot.png)
