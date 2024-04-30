
# Install the physfs ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_physfs

# Clone the physfs ansible role. 
git clone git@github.com:computate-org/computate_physfs.git ~/.ansible/roles/computate.computate_physfs

# Change into the physfs ansible role directory. 
cd ~/.ansible/roles/computate.computate_physfs
```

# Run the physfs ansible playbook to install physfs locally. 

```bash
ansible-playbook install.yml
```

