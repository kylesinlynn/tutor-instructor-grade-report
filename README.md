# Change User Password Plugin
Customizable Tutor Plugin for Open edX

# Content
- [Change User Password Plugin](#change-user-password-plugin)
- [Content](#content)
- [Setup](#setup)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

# Setup
> This is the `main` branch which is intended to be used for development purpose. Some bugs and unexpected behaviors will occur while installing from this branch.

1. Clone the git repository into `tutor plugins root` using the following command.
   ```bash
   git clone https://github.com/kylesinlynn/openedx/tutor-instructor-grade-report.git && mv "$(pwd)/tutor-instructor-grade-report/instructor-grade-report.py" "$(tutor plugins printroot)"
   ```

2. List the installed plugins.
   ```bash
   tutor plugins list
   ```

3. Enable the plugins if you found `instructor-grade-report` plugin.
   ```bash
   tutor plugins enable instructor-grade-report
   ```

# Troubleshooting
Create an issue upon your error that is associated with this project.

# Contributing
Feel free to fork and create pull requests. Your contribution will be appreciated.

# License
This project is licensed under [BSD License](LICENSE).