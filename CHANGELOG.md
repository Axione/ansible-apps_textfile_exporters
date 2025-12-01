# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.1](https://github.com/lotusnoir/ansible-apps_textfile_exporters/compare/1.2.0...1.2.1) - 2025-11-29

### Commits

- add no changes on run flag to keep idempotence [`9709d7d`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/9709d7d270c25cf6d0e20213f3b386e040bb8ead)

## [1.2.0](https://github.com/lotusnoir/ansible-apps_textfile_exporters/compare/1.1.0...1.2.0) - 2025-11-25

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`4a51cde`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/4a51cde55105e7ad3931889b0a77f0b01baaf371)
- add tags [`d09bf0c`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/d09bf0c49539b0d2ed4569d9d4944db1e6a94760)

## [1.1.0](https://github.com/lotusnoir/ansible-apps_textfile_exporters/compare/1.0.0...1.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`9f630d5`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/9f630d5962055fd93363d5d54b4275b967266254)
- add oraclelinux10 support + lint and core fixes [`9b3c2a5`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/9b3c2a5e6ed59ef20df6b62d40c2d1553da3267d)
- add tags to select specific tasks [`042a9f8`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/042a9f89dd38bdad7e67fdc892390445c2ce3805)

## [1.0.0](https://github.com/lotusnoir/ansible-apps_textfile_exporters/compare/0.1.0...1.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`9e901ec`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/9e901ecc736c54daa45c78b9007807a3fb28138f)
- update core, molecule + gitlab-ci [`0753457`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/0753457955c8555c2b903a3ba46f656d3d9d4924)
- changes on molecule [`3d2eeff`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/3d2eeff374b1fa38cf874970f1e3036a392ff99e)
- fix marker [`c0f2180`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/c0f2180b8931caf8cda3fc70e8ed78025582bdcd)
- add posibility to custom a script [`f174cf0`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/f174cf0777d6ddb8f983e906d01ca40719b81ccf)
- speed up copy with query('fileglob') than with_fileglob [`af11f88`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/af11f888dee9ead8cd0145939658663782165886)
- activate oraclelinux8 8 [`f6ef499`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/f6ef499ee8a3c41f7c5c0877b63ffc1f56f3b21e)
- fix lint [`58ff183`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/58ff18304779b4537b471d32c8c119b7bda7df69)
- fix molecule paralelism and little updates [`0147e47`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/0147e470cf65d848eb5814713f9d31268cfa6369)

## 0.1.0 - 2025-01-16

### Commits

- add support for ubuntu24 [`7cf91a7`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/7cf91a7c0841ee7ce984545de97b1f4b8967ee34)
- fix check tmp dir [`c5b05fd`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/c5b05fd630b3acd08e48bf66b129c60d8a4c7014)
- add retry on git + add pkg prometheus [`0851dd8`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/0851dd8307d2920ce1cfca5cbdbb8b26206e7a14)
- fix install [`49955ce`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/49955ced297295cef6f947cd9a14ac99296e7555)
- fix install [`839d84c`](https://github.com/lotusnoir/ansible-apps_textfile_exporters/commit/839d84c8e7171e00558746eef977f97e88cd6edd)
