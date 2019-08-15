# Pypi
Deploy package to pypi.


## Usage:
```yaml
- name: Deploy package
  uses: remorses/pypi
  with:
    setupfile: ./setup.py
    username: ${{  secrets.pypi_username }}
    password: ${{ secrets.pypi_password }}
    distributions:
      - sdist
      - bdist_wheel
```
