# ansible-clone

This Ansible playbook ensures that `git` is installed on your machine and then clones a specified GitHub repository to a defined directory.

## Prerequisites

- Ansible installed on the machine.

## How to use

1. Clone this repository:

```bash
git clone https://github.com/ibilalkayy/ansible-clone.git
cd ansible-clone
```

2. Modify the playbook (`playbook.yml` or whatever you named it) by replacing `'link of the github repo'` with the actual GitHub repository link you want to clone, and `'path of the directory in which you want to clone it'` with the desired destination path on your local machine.

3. Run the playbook:

```bash
ansible-playbook playbook.yml
```

## What it does

- Ensures the `git` package is installed on your machine.
- Clones the specified GitHub repository to the provided directory path.

## Notes

- This playbook is set to run on the `localhost` and will not attempt an SSH connection as the connection is set to `local`.
- The playbook uses the `apt` package manager, which means it's designed for Debian-based distributions such as Ubuntu.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

Please modify the parts like the repository URL (`https://github.com/ibilalkayy/ansible-clone.git`) and any other placeholders to fit your specific setup and preferences.