# Ansible-Gh

> ### <ins>__Prerequisites:__</ins>
>__Ansible control node:__ The Ansible control node is a machine you will need to connect to and control the Ansible hosts over SSH. Your Ansible control node can either be your local machine or a server dedicated to running Ansible. For more information check [Ansible-Install](https://github.com/CharlaftisBill/Ansible-Install) repo.

## How to use:

1. Run the following command to install gh.

```bash
ansible-playbook gh.yml -K
```

2. Create a "Personal Access Token":
Click on your prifile image (up right) -> Settings -> Developer settings -> Personal access tokens -> Generate new token

3. Set Note (something like a Friendly Name), Expiration and click the checkboxes:
 * repo,
 * workflow,
 * admin:org.

> important: Do not click on "Generate token" yet...

4. Type on termnal:
```bash
gh auth login
```
5. Follow the steps and when you been asked paste the token go back to your browser and click on "Generate token"

6. Copy-paste the token (gh...) from  browser to terminal and press enter.

7. Enjoy!