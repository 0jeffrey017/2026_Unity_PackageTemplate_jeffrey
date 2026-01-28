# Example Template Package

A template package structure to demonstrate best practices.

## Installation

### Install via Unity Package Manager (Git URL)

1. Open **Window** > **Package Manager**
2. Click the **+** button in the top-left corner
3. Select **Add package from git URL...**
4. Paste the following URL:
   ```
   https://github.com/0jeffrey017/2026_Unity_PackageTemplate_jeffrey.git?path=Packages/com.example.template
   ```
5. Click **Add**

Alternatively, you can add this directly to your `Packages/manifest.json`:

```json
"dependencies": {
    "com.example.template": "https://github.com/0jeffrey017/2026_Unity_PackageTemplate_jeffrey.git?path=Packages/com.example.template",
    ...
}
```
