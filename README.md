## note
This repo is a clone of [xarantolus/fdroid](https://github.com/xarantolus/fdroid), filtered (via git-filter-repo's clean-ignore filter) to remove all app-specific commits. A modification has been made to the metascoop go program to only fetch 5 releases from each repo. You can get a clean copy of this repo (without apks or metadata) at [efreak/fdroid-action](https://github.com/efreak/fdroid-action), however it's not guaranteed to be up to date with xaranolus' code.

# fdroid
This repository hosts an [F-Droid](https://f-droid.org/) repo for the following apps. This allows you to install and update apps very easily.

### Apps

<!-- This table is auto-generated. Do not edit -->
| Icon | Name | Description | Version |
| --- | --- | --- | --- |
| <a href="https://github.com/k0shk0sh/FastHub"><img src="fdroid/repo/icons/com.fastaccess.github.461.png" alt="FastHub (official) icon" width="36px" height="36px"></a> | [**FastHub (official)**](https://github.com/k0shk0sh/FastHub) | FastHub the ultimate GitHub client for Android. | 4.6.1 (461) |
| <a href="https://github.com/LightDestory/FastHub-RE"><img src="fdroid/repo/icons/" alt="FastHub Re(vival) icon" width="36px" height="36px"></a> | [**FastHub Re(vival)**](https://github.com/LightDestory/FastHub-RE) | Revival Attempt for FastHub the ultimate GitHub client for Android. | 4.7.7 (477) |
| <a href="https://github.com/Livinglist/Hacki"><img src="fdroid/repo/icons/" alt="Hacki icon" width="36px" height="36px"></a> | [**Hacki**](https://github.com/Livinglist/Hacki) | A simple noiseless Hacker News client made with Flutter that is just enough. | 0.2.17 (56) |
<!-- end apps table -->

### How to use
1. At first, you should [install the F-Droid app](https://f-droid.org/), it's an alternative app store for Android.
2. Now you can copy the following [link](https://raw.githubusercontent.com/xarantolus/fdroid/main/fdroid/repo?fingerprint=080898ae4309aeceb58915e43a4b7c4a3e2cda40c91738e2c02f58339ab2fbd7), then add this repository to your F-Droid client:

    ```
    https://raw.githubusercontent.com/xarantolus/fdroid/main/fdroid/repo?fingerprint=080898ae4309aeceb58915e43a4b7c4a3e2cda40c91738e2c02f58339ab2fbd7
    ```

    Alternatively, you can also scan this QR code:

    <p align="center">
      <img src=".github/qrcode.png?raw=true" alt="F-Droid repo QR code"/>
    </p>

3. Open the link in F-Droid. It will ask you to add the repository. Everything should already be filled in correctly, so just press "OK".
4. You can now install my apps, e.g. start by searching for "Notality" in the F-Droid client.

### Apps

<!-- This table is auto-generated. Do not edit -->
<!-- end apps table -->
Please note that some apps published here might contain [Anti-Features](https://f-droid.org/en/docs/Anti-Features/). If you can't find an app by searching for it, you can go to settings and enable "Include anti-feature apps".

### For developers
If you are a developer and want to publish your own apps right from GitHub Actions as an F-Droid repo, you can fork/copy this repo and see  [the documentation](setup.md) for more information on how to set it up.

### [License](LICENSE)
The license is for the files in this repository, *except* those in the `fdroid` directory. These files *might* be licensed differently; you can use an F-Droid client to get the details for each app.
