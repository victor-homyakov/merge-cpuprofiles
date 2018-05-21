# merge-cpuprofiles
Merge V8 .cpuprofile files

1. Collect CPU profiles, either manually or automatically via `console.profile()` .. `console.profileEnd()`
2. Save profiles into `in` directory
3. Merge profiles into single file
4. Load merged profile from `out` directory back into the Developer Tools

## Documentation

- Chrome DevTools Protocol Viewer: https://chromedevtools.github.io/devtools-protocol/1-2/Profiler#type-Profile
- Protocol sources: https://chromium.googlesource.com/v8/v8/+/master/src/inspector/js_protocol.json#1421
