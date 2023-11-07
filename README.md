## GitLab CICD plugin for JetBrains IDEs

[![gitlab-cicd-plugin](https://img.shields.io/jetbrains/plugin/r/rating/guru.ide.gitlab)](https://plugins.jetbrains.com/plugin/22202-gitlab-cicd--pipelines--jobs-builds-run-cancel-retry-view-log)
[![gitlab-cicd-plugin](https://img.shields.io/jetbrains/plugin/d/22202-gitlab-cicd--pipelines--jobs-builds-run-cancel-retry-view-log?color=green)](https://plugins.jetbrains.com/plugin/22202-gitlab-cicd--pipelines--jobs-builds-run-cancel-retry-view-log)
[![gitlab-cicd-plugin](https://img.shields.io/jetbrains/plugin/v/22202-gitlab-cicd--pipelines--jobs-builds-run-cancel-retry-view-log?label=version)](https://plugins.jetbrains.com/plugin/22202-gitlab-cicd--pipelines--jobs-builds-run-cancel-retry-view-log)

![Preview gif](media/preview.gif)

## Download

https://plugins.jetbrains.com/plugin/22202-gitlab-cicd--pipelines--jobs-builds-run-cancel-retry-view-log

## Description

GitLab CICD is an IDE plugin designed to make it easier for you to view and manage GitLab CI/CD directly from within the 
IDE. The plugin provides a user-friendly interface that allows you to easily view, run, cancel and retry GitLab Pipelines 
and Jobs without having to switch between the IDE and the GitLab web interface. It works with both **GitLab SaaS** and **GitLab 
Self-Managed (13.x or later)**.

With **GitLab CICD**, you can:

- 🔎 Quickly view the status of pipelines.
- 🖥 View detailed information about each pipeline, stage and job.
- 🛠 Run, cancel and retry pipeline or job.
- 📋 Display job log in real time.
- 💾 Download job artifacts.
- 🔔 Receive notifications when your pipelines have been started or finished.
- ✅ Validate/Lint your CICD configuration files (e.g. .gitlab-ci.yml).
- 🌙 Enjoy GitLab CI/CD in Dark Mode.


**❗Important note:** The plugin acts as a direct client for GitLab, ensuring that no data is transmitted to any server other 
than GitLab itself. Access tokens are stored securely on your local machine in the IDE's password storage, which you can 
configure in the IDE Settings.

To open plugin, click on `View -> Tool Windows -> GitLab CICD`.\
To validate CICD file, right-click on file, then select `Validate CICD file`.

By using GitLab CICD, you can save time and streamline your development workflows by eliminating the need to switch between 
multiple applications and interfaces. The plugin is easy to install and use, and provides a seamless integration between IDE
and GitLab CI CD.

## Getting started

### Installation

1. Install a compatible JetBrains IDE, such as IntelliJ IDEA, CLion, PyCharm, or other IntelliJ-based IDEs.
2. Launch the IDE and open plugin settings.
3. Search for GitLab CICD - Pipelines & Jobs, Builds Run Cancel Retry View Log and click install.
4. Restart your IDE to complete the installation.

### Configuration

1. After restarting, click on `View -> Tool Windows -> GitLab CICD` to open the plugin.
2. If needed, you can configure plugin settings. In the plugin window, click on the settings icon to configure the plugin.
3. To add repository click on `Add repositories...` and then, in the appeared dialog, on plus icon.
4. Choose the GitLab instance type: either "GitLab Cloud" or "GitLab Self-Managed".
5. Provide your GitLab instance url and access token. You can generate a token in your GitLab account settings.
6. Type project name (at least three characters) and choose project.
7. Click "OK" to store your configuration.
8. You can add as many GitLab instances/repositories as you want.

### Using the Plugin

Once you have installed and configured the GitLab CICD plugin, you can start using its features.
1. Open your IDE.
2. Click on the GitLab CICD tool window to view your pipelines.
3. Similar to GitLab CI/CD web interface you can:
- Go to pipeline details view. Just click on pipeline in the pipelines view tab.
- Go to job details & console view. Just click on job in the pipeline details tab.
4. Here is list of the main features of the GitLab CICD plugin:
- View the status of pipelines.
- Access detailed information about each pipeline, stage, and job.
- Run, cancel, or retry a pipeline or job.
- View job logs in real-time.
- Download job artifacts.
- Receive notifications for pipeline events.
- Validate/Lint your CICD configuration files (*gitlab-ci*.yml or *gitlab-ci*.yaml).

### Security

The GitLab CICD plugin ensures the security of your data:
- No data is transmitted to any server other than GitLab itself.
- Your access tokens are securely stored in your local machine's IDE password storage.
- You can configure the password storage in the IDE settings.

### Conclusion

By using the GitLab CICD plugin, you can streamline your development workflows and save time by eliminating the need to 
switch between applications and interfaces. Enjoy the seamless integration between your IDE and GitLab CI/CD!

## [License](LICENSE)
