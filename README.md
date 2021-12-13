#How To Install

### Install by add directly in `manifest.json` in folder `Packages/manifest.json`

+ version 1.2.167
```csharp
"com.snorlax.external-dependency-manager": "https://github.com/snorluxe/external-dependency-manager.git?path=Assets/_Root#1.2.167",
```

### Install by scoped registry

- Step1:
  - Add following info scoped registry in PackageManager
  - Name:     Snorlax
  - URL:      https://npm.pkg.github.com/@snorluxe
  - Scope(s): com.snorlax 
    ![image](https://user-images.githubusercontent.com/44673303/142346105-6a33b3c6-bddd-4542-ae65-4be12db60bd8.png)

- Step 2:
  - add "com.snorlax.external-dependency-manager": "1.2.167" to `manifest.json`