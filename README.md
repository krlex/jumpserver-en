# Jumpserver Better bastion machines in cloudy environments

[![Python3](https://img.shields.io/badge/python-3.6-green.svg?style=plastic)](https://www.python.org/)
[![Django](https://img.shields.io/badge/django-2.1-brightgreen.svg?style=plastic)](https://www.djangoproject.com/)
[![Ansible](https://img.shields.io/badge/ansible-2.4.2.0-blue.svg?style=plastic)](https://www.ansible.com/)
[![Paramiko](https://img.shields.io/badge/paramiko-2.4.1-green.svg?style=plastic)](http://www.paramiko.org/)

Jumpserver Is the world's first fully open source bastion machine, using GNU GPL v2.0 The open source protocol is an operation and maintenance security audit system that complies with the 4A mechanism.

Jumpserver use Python / Django Develop, follow Web 2.0 Specifications, equipped with industry-leading Web Terminal Scheme, beautiful interactive interface and good user experience.

Jumpserver adopt a distributed architecture, support multi-machine room cross-region deployment, support horizontal expansion, and have no restrictions on the number of assets and concurrency.

Change the world, starting from a little bit.

Note: [KubeOperator](https://github.com/KubeOperator/KubeOperator) yes Jumpserver team in Kubernetes another new masterpiece in the field, welcome attention and use.

## List of core functions

<table>
  <tr>
    <td rowspan="7">Authentication</td>
    <td rowspan="4">Login authentication</td>
    <td>Unified resource login and authentication</td>
  </tr>
  <tr>
    <td>LDAP/AD Certification</td>
  </tr>
  <tr>
    <td>RADIUS Certification</td>
  </tr>
  <tr>
    <td>OpenID Authentication (implement single sign-on)</td>
  </tr>
  <tr>
    <td rowspan="2">MFA Certification</td>
    <td>MFA Secondary certification（Google Authenticator）</td>
  </tr>
  <tr>
    <td>RADIUS Secondary certification </td>
  </tr>
  <tr>
    <td>Login review（X-PACK）</td>
    <td>User login behavior is supervised and controlled by administrator</td>
  </tr>
  <tr>
    <td rowspan="11">Account management</td>
    <td rowspan="2">Centralized account</td>
    <td>User management</td>
  </tr>
  <tr>
    <td>System user management</td>
  </tr>
  <tr>
    <td rowspan="4">Unified password</td>
    <td>Asset password escrow</td>
  </tr>
  <tr>
    <td>Generate password automatically</td>
  </tr>
  <tr>
    <td>Push password automatically</td>
  </tr>
  <tr>
    <td>Password expiration settings</td>
  </tr>
  <tr>
    <td rowspan="2">Batch change password（X-PACK</td>
    <td>Change the password regularly in batches</td>
  </tr>
  <tr>
    <td>Multiple password policies</td>
  </tr>
  <tr>
    <td>Cloudy Management（X-PACK</td>
    <td> Automatic unified management of private cloud and public cloud assets </td>
  </tr>
  <tr>
    <td>Collect users（X-PACK）</td>
    <td>Custom tasks periodically collect host users</td>
  </tr>
  <tr>
    <td>Password box（X-PACK）</td>
    <td>View, update, and test user passwords of asset hosts in a unified manner</td>
  </tr>
  <tr>
    <td rowspan="15">Authorization control</td>
    <td> Multidimensional authorization </td>
    <td> Authorize users, user groups, assets, asset nodes, applications, and system users </td>
  </tr>
  <tr>
    <td rowspan="4">Asset authorization</td>
    <td> Assets are displayed in a tree structure </td>
  </tr>
  <tr>
    <td>Flexible authorization of assets and nodes </td>
  </tr>
  <tr>
    <td>Assets within nodes automatically inherit authorization</td>
  </tr>
  <tr>
    <td>Child nodes automatically inherit parent node authorization </td>
  </tr>
  <tr>
    <td rowspan="2">Application authorization </td>
    <td>Enable finer-grained application-level authorization</td>
  </tr>
  <tr>
    <td>MySQL database application 、RemoteApp Remote application（X-PACK）</td>
  </tr>
  <tr>
    <td>Action authorization</td>
    <td> Implements control of file uploads, downloads, and connection actions for authorized assets</td>
  </tr>
  <tr>
    <td>Time authorization</td>
    <td>Implement restrictions on the time period for which authorized resources are used </td>
  </tr>
  <tr>
    <td>Privileged instruction</td>
    <td>Implement the use of privileged instructions (supports black and white lists) </td>
  </tr>
  <tr>
    <td> Command filtering</td>
    <td>Implements control over commands executed by authorized system users</td>
  </tr>
  <tr>
    <td>file transfer</td>
    <td>SFTP File upload / download</td>
  </tr>
  <tr>
    <td>File management</td>
    <td>Implement Web SFTP file management</td>
  </tr>
  <tr>
    <td>Ticket Management（X-PACK</td>
    <td>Support control of user login request behavior</td>
  </tr>
  <tr>
    <td>Organization Management（X-PACK</td>
    <td>Implement multi-tenant management and permission isolation</td>
  </tr>
  <tr>
    <td rowspan="7">Security audit</td>
    <td> Operational audit</td>
    <td>User operation behavior audit</td>
  </tr>
  <tr>
    <td rowspan="2">Session audit</td>
    <td>Online session content audit</td>
  </tr>
  <tr>
    <td>Audit history content</td>
  </tr>
  <tr>
    <td rowspan="2">Asset authorization</td>
    <td> Support playback auditing of recordings of asset operations such as Linux and Windows</td>
  </tr>
  <tr>
    <td> Supports playback auditing of remoteApp (X-PACK), MySQL and other application operations</td>
  </tr>
  <tr>
    <td>Instruction audit</td>
    <td>Supports auditing of commands such as assets and applications</td>
  </tr>
  <tr>
    <td>file transfer</td>
    <td>Audit of file upload and download records</td>
  </tr>
</table>

## Installation and use guide

-  [Docker Quick installation documentation](http://docs.jumpserver.org/zh/docs/dockerinstall.html)
-  [Step by Step Installation documentation](http://docs.jumpserver.org/zh/docs/step_by_step.html)
-  [Full documentation](http://docs.jumpserver.org)

## Demo videos and screenshots

We provide demo videos and system screenshots to let you quickly understand Jumpserver：

- [Demo video](https://jumpserver.oss-cn-hangzhou.aliyuncs.com/jms-media/%E3%80%90%E6%BC%94%E7%A4%BA%E8%A7%86%E9%A2%91%E3%80%91Jumpserver%20%E5%A0%A1%E5%9E%92%E6%9C%BA%20V1.5.0%20%E6%BC%94%E7%A4%BA%E8%A7%86%E9%A2%91%20-%20final.mp4)
- [System screenshot] (http://docs.jumpserver.org/zh/docs/snapshot.html)

## SDK

We have written some SDKs for your other systems to quickly interact with the Jumpserver API:
- [Python](https://github.com/jumpserver/jumpserver-python-sdk) Jumpserver Other components use this SDK to interact
- [Java](https://github.com/KaiJunYan/jumpserver-java-sdk.git) Java version of SDK provided by Kaifeng

## License & Copyright

Copyright (c) 2014-2019 飞致云 FIT2CLOUD, All rights reserved.

Licensed under The GNU General Public License version 2 (GPLv2)  (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

https://www.gnu.org/licenses/gpl-2.0.html

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
