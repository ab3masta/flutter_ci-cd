# 🚀 Flutter Template with CI/CD using GitHub Actions

[![Build Status](https://github.com/AbdouAbarchiAboubacar/flutter_ci-cd/actions/workflows/firebase-hosting-merge.yml/badge.svg)](https://github.com/AbdouAbarchiAboubacar/flutter_ci-cd/actions)
<!-- [![codecov](https://codecov.io/gh/AbdouAbarchiAboubacar/flutter_ci-cd/branch/main/graph/badge.svg?token=your-token)](https://codecov.io/gh/AbdouAbarchiAboubacar/flutter_ci-cd) -->


This is a Flutter template with Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions. The CI/CD pipeline runs Flutter tests and analysis, generates APK files, generates App Bundle files, builds Flutter Web, and deploys the web app to Firebase Hosting. 🚀

## Getting Started 🏁

To use this template, simply click on the "Use this template" button at the top of the repository page or clone this repository to your local machine: 🤖

```
git clone https://github.com/your-username/your-repo-name.git
```

You will need to set up a few things before the CI/CD pipeline can run: 🛠️

1. Set up your environment variables in the GitHub repository settings (see `env.example` for a list of required environment variables).
2. Set up your Firebase project and get the Firebase token (see the [Firebase Hosting docs](https://firebase.google.com/docs/hosting/quickstart)).
3. Replace the Firebase configuration in `web/index.html` with your own Firebase configuration.

Once you have set up these requirements, the CI/CD pipeline will run every time you push to the `main` branch. You can also trigger the pipeline manually from the Actions tab in your repository. 🚀

## Features 🎉

This template includes the following features:

- Flutter tests and analysis ✅
- Generate APK files 📱
- Generate App Bundle files 📦
- Build Flutter Web 🌐
- Deploy Flutter Web to Firebase Hosting 🔥

## Contributing 🤝

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License 📝

This project is licensed under the [MIT License](https://github.com/AbdouAbarchiAboubacar/flutter_ci-cd/blob/master/LICENCE).
