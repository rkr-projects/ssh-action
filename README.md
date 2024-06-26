# ssh-action
Git action for ssh setup in runner
# Usage
```yaml
    - name: SSH key setup
      uses: MRKR-PROJECTS/ssh-action@V1.0
      with:
        private_key: {{ secrets.SSH_KEY }}
```
