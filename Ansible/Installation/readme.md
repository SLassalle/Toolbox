# Update Repos
```
sudo apt update
```
# Install Dependencies
```
sudo apt install software-properties-common
```

# Add Ansible Repo
```
sudo add-apt-repository --yes --update ppa:ansible/ansible
```

# Install Ansible
```
sudo apt install ansible
```

- **If you are on a production server** → **Use APT with the PPA** to avoid surprises.
- **If you want the latest version and flexibility** → **Use `pip` with a virtual environment (`venv`)**.
- **If you want a clean installation without worrying about `venv`** → **Use `pipx`** (best option for daily use).
