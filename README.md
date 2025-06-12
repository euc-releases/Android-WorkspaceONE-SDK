## Workspace ONE SDK for Android

This repository contains the Workspace ONE SDK for Android.

For detailed information about the Workspace ONE SDK and managing internal apps, see the [Omnissa Developer Portal SDKs](https://developer.omnissa.com/sdks/) page and navigate to the appropriate area.

## Release Notes

Up to date release notes can be found in the [Omnissa Developer Portal](https://developer.omnissa.com/ws1-sdk-for-android/release-notes/).

## Integration

The SDK is accessible from a Maven repository. For integration documentation, refer to [Workspace ONE SDK for Android](https://developer.omnissa.com/ws1-sdk-for-android/) page in the Omnissa Developer Portal and KB article [General Availability of Workspace ONE SDK Android (6000158)](https://kb.omnissa.com/s/article/6000158).

Developers must follow the instructions in the [Public Maven Repository Integration Note](https://github.com/euc-releases/workspace-ONE-SDK-integration-samples/blob/main/IntegrationGuideForAndroid/Guides/PublicMaven/WorkspaceONE_Android_PublicMavenNote.md) to integrate the Workspace ONE SDK Android package into their applications.

Also when adding module dependencies, ensure the group and module names are in lowercase. Example: 
```c
dependencies { implementation ("com.airwatch.android:airwatchsdk:${airwatchVersion}") implementation ("com.airwatch.android:awframework:${airwatchVersion}") implementation ("com.airwatch.android:awnetworklibrary:${airwatchVersion}") }
```

This SDK is free and public. To obtain technical support for the use of the SDK, please submit a Support Request (SR) via [Omnissa Customer Connect](https://customerconnect.omnissa.com/home) to get help from the Omnissa Global Customer Services (GCS).

## Downloads

Omnissa provides this Software Development Kit (the “Software”) to you subject to the following terms and conditions. By downloading, installing, or using the Software, you agree to be bound by the terms of [Omnissa SDK License Agreement](https://static.omnissa.com/sites/default/files/omnissa-sdk-agreement.pdf). If you disagree with any of the terms, then do not use the Software.

For additional information, please visit the [Omnissa Legal Center](https://www.omnissa.com/legal-center/).

The SDK is provided as a [Release](https://github.com/orgs/euc-releases/packages?repo_name=Android-WorkspaceONE-SDK). Primarily, the SDK is accessible as a Maven package.

## License

This software is licensed under the [Omnissa Software Development Kit (SDK) License Agreement](https://static.omnissa.com/sites/default/files/omnissa-sdk-agreement.pdf); you may not use this software except in compliance with the License.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

This software may also utilize Third-Pary Open Source Software as detailed within the [open_source_licenses.txt](open_source_licenses.txt) file.

## Copyright

Copyright © 2010-2021,2024-2025 Omnissa. All rights reserved. This product is protected by copyright and intellectual property laws in the United States and other countries as well as by international treaties. Omnissa products are covered by one or more patents listed at: https://www.omnissa.com/omnissa-patent-information/. Omnissa products are also covered by general and offering-specific legal terms, as well as the privacy and open-source software notices hosted on the Omnissa Legal Center at: https://www.omnissa.com/legal-center/.

Omnissa, the Omnissa Logo, Workspace ONE, and Horizon are registered trademarks or trademarks of Omnissa in the United States and other jurisdictions. All other marks and names mentioned herein may be trademarks of their respective companies. “Omnissa” refers to Omnissa, LLC, Omnissa International Unlimited Company, and/or their subsidiaries.
