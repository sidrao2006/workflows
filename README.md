# Workflows

A set of reusable workflows used across my repositories.

### Index

| Workflow | Description |
|--|--|
| [Analyze Flutter Project][analyze_flutter_project.yml] | Analyzes Flutter projects using `flutter analyze` |
| [Documentation Analysis][dartdoc.yml] | Uses the latest available version of [dartdoc][dartdoc] to check the validity of dartdoc comments |
| [Verify Formatting][verify_dart_formatting.yml] | Verifies that code has been formatted to my preferred line length of 100 |
| [Pana Code Analysis][pana_code_analysis.yml] | Analyzes dart/flutter packages using [pana][pana] <br><br> <blockquote> ⚠️ Requires additional setup in workflow config! </blockquote> |
| [Unit Test][flutter_unit_test.yml] | Runs flutter unit tests |
| [Android Integration Tests][flutter_android_integration_test.yml] | Runs android integration (instrumentation) tests using a device on Firebase test Lab <br><br> <blockquote> ⚠️ Requires additional setup in workflow config! </blockquote> |
| [iOS Integration Test][flutter_ios_integration_test.yml] | Runs iOS integration tests on an emulator (Uses a macos image) |
| [Web Integration Test][flutter_web_integration_test.yml] | Runs web integration tests on headless chrome (Uses a windows image) |
| [Desktop Integration Test][flutter_desktop_integration_test.yml] | Runs integration tests on Windows, MacOS and Linux (Ubuntu) |
| [Deploy to Github Pages][flutter_gh_pages_deploy.yml] | Builds a flutter web app and deploys it to Github Pages <br><br> <blockquote> ⚠️ Requires additional setup in workflow config! </blockquote> |
| [Pull Request Labeler][pr_labeler.yml] | Adds appropriate labels to PRs using the provided config. <br><br> <blockquote> ⚠️ Requires additional setup! </blockquote> |
| [Pub pre-check][pub_pre_check.yml] | Tries to publish dart/flutter package in dry run mode and reports any failures. <br><br> <blockquote> ⚠️ Requires additional setup in workflow config! </blockquote> |
| [Release and publish package][pub_release.yml] | Ensures that required files (changelog, pubspec files) have been modified and then publishes the package to pub.dev and as a Github Release <br><br> <blockquote> ⚠️ Requires additional setup! </blockquote> |


[analyze_flutter_project.yml]: .github/workflows/analyze_flutter_project.yml
[dartdoc.yml]: .github/workflows/dartdoc.yml
[flutter_android_integration_test.yml]: .github/workflows/flutter_android_integration_test.yml
[flutter_desktop_integration_test.yml]: .github/workflows/flutter_desktop_integration_test.yml
[flutter_gh_pages_deploy.yml]: .github/workflows/flutter_gh_pages_deploy.yml
[flutter_ios_integration_test.yml]: .github/workflows/flutter_ios_integration_test.yml
[flutter_unit_test.yml]: .github/workflows/flutter_unit_test.yml
[flutter_web_integration_test.yml]: .github/workflows/flutter_web_integration_test.yml
[pana_code_analysis.yml]: .github/workflows/pana_code_analysis.yml
[pr_labeler.yml]: .github/workflows/pr_labeler.yml
[pub_pre_check.yml]: .github/workflows/pub_pre_check.yml
[pub_release.yml]: .github/workflows/pub_release.yml
[verify_dart_formatting.yml]: .github/workflows/verify_dart_formatting.yml

[dartdoc]: https://pub.dev/packages/dartdoc
[pana]: https://pub.dev/packages/pana
