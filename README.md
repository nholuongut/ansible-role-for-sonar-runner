# Ansible Role: SonarQube Runner

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

> **DEPRECATED**: This role is no longer actively maintained. It may still work, but I have marked it as 'deprecated' on Ansible Galaxy, and recommend you find a new role to replace it, or fork it and use your fork.

An Ansible Role that installs Sonar Runner on RedHat/CentOS and Debian/Ubuntu Linux servers.

The role is currently configured to support SonarQube installations using MySQL as a database backend.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    workspace: /root

Directory where downloaded files will be temporarily stored.

    sonar_runner_download_url: https://repo1.maven.org/maven2/org/codehaus/sonar/runner/sonar-runner-dist/2.3/sonar-runner-dist-2.3.zip
    sonar_runner_download_file: sonar-runner-dist-2.3.zip
    sonar_runner_expanded_file: sonar-runner-2.3

URL and filenames for sonar distribution/version.

    sonar_protocol: http
    sonar_host: localhost
    sonar_port: 9000

The SonarQube installation to which sonar-runner will connect.

    sonar_login: ""
    sonar_password: ""

The SonarQube installation login (if configured).

    sonar_mysql_host: localhost
    sonar_mysql_port: 3306
    sonar_mysql_database: sonar
    sonar_mysql_user: sonar
    sonar_mysql_password: sonar

SonarQube MySQL database connection details.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - { role: nholuong.sonar-runner }

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
