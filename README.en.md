# Debug React 18 Source Code

[中文](./README.md) | [English](./README.en.md)

This is a benchmark debug environment for React18, and you can start debugging React using the main branch after the fork project.


## Attentions

### Debugging React by using stable branch

If you want to build your own debug environment from zero, download stable branch from react repo. Because developers often submit code in the main branch, the code is unstable, and it is difficult to troubleshoot problems encountered in the construction process.

```shell
git clone git@github.com:facebook/react.git --depth 1 --branch v18.2.0
```

### Turn off all lint checks (optional)

Because React uses the Flow syntax, VSCode and WebStorm will report many errors if they do not configure the corresponding parser. It is recommended to close the lint check of the editor when debugging the source code of React.
